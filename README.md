# csci112-lab-6--dynamic-programming-solved
**TO GET THIS SOLUTION VISIT:** [CSCI112  Lab 6- Dynamic Programming Solved](https://www.ankitcodinghub.com/product/csci112-dynamic-programming-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116927&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI112 &nbsp;Lab 6- Dynamic Programming Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
File names: Names of files, functions, and variables, when specified, must be EXACTLY as specified. This includes simple mistakes such as capitalization.

Documentation: Each file should begin with a docstring that includes your name, the class number and name, the lab number, and a short description of the lab, as well as documentation pertinent to that particular file.

Substring: One string is a substring of another if the characters in the first string occur, in order, somewhere in the second string. For example, the string “geoff” is a substring of the string “xxgxxeoxxfxxxf”. We will write a boolean function that returns True or False depending on whether the first argument is a substring of the second.

Recursive solution: Code up a recursive solution to this problem using the following strategy:

• If the first string is empty then return True

• If the second string is empty then return False

• If the first letter of the first string does not match the first letter of the second string, then recursively try to match the first string with the second string without its first letter.

• If the first letter of the first string does match the first letter of the second string, then check recursion both with and without matching the first letters. If either one succeeds, then the case succeeds.

Dynamic programming: Code up a non-recursive solution to this problem by building up an m×n table of results matching each letter of the potential substring with the superstring. For example, trying to determine whether “abc” is a substring of “xabbxc” we get the following table, where 1 is True and 0

is False:

c a

b b x c

1 1 1 1 1 1 1

a 0 0 1 1 1 1 1

b 0 0 0 1 1 1 1

c 0 0 0 0 0 0 1

Each cell in the table represents whether the string at the left (up to the current row) is a substring of the string at the top (up to the current column). This can be determined from the two current characters in the strings, and the entries in the table above and to the left of the current entry, so the table can be filled in with a dynamic programming algorithm.

Turn in: Two procedures: is_substring_recursive and is_substring_dynamic, defined in a file called substring.py. Also a unittest module called substring_test.py with randomly generated test strings. Put all in a folder called csci112lab06yourname, zip and turn into canvas.

1
