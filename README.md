## Table of contents
* [Abstract](#abstract)
* [Prerequisites](#Prerequisites)
* [Setup](#setup)

## Abstract
Have you ever wondered how auto completion works? It’s a lot more
complicated in real life, involving machine learning and a lot of backend stuff
that I certainly can’t develop on my own!
As a result, I decided to create a functional prototype that searches an
English word dictionary of roughly 102k terms (because that’s all I could find)
for auto-completion ideas. As you can see, there is no association between
the words because no machine learning is being utilised, but the important
purpose here is to be able to finish the unfinished term (independently i.e
irrespective of what was typed before).
I was more interested in how the back-text (the transparent ghost text
that completes your query) functioned and how I would integrate my word
suggestion into the input field itself than in completion. Here is a list of
words. The words in this repository form a repository.
I utilised a popularity measure based on the frequency of usage of English
words found here to generate better choices. (You can find the repository
here). The only drawback is that it only contains about 10,000 words, which
isn’t bad!

## Prerequisites
Before moving on to the code part, there are few prerequisites to meet:
* Understanding of JavaScript ES6 syntax (classes, async/await) is re-
quired.
* The data structure of a trie.
* Adding DOM event listeners.
* Understanding of the concept of debounce.	

## Setup
To run this project:
Download: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

```
$ git clone https://github.com/sagarbgohil/AutoComplete.git
$ cd AutoComplete
```
Then open the code in VS Code and Run on LiveServer.
