# Today I learned (Markdown edition)

I want to try and keep this one brief, I learned a lot of stuff this week, but maybe keeping it short and sweet is for the better, anyway here we go. I'm trying new stuff, seeing what works and what doesn't so bare with me.

## Introduction

This week's theme was _"Fancy Topics"_, which I think was refering on the level of complexity of the videos and articles we were supposed to read, which ranged from test driven development, to quantum physics and reality.
**VERY** interesting stuff, some of the lectures, which I found the most interesting were:
* [Test Driven Development](http://wiki.c2.com/?TestDrivenDevelopment) and [Unit testing](https://martinfowler.com/bliki/UnitTest.html)
* [Mocks aren't stubs](https://martinfowler.com/articles/mocksArentStubs.html)
* Missing semester, [Vim](https://missing.csail.mit.edu/2020/editors/) and [Git](https://missing.csail.mit.edu/2020/version-control/)

Along with another lecture that talked about java build tools, how to manage dependecies with maven, gradle nad ant+ivy.

And some of the videos I found the most interesting and understood the most were a video by carl sagan, a crash course on machine learning by google, as well as some videos detailing their enterprise methodologies, one about how to make presentations intriguing, and a lot of very interesting but hard to understand as well videos on quantum physics.

## Lectures

Starting with the missing semester ones, I had a nice understanding on why we need tools like Vim, we need to write a lot, but the way we write is very much different than writing a book or an article for example, so we need ability to write code, and ability to use an editor.
We can choose any editor we please, but here we learn why Vim is an incredible tool that, while a bit tough to get around on your first go, can allow you to write in ways you never imagined, being also extremely customizable.

Then we learn about Git, one of the most important tools in version control. It's essential to use it while working in teams, and facilitates so much work that people never even thought about, it's a bit tough to understand at first, but unlike Vim, it's very easy to master once you can handle the basics.

Moving on to the testing lectures, the "Mocks are not stubs" was a very informative reading about how implementing objects that simulate a real working environment to test code is very efficient, but there is a key difference in these *"doubles"* which is that mocks are more complex and simulate more of the intended behaviors, and stubs mostly just tell you what you want to hear, what you program them to say.
Then we had unit testing, and one of the most popular frameworks to work with it, which is Xunit. These are tests focusing in a low lvel part of the software system, these tests are written in a tool like a programming language, and since they are not supposed to use the whole system, they are quite fast. In other words, Unit testing tests *classes* or *functions* alone, in a separated environment.

All of these readings sort of clicked with me when I remembered Test Driven Development, which was this sort of cycle where we create tests, we code this tests to pass, we integrate them into our program, we deploy it, we release it and finally, we keep it update it, we maintain it or *steer* it.
However, the main thing of TDD is that if at any point, any of the steps in the cycle fail, we get back to testing. It's important to keep in mind how we'll test the project while building it.

## Videos

Pale Blue dot is an existencialist masterpiece delivered in 4 minutes, because Carl Sagan was a genious and understood that we're just so unimportant, but at the same time, the most important thing we have. Be nice, have a good time.

We then watched Bret Victor rant about how programming tools and mindsets have stagnated in both the future of programming and inventing on principle, where we learn about how it's difficult to adapt to new ways of creating and we tend to elitisticly stick with our old ways of doing things.
Reminds me when I was learning Rust, Scala and Go, and I couldn't help but think how weird this languages were, but then I realized, if I had learned this languages first, maybe I'd think c, java and python are weird. Get it?

We also watched machine learning by google, imparted by Josh Gordon, and if I gotta say I learned something, it would be... damn, python makes ML look easy! because it kind of is, it's just the mindset and theory you need to master, since somebody else already built tools to make coding it easy. Beautiful.

Then we checked _"the best presentation of your life"_ By Enric Lladó, which was in spanish surprisingly, it was a very good video about how making your presentations engaging, and why you should explain that what you're about to say is interesting or valuable.

There was this google talk, about basically how to grow and why do we stop. It was very interesting, it's mostly about learning to work in teams and learning to lead to success, how we can keep growing and learning if we have the proper mindset. We sometimes are just scared of going forward, so he coins the term **feedforward** to explain how to keep learning and be focused.

Finally the quantum physics talk, oh boy...
I learned that there's so much we can get out of current technology and theorems, as we think of them now, we need to move forward on how we think reality works, what we have now has worked for a long time, but we keep looking for more.
Quantum computers promise doing calculations and connections in ways we never even imagined, allowing us to go even further in the computer science field, something tells me I'm gonna have to properly learn about them sooner or later given these reasons.
It's really mind boggling to think that reality and physics as we know them might not be the most accurate to what is actually out there, but if I have to be completely honest, I had a hard time with these videos, I got lost easily, very, very interesting topics nonetheless, or should I say *"fancy"* topics.

## FINAL ACT: DON'T THINK I FORGOT ABOUT IT

We were tasked with solving a jave problem about Big Data, I spent the first two days since I received it working on it, when I got to the hard part I realised I was missing something to solve it, when I read the first lecture I then understood I had to use what I'd learned from that in the problem.
We gathered and discussed solutions and I shared my take on how to solve it, we didn't give specific details at the time, but we managed to get a vague idea on how to solve it.
With that, I solved it and focused on the videos the rest of the week, never worked with maven before, but I've had my fair share of Java issue solving in my days, mahout was new to me, and implementing it at first was very complicated because it wasn't automatically importing.

Other than that, it was a fun excercise.

## Conclussion

Fun week, complex topics, my head was spinning with those quantum physics videos, and my heart was pounding each time i wrote <code>mvn test</code>.
Thanks for reading.