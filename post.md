# Lab 2: Let's play with Circuits!

# Overview and Motivation
Welcome to the Lab 02 of CS281: Introduction to Computer Systems! 
This lab will help you get more familiar with mux and logic circuits. The lab will take you through the intricacies of the 74150 mux chip and different gates (And, Or, Not). By the end of this lab, you'll be adept at working with essential circuit components.

<br><img width="400" src="number.png">

# Objectives of the Lab
1. Familiarize yourself with the mux chip and learn to control it.
2. Understand and construct an Adder by using circuit chips.
3. Develop the ability to read and interpret IC data sheets.
4. Gain hands-on experience in controlling circuits with the Arduino.
 
# Materials
- PB-503 breadbofard prototyping station (integrated device with a number of electrical components like switches)
- Arduino kit
- Potentiometer
- 7404 NOT gate IC
- 7408 AND gate IC
- 7432 OR gate IC
- Resistor
- Wires
- LED
- Arduino controller and USB cable



# Building the Lab: The Voltage Divider
## 0 What do we need to know?
First of all, we need to know about hte Voltage Divider!<br>
Voltage divider is a arrangement of resistors configured to create a target voltage. <br>
We will use below equation to calculate the volage current.
<br><img width="400" src="eq1.png">

We will have a constant voltage with 5 volts and the current is inversely proportional to the resistance. <br>
Which means changing the resistance will inversly change the current that bigger the resistance, smaller the current. <br>
<br><img width="400" src="5.png">
<br><img width="400" src="6.png">

In order to finout the voltage of the V in the above picture, we will use below equation since we know the current will be the same across the curcit.
<br><img width="400" src="eq2.png">

Since the voltage of this lab will be 5V, by changing the "R1" and "R2",  we can generate any voltage V that we want between 0 and 5 volts. <br>


Now we need to know that is a "potentiometer". <br>
A potentiomter is a variable resistor that allows us to fine tune our voltage divider. <br>
This means that by using potentiometer, we can vary the value of "R1" and "R2" in a way to change the value of V like the photo below. <br>
The value that is written in the potentiometer means that the sum of "R1" and "R2" is the number (ex 10KΩ).
<br><img width="400" src="4.png">
This is how we will set up the poteniometer!

## 1. Project Step

<br><img width="400" src="3.png"><br>

Let's start building and testing the potentiometer! <br>
We will generate voltage V in a range of 0 to 5 volts using the voltage divider from the potntiometer. <br>
We will use this output signal as a input the the Aruino for "analog input" pin 0 (A0).<br>
#### Note: Do not forget to GND the wire to the leftmost connection column of the potentiometer and +5V to the rightmost column.
#### Note: Middle connections are all the same and you will wire one of these middle connections for the output of the voltage V. 
#### Note: Make sure the input is pinned to analog input NOT digital pin 0. <br>
<br>
<br><img width="400" src="2.png"> <br>
We will use output pins 11, 12, and 13 to produce a binary signal (pin11 =B0, pin12 = B1, pin13 = B0) based on the potentiometer reading. <br>
These signals will be input to breadboard logic so that we can express numbers in 7-segment display. 
<br><img width="400" src="0.png"><br>




## 2. Testing



# Reading and Converting the Potentiometer Output
## 0 About

## 1. Project Step

## 2. Testing


# Building the Combinational Logic to Display DVal
## A LED
### 0 About
<br><img width="400" src="1.jpg">


 
### 1. Project Step



### 2. Testing



### Example tests:

## B LED
### 0 About
<br><img width="400" src="1.jpg">


 
### 1. Project Step



### 2. Testing



### Example tests:

## C LED
### 0 About
<br><img width="400" src="1.jpg">


 
### 1. Project Step



### 2. Testing



### Example tests:

## D LED
### 0 About
<br><img width="400" src="1.jpg">


 
### 1. Project Step



### 2. Testing



### Example tests:

## E LED
### 0 About
<br><img width="400" src="1.jpg">


 
### 1. Project Step



### 2. Testing



### Example tests:

## F LED
### 0 About
<br><img width="400" src="1.jpg">


 
### 1. Project Step



### 2. Testing



### Example tests:

## G LED
### 0 About
<br><img width="400" src="1.jpg">


 
### 1. Project Step



### 2. Testing



### Example tests:

# Testing Number Display




https://github.com/mlcourses/lab-3-blog-post-group2_cs281/assets/108073642/1d9d0539-d0f4-45af-96cb-9cb0b0d6a2df



https://github.com/mlcourses/lab-3-blog-post-group2_cs281/assets/108073642/cf37c88d-062a-487c-b540-a757192dc038



https://github.com/mlcourses/lab-3-blog-post-group2_cs281/assets/108073642/41df861f-9340-4d9a-9abd-e5258204418c



https://github.com/mlcourses/lab-3-blog-post-group2_cs281/assets/108073642/7650fa52-f56d-4643-9e5a-d761c9901726



https://github.com/mlcourses/lab-3-blog-post-group2_cs281/assets/108073642/9afb9545-eb94-414a-a182-eecffeac7204



https://github.com/mlcourses/lab-3-blog-post-group2_cs281/assets/108073642/6972c874-b9ce-4fbc-a84e-421ad199cb0e



https://github.com/mlcourses/lab-3-blog-post-group2_cs281/assets/108073642/2ddb0cf6-cff4-4903-a388-4d77e15e3163





# Conclusion








