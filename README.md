# cmpt135-assignment-4--recursion-solved
**TO GET THIS SOLUTION VISIT:** [CMPT135 Assignment 4- Recursion Solved](https://www.ankitcodinghub.com/product/cmpt135-assignment-4-recursion-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120270&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT135 Assignment 4- Recursion Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
The best way to understand recursion is to practice writing recursive functions. In the comments of a4.h are a series of questions, each of which asks you to write two functions: an answer function that answers the question, and a test function that tests your answer function. For each question, write both functions.

Put your answer and test functions in a4.cpp, and use a4_main.cpp to call the test functions. When you’re done, you’ll submit only a4.cpp.

You will need to compile a4.cpp and a4_main.cpp separately, and then link their .o files into executable for running the tests. A special-purpose makefile is provided to simplify the compiling and linking. Read the comments at the top of makefile to see how it can be used.

Pre-conditions and Post-conditions

The functions are specified using pre-conditions, post-conditions, and constraints. For example:

cpp // Pre-condition: // n &gt;= 0 // Post-condition: // Returns the sum of the first n integers, i.e. 1 + 2 + 3 + … + n. // If n is 0, then 0 is returned. // Constraints: // Must be implemented using recursion (and no loops). You can write // helper functions if necessary. // Note: // You don’t need to worry about sums that overflow int. int sum(int n);

The pre-condition states what must be true before the function is called, and the post-condition states what must be true after the function returns correctly (assuming that the pre-condition was true before the function was called).

Constraints lists anything else that is required for the function to be considered correct.

If a function’s pre-condition is false when the function is called, then that means it’s being called with bad input, and so you probably have a bug somewhere earlier in your code.

Hint A good way to check pre-conditions bugs is to call assert at the start of a function to check if the pre-condition is true.

Testing

For each question, also write a corresponding test function that automatically runs tests on the answer function. For example, the test function for sum could be this:

“`cpp

include

// …

void sum_test() { cout &lt;&lt; “Testing sum … “; assert(sum(0) == 0); assert(sum(1) == 1); assert(sum(2) == 1 + 2); assert(sum(3) == 1 + 2 + 3); assert(sum(4) == 1 + 2 + 3 + 4); cout &lt;&lt; “all sum tests passed! “; } “`

In some cases, you might prefer to use an if-statement rather than assert. The test assert(sum(2) == 1 + 2) could be written like this:

cpp if (sum(2) != 1 + 2) cmpt::error(“test failed”);

However you write your tests, make sure they all run successfully and are checked automatically.

General Implementation Constraints

No loops are permitted in any of the code you write for this assignment (not even in the test functions or helper functions). If your code for a question uses a loop then you will get 0 for that question.

You can use helper functions if you like, as long as you write them yourself and they don’t use loops. Don’t use code from the web or other people.

Do not use any global variables, static local variables, or other such tricks when implementing your functions. Just use functions, parameters, and return values in the style shown in the notes and in lectures.

Use exactly the function names and parameters given in a4.h. Don’t change them in any way.

Do not #include any files other than those that are already in a4.h.

Submitting Your Work

On Canvas, please submit just the filea4.cpp with your answers in it. Don’t submit anything else.

The marker will use the assignment makefile to compile your a4.cpp and link it with their own main() function. A copy of a4.h, cmpt_error.h, cmpt_trace.h, and cmpt_trace.cpp will be in the same folder as your program when it runs.

Basic Requirements

It must compile on Ubuntu Linux using the makefile in this assignment. Just type make:

“`bash $ make g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g -c -o a4.o a4.cpp g++ std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g -c -o a4_main.o a4_main.cpp g++ -std=c++17 Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g -c -o cmpt_trace.o cmpt_trace.cpp g++ -o a4_main_test a4.o a4_main.o cmpt_trace.o $ ./a4_main_test … “`

makefile is customized for this assignment: it’s not the usual course makefile. Notice also that the name of the executable it builds is a4_main_test. See the comments at the top of makefile for how to use it.

If your program fails to compile using this makefile, your mark for this assignment will be 0.

It must have no memory leaks or memory errors, according to valgrind, e.g.:

“` $ valgrind ./a4_main_test

// … lots of output … “`

A program is considered to have no memory error if:

In the LEAK SUMMARY, definitely lost, indirectly lost, and possibly lost must all be 0.

The ERROR SUMMARY reports 0 errors.

It is usually okay if still reachable reports a non- zero number of bytes.

You must include the large comment section with student info and the statement of originality. If your submitted file does not have this, then we will assume your work is not original and it will not be marked.

If your program meets all these basic requirements, then it will be graded using the marking scheme.

Marking Scheme

All code is sensibly and consistently indented, and all lines are 100 characters in length, or less.

Whitespace is used to group related pieces of a code to make it easier for humans to read. All whitespace has a purpose.

Variable and function names are self-descriptive.

Appropriate features of C++ are used, as discussed in class and in the notes. Note If you use a feature that we haven’t discussed in class, you must explain it in a comment, even if you think it’s obvious.

Comments are used when needed to explain chunks of code whose purpose is not obvious from the code itself. There should be no commented-out code from previous versions.

1 mark for correctly and efficiently implementing each solver function.

1 mark for thoroughly testing each requested recursive function with its own test function.

Deductions

a score of 0 if you don’t include the “statement of originality in the header of your file.
