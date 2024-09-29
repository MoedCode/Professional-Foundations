# Data Preparation Techniques Pt 1
Most of the data cleaning that you will do will most likely be in a data processing app or spreadsheet app like Google Sheets or Microsoft Excel. In this module, you will learn how to use specific techniques using Google Sheets or Microsoft Excel.

We will refer to both Excel and Google Sheets. We have talked about Google Sheets at length in Month 1 and we want you to be familiar with Excel too. You do not need Excel on your computer. If you have it please use it to follow along with the videos we share. If you do not have Excel you can follow along using Google Sheets. There will be slight variations in the process but the logic is the same. If you know how to use Google Sheets you will easily figure out Excel and vice versa. They are both spreadsheet applications and very similar in function.

Okay, let’s get started!

As you clean and prepare your data set further, you can use the techniques below and on the next few pages to make it as pristine as possible!

Note: As you’re going through this lesson, it would be best practice for you to open your Excel (or Google Sheets) on your computer and play around along with the videos and exercises!

Decimal Formatting
Sometimes it gets really tricky handling decimals in Excel or Sheets. We have got your back, this video helps you understand how to manage decimals in Excel. And the use of the round function to help you get your desired outcome.



References:

https://youtu.be/ux_7pZdQFfs
***Desorption***
```md
478,527 views  20 May 2015
Quick tutorial which shows how to round numbers to a set number of decimal places in Excel, and how to add decimal places to whole numbers.
Transcript
Follow along using the transcript.
```
***Transcript***:
```txt
hello so you have a spreadsheet with a
column like this containing more
decimal places than you know what to do
with how can you round those numbers to
a set
number of decimal places
if in your spreadsheet you end up with
formulas that generate numbers that have
huge number of decimal places and it
gets we
unwieldy it gets scruffy and tidy and
how can you round those numbers
so that they are a set number of decimal
places
so one or two decimal places at most
it's actually quite simple and to
demonstrate this i'm going to
insert a new column and put a function
in this column
which takes these numbers and rounds
them to
two decimal places the function itself
is the
round function so we simply type equals
and then round open up our brackets
and select the cell we want to round
that's e2 and then we have to just put a
comma
and the number of decimal places we want
to round that number to so let's say we
want this number to be rounded
to two decimal places would type a two
and then of course close our brackets so
equals
round this number to two decimal places
if we press enter then we can see we've
now rounded this number
to 67.33 if i quickly change that
two to a three we can see we're rounding
that number now
to three decimal places we could do the
same
for one i'm going to keep that to two
for the moment
and replicate this formula
down by grabbing the box at the bottom
right corner
drag that down so that all of these
numbers
are now rounded to two decimal places
except of course they're not because
these two numbers
were not uh they did not have decimal
places at all they were whole numbers
now this can look a little scruffy some
people prefer it if
all the numbers have the same number of
decimal places
regardless of whether they need decimal
places or not
how can you do that the quick and simple
way of doing this
is to highlight all of those cells and
at the top
in your home tab find this
number section on the ribbon and on the
right hand side
of the number section you have these two
little buttons with
three zeros on the first one increases
the number of decimal places
and the second one decreases the number
if we click on the first one and then
the second one
what you can see is that it
automatically adds
the decimal places in for the numbers
which didn't need them in the first
place
there are other ways of doing it such as
going into the number menu and choosing
number
um but this is the the quickest and
simplest way of doing it
so just show you that again simply
highlight the cells you want to
uh have all the same number of decimal
places for
and in the number section where you have
the increase and decrease decimal places
click one then click the other and then
you're back
to showing the same number of decimal
places as you were originally
with the added benefit those numbers
that didn't originally need
decimal places now have them and that
looks a lot neater and simpler
so that's how to have all of your
numbers
rounded to a certain number of decimal
places
whether they need it or not
you

```
# Data Preparation Techniques Pt 2
Practice Example 1
Consider the data below. Input this information in Excel and use the tools available to you to format the height and weight columns to show figures with 2 decimal points. Apply the same font and font size. Make the text to align uniformly throughout the dataset. Go ahead and try it now!

