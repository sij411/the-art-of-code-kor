Youtube scripts 기준

# Introduction

0:00

good afternoon NDC thank you have you

0:05

had a good few days I have it's been a blast and they have asked me to to come

# Logo

0:11

along and close out the conference for some of you those of you who were wise enough to be here because there's some

0:18

strong competition in this spot by talking to you about something that I call the art of code now does anyone

0:25

recognize the language that this little intro sequence here is written in logo

0:32

this is not only is this logo this is original Amstrad logo from 1985 because

0:40

the first computer that I ever had was this the Amstrad six one two eight it

# Amstrad

0:49

was rubbish I mean it was brilliant because I'd never had a computer before but it had the games that it had were

0:57

all this kind of green screen and they weren't much fun compared to the games in the arcades and everything and you

1:02

couldn't do very much with it no modem no dial-up no BBS or bulletin boards or internet but what it did have on it was

1:09

this logo programming language and logo got me hooked because using logo I could

1:15

make the computer draw pictures and that was a big deal in 1985 because I'd never

1:24

seen like I could put things on that screen using logo that maybe nobody had ever seen on any screen before and I got

1:31

hooked on it and I got this this lovely kind of you know feedback loop where I

1:37

liked it because I could make the computer do what I wanted and every time I did that I'd get this little thrill

1:43

and this rush and I'd go back and I'd have another go and you know throughout my entire career developing software and

1:50

designing systems that thrill for me has never gone away and I hope for you all you here as well you know you have good

1:56

days and bad days but you still get that rush when you know all your tests are green or when you you know you hit

2:01

monitoring and it's a hundred percent or something just works and you're like I did that I made that work and over the

2:08

last three days here at NDC London we've had some amazing brilliant people telling us how

2:14

to solve useful important problems how to design scalable services deployment

2:19

strategies information security the ethics of artificial intelligence and machine learning I'm not going to talk

2:26

to you about anything useful because I am going to talk to you about art and all art is quite useless says Oscar

# Art

2:34

Wilde now I don't entirely agree with this quote I like this quote a lot

2:40

better the function of art is to hold a mirror up to nature and if we want to

2:47

use art as a tool to explore and understand the world around us we can

2:54

hold a mirror up to it but before we can do that we need to invent to the mirror and that is where science and technology

3:01

and engineering come in because for centuries we humans have built machines and tools to help us explore and

3:08

understand the world around us we've created scanning electron microscopes that have allowed us to see things like

3:14

this this is shards on the eyelid of a beetle it's been there the whole time

Science

3:21

and nobody had ever seen it until we invented machines that could take photographs of something that's only a

3:27

handful of micrometers across this is crystals growing in a dish of soy sauce

3:33

this is the stems inside one strand of a banana leaf this amazing beautiful

3:39

microscopic world we had never ever seen and we've sent machines and cameras and telescopes and people into space and

3:46

we've looked back we've seen you know our planet Earth rising above the moon we've looked back from beyond the rings

3:53

of Saturn this is us down here this is the pillars of creation this is six

3:59

thousand light-years away in the Horsehead Nebula and until we invented machines to show us these things nobody

4:05

had ever seen it and within the last thirty years maybe we've started

4:10

exploring another hidden world that's been there the whole time until we developed the machines that allowed us

4:17

to go in and see it and play around with it it's a world of mathematics and information throughout the 1970s there

4:25

was a guy called Martin Gardner who wrote a column for Scientific American magazine about mathematical puzzles and

4:32

curiosities and certainly the most influential of his columns he ever published was this one October 1970

4:38

where he described something called Conway's Game of Life created by an

4:44

English mathematician called John Conway now as games go Conway's Game of Life

4:49

does not look terribly exciting it is a game for no players played on an

# Game of Life

4:55

infinite board and it has four rules the rules of life the first rule each of

5:01

these cells on our grid can either be living or dead if a cell has zero or one

5:06

neighbors it will die of loneliness if a cell has two or three neighbors it

5:13

survives to another generation if a cell has four or more neighbors it's like

5:18

being in London it dies of overcrowding or it moves to Germany I don't know but

5:23

it's not there anymore and finally and this is where it gets a little bit spooky weird if a dead cell has exactly

5:30

three neighbors it will come back to life and that's it that is you now understand everything

5:37

that there is to understand about the rules of Conway's Game of Life now when Martin Gardner's article was

5:43

first published 1970 very very few people had computers and so they used

Tetris

5:49

pens and graph paper to play the game of life and they drew diagrams like this

5:54

now these these five shapes of what we call the tetrominoes there are five Tetris tiles and this shows you the

6:00

evolution of each of those shapes under the rules of Conway's Game of Life but you know looking at this it's like go

6:07

new Museum where they have the butterflies pinned in a glass case you can see what the butterfly looks like

6:12

but you don't understand anything about a butterfly from looking at this kind of

6:17

representation it wasn't until we started using computers to actually simulate this stuff that we really

6:24

understood the behavior we were looking at because these four patterns they all stabilized quickly but this one over

6:30

here this is just gonna keep going over and over and over and once we could visualize things like

6:35

this exploring the game of life became addictive people started saying you know are there packings that will move across

6:43

the grid and just keep going are there limits is the game bounded or is it infinite this was one of the first

6:48

shapes this is known as a glider repeats itself every six generations and it just keeps crawling across the grid forever

6:54

and once we realized bladers were Possible's people started looking for more and they found hundreds of these

7:00

shapes spaceships they call them these incredibly elaborate beautiful creations

7:06

that just glide across this grid driven by four simple rules and that's it one

7:12

of the earliest questions that came up in the game of life can you create patterns that will grow infinitely it's

