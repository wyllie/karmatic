# karmatic
A karma detection tool
## Introduction

Have you ever wanted something good (or bad) to happen to someone because of
something they did to you?  Have you ever waited for something to happen so
you could "pull the trigger" and send that good/bad email that could change
the course of a person life?

Maybe you just don't like revenge much, you rather let the forces of the
universe create balance.  The probelm is, how do you know if the forces of
nature have acted?  How do you know if the guy that cut the line at Starbucks
spilled his cofffee on his lap when he got back to his car?  How do you
know if the girl that gave you a buck so you could cover your bill at the
dry cleaner had someone do something nice for her later in the day?  Maybe
you are trying to make a difficult decision and you just need "some sign"
to tell you if you should proceed or not.

It's for all these reasons (and more) that karmatic has been created

## Description

karmatic was designed to pick up on rare events using two sources.  The
first is a randomly generated number from random.org.  If you think you
know a thing or two about random numbers, you should check out how the
people over at random.org find randomness.  Basically, they use atmospheric
noise (like static on your TV) to generate series of numbers.  You can
query their website for all kinds of numbers which, according to them, 
are as close to purely random as you can get.
The second source of data is a wind speed from a random US or Canadian
airport (in knots).  What we want to do is see if the random atmospheric
noise aligns with the wind speed at randomly selected airport.  If they
match then karma happened!  You can then go about your day knowing that
the world is a fair place.


## Instructions
There really is not a lot to this program.  

Simply clone this repo to your local computer.  

Edit the config file and add an:
  an email address
  a subject for your karma email
  your personal random.org API key
  
Now you are ready to see if karma is happening.  You can just run the
script manually or you can set it up to run periodically with a cron
job to run the program as often as you like.

You'll need to register with random.org to get an API key.  It's a simple 
process and it keeps people from abusing their website.

Get a random.org API key here:

## Enjoy!

Not sit back, relax and stop worrying about the balance of the universe
