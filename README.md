# cse230-assignment-7-solved
**TO GET THIS SOLUTION VISIT:** [CSE230 Assignment 7 Solved](https://www.ankitcodinghub.com/product/cse230-assignment-7-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96175&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE230 Assignment 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Minimal Submied Files

You are required to turn in the following source file: assignment7.s

Objecves:

-write assembly language programs to:

-define a recursive procedure/function and call it.

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
-use syscall operations to display integers and strings on the console window

-use syscall operations to read integers from the keyboard. Assignment Description:

Implement a MIPS assembly language program that defines “main”, and “function1” procedures.

The function1 is recursive and should be defined as:

function1(n) = 5*n + 14 if n &lt;= 3

= function1(n-1)/n + n*function1(n-3) + 4*n

otherwise

The main asks a user to enter an integer for n and calls the function1 by passing the n value, then prints the result. If your program causes an infinite loop, press Control and ‘C’ keys at the same time to stop it. Name your source code file assignment7.s.

C program that will ask a user to enter an integer, calls the fuction1, and prints the returned value from the function1.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>// The function1 is a recursive procedure/function defined by:
// function1(n) = 5*n + 14 if n &lt;= 3
//              = function1(n-1)/n + n*function1(n-3) + 4*n  otherwise.
</pre>
<pre>int function1(int n)
{
</pre>
if (n &lt;= 3) {

<pre>        int ans1 = 5*n + 14;
</pre>
<pre>        return ans1;
    }
</pre>
else {

<pre>        int ans1 = function1(n-1)/n + n*function1(n-3) + 4*n;
</pre>
<pre>        return ans1;
    }
</pre>
}

<pre>// The main calls function1 by entering an integer given by a user.
void main()
{</pre>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
https://canvas.asu.edu/courses/56799/pages/assignment7-due-friday-september-25th-5pm?module_item_id=3410174 3/4

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
The following is a sample output (user input is in bold):

Enter an integer:

9

The solution is: 2207 ————————————————–

What to turn in:

-Upload your assignment7.s file through the assignment submission link in the course website by the assignment deadline. You must have your name, email address, program description, and other information in the header block as it was described in the assignment 1, and your programs should be well commented.

Go to “GradeScope” tab on Canvas -&gt; CSE/EEE230 -&gt; Assignment7, and upload your program file.

Each procedure/function needs to have a header using the following format:

############################################################ ################

# Procedure/Function function1

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>    int ans, n;
    printf("Enter an integer:\n");
</pre>
<pre>    // read an integer from user and store it in "n"
    scanf("%d", &amp;n);
</pre>
<pre>    ans = function1(n);
</pre>
<pre>    // print out the solution computed by function 1
    printf("The solution is: %d\n", ans);
</pre>
return; }

</div>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
mb

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
9/23/2020 Assignment7 – Due: Friday, September 25th, 5pm: CSE 230: Computer Org/Assemb Lang Prog (2020 Fall)

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
# Description: —–

# parameters: $a0 = n value

# return value: $v0 = computed value

# registers to be used: $s3 and $s4 will be used. ############################################################ ################

</div>
</div>
</div>
</div>
</div>