7:19

a guy called Bill Cosby was a founding artificial intelligence researcher and computer scientist some of you may have

7:24

heard of and his team at MIT in the 1970s they created something absolutely

7:30

wonderful they created a thing called gospel glider gun now what the glider

7:36

gun is is it's a stable configuration and every 27 generations it creates a

7:43

glider and since these gliders streaming out across the grid and gossip esteem

7:48

discovered another you know lots of configurations while they were exploring this they also discovered this thing here which was called Villita

7:54

now we have a glider generator and we have a glider consumer we can generate signals and we can destroy signals we

8:01

have one and we have zero and if we have one and 0 we have binary logic and we

8:07

can use that to create logic gates so this thing here is a NAND gate built in

8:12

the game of life these little highlighted cells are our inputs now

8:18

what we're going to do first of all we're going to start the circuit running and then we're going to say ok we're

8:24

gonna take that blocker out so that our input a becomes true there we go a is now switched on we have no output

8:33

signal we only have one input let's flip the inputs what happens if we switch B on will be as on but we still have no

8:41

output signal because this is a NAND gate in order to get an output signal here we need to enable a and

8:46

be we switch on both of those inputs we switch on our circuit and there we go we

8:52

have a NAND gate now the brilliant thing about this is that if you have logic

8:58

gates you can make circuits and if you can make circuits you can create computers and if you can create

9:05

computers you can run programs including this program that you may have heard

9:10

about a little while ago it's a thing called John Conway's Game of Life and it goes a little something like this

9:43

now Conway's Game of Life is just one of a whole category of systems that exhibit

9:51

very very complex behavior based on what looked like very very simple rules simple inputs you've probably heard of

Butterfly Effect

9:57

this thing called the butterfly effect it's a term we get from a branch of science called chaos theory the idea

10:03

that weather prediction is impossible because if a butterfly flaps its wings that input is gonna change the output

10:09

and you're gonna get hurricanes instead of sunshine in Tokyo two weeks later or something and over the last few decades

10:17

mathematicians everywhere have started studying systems in a different way for a long time

10:22

maths was only interested in problems you could solve give us the solution if you can't give us the solution this problem is not interesting we're just

10:29

gonna go and find something else to look at but mathematicians kind of embraced

10:36

this this whole at different school a different way of thinking we created

10:41

imaginary numbers now the basic rule of an imaginary number we have this number

Imaginary Numbers

10:47

I and in the natural world negative numbers don't have a square root 2 times

10:53

2 is 4 minus 2 times minus 2 is also 4 so how do you get what times what equals minus 4 well nothing it doesn't exist

11:00

and mathematicians go no problem we'll just make something up we'll invent I it's an imaginary number and I squared

11:06

equals minus 1 and they just this is where the rest of the world goes you can't do that and mathematicians go we can do anything we want it's an

11:13

imaginary we don't we don't care but then once they've developed this and they've come up with a rigorous set of

11:18

mathematics around it you can do some really interesting things with it now this thing here zero point eight plus

# Complex Numbers

11:25

one point two I I hang on a second give me one second there's a bunch of slides of gonnna stare and this is not making a

11:31

huge amount of sense that yet no wicked

11:36

will get we get we get one slide is missing right now this number here no

11:42

point eight plus one point two I this is what's called a complex number a complex number is like a project plan it has a

11:47

part that is real and it has a part that is imaginary and it is very difficult to predict what is going to happen next

11:54

once these things get involved now there is a whole study of systems and the

12:01

behavior of systems that we can talk about this thing here is called an Argand diagram and the the blue bit is

12:08

imaginary the red bit is real so not point eight over there on one point two I plot it up there and this way we can

12:13

plot numbers in in complex mathematics in this this kind of space and we can do arithmetic with these

12:19

numbers just like you used to do in high school so we take point eight plus one point two I you just expand the numbers

12:25

out as you go and you multiply and all you need to do is remember that anywhere

12:31

you have two blue numbers multiplied together the result is going to come out negative it's gonna come out backwards

12:37

so this one point two times one point two I will you square them and then you stick a minus on the beginning and you

12:43

take negative complex inputs you get complex numbers out the other end now what's really interesting is when you

12:49

start studying the behavior of systems that are driven by these let's take a really simple function e we're gonna

12:54

take some real number X so we're back in in ordinary mathematics and every generation X is gonna go to X plus 1 so

13:01

one two three four and you can already intuitively see you know how this system

13:06

is gonna behave you can can't be confident you understand its behavior all the way up to infinity let's try

13:12

another one so if we take this example x equals 2 minus X it's gonna go to there not - - - - - not - - round and round

13:21

and round if we apply the same thing to this complex number what we're gonna do is we're gonna keep taking that number

13:27

and squaring it first time we square it it goes to here we square it again goes

13:32

to here we square it again it ends up over here and then over here and then it disappears off to infinity we're gonna

13:39

move it ever so slightly and we're gonna run the same sequence again this time point six and it goes to here and here

13:46

and here and here but it doesn't escape this time it goes into this little kind of weird

13:52

almost circular orbiting pattern now those two points are right next to each other but they exhibit dramatically

13:58

different behavior when we iterate them over and over again by squaring them and squaring them and squaring them and

14:04

eventually this one disappears now the first really rigorous study of these

14:10

kinds of systems was done by this guy a Polish mathematician called benoit mandelbrot and Mandelbrot was fascinated

14:17

by the mathematics of real life he had this quote clouds are not spheres mountains are not cones coastlines are

14:23

not circles a bark is not smooth not as lightning travel in a straight line now Mandelbrot had a brilliant job he

14:30