Student_ID	Height (cm)	Weight (kg)
22122018	65.325	52.233
23252018	67.1	55
25282018	60.287	61.3
14152018	53	80.124
Below are other steps you would normally take when cleaning a dataset:

Make sure the text is aligned correctly and uniformly throughout the dataset.
Make sure the text and background colours are complementary. The standard is to use black text and a transparent/white background.
Do a general observation/screening and make sure all abnormalities are checked for.
Check specific columns and rows and make sure you address inconsistent formatting.
Also make sure the right type of formatting is used (number, text, date, etc.)
Make sure the information is correct.
If there is a lot of data, make sure the relevant rows and columns are frozen so that you know what information you are reading.
Make sure column/row headers clearly identify the information being presented in the cells.
Make sure each column/row has enough space to easily read the information presented in each cell. Increase the width/height of the column/row or wrap cells to allow this.

# Data Preparation Techniques Pt 3
Let’s now watch and follow along with these videos to understand the Split function in Google Sheets.
As explained in the videos, splitting or merging text into separate columns is a very important technique in data preparation. It may not be important for every analysis but based on what you intend to do with the data sometimes certain information may not be readily available to you, hence you must split cells or merge cells to achieve this. For example, let’s say you have a dataset of Student Admissions. The dataset contains student ID, gender, and date of birth (in the format DD/MM/YYYY). In your analysis, you want to find out the number of students born in a specific month, as well as the number of students born after a particular year.

Both of these elements are contained in one column called Date of birth. One way of separating the different elements would be to split this information into separate columns.



References:

https://youtu.be/_RZYr8127fo

