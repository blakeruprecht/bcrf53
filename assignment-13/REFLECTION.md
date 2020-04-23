## A description of which projects you looked at
I mainly looked at OpenID and Auth0. OpenID looked fantastic, and I know it's being used by a lot
of large companies (like Google). Auth0 allows for many different features, including sign-on using
social accounts, SSO, 2FA, and more. The benefit of Auth0 is that it is a drop in framework.

## Why you chose the one you did
I ended up choosing Auth0 because it had an example written in Python, which is the lang I'm most
familiar with, and also it is a full SSO framework, whereas a few other projects I looked at didn't
appear to be full examples.

## How far you got in making it work
Since it is a drop in framework, I was able to get 90% of the way there. It was relatively simple to
set up the login, after cloning the github. It required a few dependencies, and then used Docker to
run the app. It handles all of the login/SSO stuff within the Docker section, I just need a website
to put it on.

## What obstacles you encountered in the process
The main problem I encountered was the last step of getting it up on a website, mainly because I don't
know anything about websites and it was not part of any tutorials I found. What I /think/ I have to 
do is to setup the path that the Auth0 login must run to, and to do that I need to allow localhosting
on my machine, or send it to a website that I have control over. 

