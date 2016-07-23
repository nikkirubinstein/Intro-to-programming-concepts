Data types
==========

<!--sec data-title="Learning Objectives" data-id="obj" data-show=true data-collapse=false ces-->
-   to fill in later

<!--endsec-->
<br>

------------------------------------------------------------------------

**Table of Contents**

<!-- toc -->
<br>

------------------------------------------------------------------------

Introduction
------------

So now we know a bit about the data types and data structures that
computers can understand. The next step is to talk about programming
concepts. With each example, I’ve shown you a piece of code to create
data types. So we can create data types and we can assign them value and
store them with names as variables. But what if we wanted to query them.
What if we only wanted to run our code if certain conditions were met?
Such as I only want to analyse the data for participants that have no
missing values, or only for people over the age of 75, only for people
that have brown hair? This is where conditionals come in to the picture.
Everyone up on your feet. Let’s play Simon Says…. In this case, you were
being the computer. I gave you a conditional statement, if I say simon
says then follow the instructions, otherwise don’t do anything. The
important parts here are the word if, the condition that needs to be met
- in this case whether I said Simon Says, which can evaluate to a
logical values - true if I said Simon Says and false otherwise and then
the instructions to follow if the conditional is true and the
instructions to follow if the conditional is false. Let me give you
another example, if number is greater than 5, yell out greater than 5,
else yell out not greater than 5. Number is 6. Number is 4. Number is 5?
I think you’ve got it. Here is an example of some code written in R to
check whether I should eat the tim tam. If I’m hungry then the computer
will print out give me a tim tam!! If I’m not hungry, then the computer
will tell me to politely decline the tim tam. Hungry is a logical value
that is true if I’m hungry and false otherwise. And that is
conditionals. Now we’re going to look at loops. One way we can write
code is to spell out each instruction one by one. Even though it might
be a bit repetitive. If we wanted to print the numbers 1:10 we could say
print 1, print 2, print 3, print 4, etc. Or if we want to analyse
patient data, we could say analyse data for patient 1, analyse data for
patient 2, analyse data for patient 3, etc. If you have several hundred
patients, that would end up being a lot of copy and paste! This is where
we can use loops. When you’re repeating the same instructions - such as
print or analyse - over different data, you can use a for loop. Let’s
create one now. For each table in the room, yell out the team name and
the number of people sitting on your table. Let’s start at the back of
the room. We’ve just created a for loop. The important thing to note is
that we have a collection of items that we want to apply the
instructions to - in this case the tables in the room - and the set of
instructions - which were to yell out the table name and number of
people sitting on the table Now you can create a for loop for me - you
can give me 4 dance moves - make them simple because I’m not very good -
and I will repeat them 4 times Here I have an example of the two step,
universally popular with uncoordinated people. I have written the
instructions once but have asked the computer to repeat them 4 times for
me. You can see that they quickly exceed the length of my slide. The
items I am repeating the instructions over are the numbers 1 to 4 and
the instructions are the dance steps. Hopefully you get the message that
for loops are useful for repeating instructions over a collection of
items and can save you time on writing lots of lines of code as well as
a lot of copy and paste! The last concept we’re going to talk about is
my favourite, functions. Functions are a series of instructions that we
have given a name to. We can then call that function by name and the
instructions will be run by the computer. This is again useful to reduce
the amount of copy and paste required when repeating instructions. An
example might be that you are constantly wanting to convert units from
celsius to fahrenheit. You could store the formula as a function called
convertcelsiustofahrenheit and then call it each time you want to make
that conversion. Then you don’t need to remember the formula We use
functions all the time. When I walk across the room, I am telling my
brain to walk, but I’m not consciously telling it which muscles need to
be activated for that to happen. In this case the function would be
named walk and the series of instructions required to walk would be
stored in that function. Note that you can’t access the instructions
inside a function when you call it by name. You only get the output. So
the temperature conversion function will convert temperatures for you,
but not give you the temperature conversion formula. Another function
can be found in cooking. When following a recipe, cookbooks often assume
knowledge. They assume that you will understand that dice means take a
knife and cut ingredient into small cubes. In this case the function
name is dice and the instructions are to take a knife and cut
ingredients into small cubes. Or that sautee means fry quickly in a
little hot fat. You can also artificially create functions. Let’s create
a function called name the singer. You can be the computer and evaluate
the function for me. Name the singer of hit me baby one more time. Name
the singer of Story of My Life. Name the singer of the Piano Man. Great
work. Again, I want to stress that I don’t know the steps that you took
to come to your answer, I only get to know what the answer was. Here is
an example of a function that I have written in R called moodCalendar. I
could give you this function so that you can check what my mood is
likely to be on any given day so that you can decide whether you want to
talk to me that day….