taught mathematics at Harvard and when he got bored he went to IBM and played on the computers because this is the

14:36

1970s when IBM had computers and nobody else did so he would come up with these you know wonderfully complex

14:42

mathematical ideas and then he'd go over to IBM and spend a couple of months playing around and simulating them and

14:47

then he'd go back to Harvard and you know talk to his graduate students about all this kind of stuff and he was the

14:54

first person to see the shape which now bears his name it's his name was Mandelbrot but everyone calls it the

15:00

Mandelbrot set and I know that I'm gonna do that so let's just call it the Mandelbrot set basically it took each of

15:06

these numbers in this grid and he said we are going to square this and add it to itself and square it and add it to

15:13

itself and we are gonna see whether it stays on the grid or not and if it stays on the grid

15:19

we are gonna color it in black and if it disappears and vanishes off the grid

15:24

we are gonna color it in a different color depending how quickly it what's called tends towards infinity he started

15:32

off with these very very low resolution renditions of this image but the one that you're probably used to the one

15:37

that all of us have seen is this the Mandelbrot set now the astonishing thing about this from this incredibly simple

# Mandelbrot

15:44

mathematical rule there is an infinite amount of complexity we're going to take a Mandelbrot set here and we're just

15:51

gonna start magnifying and we are gonna start zooming in and when we get to around about here we're gonna say that's

15:59

1 times magnification and we're gonna keep zooming and zooming and zooming and by the time we get about here that

16:07

original shape is now size of this building and we are still zooming in when we get to around about here that is

16:16

2 to the 21st Amana fication the original shape is now bigger than London and we are still zooming in and around

16:24

about now the original shape is bigger than the United Kingdom and we are still zooming in and we are still zooming in

16:31

and we can continue zooming into the shape forever it never repeats it is what's called self-similar which means

16:37

it resembles itself at different scales but it never repeats exactly there is an

16:44

infinite amount of detail buried inside this one shape and this has been there the whole time nobody invented this we

16:51

discovered it now this the Mandelbrot set some people have called it the

16:56

thumbprint of God now I'm not a very spiritual person but I do play a lot of

17:01

computer games and I love that thing in a computer game where you're doing something silly that maybe isn't part of

17:07

the main campaign and you find that the game designers left something there to

17:12

persuade you that you were supposed to be here and you're on the right track and this thing has been hidden in

17:17

mathematics since you know our universe was created and no one ever saw it until we humans we invented computers which

17:24

means taking lightning and sticking it in a rock until it learns to think and we invented advanced mathematics we

17:30

invented high-definition color displays and rendering technologies all this kind of stuff and this is what we found

17:36

something that was hidden there the whole time nobody had ever seen until we built the machines and the technology to

17:42

allow us to visualize it now in this day and age just putting pictures on a

Tron

17:47

computer screen is not actually that big a deal anymore this was from Tron which was a movie Disney made in 1982 first

17:54

film to have completely computer-generated sequences Tron did not win the Academy Award for Best

18:01

Visual Effects it was disqualified because using a computer to make a film was cheating according to the Academy of

18:09

Motion Picture Arts and Sciences they changed their minds eventually and they gave it a lifetime award but we've got

18:15

really really good at using computers to simulate things luxo jr. was the first completely computer-generated film 1985

18:22

Jurassic Park 1994 the first time we had computer-generated characters on screen with human actors and it looked

18:29

convincing you know it looked compelling it became part of the story a couple of years ago we had this guy on

18:35

our cinema screens don't who this is because there's one bunch of people who say that's Peter Cushing and he's my

18:41

grandfather and he's dead and you shouldn't have done that and there's another bunch of people going that's grand moff tarkin copyright Lucasfilm

18:48

Entertainment 1978 we own him you know and you know who is it is it the actor

18:53

or the fictional character it's triggered this really interesting left ethical and legal debate but the point is we can put I saw a review of the last

19:01

Jedi the last door which says we've now that living actors playing dead characters and dead actors playing living characters it's come full circle

19:07

thanks to computer technology and we're at the point where we can do anything you could turn to your computer and go

19:13

you know what I'm bored what would it have been like if they'd made friends with Nicolas Cage playing all the parts

Nicolas Cage

19:19

and we can just do that now

19:36

now the reason we can do things like this is that we have created computers

19:42

and algorithms that work on the same principle as some of the the most complicated firmware in our own brains

19:48

you ever rely on your back in a field on a sunny day and you're watching clouds and your brain is kind of filling in

# Neural Networks

19:54

shapes for you it's cloud looks like a rabbit that looks like an aeroplane that whenever there looks like a house and you're running all of these pattern

20:02

recognition algorithms and filling in shapes and recognizing things and one of the things that we are hardwired to do

20:08

is to recognize faces now we've got very very good we don't entirely understand

20:13

how they work but we can now create something called a convolutional neural network you build a whole stack of

20:19

layers of logic and you give it input you say these are cats and these are dogs learn and it goes away and it

20:26

learns and it learns and it learns and eventually it creates an algorithm that

20:32

you can give it a photograph and it will say with confidence that's a cat or that's a dog now you know that doesn't sound terribly difficult right I mean

20:39

how hard can it be to tell a difference between a puppy and a muffin you know it

20:47

can be a lot harder than you think but we're getting good at this but what gets really interesting is when people

20:53

take the dog detection algorithm the dog detector and they wire it backwards and

20:59

they say this is now a dog amplifier and the Machine goes alright and then you

21:04

give it a picture like this and you say amplify the dogs and the computer says this is a horrible idea please please

# Deep Dreaming

21:12

please don't make me and you say neural network find the dogs and enhance the dogs and it goes

21:19

