# Name/technique
Loop through files

## About
Shell "one liner" that allows you to do something to every file that meets a condition.

## Installs/Dependencies
None. Uses default POSIX features.

## How to Setup
None. No setup required

## How to Use
Here is a sample of this technique:  

Let's say you have some files that want to use `nc` to transfer one at a time.  
`for i in '*.txt'; do nc IP PORT < $i; done`  

There are two parts. The "selector" condition, and the "do-er" section.  

The selector in the above example is between the `' '`.  
The do-er section is the `do nc IP PORT < $i`  

You can swap these two sections for whatever you need.

FWIW: you have to do this because most versions of netcat don't allow file wildcarding.

## Warnings/Issues
Be careful if you delete data in your "do-er"!

## Thanks  
Thanks to Mark H. who showed me this way back in the day! I still use this years later. :-)
