LadBot
======

A bot for keeping track of users' ladpoints in an IRC channel. It's written in node.js, and uses [Martyn Smith's node-irc module](https://github.com/martynsmith/node-irc).

Ladpoints are intended to be given to people when they do something great. When they do something stupid, you take away some of their ladpoints.

### Use:

* **?ladpoints [user]**:  
  Display the ladpoints for a user.
* **++ladpoitns [user]**:
  Increment a user's ladpoint count.
* **--ladpoints [user]**:
  Decrement a user's ladpoint count.
  
Only users who are registered and identified with nickserv can have ladpoints.

## Contribute:

If you feel like contributing to this project, but don't know a lot about programming, you can add random messages.

* **[messages/goodLad](https://github.com/mortie/LadBot/blob/master/messages/goodLad)**:  
  Messages displayed when someone increments {nick}'s ladpoint count.

* **[messages/badLad](https://github.com/mortie/LadBot/blob/master/messages/badLad)**:  
  Messages displayed when someone decrements {nick}'s ladpoint count.

* **[messages/points](https://github.com/mortie/LadBot/blob/master/messages/points)**:  
  Messages displayed when someone wants {nick}'s ladpoint count.

* **[messages/unknownLad](https://github.com/mortie/LadBot/blob/master/messages/unknownLad)**:  
  Messages displayed when someone tries to do somethnig with a lad which doesn't exist, or isn't registered.

* **[messages/modifySelf](https://github.com/mortie/LadBot/blob/master/messages/modifySelf)**:  
  Messages displayed when {nick} tries to modify their own ladpoint count.

 Each new line is its own message, and the messages are chosen at random. Feel free to pull request with creative messages!
 
 If you know programming on the other hand, it's basically the same as with any other open source project: add features, clean up code, optimise, etc.