***Desorption***
```md
Google Sheets SPLIT Function Tutorial - Text to Columns Using a Delimiter, INDEX, COUNTA, IMPORTRSS

Learn Google Sheets & Excel Spreadsheets
276K subscribers

Subscribe

1.1K


Share

150,345 views  12 Dec 2016
This video is about SPLIT function in Google Sheets and various ways it can be applied. Other functions covered in this video: INDEX, COUNTA, IMPORTRSS.

SPLIT Function
https://docs.google.com/spreadsheets/...

New York Times RSS Feeds
http://www.nytimes.com/services/xml/r...

Google Sheets
https://www.google.com/sheets/about/
```
***Transcript***:
```txt
today we'll be talking about split
function
primarily uh obviously we'll be covering
some other functions and some uh
interesting ways you could apply split
function but primarily it's going to be
about split function so I'm going to go
ahead uh we're not going to be using any
existing data so I'm going to start with
a new
spreadsheet let me name this
spit
function as usual uh all the links uh
and all the worksheets uh for this
tutorial will be under the
video so you can use them anytime you
want so uh first I will need some data
for my split function so what I'm going
to do uh go to New York
Times and while we're on it we'll learn
some other functions and in New York
Times we have a lot of sections right so
if I go under the sections link all the
way on top left you'll see we have all
these different sections for example we
have the section for the US and under
the US section we have subsections like
education so I'm going to go there it's
good enough so that's our education with
see some of the latest articles posted
on the New York Times so uh what we will
do right now uh we'll try to find the
RSS feed so on New York Times that's
under my
times.com
RSS so here are there RSS feeds so I'm
going to go under the same if you
remember it was under the U us education
so there we are
us
education so there is our RSS feed so
we're going to import this to Google
Sheets so I'm going to copy
this I'm going to go to my
new Google Sheets Tab and I'll start
with a function called
import
feed so import it is a function uh that
will let you import RSS feeds basically
and what is uh the RSS basically is a
type of
XML format so this is a simplified
version I guess you could say of an XML
so if you wanted to dig deeper into it
you could also look into import
XML function but but for now uh the
first argument in this function is the
URL it has to be string so therefore
coach I'm going to paste the RSS link
and quote that's our RSS link so the
second portion of this links will be
what I'm trying to get out of that link
so in our RSS basically what I'm going
to try to do is just get this titles for
our articles that we have
so if we look under our RSS right
here uh and it helps if you understand
RSS or some HTML but if you don't even
then it's not a big deal so I'm looking
for this item section so if you look
this is the first item that shows up
here and under the item there is title
and that's the title for our first
article so at some point there's going
to be another
item and there it is and there's the
title for the next item and so on so to
breach to those titles what I'm going to
do is provide a string
items title and again this video is
primarily about split functions so I'm
not really going to go into much of
details how to use import feed function
and so on uh you may want to watch
another video that covers that in detail
now the next thing is headers so this is
a Boolean so true or false argument so
whether you want the basically the title
or the header or the column
label on top so I guess I'll put in true
so we'll have the column label in there
so and the last argument is how many
items we want I'm not going to use it
it's optional so I'll just close this so
there is my
import feed function I'm going to hit
enter and everything went well as you
can see if I double click see the first
article is Google effect robs off
whatever that is so there it is that's
the first one then this probably should
be the second
one uh no I guess the second one is this
one feature
of f Ms if we can find where that comes
from that would be nice oh I guess comes
from here
interesting so so it goes so there it is
now we have some
data so now that we have these titles we
would like to use our split function so
what is a split function so basically uh
easy way to say a split function if
you've ever used in Excel like text to
columns functionality that's basically
you can think about it kind of like that
that functionality only inside of a
function which gives you some advantages
and we'll really talk about those
advantages in just a little bit but if
you just go ahead and just type equals
split right here that's our function so
the first argument is the text we're
working with so I'm working with this
text on the left comma and the second
parameter is our
delimiter so
if I want the limiter basically the
separator as a space then I'll go quote
space quote now there's a third argument
in this function
and this is only going to make any
difference like the third argument if
you have more than one
character here right here between this
two quotes right now I have just one
character so it doesn't really matter so
I'm just going going to close this down
and hit enter so right now you'll see
how we split that text using the
space and all of the cells going to the
right so just like that so now let's
look into
this having a second character option
so let's say I have a second character
and I want to split by both of them and
one of my character is going to be the
space
and the other character is going to be
this lowercase o character so we have
one on this on and another one on this
town so I'm going to basically just
after the space type the character
lowercase o so if I enter you'll see how
the text is being split there it is oh
there also I have
this double O here uh now this is case
sensitive so you'll see that this off
which is uppercase isn't being touched
so now we're using both characters to
split the text the space and the
lowercase o now if you want the
uppercase o you can just add it so you
can just keep adding all the characters
you want to split by so this is where
this last argument makes a difference so
if I do another comma and there it is
this argument split by each so right now
by fold that's pretty much what it's
doing it's basically splitting by each
so that's if we do true we should really
get the same results but if I change
that Lo argument to
false hit enter see nothing happened so
everything is in one single cell there
it is so right now what is doing instead
of splitting by each one of these
characters is looking at this entire
character set as one string so if what
I'm splitting by
is let's say space on
space I can still do that but now I'm
looking at all those characters as one
whole long string that I want to split
by instead of just having many
characters we're splitting by
so there you go so obviously you can
just drag this
down uh and get it for each one of these
characters but I'm going to go ahead
just since we've covered what this
are so we know what those are so I'm
going to go ahead and just split it by a
space so there it is so now we have this
all of them split by a space and again
if I
pull this down it's just going to split
each one of those and use the space for
for that
separation so now let's get to the cool
part so this is like our regular text to
columns now what's interesting about
Google functions like this they're
basically like returning an array and
they're just putting this entire array
in the cells going to the right however
the function itself again returns an
array right so therefore we'll be able
to use that function inside of another
function as an array so what does that
mean so this brings us an interesting
opportunity to make some functions that
in Excel are pretty complicated very
simple actually in Google Sheets so
let's say what we want to return is the
first
word of each one of these titles we have
to the left
so what we can do we can wrap the split
function inside of an index function so
what does an index function do so let me
just for those who don't know what index
function does I'm just going to do a
very quick explanation if you want in
depth for index please watch the index
function video so I'm going to go ahead
and basically
just type equals index
and the first argument in our index
function is our reference so I'm going
to give it this range of numbers which
is
ABC so we can think about it as an array
of numbers in a way so comma the next
thing is our row index so there's an
optional column index we're not going to
be talking about it today but for row
index I'm just going to type three and
just close my codes so what is this
going to do so so let's hit enter so you
can see it's returning C the re reason
it's returning C is basically I'm giving
this array to my index function or range
I guess and we basically go from top one
two and three so the third element in
this array is C so therefore it's
returning that c so if
I hit the second element it's going to
return to B and the first element it's
going to return that a so that's
basically our index function in a
nutshell so now I'm going to go back
here and as I said what I'm going to do
I'm going
to basically just select the split
function without the equal sign and I'll
press control X or command X if you're a
on if you're on a Mac right and as I
said we we want to put this
split function inside of our index
function so I'm going to go ahead and
type
index there we are so the first thing we
want to do is the reference so the
reference if you remember is an array so
what I'm going to do just
paste my split function right there as
my reference so that split function is
going to return an array and I'm going
to do comma Now I want the first element
in that array so there it is
one and close that parenthesis hit enter
and there it is I'm getting the first
word of the title so if I send this down
you can see that I'm getting the first
word of all of those different titles we
have on the left so here we go so that
that's are split with index so this is
how we can oops let's get this back
return so first
word so obviously if you wanted to get
the second
word that's pretty straightforward right
so
second word so you would just go ahead
and do your index function and then I'm
going to paste my split function and
instead of one it's going to be two
so very easy to get the first the second
the
third whichever word you need out of
that shouldn't be a problem at all so
that should be nice so now let's say
what we're trying to accomplish is get
the last
word so for example the town hit
schools unionize those are the words
we're trying to get the last word so how
can we get the last word so first of all
we have to figure out uh so what do we
do here uh we basically provide the
index which word we want so uh that's
like if we had to count one 2 3 4 5 6 7
8 9 10 11 right that's our word 11 here
but it could be different so it's not
always going to be number 11 so what we
have to do we have to figure out a
dyamic way to figure out what is the
last word in each one of these so what
I'm going to do actually before we get
the last word let's get the last
word number I
guess or index whatever we want want to
do so how can I get the last word index
well as I said split function returns an
array so an array is going to give me a
number of items so if I had a way to
know how many items that array has the
that would be basically the last item so
how can we do that simply by using our
counter function so there's by the way
you have to be careful there is a
function count so count only will count
if it's a number now in our case
obviously it's not number so it's going
to be counter to get numbers and so
basically it's alpha numeric count so
counter so the
first argument is the range in our case
the range is going to be our split
function so I'm just going to do split
function and close our parentheses for a
counter function hit enter and you see
it's number 11 great now let's see if
we're getting the right thing for them
so there it is we got number 11 for this
number 10 for this number seven for this
so that's how we can get the count and
figure out which
number that is so that's nice right so
now that we have the last one word count
we can also get just the last
word so how are we going to do that so
pretty simple we'll go and type our
index function the first one it will be
the reference so the reference if you
remember is going to be the array so I'm
going to paste our split function that's
going to give me that array I'm going to
do comma and this is where we get the
number so I could simply click on this D
B2 cell but I want this function to be
independent from this column to the left
so therefore what I'm going to do is
just give it counter function just like
that and paste my split function one
more time I'll do another comma to close
the counter function here and I'll need
another comma to finally close my index
and you can see it's already displaying
that the answer is town that's great
that means we're getting the right thing
I'm going to double click Send this down
and you can see town hit schools uniz
there we are we got the last
word of each one of those and again if
you wanted the second to
last that should be a pretty easy one to
figure out now so to really save time
here I'm not going to type the whole
thing in I'll simply just copy
this entire function here escape to get
out of that I'll paste it in here and
instead of having
counter return we want one less so I
simply do minus one so there it is it's
going to
be second to L so there it is we can see
that it works just fine it's looking
good so those are some
of you know some interesting ways you
can actually
apply our split function and use it
together with our index and counter
function to do some cool tricks

```

