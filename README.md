# hello-world
The repository is created with the goal of learning how GitHub works.
Procedures learned and tested include branching, pulling, pushing, merging, etc. as per the GitHub tutorial.
# Exercises: C# Intro and Basic Syntax

Problems for exercises and homework for the [&quot;Programming Fundamentals Extended&quot; course @ SoftUni](https://softuni.bg/courses/programming-fundamentals).

## Problem 1. Debit Card Number

Write a program, which receives **4 integers** on the console and **prints them** in **4-digit debit card format**. See the examples below for the appropriate formatting.

### Examples

<table>
  <tr>
    <td><strong>Input</strong></td>
    <td><strong>Output</strong></td>
  </tr>
  <tr>
    <td>12</td>
	<td rowspan="4" valign="top">0012 0433 0001 5331</td>
  </tr>
  <tr>
    <td>433</td>
  </tr>
  <tr>
    <td>1</td>
  </tr>
  <tr>
    <td>5331</td>
  </tr>  
  <tr>
    <td>9182</td>
	<td rowspan="4" valign="top">9182 4221 0012 0003</td>
  </tr>
  <tr>
    <td>4221</td>
  </tr>
  <tr>
    <td>12</td>
  </tr>
  <tr>
    <td>3</td>
  </tr>
  <tr>
    <td>812</td>
	<td rowspan="4" valign="top">0812 0321 0123 0022</td>
  </tr>
  <tr>
    <td>321</td>
  </tr>
  <tr>
    <td>123</td>
  </tr>
  <tr>
    <td>22</td>
  </tr>
</table>

## Problem 2. Rectangle Area

Write a program, which calculates a **rectangle&#39;s area**, based on its **width** and **height**. The **width** and **height** come as floating point numbers on the console, **formatted to the 2<sup>nd</sup> character after the decimal point**.

### Examples
<table>
  <tr>
    <td><strong>Input</strong></td>
	<td><strong>Output</strong></td>
  </tr>
  <tr>
    <td>2</td>
	<td rowspan="2" valign="top">14.00</td>
  </tr>
  <tr>
    <td>7</td>
  </tr>
  <tr>
    <td>7</td>
	<td rowspan="2" valign="top">56.00</td>
  </tr>
  <tr>
	<td>8</td>
  </tr>
  <tr>
    <td>12.33</td>
	<td rowspan="2" valign="top">61.65</td>
  </tr>
  <tr>
	<td>5</td>
  </tr>
 </table>

## Problem 3. Miles to Kilometers

Write a program, which **converts miles** to **kilometers**. **Format** the output to the **2<sup>nd</sup> decimal place**.

Note: **1 mile == 1.60934 kilometers**

### Examples

<table style="border: 0px solid black; border-color: none; background-color: none;">
  <tr>
    <td>
	  <table style="float: left;">
		<tr>
		  <td><strong>Input</strong></td>
		  <td><strong>Output</strong></td>
		</tr>
		<tr>
		  <td>60</td>
		  <td>96.56</td>
		</tr>
	  </table>
    </td>
	<td>
	  <table style="float: middle;">
		<tr>
		  <td><strong>Input</strong></td>
		  <td><strong>Output</strong></td>
		</tr>
		<tr>
		  <td>1</td>
		  <td>1.61</td>
		</tr>
	  </table>
	</td>
  	<td>
	  <table style="float: right;">
		<tr>
		  <td><strong>Input</strong></td>
		  <td><strong>Output</strong></td>
		</tr>
		<tr>
		  <td>52.1113</td>
		  <td>83.86</td>
		</tr>
	  </table>
	</td>
</table>

## Problem 4. Beverage Labels

Write a program, which reads a food product **name, volume, energy content per 100ml** and **sugar content per 100ml**. Calculate the **energy** and **sugar content** for the **given volume** and print them on the console in the following format:

- Name – as per the input
- Volume – **integer** , **suffixed** by &quot;**ml**&quot; (e.g. &quot;**220ml**&quot;)
- Energy content – **integer** , **suffixed** by &quot;**kcal**&quot; (e.g. &quot;**500kcal**&quot;)
- Sugar content – **integer** , **suffixed** by &quot;**g**&quot; (e.g. &quot;**30g**&quot;)

### Examples

<table>
  <tr>
    <td><strong>Input</strong></td>
	<td><strong>Output</strong></td>
  </tr>
  <tr>
    <td>Nuka-Cola</td>
	<td rowspan="4" valign="top">220ml Nuka-Cola:<br>660kcal, 154g sugars</td>
  </tr>
  <tr>
    <td>220</td>
  </tr>
  <tr>
    <td>300</td>
  </tr>
  <tr>
    <td>70</td>
  </tr>
</table>

<table>
  <tr>
    <td><strong>Input</strong></td>
	<td><strong>Output</strong></td>
  </tr>
  <tr>
    <td>Ice Cold Nuka-Cola</td>
	<td rowspan="4" valign="top">250ml Ice Cold Nuka-Cola:<br>875kcal, 162.5g sugars</td>
  </tr>
  <tr>
    <td>250</td>
  </tr>
  <tr>
    <td>350</td>
  </tr>
  <tr>
    <td>65</td>
  </tr>
</table>
<table>
  <tr>
    <td><strong>Input</strong></td>
	<td><strong>Output</strong></td>
  </tr>
  <tr>
    <td>Nuka-Cola Quantum</td>
	<td rowspan="4" valign="top">350ml Nuka-Cola Quantum:<br>2100kcal, 490g sugars</td>
  </tr>
  <tr>
    <td>350</td>
  </tr>
  <tr>
    <td>600</td>
  </tr>
  <tr>
    <td>140</td>
  </tr>
</table>

## Problem 5.\* Character Stats

Write a program, which **displays information** about a video game character. You will receive their **name, current health, maximum health, current energy** and **maximum energy** on separate lines. The **current** values will **always** be valid (**equal or lower** than their respective **max** values). Print them in the format as per the examples.

### Examples
<table>
  <tr>
    <td>
		<table style="float: left;">
		  <tr>
			<td><strong>Input</strong></td>
			<td><strong>Output</strong></td>
		  </tr>
		  <tr>
			<td>Mayro</td>
			<td rowspan="5" valign="top">Name: Mayro<br>Health: ||||||.....|<br>Energy: ||||||||||.|</td>
		  </tr>
		  <tr>
			<td>5</td>
		  </tr>
		  <tr>
			<td>10</td>
		  </tr>
		  <tr>
			<td>9</td>
		  </tr>
		  <tr>
			<td>10</td>
		  </tr>
		</table>
    </td>
    <td>
		<table style="float: left;">
		  <tr>
			<td><strong>Input</strong></td>
			<td><strong>Output</strong></td>
		  </tr>
		  <tr>
			<td>Bauser</td>
			<td rowspan="5" valign="top">Name: Bauser<br>Health: ||||||||||||<br>Energy: ||||||||||||</td>
		  </tr>
		  <tr>
			<td>10</td>
		  </tr>
		  <tr>
			<td>10</td>
		  </tr>
		  <tr>
			<td>10</td>
		  </tr>
		  <tr>
			<td>10</td>
		  </tr>
		</table>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
		<table style="float: left;">
		  <tr>
			<td><strong>Input</strong></td>
			<td><strong>Output</strong></td>
		  </tr>
		  <tr>
			<td>Loogi</td>
			<td rowspan="5" valign="top">Name: Loogi<br>Health: |||||||||............|<br>Energy: |||............|</td>
		  </tr>
		  <tr>
			<td>8</td>
		  </tr>
		  <tr>
			<td>20</td>
		  </tr>
		  <tr>
			<td>2</td>
		  </tr>
		  <tr>
			<td>14</td>
		  </tr>
		</table>
    </td>
    <td>
		<table style="float: left;">
		  <tr>
			<td><strong>Input</strong></td>
			<td><strong>Output</strong></td>
		  </tr>
		  <tr>
			<td>Toad</td>
			<td rowspan="5" valign="top">Name: Toad<br>Health: |.....|<br>Energy: |..........|</td>
		  </tr>
		  <tr>
			<td>0</td>
		  </tr>
		  <tr>
			<td>5</td>
		  </tr>
		  <tr>
			<td>0</td>
		  </tr>
		  <tr>
			<td>10</td>
		  </tr>
		  </table>
    </td>
  </tr>
</table>

### Hints

- You can print a character **multiple** times, using **new string(character, count)**.