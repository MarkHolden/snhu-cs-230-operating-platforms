# CS-230 Operating Platforms

## Briefly summarize The Gaming Room client and their software requirements.
### Who was the client?
The Gaming Room is a software company that has a game which renders images at a steady state for players to guess, and would like to expand to additional operating platforms. 

### What type of software did they want you to design?
The type of software was basically a cross platform team collaboration software that would also render images at a steady state.

## What did you do particularly well in developing this documentation?
I think the best part of the documentation, and also the thing that I learned that was most important for my career is the part about memory management. I have had a vague notion of the heap and the stack and the fact that they are places where memory is, but I have never considered the performance implications of keeping allocated memory together by requesting memory on the heap once at application startup, and preferring to use the stack as much as possible.

## What about the process of working through a design document did you find helpful when developing the code?
Having something to refer back to and not have to keep every detail of the system in my brain all at once is helpful for me. I have had the most success on projects where I have written a detailed System Requirements Specification (SRS) before writing any code because 
1. I knew the system inside and out before writing any code
2. I needed to quickly provide the interface specifications to other developers so they could start on their pieces.
3. I had something to refer back to for details.

## If you could choose one part of your work on these documents to revise, what would you pick?
I wasn't really pleased with how my evaluation portion turned out. It might be just because the skinny columns make it hard to see and read, but the content could also use a refactor.

## How would you improve it?
The first thing I would do is decide a table structure that would prevent the text from being in super narrow columns. 

## How did you interpret the user’s needs and implement them into your software design?
To interpret the user's needs, I read through the requirements provided by the client, and try to put myself in the position of someone who is actually using the application. If one of the requirements doesn't make sense in that context then I need to get more information about it because either I don't understand the requirement, or it is not a good requirement and should be removed or improved.

## Why is it so important to consider the user’s needs when designing?
The importance for a game is that if the game doesn't meet the end user's needs, then they won't play it, and the client won't make any money, and as a result I won't be developing any more games for them, so it behooves me to meet the needs of the end user.

## How did you approach designing software?
My approach was not a well thought out plan, but more of adding on features that I have seen before and trying to get them to work together without an underlying framework for how the systems work together.

## What techniques or strategies would you use in the future to analyze and design a similar software application?
The company that I work for right now is striving to implement domain driven design (DDD), and because I want to be indispensible to them, I need to be familiar with DDD and become an expert over time.