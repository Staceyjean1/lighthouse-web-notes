# README.md

## Stacey's Notes

### Summary

This repository contains all the notes taken by [Stacey](https://github.com/Staceyjean1) for the [Lighthouse Labs](https://www.lighthouselabs.ca) Web Developer program

*[Week 1](/Week_1)

  *[Day 1](/Day_1)

### Tips


Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```const whatToDoForLunch = function (hungry, availableTime) {
  console.log("I don't know what to do!");
if (hungry === false) {
  console.log('Get back to work');
  }
  else if (hungry === true && availableTime < 20) {
    console.log('Pick up a snack or grab something you have ready at home.');
  }
  else if (hungry === true && availableTime < 30) {
    console.log('You deserve a break. Take some time to cook a tasty meal.');
  }
  else (hungry === true && availableTime > 30) 
    console.log('This is an intense program and you might want to reconsider');
};
