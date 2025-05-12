# verilog-lab-11-morse-code-to-ascii-solved
**TO GET THIS SOLUTION VISIT:** [Verilog Lab 11-Morse Code to ASCII Solved](https://www.ankitcodinghub.com/product/verilog-lab-11-morse-code-to-ascii-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91455&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Verilog Lab 11-Morse Code to ASCII Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Lab 11

Morse Code to ASCII

In this lab you will use a lookup table (LUT) implemented using a memory elements to convert Morse code patterns of dots and dashes into ASCII code. The outputted ASCII codes will be pushed into a FIFO buffer and displayed on the seven-segment display

<ul>
<li>Implement the system shown in the figure on the FPGA board</li>
<li>The red OR gate resets the 5-bit shift register and the 3-bit UDL counter after each letter
(or word)
</li>
<li>wg_delayedisnecessarytopushaspaceattheendofaword(i.e.afterawg)</li>
<li>Figure out the width and depth of the ROM and FIFO buffer interface</li>
<li>Use the included morse2ascii_lut.xlsx to figure out the initial values of ROM</li>
<li>You can use your Morse Decoder or the decoder I provided in the starter code.
However, if you decided to use mine, please keep in mind:

o The decoder was designed using a single timer/counter structure

o The functionality of the decoder depends on knowing when to reset, enable, and

disable the timer/counter structure 1
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Note:

</div>
</div>
<div class="layoutArea">
<div class="column">
o YoucanchangethetimervaluebychangingtheTIMER_FINAL_VALUE parameter

o Generatingawgsignaldoesn’tmeanlgwillalsobegenerated

o I have tested my decoder; however, I might have missed some corner cases (i.e.

use it at your own risk)

</div>
</div>
<div class="layoutArea">
<div class="column">
I used the binary tree shown above to fill out the lookup table in the excel sheet. To get the letter associated with a certain code, move right for a dash and left for a dot.

Submission check list:

[ ] All Verilog code you generated or modified

[ ] All testbenches written

[ ] Embed all screenshot of your testbench output in your README.md

[ ] Embed all block diagram or state diagrams generated in your README.md

[ ] Short videos demonstrating each of the parts you implemented on the FPGA

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