# Data Preparation Techniques Pt 4
Now let’s watch the next videos, follow along and learn how to use the merging funding and VLOOKUP function. Both will come in handy when you are preparing your data.
1. The Merging function in Google Sheets

Sometimes the data will be in multiple categories and you’d want to format it for better and easier understanding. This is where the merge function can help. Let’s see how it works.
***Desorption***
```md
How to Quickly Merge Cells in Google Sheets (Horizontally, Vertically, Unmerge)

Spreadsheet Point
13.5K subscribers

Subscribe

637


Share

145,835 views  30 Dec 2016  #GoogleSheetsTips #GoogleSheets #Spreadsheet
Article Link: https://spreadsheetpoint.com/merge-ce...

When you work with data that has headers, sometimes, you may feel the need to merge cells in Google Sheets.

For example, if you have the main header as Revenue and subheaders as 2016, 2017, and 2018, you can merge the three cells that make up the revenue header.

In this video, you'll learn how to quickly merge all the cells, merge cells horizontally, merge cells vertically, and unmerge cells in Google Sheets.

00:00 Intro
00:10 Example of Merged Cells in Google Sheets
00:27 Megre Option in Google Sheets
01:00 Merge All
02:02 Merge Horizontally
02:35 Merge Vertically

Note: When you merge cells, it only retains the value in the top-left cell. If there is anything in cells apart from the top left cells, Google Sheets shows you a prompt.

Read More about it here: https://productivityspot.com/merge-ce...

You May Also Like the Following Tutorials:
--    • How to Freeze Rows and Columns in Goo...
--    • Split Text to Columns in Google Sheet...
--    • How to Add a Drop Down List in Google...
--    • How to Insert an Image in a Cell in G...

Subscribe to this YouTube channel to get updates on Google Sheets Tips and Google Sheets Tutorials videos -    / spreadsheetpoint

This channel is meant for people who want to learn about Google Sheets and be more productive in their day to day life. It covers a range of Google Sheets topics such as useful Google Sheets features, Google Sheets functions, Google Sheets formulas, Pivot table, Google Apps Script,.Shortcuts, Google Sheets Charting, Data Analysis, etc. Please subscribe to this channel and never miss a new video on Google Spreadsheets

You can also find a lot of useful resources on Google Sheets here: https://spreadsheetpoint.com/

#GoogleSheets #GoogleSheetsTips #Spreadsheet

```
***Transcript***:
```txt
hello and welcome to the video by
productivity spot I'm Sumit bunel and in
this video I will show you how you can
quickly merge an unmerged cells in
Google Sheets here I have a data set and
Example of Merged Cells in Google Sheets
you can see that I have merged these
three cells B1 C1 and D1 as one so that
I have a main heading here which is
revenue and then within that I have
these subhe headings which is 2016 17
and 18 so there are cases when you may
need to merge these sales because you
Megre Option in Google Sheets
need to create something like this so
let's see how to quickly do this I'll go
to sheet two here and here I would type
what I want in the merged cells here in
the top left cell remember that only the
top left value is retained everything
else uh is Lost And now when I select
all these cells all these three cells
here I would go to format merge and then
I would click on merge all and as soon
as I do this it'll instantly merge these
cells it becomes one and the value in
the top left cell has been retained
which is revenue now now let's see a
Merge All
couple of examples here so let me first
show you how we can use merge to merge
all the cells and make it one so here in
this case I have two rows and two
columns in this data set and I would
select everything I would go to format
merge cells and I would click on merge
all when I do this this entire thing
would get merged as one single block so
when I click on merge all it gives me
this prompt which is merging cells will
only preserve the Top leftmost Value mer
anyway so you need to know that it will
only preserve the top left value which
is one in this case rest all other
values would disappear so only have the
value here or be ready to lose the other
values and then when I click okay you
can see that I have this this block
where it is a block of merged cells and
it only retains the value which was in
the top left cell now I can quickly
unmerge it by going to format merge
cells and I would unmerge this now let's
see another example here I would have
one two and here I would have three and
four now I want to merge these cells but
Merge Horizontally
I only want to merge horizontally and
not vertically so I don't want this to
become a one block of uh merged cell
rather I want one and two to merge and
three and four to merge so to do that I
would select all these cells I would go
to format merge and I would select merge
horizontally and when I do that and
again the same prom I click okay it'll
merge these two cells and these two
cells it has merged horizontally
retaining
the leftmost value let me select and
unmerge this
Merge Vertically
again and now let's see uh the opposite
of it or which would be merging cells
vertically so I have these four cells
here I go to format merge cells and now
when I go to merge vertically it'll
merge one and two and this would become
one and it will become three and four
and this will become three so if I
select merge vertically you can see that
these cells have merged so you can
quickly merge more than one row or
column of cells based on what you need
uh and then you can unmerge it by again
going to format merge cells and unmerge
so this is how you can quickly merge and
unmerge cells in Google Sheets I hope
you found this video useful thank you
and have a nice day
```
https://www.youtube.com/watch?v=8DIKWsRYuGY
# 2. Looking Up information on different sheets

