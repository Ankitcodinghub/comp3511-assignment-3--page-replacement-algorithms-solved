# comp3511-assignment-3--page-replacement-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [COMP3511 Assignment 3- Page-Replacement Algorithms Solved](https://www.ankitcodinghub.com/product/comp3511-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115069&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3511 Assignment 3- Page-Replacement Algorithms Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

You are highly recommended to attend the corresponding project-related lab.

Program Usage

The program name is page_replacement. Here is the sample usage:

$&gt; ./page_replacement &lt; input.txt &gt; output.txt

$&gt; represents the shell prompt.

&lt; means input redirection, which is used to redirect the file content as the standard input

&gt; means output redirection, which is used to redirect the standard output to a text file Thus, you can easily use the given test cases to test your program and use the diff command to compare your output files with the sample output files.

Getting Started

page_replacement_skeleton.c is provided. You should rename the file as page_replacement.c

You can add new constants, variables, and helper functions

Necessary header files are included. You should not add extra header files.

Some constants and helper functions are provided in the starter code. Please read the skeleton code carefully.

Assumptions

• There are at most 10 different frame numbers (i.e., frame 0-9)

• The maximum number of available frames is 10

• The maximum size of the queue data structure (used in FIFO) is 10

• The maximum length of the reference string is 30 (defined in the starter code)

Input and Output Format

The input parsing is given in the skeleton code. Empty lines and lines starting with # are ignored A sample input file:

The output consists of 2 regions:

• Displaying the parsed values from the input

• Displaying the steps of the algorithm and the total page fault.

First-In-First-Out (FIFO) Page Replacement Algorithm

A queue data structure is given in the starter code. You should use a queue to implement the FIFO page-replacement algorithm.

Optimal (OPT) Page Replacement Algorithm

To avoid multiple solutions, if there are more than one choice of the victim frame, we should choose a frame with the smallest frame number. For example, if frame 0 and frame 1 are victim frames, you should choose frame 0.

Least Recently Used (LRU) Page Replacement Algorithm

There are 2 possible implementations of LRU page-replacement algorithm: Counters implementation and Stack implementation.

In this project, we have a small number of frames (i.e., frame 0-9), so the counters implementation is more suitable. You can create an array of integers to store the current count of the frames. So, there is no specific data structure for the LRU page-replacement algorithm if you use the counters implementation.

If you prefer to have the stack implementation, you can implement your own stack data structure, which is quite similar to the queue data structure given in the starter code.

Compilation

The following command can be used to compile the program

$&gt; gcc -std=c99 -o page_replacement page_replacement.c

The option c99 is used to provide a more flexible coding style (e.g., you can define an integer variable anywhere within a function)

Sample test cases

Several test cases (both input files and output files) are provided. We don’t have other hidden test cases.

$&gt; diff –side-by-side your-outX.txt sample-outX.txt Sample Executable

The sample executable (runnable in a CS Lab 2 machine) is provided for reference. After the file is downloaded, you need to add an execution permission bit to the file. For example:

$&gt; chmod u+x page_replacement

Development Environment

CS Lab 2 is the development environment. Please use one of the following machines (csl2wkXX.cse.ust.hk), where XX=01…40. The grader will use the same platform.

In other words, “my program works on my own laptop/desktop computer, but not in one of the CS Lab 2 machines” is an invalid appeal reason. Please test your program on our development environment (not on your own desktop/laptop) thoughtfully before your submission, even you are running your own Linux OS. Remote login is supported on all CS Lab 2 machines, so you are not required to be physically present in CS Lab 2.

Marking Scheme

2. Make sure you use the Linux diff command to check the output format.

3. Make sure to test your program in one of our CS Lab 2 machines (not your own desktop/laptop computer)

4. Please fill in your name, ITSC email, and declare that you do not copy from others. A template is already provided near the top of the source file.

Submission

File to submit:

page_replacement.c

Please check carefully you submit the correct file.

You are not required to submit other files, such as the input test cases.

There is a 10% deduction, and only 1 day late is allowed
