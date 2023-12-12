# Console-Finances
## Console Finances Challenge for edX
### Matthew Dudman

## Description

Within this challenge, I was given a  real-world situation where I was tasked with creating code for analyzing the financial records of a company. 

## Table of Contents

- [Introduction](#introduction)
- [About](#about)
- [License](#license)
- [Deployed Link](#deployed-link)
- [Author](#author)


## Introduction

My goal was to calculate what is stated below - 

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the changes in Profit/Losses over the entire period.

* You will need to track what the total change in Profit/Losses are from month to month and then find the average.

* The greatest increase in Profit/Losses (date and amount) over the entire period.

* The greatest decrease in Profit/Losses (date and amount) over the entire period.

This code essentially goes through each month in the financial dataset, I have instructed it to perform calculations such as net total, average change, and identifies the months with the greatest increase and decrease in profit/loss. 


## About

I started by pseudo coding out what I needed to do for this challenge within my JS file. This way when I was working through the task, I could recite back if I was getting lost at all. 

I started by naming and establishing the variables which I had as 

* var finances - this data was already provided which was a dataset composed of arrays with two fields, Date and Profit/Losses
* var totalMonths -  set to the total number of months in the finances dataset. It is determined by the length of the finances array.
* var netTotal - will store the total profit/loss over the entire period.
* var totalChange - will store the sum of changes in profit/loss over the entire period.
* var greatestIncrease & var greatestDecrease - These are objects used to store information about the greatest increase and decrease in profit/loss. 

I then used a for loop to loop through the dataset and then used the 'date' and 'profitLoss' to house the date and profit/loss for the month. After this I went on to calculate the net total by adding the profit/loss for the month. 

The next step was to calculate the chnage and greatest increase/decrese which I went about by using an if statement. Then calculated the average chnage by using the formula (Total Change) / (Number of months - 1).

At the end I displayed everything with Console.log for each statement. 

I got the console to display the numbers with pounds sterling and decimnal points by using - 
* console.log('The Net total is £' + netTotal.toLocaleString('en-GB'));

I used "toLocaleString('en-GB')" to format the numbers accordingly. 

This is what was shown in the console at the end - 

![Alt text](<Assets/Screenshot 2023-12-12 at 21.31.41.png>)


## License

MIT License

Copyright (c) 2023 Matt Dudman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Deployed Link
 * [See Deployed Link Here](https://atypicalbitter.github.io/Console-Finances/)

## Author
 * [Matt Dudman](https://github.com/atypicalbitter)