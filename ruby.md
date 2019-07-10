# Ruby Assessments

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What is a method in Ruby? How is it different or similar to functions in JavaScript?
Methods in Ruby are similar to functions in JavaScript, because they both take in input, do something with it, and returns back a result.
They are called methods in ruby because everything in Ruby is an object.

#### 2. What does it mean that a class inherits from another class? Try to explain Ruby inheritance. 

[Your Answer]
When a class inherits from another class, the inheriting class takes on attributes from the higher up class.
The inheriting class is then able to add on attributes that is unique to itself.

[Googled Answer]
Inheritance is a relation between two classes.
The benefit of inheritance is that classes lower down the hierarchy get the features of those higher up, but can also add specific features of their own.

#### 3. What is rspec and what is the general process for writing tests in RSpec?

//Your Answer
Rspec is tool to test Ruby language code.
You want to create a testing file in the same folder as your code.
In your testing file you will want to link to your code and cd into the testing file.

//Googled Answer
RSpec is a 'Domain Specific Language' testing tool written in Ruby to test Ruby code. 
It is a behavior-driven development framework which is extensively used in production applications.

#### 4. Name three possible non-inheritance relationships between ruby objects? 

//Your Answer
Ruby does not allow a classes to inherit from multiple classes.

//Googled Answer
Inheritance is a relation between two classes. 
We know that all cats are mammals, and all mammals are animals. 
The benefit of inheritance is that classes lower down the hierarchy get the features of those higher up, but can also add specific features of their own. 
If all mammals breathe, then all cats breathe. 
In Ruby, a class can only inherit from a single other class. 
Some other languages support multiple inheritance, a feature that allows classes to inherit features from multiple classes, but Ruby doesn't support this.

#### 5. What do we call the #{} convention used below? What is it accomplishing?

```ruby
x = 1022
puts "I am printing a random number #{x}"
```
We would call the #{} string interpolation. We use it to insert an expression into a string.

#### 6. How do you feel about testing right now? What potential pros/cons/barriers/advantages do you see to implementing BDD in your own code?

//Your Answer
I feel decent with testing. It is definitely something that I need to practice more.
I can see the benefits of testing as it tells you that your code is doing what it is supposed to be doing.  

//Googled Answer
Behaviour-Driven Development (BDD) is a set of practices that aim to reduce some common wasteful activities in software development: Rework caused by misunderstood or vague requirements. 
Technical debt caused by reluctance to refactor code.

#### 7. What is an instance variable in Ruby? How is it different from a normal, local variable?

//Your Answer
An instance variable is available everywhere withing an objects scope.
The difference between an instance and local variable is the scope within the object.
An instance variable has a broader scoper that is available anywhere within an object, while a local variable is only available within the method.

//Googled Answer
Instance variables live in, and are visible everywhere in the object’s scope.

#### 8. Ruby has a great community and tons of free resources to help you learn. Here is the long list of great resources: https://www.ruby-lang.org/en/documentation/. Below are a few popular ones:
- Interactive Ruby tutorial (http://tryruby.org/levels/1/challenges/0)
- Why's (poigniant) Guide to Ruby: comics, anecdotes, and microscopic canaries (http://poignant.guide/book/chapter-1.html)
- Ruby in 20 min (https://www.ruby-lang.org/en/documentation/quickstart/)


Choose one of these resources and go through the material (not for hours, only looking for around 10min of your time) then come back here and list a few new things you learned about Ruby.

Poigniant guide means code so beautiful that tears are shed.