you're gonna regret this and you cannot turn up the power maximum dog amplification and you get stuff like

21:26

this either this is a whole new kind of art that has become possible because of

21:31

machine learning that nobody had ever even thought of before and the technique that's used to do this is something

21:37

called deep dreaming came out of a project in Google in 2015 it's really

21:42

unsettling isn't it because you're looking at it and what's happening is those same circuits in your brain that

21:47

we've learned to emulate in in hardware those circuits are going dog no it's not dog dog no it's not a dog dog and kind

21:54

of your peripheral vision is finding patterns you recognize but then when you look at them it turns out you've been tricked and so you get the kind of very

22:01

very complex perception around what's going on with it now this is just one of a whole bunch of ways that people are

# Robert Felker

22:08

using modern technology and software as artists to create new kinds of art I

22:14

wanna introduce you now to a guy called Robert Felker who I met in Warsaw the other week who's doing some really

22:20

really interesting stuff when I start a new art work it's just an inspiration you just have a feeling so between the

22:28

first ID and the end wizard there's just the same feeling it's not

22:33

about the visual I'm not interesting in what you see I'm interested in what you feel I'm Robert my everyday job I'm a

22:43

flutter dev and project manager and I'm also photo artists previously I wasn't

22:50

kind of locked by the tool I can do a lot of stuff but only what the tool

22:55

permits me when I found the flutter it opened the door inside me now I can

23:03

really push further [Applause] generative art is a lot of research like

23:11

a lot it's a lot of failure it's a lot of failure finding the color finding the form understanding the good behavior of

23:19

light what's really good with flutter is the speed of the feedback

23:24

it's nearly instant currently artists do not understand the

23:32

full potential of the tool when you start further you start with material design or you start with the iOS

23:39

component and you think this is flat but this is just the the tip of the iceberg

23:44

now if you want to push then you start to enter the photo engine and the photo

23:50

engine is like the juice of the cone each time I start to cut

23:58

I just feel joy so some people are painting so people are cooking I just do

24:05

flutter and photo in and this is an

24:12

example of one of Roberts works this is a photograph he took in Tokyo at night that he then used machine learning to do

24:19

a depth perception analysis to identify from the photograph the depths of all

24:24

the elements in this and then use software and tools to creatively rebuild

24:30

the photograph working in layers and I think this is quite beautiful it's kind of hypnotic and every time you watch it

24:36

loop through it reveals something new and this is just one of hundreds of ways that artists are using code to create

24:43

new kinds of artworks we've never seen before but what if we stopped talking

24:49

about using code to create art and we start talking about code as an art form

# Coding as an art form

24:56

in its own right now this very famous book one of the great text books or

25:01

volume set of text books in computing science Donald Knuth's the art of computer programming and we can debate

25:07

for a long time is programming an art is it science is it engineering is it typing is it you know now but I'm sure

25:13

many of you have reviewed code that came from somewhere maybe somebody on your team was was tired or out of that depth

25:21

with it or maybe you were just having a bad day and you look back at it a few days later and you're like I don't know what this is it's not engineering it's

25:29

not art I don't think it's terribly creative I wouldn't dignify it by

25:34

calling it hacking I have no idea what this is but fortunately there is now a safe space for this kind of

25:41

code and these kinds of programs and it is the International obfuscated speedboat contest the goals are to write

25:49

the most obscure C program to show the importance of programming style in an ironic way to stress compilers with

25:55

unusual code to illustrate some of the subtleties of the C language and to provide a safe forum for port C code I

26:03

just like to share some examples with you so this was a black I think Jonathan

# Examples

26:10

Mills contributed this this is the entire source code for this program very C programs here in the room today

26:15

you want to tell me what this does and it's just code right there's only one screen of it how hard can it be

26:20

let's just run it and find out because you know why not we'll just run that to make file and then we'll run it and

26:26

there it is it's flappy bird running in a terminal

26:34

here's another one lynnium zoom out give you a little bit of context so this code

26:39

actually generates and draws the Mandelbrot set in a text window and it

26:44

does it in a relatively kind of compact code base that's shaped like the thing

26:51

it dramas which i think is rather neat now brevity is one of the objectives of obfuscated code you want to do something

26:57

really surprising with a very very small amount of code this is the entire source

# Oscar Pulido

27:02

code for a program by a guy called Oscar Pulido gee if you copy and paste this into your web browser it plays chess it

27:11

doesn't draw a chess board it plays chess it is a chess algorithm implemented in just under a kilobyte

27:18

including JavaScript HTML graphics behavior logic engines all the rules of

27:24

chess and an engine that is actually better at chess than me this thing beat me in games is that much JavaScript now

27:31

there are some astonishing examples of programs that do wonderful things with

27:36

very very small amounts of code but none of them is quite as good as this one this was submitted to the International

# Simona Syncovich

27:43

obfuscated contest by Simona syncovich in 2005 and it was accompanied with

27:50

documentation saying if you compile this using this compiler it will print its own source

27:56

code there's nothing here this is an empty file but that compiler had a quirk

28:02

that if you fed it empty input it would create a C program and compile it that produced no output and so he quite

28:10

rightly said this program prints its own source code now the obfuscated C competition when okay one very clever to

28:18

have a price three we're changing the rules from now on all programs have to have at least one character of input

28:24

otherwise they are just this program completed again but this idea of a program that prints its own source code

28:30

is something called a quiet the word comes from from this book which some of you may have read which is that's kind of fascinating riff on mathematics and

# A Quiet Word

28:37

recursion and fractals and poetry and music and stuff and it turns out that

28:43

writing a program that prints its own source code is actually surprisingly hard now you're not allowed to just read

28:49

