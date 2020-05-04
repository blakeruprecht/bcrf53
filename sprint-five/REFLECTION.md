### Reflection Part 2: SSO
I got the google app working with SSO, displaying my picture. Screenshot included.
I intend to do a bit of a "data expos\'e" with my app, which is just intended to
show people what type of data can be gathered about them from a simple SSO. For
my own curiosity, and potentially for others.


### Reflection Part 1: Dex
Now that I finally got the `make` command to work, I breezed through making the 
login server and the basic app work. Screenshot included.


### Reflection Part 0: Make my day
Yesterday, I finished up a massive report for another class. I took a break, and 
then dove into this project around 3:00pm. I worked until 11:30pm, taking a one 
hour break for dinner. During this time, I was running into a problem where my 
`make` command when trying to make the dex app was failing due to a fatal error.

PROBLEM: I tracked down the source of the problem, and determined that parts of the
Golang were not finding the C headers they needed from my commandlinetools. This
led to the first "learning experience" of this project. 

PROBLEM SOLVING STEPS:
- I spent many hours googling every possible thing I could think of
- reading stackexchange
- searching through the 30k open issues on github.com/golang/go/issues
- eventually downloading Ubuntu (which takes a surprising amount of time, I've 
only ever downloaded Arch and Debian), and creating a virtual machine on my 
laptop, which began to cause more problems (I am definitely not a linux expert). 
- Failing this, I reinstalled Golang twice, 
- learned what a `PATH` variable was
- learned what `export PATH` means
- set my `PATH` variable multiple times thru command line and in my .bash_profile
- removed homebrew package manager
- update system
- restart computer twice
- try to force updates

SOLUTION:
- eventually force removed all commandlinetools, including `git` and `make`
- reinstalled commandlinetools
- and now it works... I'm not sure why this fixed it, but I assume some headers
  got lost somewhere along the way... all good now!




