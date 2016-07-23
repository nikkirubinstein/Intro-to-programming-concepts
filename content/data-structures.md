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

Now that we have our data types - numeric, logical and character strings
- what sort of data structures can we create? In spoken language we make
sentences, paragraphs, essays. In programming, we have vectors,
matrices, lists and dictionaries. Let’s go through these one-by-one.
Vectors or tuples (the terminology changes depending on the programming
language that you use) are ordered groups of variables of a single data
type. Now when I say ordered, I don’t necessarily mean in ascending or
descending order, just that the order matters. Let’s create a vector of
people. Can I get table *x* to stand up and come up the front and stand
in a line. This is a vector with *x* number of elements. We’re going to
number the vector from left to right, as I call your element number
please tell everyone your name. 1,2,.... Now let’s create a new vector
by ordering in height order. Now in alphabetical order. Great work, you
can sit down now. So let’s have a go at doing the same things but
instead of using people as the elements that make up our vector, let’s
use the data types that the computer can understand. Each table needs to
make 3 vectors using the coloured paper on the tables. One logical
vector, one numeric and one character vector. These can be of any length
that you like. Don’t forget that order matters. You have 2 minutes to do
this one. Can table *x* give me their numeric vector? Table *y* give me
their logical vector and table “z” give me their character vector? Great
work. Here is an example of creating a couple of vectors in R. The first
vector is very imaginatively called vector 1 and have the values 1:10
stored in it. The second vector, called vector 2, has the character
strings learning to code is fun. So now we have vectors. You might have
noticed that they are 1-D. What if we have a table of values with rows
and columns? We can store 2dimensional data using a matrix. Data frame
or array. Again the terminology changes based on the programming
language that you are using. So to explain matrices, can I get table *x*
to come up the front and help me. We want a matrix with 2 rows and 3
columns. Can you arrange yourself like that? Now I want a matrix with 3
row and 2 columns. Instead of referring to you by name, I could now
refer to you by your row and column number. So if row 1 is the back and
row 2 is the front, while column 1 is the left hand column and column 3
is the right… raise your hand element in row 1 column 2. Row 2 column 3.
Row 5 column 2. You have to be careful when using data structures that
the element that you are referring to actually exists. Now let’s create
matrices using the data types the computer can understand. Each table
should make a single matrix. Your matrix can only contain one data type,
so I shouldn’t see any multi-coloured matrices. You have 2 minutes.
Table *x* can you describe your matrix for us? What data type, how many
rows and how many columns? Table *y*? Here is some example R code. Data
frames are data structures unique to R, so I have used that for my
example. In ResBaz we are broken up into four different platoons, which
each platoon having a lead. I have represented that here by creating a
variable called platoon leads, which is a data frame with 2 columns
called platoon and name and four rows, where each row represents a
different platoon. So we’ve seen vectors and matrices, but what if we
want to store different data types (numeric, logical and character
strings) together in the one data structure? And what if we don’t have
the same number of elements in each of the different groups? We have 2
numbers, 1 logical and 5 character strings. This is where lists or
structures come into the picture. Here I have a picture of a collection
of musical instruments, with many more wind instruments than string
instruments. I could represent this as a list with 2 elements, one
element would be a vector of string instruments and the other a vector
of wind instruments. Can I get table *x* to come up the front and help
me to give an example of lists. I want two elements, one containing a
vector of males and one containing a vector of females. And now I want
to create a list with each element representing a different hair colour.
Great you can sit down now. Now I want each table to create an example
of a list using data types that the computer understands. Each element
of your list can contain either a single variable, a vector or a matrix.
You have 2 minutes. Table *x* can you describe your list to me. How many
elements and what does each contain? Table *y*? I have an example of a
shopping list, that I have broken down according to meal, where the
number of items is different for each meal, so I have stored it as a
list. I have called the variable shoppinglist. We’ve looked at vectors,
matrices and lists. The final data structure we will look at, which is
unique to the python programming language is dictionaries. Dictionaries
contain pairs of variables, values and keys. When we created vectors, we
could look up the element by its number in the vector. In contrast
dictionaries are unordered and you look up elements by their key. Much
like opening a dictionary, where the word is the key and the definition
is the value. It’s important that each key is unique. It would be
difficult to look up the meaning of a word in the dictionary if the word
were repeated multiple times with completely different meanings each
time. The keys must all be the same data types and the values must be
the same data type, but the data type of the keys can be different to
the data type of the values. For examples, the keys may be numbers and
the values vectors or tuples. Have a go at creating a dictionary by
pairing up keys and values using the data types on your table. You have
3 minutes. Table *x*? Table *y*? Here is an example of a dictionary
written in python. I have called it IMDBRatings. The keys are character
strings: game of thrones, sherlock, firefly, friends and the values are
numeric values that represent the average rating of those tv shows on
IMDB