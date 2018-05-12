# Feed Reader Testing

## Table of Contents
* [Introduction](#introduction)
* [Instructions](#instructions)
* [Test Suites](#test_suites)


## Introduction

This project is for use [Jasmine](https://jasmine.github.io)testing framework.Learn how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation. Testing is an important part of the development process.

## Instructions

To load and run testing project follow the steps:
  - Clone the project in the folder you want
    ```
    git clone https://github.com/morojAlh/frontend-nanodegree-feedreader.git
    ```
  - Go to the folder you download the project in it > frontend-nanodegree-feedreader
  - Open `index.html` with your browser if you want to see the result of the test.
  - `spec/feedreader.js` file, it has all the testing code.

## Test Suites

There are a four test suites in this project.
* ### RSS Feeds
1. Test if feeds are defined.
2. Test if feeds have defined URL and not empty.
3. Test if feeds have defined name and not empty.

* ### The menu
1. Test if the menu is hidden by default.
2. Test if the menu is hidden/show when clicking menu icon.

* ### Initial Entries
1. Test if the feed has at least one entry.

* ### New Feed Selection
1. Test if the content actually changes when lode a new feed.