Sometimes you can have multiple sheets or workbooks with interconnected information and doing a good analysis would sometimes require fetching information from various sheets to make sense out of your analysis. A technique needed to make this happen is the VLOOK-UP function. As explained in the video, the VLOOKUP function is used to access information from different columns or workbooks to make a good analysis. Let’s see how it works in Google Sheets.




***Desorption***
```md

203,402 views  24 Jan 2020
VLOOKUP IN Google Sheets is one of the most used functions when reporting big data. In this video I’ll teach you all the necessary steps to learn the VLOOKUP formula.

Other vides you might like:
• Pivot Tables in Google Sheets - https://www.youtube.com/watch?v=bWKt1...

Thanks for Watching. Please remember to Subscribe, and click the bell notification. Also – Leave a comment letting me know how you are using the Sumif Function.
Key moments
```
***Transcript***:
```txt
hey everyone thanks for watching this
video will be all about teaching you to
use the vlookup function within Google
sheets I'll show you how to simplify a
big set of data like this one into a
single line automated report card like
this
so let's dig in before I get started I
am going to take seven seconds to ask
you to subscribe to my channel and click
the bell notification if you do that
you'll get notified every week when I
post a new video also feel free to hit
that like button or comment on what you
learned okay so here we go
in this sheet I have a list of 31 made
up students and their overall percentage
scores in each of the four quarters last
year my goal is to make an automated
single student scorecard on this page
using the V look function I want the
scores in these four cells to populate
based on the name I select in this
drop-down list the vlookup functions
simply defined is a vertical lookup in
other words it searches down the first
column of a range for a key and returns
the value of a specified cell in the row
found let's break it down further than
that though when you enter the vlookup
formula Google sheets will ask for four
criteria the first criteria will be the
search key when you're looking at the
first column of the table what value do
you want the formula to focus on in our
example the search key would be the name
in the drop down list that's the name we
want to focus on when pulling the scores
for the four quarters the second
criteria will be the range to consider
for the search in other words we'll need
to use all of the columns in the table
because we're looking at all four
quarters so the range would be the
entire table listed here the third
criteria is the index or the column
index number this is the column number
that you want the formula to focus on so
if we want the formula to only look at
the scores for the first quarter then we
will put 2 as the column index number
because it's the second column in the
table the fourth and final criteria is a
bit tricky and in most cases it isn't
even needed it's called is sorted this
basically asks you whether or not the
first column in your chart is sorted
long story short it asks you if Google
sheets should try to find the most
approximate match if they can't find an
exact match now that we've gotten over
each criteria in the formula let's put
it to work let's set up a formula for
the first quarter and then we'll build
it from there before we start the
equation I'm going to select a name in
the drop-down so we have something to
build the formula from now let's open
the formula up by typing equals vlookup
and opening parenthesis now I have to
select
the search key I'm going to select D 11
since I want the numbers to change based
on who I select from the drop-down list
then I'll type a comma to get to the
next criteria in our formula it's now
asking me for the range I want to look
at so I'm going to select the entire
table on the student information sheet
you'll notice that Google sheets is
smart enough to follow you as you go
back and forth on sheets so it's
collecting the fact that you want to
look at cells a1 through e 25 on the
student information sheet not the end of
your report card sheet after I select
the table I'll add another comma to get
to the next criteria in the formula now
it's asking me for the index or the
column index number since for this
formula I want to look at the first
quarter scores I'm going to choose the
second column in the table that means I
type 2 here then add a comma to get to
the next criteria the final piece of the
formula is essentially telling Google
sheets if you wanted to return an
approximate value I almost always select
false here because I always wanted to
return in an exact match you can also
just type 2 quotation marks here as well
which tells Google sheets you don't even
want to use this portion of the formula
now I just add a closing parenthesis to
the formula and hit enter to close it
out you can see now that if I select
Joshua Williams from the drop-down list
it returns his first quarter score
I could even go back to the table to
validate that the cool thing is now I
don't even need to redo this formula for
all four quarters if I set their
parameters correctly I can just drag the
formula all the way across all I have to
do is change two arguments in the
formula to be absolute I can do that by
clicking on the search key and hitting
f4 to ensure that it always looks at d11
as the search key and then do the same
thing for the range to ensure Google
sheets always looks at the same table
now I can drag the formula all the way
across
once I do that I still need to change
one thing in each formula I'll need to
change the column index for each formula
so when I look at the second quarter
I'll need to change the column index
number to be 3 since I'm looking at the
third column
then change it to four in the third
quarter cell since I'm looking at the
fourth column
then to five in the fourth quarter cell
since I'm looking at the fifth column
the last thing I'm going to do is add an
average here and we'll be done
equals average opening parentheses cells
11 through H 11 and closing parentheses
I'm going to bold that just for
appearance as well now I should be able
to change the name in the drop down and
these values will change based on the
name selected the vlookup is as simple
as that I hope you've learned something
and can now work smarter and set it
harder see you next time hey guys how
you doing if you learned something from
this video you're gonna want to do a
couple things first you gonna want to
hit that subscribe button and the Bell
notification if you do that you're gonna
be the first one to get notified when I
post a new video which is about once a
week I'd also ask that you hit that like
button and the share button and then
tell me what you learned in the comments
section if you do all those things this
video is actually gonna get out there
for more people to see and to learn from
thanks guys I'll see you next time
```