it from disk and printed that would be cheating you have to generate the source from within itself so let's let's write

28:55

one I don't write a coin for you now using c-sharp so we need a class program with a static void main method and then

29:02

we obviously need to write line the class program and close the bracket and we need to write line the static void

29:07

main and now we need to write line the right line and then we need to write

29:13

line the bright line with the and you very quickly get tangled up in oh this is just kind of e strings all the way

29:18

down but every language out there has quirks loopholes that we can exploit to

29:24

make it do things that it wasn't supposed to do now in c-sharp there is a

String Templating

29:30

feature called string templating so we can define a string that looks like this

29:35

and we can put placeholders in it these little things here say when you see an argument put that in the string at this

29:41

point and then we are going to feed this string back into itself as a placeholder

29:46

variable so that when it gets to that bit it prints itself and it doesn't go into an infinite loop what it does is it

29:53

prints itself it prints its own source code and different languages have different loopholes you can exploit to

29:59

make coins JavaScript coins are very easy because every function in JavaScript has a two string that prints

30:05

it so this javascript function itself in JavaScript and ACMA script six this is a coin and I didn't believe this

30:13

because that doesn't look like anything so I ran it in a console and sure enough that's the output that gets produced

30:20

when you run it but what's really interesting this is an idea I got from a guy called Leon BAM brick who wrote it a

30:26

great post about this is can you make a coin in HTML now HTML like you know is

Can You Make a Coin in HTML

30:32

it a real programming language I'm not touching that argument can you write a coin in it well let's find out here is

30:38

some simple HTML source code title head body couple of paragraphs and a link to

30:43

Leon's original thing on this and this is what it looks like in a browser right

30:49

start breaking some rules so first we're going to put some style on that says display everything as a block even

30:55

things that are supposed to be invisible this star will match everything we run that in a browser and now we can see our

31:03

CSS our source code is coming through in that browser now we're gonna put some rules in let's say well before HTML we

31:09

want you to display this and afterwards you displayed this now the slash HTML is actually down here off the bottom of the

31:15

screen because it knows it has to draw it but we haven't told it where to put anything and the safety is off at this point we have no idea no the browser is

31:22

like you're on your own kids have fun we plug in a bunch more rules style here we have to put a backslash to escape the

31:29

slash because the web browser is actually running three different passes it's pausing HTML it's pausing CSS and

31:34

it's pausing JavaScript and they're all fighting over who gets to eat the next bit of input and at this point if we put

31:40

slash style our CSS parser is going to go yep I'm done and HTML is gonna choke on the rest of this chunk here so we

31:46

have to escape it now we have before and after tags now there's no way of

31:52

generating these we just need to go and plug-in head body title anchor paragraph and we get this now you'll notice that

31:58

down here we've got this a but we don't have the href equals with the web address we want to link to can we do that using HTML and CSS oh yeah no

32:07

problem if you see a with an href we want you to take this attribute and put it into some content and stick it in before the thing

32:13

and there you go and the last thing that we're going to do just to make it look nice is we're going to put a margin on there

32:19

and change the height of the age and there we go we have a web page that actually prints its own source which is

32:26

completely useless and utterly pointless but how many of you learned something you didn't know about the ages here's

32:33

our parser when you were watching that little run-through there look at some more here is some source code who wants

32:41

to tell me what language this code is written in si si si any other votes for

32:47

si well let's let's apply a C preprocessor to it well take out the comments include standard IOH main char

32:55

I mean that the formatting on this is a little wonky but yeah this is this is fine this is completely valid C code but

33:02

what happens if we apply Ruby syntax highlighting and highlight the strings

33:08

because that looks to me like perfectly valid Ruby code right

33:15

let's try running it and see what happens so I'm going to take that

33:21

program poly coin see there it is and now I'm gonna feed that program into the

33:27

GCC compiler and I'm gonna run it it's got a warning but we're way past the

33:34

point where we care about warnings and there we go that program prints its own source code and now because why not we

33:41

are going to run the same thing through the Ruby interpreter and we are gonna get look at that it prints its own source code now we're going to run it in

33:48

Python because we can and it prints its

33:54

own source code and now hey in for a penny let's run it in Perl and see what

33:59

we get and it prints its own source code again and apparently it'll also do it in C++

34:05

if you can find an old enough compiler this is a poly coin this is a program that is valid in more than one language

34:12

at the same time and in this example it always prints its own source code now

# Languages

34:18

who would like to tell me what language this program is written in well let's

34:24

break it down alright let's do some syntax highlighting so we got system dot console which is kind of like a dotnet

34:29

II kind of a thing right and then we got this chunk here which is an XML namespace we got a console dot log in a

34:36

for each in the lower case so that smells kind of JavaScript T to me right we've got an ADA textio procedure we've

34:44

got begin in capital letters which is either COBOL or SQL it's definitely from the 1970s and it lives in a bank and up

34:52

here we've got act 1 scene 1 enter Ajax which doesn't look like any program I've

34:58

ever seen now this is an excerpt from something called the or Robert Quine

35:05

it's a ruby program that creates a rust program and the rust program creates a

35:10

scholar program and the scala program creates a scheme program which said Shakespeare all the way around the

35:15

circle 128 languages until you end up with a RC program that creates a Rex

35:21

program that creates the original rust program again this was written by a

35:27

Japanese developer called Yosuke and though who one of the contributors to the Ruby core language and the fact that it exists at

35:34

all is astonishing this is what the source code to that coin looks like

35:42

[Laughter] which is also incredible and if you zoom

35:49

in on the end of the source code you'll notice that the last four lines all just

35:55

say buffer for future bug fixes because they don't want to mess up the shape of the source you know now this is the most

