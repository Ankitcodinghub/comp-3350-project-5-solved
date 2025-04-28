# comp-3350-project-5-solved
**TO GET THIS SOLUTION VISIT:** [COMP 3350 Project #5 Solved](https://www.ankitcodinghub.com/product/comp-3350-project-5-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118986&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP 3350 Project #5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Requirements:

• Read the design section and write a program. Submit source file .asm to Canvas.

Deliverables:

• Save your source of assembly program as a .asm file.

• Name document of source code as a “Firstname_Lastname.asm”.

• Submit your “Firstname_Lastname.asm” and “Firstname_Lastname.png” through the Canvas system.

Rebuttal period:

Objective:

This program has two objectives. The first objective is to create a procedure that will take plaintext and an encryption key, use the Vigenère cipher, and encrypt the plaintext. The second objective is to create a procedure that will take cypher-text, an encryption key, use the Vigenère cipher, and decrypt the cypher-text.

Assume that all characters will be uppercase letters, no spaces, symbols, etc.

All “high level” directives are not allowed on this homework. (e.g. .IF .ENDIF .REPEAT, etc)

Design:

Create a BYTE array with the label ‘key’. This array will have length between 1 and (LENGHTOF input -1). Meaning the lower bound for ‘key’ is one character and the upper bound is one less than the number of characters in ‘input’.

Create a BYTE variable named “options”. This variable will be used to determine which procedures should be executed. If ‘options’ contain the value 1 it means the program should execute encryption procedure. If ‘options’ contain the value 0 (or any other value than 1) the program should execute decryption procedure.

Create a BYTE array with the label ‘output’. This array will have a dynamic length equal to

LENGTHOF input. When executing the program using encryption, the variable ‘output’ will hold the cypher-text and in the case of decryption, ‘output’ will hold plaintext.

Example of encryption / decryption:

For more information check the Wiki link: (https://en.wikipedia.org/wiki/ Vigenère_cipher) The example below will use the plaintext word MEMORY and the key BAD.

First you “line up” your plaintext word with your key by writing the key directly beneath the plaintext word. Continue to repeat the key under each plaintext character:

MEMORY

BADBAD

In the above example MEMORY is longer than BAD, therefore, BAD was repeated. Next choose each character in the plaintext word, starting with the first and encrypt it.

To encrypt a character, you first find the column on the chart corresponding to the character in the plaintext, e.g. the character M (circled in red). Next, find the row starting with the key character, e.g. the character B (circled in red). Finally, find where the plaintext column and the key row intersect, e.g. the character N (circled in red). Continue this for each character.

MEMORY

BADBAD

MEMORY

BADBAD

MEMORY BADBAD

Continue until all characters have been encrypted:

Input = MEMORY (plaintext) Key = BADBAD (key) output= NEPPRB (cypher-text)

Decrypting is the opposite of encrypting. To decrypt NEPPRB first write the key under the cyphertext. Then find the row starting with the key character. Next, move across that row until you find the cypher-text character. The cypher-text character’s column is the plaintext column.

NEPPRB

BADBAD

NEPPRB

BADBAD

NEPPRB

Continue until the cypher-text has been decrypted:

Input = NEPPRB

Key = BADBAD

Output = MEMORY

(80 points): Read the comments in the template file “project5_template.asm” and finish (1) – (8) (15 points) A screenshot of the result after you compile and run program, correctly demonstrate the decryption result of the input “JPUESZSBAPANNHTXRTLBVLL”. The screenshot file should be named as “Firstname_Lastname.png” or “Firstname_Lastname.jpg” or any other valid picture format suffix.

To take a screenshot, right-click on output, select Add Watch.

Change the Name of output into &amp;output,30. The result should appear in the value column.