```
References:

https://youtu.be/8DIKWsRYuGY
https://youtu.be/EgGu8UqjnRQ
```

# Data Preparation Spreadsheet Functions
Both Excel and Sheets provide functions that allow us to work with the data to generate meaningful insights. Here is a list of some of the more helpful and common functions and how to use them.

| Function     | Function Description | Explanation                                                                 |
|--------------|----------------------|-----------------------------------------------------------------------------|
| SUM          | Adds numbers         |  allows you to sum any number of columns or rows by selecting them or typing them in, for example, =SUM(A1:A8) would sum all values from cell A1 to cell A8. |
| AVERAGE      | Calculates average   | AVERAGE does exactly what it sounds like and takes the average (arithmetic mean) of the numbers you input. For example, if the range A1:A20 contains numbers, the formula =AVERAGE(A1:A20) returns the average of those numbers. |
| COUNTA       | Counts non-empty cells | COUNTA counts the number of cells that are not empty in a range. Eg. =COUNTA(A2:A7) Counts the number of nonblank cells in cells A2 through A7. |
| IF           | Logical comparison   | The IF function allows you to make logical comparisons between a value and what you expect. In its simplest form, the IF function says: IF(If something is True, then do something, otherwise do something else). It allows you to output text if a case is valid. So an IF statement can have two results. The first result is if your comparison is True, and the second if your comparison is False. For example, you could write =IF(A1>A2, "GOOD", "BAD"), where A1>A2 is the case, "GOOD" is the output if true and "BAD" is the output if false. |
| SUMIF        | Conditional sum      | SUMIF allows you to sum cells based on a condition. For example, =SUMIF(A1:A15, "GOOD", B1:B13) would add B1 through B13 if the values of A1 through A15 all said GOOD. |
| AVERAGEIF    | Conditional average  | AVERAGEIF allows you to average cells based on a condition. For example, =AVERAGEIF(A1:A15, "GOOD", B1:B13) would average B1 through B13 if the values of A1 through A15 all said GOOD. |
| COUNTIF      | Conditional count    | COUNTIF counts the number of cells that meet a criterion. For example, =COUNTIF(A2:A5,"apples") counts the number of cells with apples in cells A2 through A5. The result is 2. |
| VLOOKUP      | Vertical lookup      | VLOOKUP allows you to search for something in the leftmost column of a spreadsheet and return it as a value. For example, =VLOOKUP(lookup value, the table being searched, index number, sorting identifier). |
| CONCATENATE  | Combines text        | CONCATENATE is used to combine data into one cell. For example, =CONCATENATE(A1," ",B2) would combine the names in cells A1 and B2 into one cell, with a space in between. |
| MAX & MIN    | Finds max or min     | MAX and MIN functions are used to find the maximum or minimum value in a range. For example, =MAX(A1:A10) would output the maximum numerical value in those rows. |