# Linux

36:05

astonishing thing about this all 128 of those languages can be installed on a win to Linux by going apt-get recs

36:12

apt-get Shakespeare apt-get TC so there is a github actions continuous build pipeline for this thing that whenever

36:19

changes to it are committed it runs them through all 128 languages and tells you whether it succeeded or not which I just

36:25

think is fantastic and you know weird but I love the fact that we can do that

36:30

but let's backtrack a little bit in that chunk of code we looked at there was some C and there's some JavaScript but

36:36

there's also act 1 scene 1 & 2 Ajax now that is an excerpt of a program written

36:43

in the Shakespeare programming languages one of a family of what are called the esoteric languages ISA Lange's and

36:49

Shakespeare is designed to let you write computer programs that are also Shakespeare plays this is hello world in

Hello World

36:57

Shakespeare the infamous hello world program now all variables in Shakespeare have to be declared as the characters in

37:04

the play so we have Romeo and we have Hamlet act 1 scene 1 that's a namespace

37:10

and a block enter Hamlet in Romeo this is variable scope we are dealing with right now and then the way variables

37:18

work in Hamlet is when they say nice things they increment and when they say insulting things they decrement so at

37:26

this point Hamlet is talking to Romeo and Hamlet says you lying stupid fatherless big smelly half-witted coward

37:33

you are a stupid as the difference between a handsome rich brave hero and myself speak your mind

37:40

that puts the letter H into Romeo and then outputs it because H is the first

37:47

character in hello world the next chunk here will print e and so on hello world

37:53

and Shakespeare is about three pages of fairly florid prose which is fine because it's Shakespeare and that's what

38:00

it's supposed to look like how about this one can anyone tell me what programming language this is written in

# White Space

38:07

this is white space let's have a look at that with syntax highlighting applied

38:12

white space is a programming language that only cares about spaces and tabs it

38:18

ignores everything else it's brilliant if you want to hide programs inside other programs mix up your tabs and

38:23

spaces and you can put whitespace alongside anything else this is hello world in white space let's take a look

38:30

at the hello world souffle now this is a programming language called chef and

# Hello World Souffle

38:35

chef is designed for writing programs that are also recipes now 72 grams of

38:43

haricot beans a hundred 1 X 108 grams of lard 111 cups of oil you know 33

38:50

potatoes it's a valid program but would you like to eat this souffle you know

38:56

and so somebody called a guy called Mike worth looked at the chef's programming language and when challenge accepted I'm

39:03

going to write a hello world program that's actually a sensible recipe you can make in your kitchen and he came up

# Hello World Cake

39:09

with the hello world cake with chocolate sauce now I think this is brilliant if

39:15

you compile this on a computer it says hello world if you compile it in a

39:20

kitchen you get an edible cake with a kind of chocolate sauce ganache that you can pour over the top of it but the

39:26

thing I think about this that's beautiful is if you didn't know about chef you'd think this was just a recipe

39:32

it fits so well into two different domains of human creativity that from

39:38

one you'd have no idea that it also worked in the other one I'm going to show you how to square a number in a

Piet

39:44

programming language called Pete that is how to square a number in Pete

39:51

Pete is named after the Dutch artist Piet Mondrian and Piet is a graphical language where the instruction set is

39:58

dictated by what happens when you cross from one color into another every Piet

40:04

program starts with an instruction pointer in the top-left travelling towards the right traveling due east so

40:10

what's actually happening here is when we cross from light blue to dark green

40:15

that says input a number prompt the user and put that on the top of the stack when we get to black turn the

40:21

instruction pointer through 90 degrees when we cross from green into red that means whatever's on the top of the stack

40:26

duplicated when we cross from red to yellow multiply top two numbers off the

40:32

stack multiply them put the product back on the stack when we cross from yellow into red that is output whatever is

40:39

currently on the top of the stack omit that to standard out when we cross white that is a no operation we reach the end

40:45

of the grid we turn right again and then we follow this blue instruction certain till we end up with black on all sides

40:51

which means you have reached the end of the program please hold so that's a completely Turing complete language

40:57

whose instruction set consists of areas of light and shade and the transition

41:02

between colors this is hello world in Piet one of many many examples but you

HelloWorld

41:09

could hang this on the wall in your house and somebody could come in and take a look at it they'd have no idea they were looking at

41:15

hello world they just think you like kind of slightly weird 16-bit art you know the Windows 3.1 school of

41:21

Expressionism now we've talked so far about this whole idea of you know using

41:28

we've talked about using code to create art we've talked about code that is art and over the course of MDC you've

41:34

probably seen a couple of speakers here doing live demos which are you know the the tightrope the high wire act ooh the

Live Demos

41:41

death-defying circus thrill of the technology industry because someone is coding something on a laptop live and it

41:47

might work and it might not work and there's always this element of kind of risk and then it works and it runs like yeah and you got a big round of applause

41:53

but generally as an industry we don't like that you know we like consistency

41:59

we like reproducibility we like automation we like being able to do the same thing over an

42:04

over and over again if you've ever worked in a place where there is a server under a desk or maybe in a rack

42:11

somewhere that's running Windows 2003 Small Business Edition and you're not

42:16

allowed to touch it do not put Windows Update on that or the payroll will stop working on pain of

42:22

immediate gross dismissal you know and we have a name for these kinds of boxes

42:27

that everyone is frightened to touch we call it snowflakes snowflake servers snowflake processes it's completely

Snowflakes

42:34

unique but if you go out in the snow and you pluck a snowflake out of a blizzard

42:40

and you watch it melt on your hand you have just been part of a performance that will never ever be repeated

42:46

