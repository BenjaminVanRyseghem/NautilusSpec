Authors:

- Roberto Minelli
- Benjamin Van Ryseghem


#A user interaction based system browser

##Introduction

A system browser is the main tool of a Smalltalk developer as it
provides easy access to the whole system source code. From the early
days of Smalltalk to today the system browser has proposed a workflow
statically described by the system browser architects. Due to this
static description, the way to use the system browser is not really
adapted to the user needs. Even if some implementation of this tool
(OmniBrowser or Nautilus by example) proposed some mechanisms to bend
the system browser workflow to fit the user workflow. But so far this
implementations were based on some extensions that the user, who is also
a coder, can add by implementing new behaviours.

We would like to reimplement Nautilus (the current Pharo system browser)
using Spec. This new framework provides the possibility to dynamically
change the user interface. Such a feature combined with the ability to
collect user interaction data provided by D-Flow will be used to make
the system browser as close as the user interactions as possible.

The goal is to simplify the usage of the system browser which is the
back bone tool of the system. To achieve this goal we would like to have
a new system browser that can dynamically change the way information are
presented in order to ease its usage for each user.

##Challenges
