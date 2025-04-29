# cpsc319-assignment-1--searching-sorting-solved
**TO GET THIS SOLUTION VISIT:** [CPSC319 Assignment 1- Searching & Sorting Solved](https://www.ankitcodinghub.com/product/cpsc319-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116155&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPSC319 Assignment 1- Searching \u0026amp; Sorting Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

GOAL

The goal of this assignment is to write a Java program that arranges a list of words into separate lists of anagrams. Your program should be named “asgmt1″ and will be called from the command line. The only input to your program is a file containing a list of words to be sorted into anagrams and is read by your program through standard input. The number of words in the input is arbitrary. Your program should print to standard output the lists of anagrams in the following way:

For example, this input text file:

car

mega bed stop game pots arc tops  Should yield this output text file:

arc car bed

game mega

pots stop tops

1. All the words that are anagrams of each other are printed on one line of output.

2. The words on each line should be in alphabetic order.

3. The groups should be ordered alphabetically by the string that results by sorting the characters in each word.

4. Exactly one space between words on the same line, and no other spaces.

Input File Expected Output

example_1–8_words example_1_out

example_1–13_words example_2_out

example_1–19_words example_3_out

example_1–267_words example_4_out

on D2L) as shown in the right:

ALGORITHMS &amp; DATA STRUCTURES

Step #1. The data from the input structured in a 1-D array of words (e text file “example_1–8_words”):

0 car

1 mega

2 bed

3 stop

4 game

5 pots

6 arc

7 tops



Input text file

text file should be xample: input

LIST A

1-D array of words Step #2. “LIST A” should then be sorted:

0 arc

1 bed

2 car

3 game

4 mega

5 pots

6 stop

7 tops

LIST A

Sorted

1-D array of words

Step #3. Traverse LIST A to generate the required output text file format of found anagrams exactly as shown in the example below for all the 4 input files.

arc car

bed  game mega

pots stop tops

Output

text file for “example_1_out”

Finding Anagrams: A good way to determine if two words are anagrams is to sort the letters in both words. If the two sorted words are the same, then the original two words are anagrams. For example, array entries #5, #6, and #7 (i.e., “pots”, “stop”, and “tops”) from the sorted LIST A of words (i.e., step #2) are anagrams:

‘o’ ‘p’ ‘s’ ‘t’

0 1 2 3

‘o’ ‘p’ ‘s’ ‘t’

0 1 2 3

‘o’ ‘p’ ‘s’ ‘t’

0 1 2 3

‘p’ ‘o’ ‘t’ ‘s’

0 1 2 3

‘s’ ‘t’ ‘o’ ‘p’

0 1 2 3

‘t’ ‘o’ ‘p’ ‘s’

0 1 2 3

𝒂𝒂𝒂𝒂𝒂𝒂𝒂𝒂𝒂𝒂 𝒔𝒔𝒔𝒔𝒂𝒂𝒂𝒂𝒔𝒔𝒔𝒔𝒔𝒔

⎯⎯⎯⎯⎯⎯⎯⎯⎯

𝒂𝒂𝒂𝒂𝒂𝒂𝒂𝒂𝒂𝒂 𝒔𝒔𝒔𝒔𝒂𝒂𝒂𝒂𝒔𝒔𝒔𝒔𝒔𝒔

⎯⎯⎯⎯⎯⎯⎯⎯⎯

𝒂𝒂𝒂𝒂𝒂𝒂𝒂𝒂𝒂𝒂 𝒔𝒔𝒔𝒔𝒂𝒂𝒂𝒂𝒔𝒔𝒔𝒔𝒔𝒔 ⎯⎯⎯⎯⎯⎯⎯⎯⎯

HAND-IN

• Submit your source code electronically to D2L dropbox.

• Please name your source code file as follows: “asgmt-1-your-last name-UCID” • Late assignments will not be accepted.

MARKING

Source code that does not compile or produces run-time errors will receive a grade of 0%

Input File Expected Output # Points

for correct output (Step #3) for partially correct output (Step #2)

example_1–8_words example_1_out 2 1

example_1–13_words example_2_out 2 1

example_1–19_words example_3_out 2 1

example_1–267_words example_4_out 2 1

Total 8 4

2

Asgmt #1 – Searching &amp; Sorting Page 3 of 3

COLLABORATION

• The assignment must be done individually so you must write up the solutions on your own.

END OF THE ASSIGNMENT

3