anywhere your participation in that has created a unique human experience that

42:52

nobody else will ever understand or be part of and maybe we can do the same

42:58

kind of thing using code this guy here is Sam Aaron and Sam is the creator of a

Sonic Pi

43:06

programming language called Sonic pi was anyone in the last talk in this room yesterday where Laura did her talk about

43:11

programming with music and she was showing us had a program write computer programs whose output is not text or

43:18

graphics it's music and tones and sounds and melodies and she ended up by you

43:24

know doing this this wonderful kind of layering thing because sonic pie is a live coding music synthesizer I'll give

Sonic Pi Demo

43:32

you a very quick demo of how sonic pie works which I'm not gonna live code for you because I don't want this to get too

43:37

meta now when you start sonic pie it gives you a prompt and you say play this note

43:42

and it plays that note now sonic pie runs all your instructions in parallel unless you tell it not to imagine if

43:49

JavaScript if you want things to happen one after another you have to put sleep

43:55

instructions in and say we want to introduce some kind of delay to this and where it gets really interesting is we

44:03

can go in and we can start putting loops around our notes and our musical patterns so we got 16 times do that and

44:10

we've got the world's least exciting bass line going so let's crank up the tempo a little bit

44:16

we're gonna say use beats per minute 240-foot all right we're getting

44:21

somewhere and we're gonna change it because the sine wave is not a terribly exciting noise we're gonna use a built-in synthesizer here called Tex

44:27

Soares now this is interesting but where

44:34

it gets really interesting as you'll have seen in Laura's talk yesterday is when we introduce the concept of

44:40

something called a live loop now live loops allow you to run multiple components of your program so I'm gonna

44:49

put a light blue there around that baseline and then I am gonna drop another loop over the top of it

45:00

[Music]

46:07

the fizzbuzz now sonic pie is fantastic it's enormous amount of fun to play

46:13

around with I've seen people do live coding with multiple you musicians that picture of the beginning was Sam on

46:18

stage with the London Philharmonic Orchestra doing live coding in the Royal Albert Hall and you know it's an

46:23

absolutely astonishing tool and just one of the brilliant and creative ways that we're coming up with to use code to do

46:30

fascinating and unexpected things but I want to finish today I've talked you all

46:35

about all kinds of things that other people did I want to finish by telling you about something that I did now you

Rock Star Developer

46:41

are probably familiar with the trope of the rock star developer because we've all read job advertisements from people

46:48

looking for a rock star senior front-end rock star JavaScript engineer rock star senior Java software developer this has

46:55

been endemic in our industry for years and last year Paul Stovall put this on

47:02

Twitter he said to really confuse recruiters someone should make a programming language called rock star

47:07

and I had this experience because I

47:12

thought this is it this is my purpose this is why I was put here because what

47:18

the world clearly needs is a programming language that allows you to write

47:24

programs that are also bad 1980s heavy-metal songs and so rock star was

# Rock Star

47:31

born a dynamically typed Turing complete programming language for creating computer programs that are also song

47:36

lyrics heavily influenced by the lyrical conventions of 1980s hard rock and pala balance now

47:43

Rockstar was created in a bar as a joke that will become important shortly sad a

47:50

bar with a laptop and a beer and thinking could you make a language where rock songs could compile to something now I

47:56

used to work in VB script and Perl a lot and I've done work in Ruby so I'm used to languages which try and you know

48:03

borrow a lot of elements from natural language and incorporate them into programming syntax so I thought all right first of all if you were write

Variables

48:09

songs in it there's more than one way to do it like the Perl idiom attempt Tony you know so HelloWorld in rock star is

48:15

say hello world or scream or whisper or shout these are all syntactically valid

48:21

programming requires variables and assignment now you're probably used to in x equals five var my string the

48:28

message now we don't need int because rock star is a dynamically typed

48:34

language we are going to take those out we don't need semicolons on the end because if JavaScript can live without

48:40

them so can we now the equals sign in the middle how do you sing that and those you know let's just put is X is

48:47

five my string is hello world the message is flutter rocks because I forgot to update that that should say NDC rocks now there's this ongoing

48:56

debate about casing you've had one of those arguments longer than an hour about Pascal case versus camel case

49:02

versus get bad case versus underscore case and I shall Douglas Crockford the guy created JSON give a talk two years

49:09

ago where he said we have all these stupid arguments what we want are variable names with spaces in them well

49:15

guess what when you're inventing a programming language in a bar you can do anything you like so Rockstar has variable names with

49:21

spaces and it's not a complete free-for-all there are three kinds of variables simple variables work like

49:26

they do in JavaScript and Ruby common variables have to start with my you're the an a and proper variables need

49:33

capital letters so we can write programs about dr. feelgood and black Betty and Billy gene and all these you know great

49:38

characters who inhabit the world of rock and roll now initializing variables we normally

49:43

do with numbers fizz is three buzzes five the limit is 100

49:48

I didn't want to do this because it doesn't sound terribly metal really and

49:54

I thought how can you define a numeric literal without having to use digits in your source code and I had this idea

50:00

what if we take the lengths of the words modulo 10 and we treat those as digits

50:08

so ice is 3/5 the limit is a love-struck Ladykiller one that's 10 10 modulo 10 is

50:16

zero zero we've got three we've got five we've got 100 without having to put digits in our source code it works with

50:23

floating-point numbers as well and C decimal PI 3.14159 and JavaScript var pi

50:28

equals we're kind of almost you probably got something close to that back out because hey JavaScript right in rock

50:35

star my heart was ice a life unfulfilled waking everybody up taking booze and

50:41

pills 3.14159265 3/5 easy right you

50:50

