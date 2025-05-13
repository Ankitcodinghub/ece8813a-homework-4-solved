# ece8813a-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [ECE8813A Homework 4 Solved](https://www.ankitcodinghub.com/product/ece8813a-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93863&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE8813A Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Watch the following videos:

(a) https://youtu.be/C-BXzVBoJ3U : Algorithmic State Machine

(b) https://youtu.be/5EcYI0NfvXg : Watching from time 0 to 21 minutes is required. The rest of the video is optional.

You are responsible for the content contained in these videos and the content may be asked on a quiz or an exam.

PROBLEM 4.1:

Given: Farmer John has given some additional design clarifications. There are 10 zones that he wants to control. Each zone has different requirements for water, so he wants to be able to configure the times for each zone. The water pump is only large enough to water one zone at a time and so it is very important to only water 1 zone at a time regardless of the timing that is programmed. If more than one zone is set to be watered at time you must set the output to only water one zone and set the error out value to 1.

GPS control will be used for this design and a state machine to change zones. The state machine must be designed with an Algorithmic State Machine (ASM) diagram. Please turn in you ASM diagram and your block diagram at the start of class. The code will due turned in to T-Square.

The module declaration should be as follows:

module hw4 sprinkler(clk , rain sensor in , gps data in ,

gps valid in , program valid in , program zone in ,

program time in , zone active out , error out )

//Inputs

input clk ;

input rain sensor in ;

input [7:0] gps data in; input gps valid in ;

input program valid in ;

input [4:0] program zone in ; input [31:0] program time in ;

//outputs

output [9:0] zone active out ; output error out;

Where program zone in is set according to Table 1. The value of program zone in is passed as an unsigned value from 1 to 20. The value of program time in is set in the format hhmm in ASCII format. The program valid in must be held high for 1 clock cycle to indicate the data on the program zone in and program time in are valid.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Value

</div>
<div class="column">
Description

</div>
<div class="column">
Value Description

2 Zone 1 End Time 4 Zone 2 End Time 6 Zone 3 End Time 8 Zone 4 End Time

10 Zone 5 End Time 12 Zone 6 End Time 14 Zone 7 End Time 16 Zone 8 End Time 18 Zone 9 End Time 20 Zone 10 End Time

</div>
</div>
<div class="layoutArea">
<div class="column">
Table 1: Programming Zone Description

</div>
</div>
<div class="layoutArea">
<div class="column">
1 Zone 1 Start Time 3 Zone 2 Start Time 5 Zone 3 Start Time 7 Zone 4 Start Time 9 Zone 5 Start Time

11 Zone 6 Start Time 13 Zone 7 Start Time 15 Zone 8 Start Time 17 Zone 9 Start Time 19 Zone 10 Start Time

</div>
</div>
<div class="layoutArea">
<div class="column">
A file (zone program.txt)has also been attached to this assignment. Farmer John provided this file as an example watering schedule. The first column of the file is the program zone in and the second column is the program time in that should be passed to the module in ASCII format.

</div>
</div>
</div>
