# a 2014 test-suite <br>for project gutenberg

## a document which contains the<br>full range of features found<br>in project gutenberg e-texts  

### by bowerbird intelligentleman  


 greetings, earthling!  

 this is a test-suite created for  
 e-texts from project gutenberg,  
 a 40-year-old volunteer effort to  
 put public-domain literature online.  

 please go visit their web-site for  
 the latest news and information on  
 usage conditions for their e-texts,  
 volunteering for them, and more...  

 http://gutenberg.org

 you can "view source" for this document here:

 http://zenmagiclove.com/zml/suite/suite-2014.zml





## table of contents


 [a 2014 test-suite for project gutenberg](#a-2014-test-suite-for-project-gutenberg)  
 [table of contents](#table-of-contents)  
 [dedication](#dedication)  
 [chapter 1 -- welcome aboard](#chapter-1)  
 [chapter 2 -- the sections of the book](#chapter-2)  
 [chapter 3 -- text "styling"](#chapter-3)  
 [chapter 4 -- plain ascii versus unicode](#chapter-4)  
 [chapter 5 -- poetry and other silly things](#chapter-5)  
 [chapter 6 -- tables in your e-texts](#chapter-6)  
 [chapter 7 -- centered text](#chapter-7)  
 [chapter 8 -- pictures in your book](#chapter-8)  
 [chapter 9 -- footnotes and endnotes](#chapter-9)  
 [chapter 10 -- hotlinks in your e-texts](#chapter-10)  
 [chapter 11 -- hyphens and dashes](#chapter-11)  
 [chapter 12 -- hyphenation stinks](#chapter-12)  
 [chapter 13 -- unlucky number 13](#chapter-13)  
 [chapter 14 -- two spaces after a sentence](#chapter-14)  
 [chapter 15 -- multi-purpose block-quotes](#chapter-15)  
 [chapter 16 -- the play is the thing](#chapter-16)  
 [chapter 17 -- epigraphs and epitaphs](#chapter-17)  
 [chapter 18 -- lists in your book](#chapter-18)  
 [a subsection of chapter 18](#a-subsection-of-chapter 18)  
 [another subsection of chapter 18](#another-subsection-of-chapter-18)  
 [chapter 19 -- the meta-data chapter](#chapter-19)  
 [chapter 20 -- a demo for zen markup language](#chapter-20)  
 [chapter 21 -- the end of this test-suite](#chapter-21)  
 [the notes section](#the-notes-section)  
 [meta-data](#meta-data)  





## dedication


 to michael hart

 for his bold vision  
 and his persistence





## chapter 1

## welcome aboard


welcome!

this is a document intended to demonstrate
the range of features common throughout
the e-texts in the project gutenberg library,
and indeed to the majority of printed books.

project gutenberg is a volunteer effort for
digitizing the text of public-domain books,
for viewing and distribution in cyberspace.

 http://gutenberg.org

it was begun by michael hart back in 1971,
with the goal of creating 10,000 e-texts,
a milestone achieved in 2003, thanks to
a big boost from distributed proofreaders,
which allows people to proofread online --
thousands of them doing a page at a time,
volunteering bits and pieces of their time.

 http://pgdp.net

if you want to support the p.g. library
with software, a markup system, or so on,
you should be able to handle its features,
and you can use this file as a "test-suite"
to verify that your system is fully capable.

this is the test of a link in the middle of
a normal paragraph, to http://pgdp.net, to
see if it works correctly...

if you find inconsistencies in this test-suite,
do please let me know immediately. thank you.





## chapter 2

## the sections of the book


first, you should be able to handle
headings of different levels, such as
the book, chapters, and subsections.

you may label the levels as you like.

html can support 6 different levels,
so that's a good number to shoot for.

one of the things that users find handy
is a _table_ _of_ _contents_ for the e-book,
so you must be capable of generating one,
in cases where an e-text doesn't have one.

because of their experience with the web,
people often expect this table of contents
to be hotlinked to the appropriate sections,
so your markup system should facilitate that.
a nice touch is then to have chapter headings
then link _back_ to the table of contents...






## chapter 3

## text "styling"


project gutenberg was born a very long time ago,
before word-processors and personal computers...
a rumor is that michael used a keypunch machine
(it's ok if you're too young to know what that is)
to enter a good number of the original e-texts...

computers didn't even have lowercase characters
in the early days, so the whole book was capitalized!
luckily, before long we got lowercase characters.

but still, "luxuries" like _italicized_ and *bold* text
were not possible, so michael developed a convention
where a word that was *bold* or _italics_ in the original
was entered in all-uppercase, to show that emphasis.

because the e-texts are stored as raw ascii text,
that convention lives on, to this day, in some files.
by this time, however, we need to be able to handle
styled text, so your systems must be able to do so.





## chapter 4

## plain ascii versus unicode


most english e-texts in the library can be
represented in the lower-ascii characters,
but future e-texts are likely to require
some unicode characters, so you should
without question be able to handle unicode.





## chapter 5

## poetry and other silly things


many of the e-texts contain *poetry,*
or verse of some type, so your system
must be able to handle silliness like that.

some poems want to be left-justified,
so you should be able to handle that:

               a haiku for you
               (by bowerbird intelligentleman)

               haiku have three lines
               and seventeen syllables
               five, seven, and five

other poems want to be centered instead:

 t.v. will eat you
 (by bowerbird intelligentleman)

 t.v. will eat you
 out of a satellite dish
 with a tuning fork

and some poems want to alternate...

      six spaces at the start of this line
            12 spaces at the start of this line
      six spaces at the start of this line
            12 spaces at the start of this line
      six spaces at the start of this line
            12 spaces at the start of this line
      six spaces at the start of this line
            12 spaces at the start of this line

and some poems want to get fweaky!

      six spaces at the start of this line
          ten spaces at the start of this line
              14 spaces at the start of this line
                  18 spaces at the start of this line
                      22 spaces at the start of this line
                          26 spaces at the start of this line
                      22 spaces at the start of this line
                  18 spaces at the start of this line
              14 spaces at the start of this line
          ten spaces at the start of this line
      six spaces at the start of this line

in general, lines of a poem prefer to stay together,
that is, to be kept all on a page whenever possible,
so your system should attempt to accomplish that...

if it's not possible to keep the whole poem on a page,
try to make the page-break occur between the verses...





## chapter 6

## tables in your e-texts


there aren't a whole lot of tables in the e-texts
-- we're talking literature, not spreadsheets --
but your system should handle tables anyway;
not really big and hairy ones, just simple ones.

 |  table 1           column 1         column 2
 |  plain-text          yes              yes
 |  x.m.l.              no               yes
 |  html                yes              no
 |  .rtf                no               yes
 |  .pdf                no               no





## chapter 7

## centered text


sometimes, for one reason or another,
some of an e-text's lines are centered.
so your system should be able to do that.

 center me as well, please!





## chapter 8

## pictures in your book


most of the p.g. e-texts are text-only.
but some of them do have pictures, so
your system must be able to show 'em.

 http://z-m-l.com/go/alice/checking_watch.png

put a picture here,
or maybe a button
that someone could
click in order to
view that picture...

 http://z-m-l.com/go/alice/cat_fades.png

"what is the
use of a book,"
thought alice,
"without pictures
or conversation?"

 http://z-m-l.com/go/alice/alice_cramped.png





## chapter 9

## footnotes and endnotes


some of the e-texts have footnotes.[1]

your system must be able to handle them.
how it might do that is up to you, captain.

 http://z-m-l.com/go/alice/alice_holding.png





## chapter 10

## hotlinks in your e-texts


remember how, in chapter 2, we said
that the table of contents should be
hot-linked to the appropriate spots?

that is one type of link you'll need.
there are several other types as well.

your system should also be able to
make the jump to an internet site.
most of the e-texts are quite old,
so of course it's not like they have
a bunch of internet url's in them;
but every e-text will indeed contain
a link to project gutenberg's website,
so you must be able to execute links...

quite often there are places in an e-text
that reference other parts of the e-text.
in these cases, it's nice to have a hotlink
close to (or on) that reference point that
transports the reader directly to the place
that is being referenced; it is convenient.
your system should facilitate such linking,
preferably making it happen automatically.

for instance, the beginning of this chapter
has a reference to chapter 2. if a reader
clicked on those words -- "chapter 2" --
they should automatically go to chapter 2.

(and likewise with each of the references
to "chapter 2" here in this paragraph too.)





## chapter 11

## hyphens and dashes


i use a hyphen between "e" and "text" in "e-text".
not everyone does, but i think that it looks nicer.

a hyphen -- as you know -- differs from a dash.
and you probably know that there are even two
(and some people say more!) types of dashes...

the first - called an "en-dash" - is a narrow one.
you will see these in a fair number of the e-texts.
it's called an "en" dash because it was traditionally
defined as being exactly as wide as the letter "n".
(or, some say, as _wide_ as a letter "n" is _high,_
so you can take your pick between those choices.)

the second -- called an "em-dash" -- is wider, and
yes, it's called that because it's as wide as an "m",
or so the story goes, according to some people...

generally, try to use an em-dash, not an en-dash...
the en-dash looks too much like a hyphen, especially
when it is run into the words that are surrounding it.

now, the convention says that you should _not_ have
spaces on the sides of a dash. the convention is wrong.
it looks _much_ nicer if you put spaces around a dash.

perhaps even more importantly, the search capability
of many programs is thrown off if you don't use spaces.

so are the re-margination routines in many programs, so
-- to avoid these problems -- put spaces around dashes.

a problem arises, though, because there is no em-dash in
the lower-ascii codes. so you have to use a double-dash
-- like these here -- for an em-dash. ok, problem solved.
your system should be able to convert the double-dash
into a proper em-dash, if the user chooses that option.





## chapter 12

## hyphenation stinks


hyphenation is another thing that messes up e-book
search capabilities. e-books don't need hyphenation.
so _turn_ _hyphenation_ _off_ when you make an e-book.





## chapter 13

## unlucky number 13


there is no 13th floor in most buildings.





## chapter 14

## two spaces after a sentence


back in the old typewriter days, students were
instructed to put two spaces after each sentence.

ever since wordprocessing, though, some people
have said two spaces are no longer required, that
it is an unnecessary leftover from earlier times.

those people were wrong. if you have one space
after a period, sentences run together too much.

but...

the thing is, it's actually a lot easier to edit
text if you only have one space after a period...
that way, you can do a search for two spaces,
and that search should come up _totally_ empty.

thus, to make life easier on the writers out there,
your software should create the smidgen of space
necessary to separate two sentences sufficiently.

so, if you're _making_ an e-book, use just one space.





## chapter 15

## multi-purpose block-quotes


sometimes you want to quote a whole block of stuff
from someone. this is often called a "block-quote".
clever, the guy who came up with that name...

many of the project gutenberg e-texts contain
block-quotes of one various type or another.

here's an example of a block-quote, a letter.

 > dear leslie,
 > 
 > how are you? i am fine.
 > the weather is nice here.
 > but i wish it was half
 > as beautiful as you are.
 > 
 > and i wish you were here.
 > 
 > love,
 > bowerbird

typically, block-quotes are indented
on both the left and right sides.

here's another block-quote, from a speech.

 > four score and seven years ago, our
 > forefathers set forth upon this continent
 > a new nation, conceived in liberty and
 > dedicated to the proposition that
 > all men[2] are created equal.

there are a number of different situations
throughout the e-texts that might call for
this type of indentation. for now, we will
just subsume them all under "block-quote";
perhaps later we will see fit to break out
a more finely-grained analysis, if we find
any special cases merit their own class.





## chapter 16

## the play is the thing


there are plays in the library.
gotta be able to handle plays.

dale: that's not what p.g. is all about.

bowerbird: i think it's important to
give people a good e-book experience.

dale: that's your opinion.

bowerbird: yes it is.

steve: (weakly) i can't...

dale: no it isn't.

steve: (weakly) get a...

bowerbird: is too.

steve: (weakly) word in edgewise...

dale: is not.

lurkers: will you two cut it out?

bowerbird: is so.

dale: is not...

fade to black.[3]

gotta be able to handle plays. dialog, instructions
to actors, stage directions, that kind of stuff...





## chapter 17

## epigraphs and epitaphs


    _there's_ _an_ _old_ _proverb_ 
    _that_ _says_ _just_ _about_ 
    _whatever_ _you_ _want_ _it_ _to..._ 
    _--_ _slashdot_ 

sometimes a chapter starts with a nice pithy quote,
which is usually _italicized,_ and often right-justified.

so you wanna be able to handle that kind of thing.[4]





## chapter 18

## lists in your book


i like lists. here's a list:

 * one
 * two
 * three
 * four
 * five
 * six
 * seven
 * i forget what 8 was for.
 * number 9, number 9...

gotta be able to handle lists...





## a subsection of chapter 18


sometimes you want a numbered list...

here's an example of a numbered list,
with the number specifically included.

 x 1. one
 x 2. two
 x 3. three
 x 4. four
 x 5. five
 x 6. six
 x 7. seven
 x 8. i still forget what 8 was for.
 x 9. number 9, number 9...

here's another numbered list, again
with the number specifically included,
where we mix things up a bit...

 x 101. one
 x 202. two
 x 333. three
 x 4444. four
 x 55555. five
 x 6. six
 x 77. seven
 x 88. i still forget what 8 was for.
 x 9. number 9, number 9...

here's another numbered list, except
this time it's an "ordered list", which
means the browser does the numbering...

 # one
 # two
 # three
 # four
 # five
 # six
 # seven
 # i still forget what 8 was for.
 # number 9, number 9...

still gotta be able to handle lists...





## another subsection of chapter 18


here's another example of a list:

 o mercury
 o venus
 o earth
 o mars
 o jupiter
 o saturn
 o uranus
 o neptune
 o pluto


like poems, items in a list generally want to
stick together on the same page, if possible.

still gotta be able to handle lists...





## chapter 19

## the meta-data chapter


a lot of people think "meta-data"
is important. i think they're full
of poop, but why not make 'em happy?

so give them their own section --
call it the "meta-data section"
-- and then let them put whatever
makes 'em happy into that section.

you will find the meta-data section
toward the very end of this document,
where it belongs, after the "real" data.





## chapter 20

## a demo for zen markup language


this test-suite document is a demonstration
of z.m.l. -- "zen markup language" -- a system
by which a set of simple formatting rules can
take the place of complicated markup languages.

this document is "marked up" in z.m.l. and will
spring to life when displayed by a z.m.l.-viewer.

furthermore, a z.m.l.-viewer can perform all of
the tasks necessary to implement the features
that this test-suite represents: the hot-linking,
the styling, different layouts, tables, pictures,
formatting for plays, the lists, the whole thing,
without the difficulty of heavy markup languages.





## chapter 21

## the end of this test-suite


we hope you've enjoyed this test-suite document.
if you have any questions, feel free to ask them.

this is a draft, so please suggest improvements.
and if you want to make your own test-suite, do!

sadly, michael hart passed away in 2011, so he is
no longer with us. he's up in heaven now, where
there are no typos, and every book is available...

but after he attained his 10,000 e-texts goal,
michael got a new goal -- a *million* e-texts!

maybe you can serve michael's memory, and say
"thanks", by helping to reach his new goal? :+)

 http://gutenberg.org

*have* *a* *nice* *day.*

the end.





## the notes section


here are the footnotes/endnotes.

[1] personally, i don't think we need to
make a distinction between footnotes
and endnotes any more, i believe that
all the types of notes should be stored
at the end of the file, like these notes,
but i think the person should be able to
_display_ them at the point of reference
in the actual body of the text. therefore,
they are actually a sort of hybrid between
footnotes _and_ endnotes, combining the
strengths and convenience of both types.

[2] in later years, it was made clear that
lincoln was referring to all "people", and
not just men, that women are equally equal.

[3] this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.

look, it even has a second paragraph!
this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.

oh no! a third paragraph. way too long!
this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.
this is a test footnote. because of that,
it's going to go on and on and on.

[4] this is another test footnote. but it will be short.





## meta-data


here's the meta-data...

 o title = a 2014 test-suite for project gutenberg
 o author = bowerbird intelligentleman
 o purpose = a test-suite
 o for = project gutenberg
 o markup = zen markup language (.zml)
 o isbn = urn:isbn:0000000000000
 o publisher = jaguar(ps)
 o subject = doing the test-suite thing
 o rights = copyright 2014 -- all rights reserved
 o file = zenmagiclove.com/zml/suite/suite-2014.zml

 http://gutenberg.org

 here's a test of some of the formatting commands.

  left-justified~tab

   centered

    right-justified

 this just has one space at the start ofit...

 .

 all of them in one paragraph:
 http://google.com
 http://pgdp.net
 http://gutenberg.org

 .

 http://google.com

 http://pgdp.net

 http://gutenberg.org

 http://z-m-l.com/go/alice/checking_watch.png

 http://z-m-l.com/go/alice/cat_fades.png

 http://z-m-l.com/go/alice/alice_cramped.png

 http://z-m-l.com/go/alice/alice_holding.png

 goodbye!
 