gotta have to do arithmetic right now we have these common you know ways of talking glitch how much is it I the

# Arithmetic

50:55

total is the price with the tax well what about the the net Anana that's the total without the tax how many do you

51:01

need get me the quantity of the product how fast were you going well speed is the distance over the time you know we have these things it's easy but this

51:08

mathematical convention also allows us to write a girl with a dream a man without a face the wings of the night

51:15

and a whisper over the water we need comparison your love is a lie true or

# True or False

51:21

false well is it the whiskey ain't the answer my heart is stronger than steel and my

51:27

soul is weaker than water as strong as a lion as low as a snake we'd each

51:32

function syntax now the sort of simplistic version here let's have a

# Modulus

51:37

function modulus it takes a number and a divisor so those are input arguments and while a number is as high as a divisor

51:43

put a number without a divisor into a number and give back a number this is how you implement modulus when your

51:49

building blocks are just addition and subtraction and loops and stuff now this works but we can do better right because

# Fizzbuzz

51:57

midnite takes your heart and your soul and while your heart is as high as your soul you

52:02

put your heart without your soul into your heart and give back your heart now

52:08

at this point I'm about three beers in I have a parody specification that is just complete enough to implement fizzbuzz

52:14

and I have fizzbuzz in Rockstar I stick this thing up on github and I'm just

52:20

like hey everyone introducing Rockstar proposal for a turing-complete programming language and I think this is

52:26

gonna be funny for like three hours you know it gets 2,000 github stars

# Rockstar

52:32

overnight it makes the front page of hakkon news and just kind of starts this

52:37

buzz it made it into a Boing Boing magazine Cory Doctorow wrote a thing about it in there it made the front page

52:42

of Reddit people and reddit we're actually saying complimentary things about it the weirdest thing that

52:48

happened is I got an email from classic rock magazine which is a real music

# Classic Rock Magazine

52:55

magazine that is nothing to do with computers saying what's this Rockstar thing that we keep hearing about so I

53:00

wrote a little thing for like an email interview for them and I'm thinking like this can't possibly get any weirder and

53:06

then people start filing issues against my parody specification and I'm looking

53:16

at these and you know some of them are just ideas like what a fool the numbers go up to 11 and I'm like don't know that arithmetics hard enough as it is but

53:22

some of them are like this undefined behavior and I'm like what do you mean there's undefined behavior why do you care and they're like I built a rock

53:28

star compiler in Scala over the weekend and it has edge cases like you did what and within about a week there was a

53:35

Scala interpreter so I would have built a compiler for in rust somebody had built a rock star to Python transpiler

53:41

and the fascinating thing is all of them had managed to do like 95% of it just

53:47

based on this random stuff I came up with in a bar as a joke and some of it makes no sense and you know if I'd known

53:54

it was ever gonna be real I'd of course have done it differently but programming is like that you know now I really liked

54:01

the idea of Dylan Beattie the creator of rock star and I didn't think I'd done enough work at this point to really earn

54:07

that and I also wanted rock star to be you know scholar and Rustin and Python

54:12

are all very well but I want it to be something accessible something that anybody could just open up in a web

54:17

browser and write some Rockstar code and see what it did and so this time last year I basically spent about five

54:24

weekends we teaching myself how to build compilers and parsers and meta-circular evaluator x' and stuff and i built a

54:31

rock star interpreter in javascript which is definitely the stupidest dumbest thing i've ever done and it's online and it is here it is at

# Microsoft

54:38

code with rock star calm and everybody here in this room is welcome to go and

54:43

try this put some code in there and you will then be a rock star developer now I

54:49

just want to shout out one thing the logo here in the top left I wanted to borrow some like real over-the-top

54:55

access 1980s rock and roll heavy metal influences and I looked at dudas priest

55:00

and Iron Maiden and Motley Crue and all these kinds of people and then somebody said have you thought about Microsoft consumer products 1980 to 1982 and I was

55:09

like that is exactly what I want that logo type is perfect so thank you Microsoft for letting me recycle your

55:15

old logo be green now I do have some certified Rockstar developer stickers to

# Rockstar Developer

55:21

give away here at NBC so come up afterwards with your code with Rockstar comm code on your phone and I will

55:26

certify you you will become a member of the world's most prestigious developer program but to end the talk today I'd

55:33

like your help in something now I showed you some examples in there of like hello world and Pete that just looks like a

55:39

painting and the chef hello world chocolate cake that could just be a cake and if you like the the test of whether

55:46

Rockstar really succeeds as a language is can you perform a rock star program

55:53

and have people just think it's a bad heavy metal song from the 1980s and so

55:58

with your indulgence I'd like to close NBC and this talk by performing live fizzbuzz in rock star

# Fizz Buzz

56:08

[Music]

56:46

takes your heart and your soul while

56:52

your heart is as high as your soon put

57:01

your heart without your soul into your

57:08

[Music] give back your heart you remember the

57:18

fizzbuzz riff [Music]

59:33

[Music]

59:44

[Music] [Applause]

59:49

[Music]

1:00:05

[Applause] [Music]

1:00:11

thank you very much in DC thank you for

1:00:20

coming thank you for your time thank you for listening who's going to pub gun if you thought

1:00:25

that was silly we got way more stuff in store if you don't if you're coming to pub gun I will be emceeing tonight we

1:00:31

got 12 amazing speakers lined up with five-minute funny talks there are still tickets on sale if anyone doesn't have

1:00:36

plans tonight Pupkin oh if you are not coming to PubCon thank you very much I will see

1:00:41

you somewhere out on the road have a wonderful weekend see you soon bye-bye

1:00:47

[Applause]

영어 (자동 생성됨)