Having an arsenal of these spreadsheet Functions and mastering them will make you a spreadsheet assassin. Keep practising each of these functions and also try to identify cases and scenarios where making use of some of these functions will be useful given whatever dataset you have.

If you need a longer Google Sheets memory jog – or if words like "array” look like alien 👽 from Pluto 🛸 – feel inspired to revisit the [Google Sheets tutorials and lessons in Week 3.](https://intranet.alxswe.com/rltoken/ACSuWyMAZ4o5mKSi1yVFFw)

# Activity: Try Cleaning Data
Now it’s your turn to get some hands-on practice in using spreadsheet functions.

Instructions
1. Make a personal copy of this Google sheet that has the following information in an editable format.

Employee Name

Performance Rating

Training Completion

Course Name

Kwame Osei

8

yes

Data Analysis

Amina Abiola

6

no

Python Programming

Mpho Ndlovu

9

yes

Machine Learning

Ifeoma Okoro

7

yes

Web Development

Sadio Traore

6

no

Database Management

Tariq Juma

9

yes

Cybersecurity

Aisha Kamara

8

yes

Project Management

Oluwaseun Adekunle

7

yes

Software Testing

Nia Nkrumah

9

yes

Data Visualization

Mounir Diop

8

no

Network Security

2. Familiarize yourself with the dataset and its columns (Employee Name, Performance Rating, Training Completion, Course Name).

