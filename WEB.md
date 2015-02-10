# Web
There are various parameters for landing upon a particular set of technology for web applications. **Time constraints**, **client preferences**, **ready made pluggins in the project domain**, **existing competitors technology preferences and their experience**,**our preferences and experience** are a few if them.

If using some framework, or technology is must for a project, and if we don't have the expertise in it, we actually invest time and money to learn that, to make sure we use the best available technology for the current project.

We maintain a technology battlefield, which is basically a list of technologies, that we think, are going to be dominant, and we start learning those. 

## What do we offer for web applications ?
### Golang
We love Golang, every bit of it. And we are one of the early adopters of Golang for web applications as well. Till date (Feb 2015), we have written in all, 5 web applications in Golang, and using different frameworks.

There are many advantages of using Golang over other languages for writing web applications.

***
When we built the first version of IronWorker, about 3 years ago, it was written in Ruby and the API was built on Rails. It didn’t take long for us to start getting some pretty heavy load and we quickly reached the limits of our Ruby setup. Long story short, we switched to Go. For the long story, keep reading, here's how things went down. - Iron.io
[(source)](http://blog.iron.io/2013/03/how-we-went-from-30-servers-to-2-go.html)

And yes they have talked about some of the issues as well - 

I can confidently say that after two years working with Go, we made the right choice. If we had started Iron.io today, it would have been a no brainer to choose it. A lot of other companies are using it now too including Heroku and Google and the people I talk to about it all have similar opinions. +Rob Pike, one of the creators of Go said:
“We realized that the kind of software we build at Google is not always served well by the languages we had available,” Pike said in 2011. “Robert Griesemer, Ken Thompson, and myself decided to make a language that would be very good for writing the kinds of programs we write at Google.”

 +Derek Collison, the founder of Apcera, said recently in a Wired article:
“The management layers and infrastructure layers of the newer technologies that provide this cloud delivery model?” he tells Wired. “Within two years, a majority will be written in Go.” 
Is Go the next gen language we've been waiting for. It's a bit too early to say, but it's certainly off to a good start. 
[(source)](http://blog.iron.io/2013/08/go-after-2-years-in-production.html)

***
| Param | Golang | Ruby on Rails |
| -- | -- | -- |
| Samples | 20,000 | 20,000 |
| Errors | 0 | 0 |
| Average | 8ms | 187ms |
| Median | 5ms | 163ms |
|90%|20ms| 214ms |
| Max | 90ms | 178,552ms  |
| Min | 1ms | 9ms |
| Throughput | 4691.79 requests/s  | 88.9 requests/s|
| Memory usage | 10MBs | 117 MBs |

Go (1.2),Rails (Rails 4, Ruby 2.0, production mode, puma web)

Benchmarks by Matt Aimonetti [(source)](https://plus.google.com/+MattAimonetti/posts/PeZk8FY3PWY)

****

**Advantages:**

1. Go compiles very quickly.
2. Go supports concurrency at the language level.
3. Functions are first class objects in Go.
4. Go has garbage collection.
5. Strings and maps are built into the language.

**Disadvantages:**

1. Go is still an experimental language subject to change. (I suppose this could be an advantage depending on how you look at it. For most it's probably a disadvantage.)
2. Go's not very usable on Windows yet.
3. The packages distributed with Go are pretty useful, but there are still some libraries you'll miss. Most notably a UI toolkit.
4. There is no support for generics in Go, although there are many discussions around it.

[Source for above points](http://stackoverflow.com/a/2200447/769189)
****
We can keep on bragging about, why Golang is right choice for writing next gen web applications. [Here](https://code.google.com/p/go-wiki/wiki/GoUsers) is the list of organizations using Golang.

### Scala with Play framework
Scala is JVM language with functional approach. Scala is the first choice of [twitter](https://twitter.com) for JVM based languages [(source)](http://www.infoq.com/articles/twitter-java-use). We love functional approach for solving problems.

We write web applications in scala using [Play Framework](https://www.playframework.com/), which is robust, faster and based on [netty](http://netty.io/).

### Java 1.8 with Play Framework
Java 1.8 removes most of the reasons, why people shifted onto Scala.

1. Lambda Expressions, a new language feature, has been introduced in this release. They enable you to treat functionality as a method argument, or code as data. Lambda expressions let you express instances of single-method interfaces (referred to as functional interfaces) more compactly.
2. Method references provide easy-to-read lambda expressions for methods that already have a name.
3. Default methods enable new functionality to be added to the interfaces of libraries and ensure binary compatibility with code written for older versions of those interfaces.
4. Repeating Annotations provide the ability to apply the same annotation type more than once to the same declaration or type use.
5. Type Annotations provide the ability to apply an annotation anywhere a type is used, not just on a declaration. Used with a pluggable type system, this feature enables improved type checking of your code.
6. Method parameter reflection.
7. Improved type inference.

 [source](http://www.oracle.com/technetwork/java/javase/8-whats-new-2157071.html)

So we also propose going with Java 1.8 and Play framework for the projects that needs to run on JVM.