3. In your Google Sheet, complete the following tasks using the applicable spreadsheet function.

Task 1: Calculate the total number of employees in the dataset.
Task 2: Determine the average performance rating of the employees who completed the training.
Task 3: Calculate the sum of the performance ratings for employees who completed the Data Analysis course.
Task 4: Count the number of employees who have a rating of 9 or above.
Task 5: Use VLOOKUP to retrieve the course name associated with a specific employee name.
Task 6: Concatenate the employee names and their respective courses, separated by a hyphen.
Task 7: Find the maximum and minimum performance ratings in the dataset.
Task 8: Evaluate logical conditions to determine if an employee completed the training and achieved a rating of 8 or above.
Task 9: Capitalize the first letter of each employee’s name using the PROPER function.
4. Record your results and observations for each task in your spreadsheet.

5. Reflect on the insights gained from analyzing the dataset and the challenges you encountered during the data analysis process.

To conclude

6. Update your spreadsheet sharing setting so that anyone with the link can view it.
You will be adding the link to your milestone worksheet.

# Quiz questions
Question #0
To start a formula you must use:


Plus +


Parentheses ()


Equals =

Question #1
This function outputs the minimum value in a range:


RANGE ()


MIN ()


LOWER ()


MINIMUM ()

Question #2
SUM() is a function that allows you to make additions.


True


False

Question #3
_____is a conditional function.


IF()


AVERAGE()


SUM()


COUNT()

Question #4
Which of these is a conditional function and is properly defined?


IF() function alway outputs false


AVERAGE() and AVERAGEIF() perform exactly the same way


COUNTIF() is used to count the number of cells that meet a criterion


COUNT() counts the number of cells that are not empty in a range while COUNTA() counts the number of cells in an array that have a number value in them.

Ready
Please make sure to validate all quiz questions before moving on to project tasks