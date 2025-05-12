# cs3-homework-6-red-black-trees-solved
**TO GET THIS SOLUTION VISIT:** [CS3 Homework 6-Red Black Trees Solved](https://www.ankitcodinghub.com/product/cs3-homework-6-red-black-trees-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91008&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3 Homework 6-Red Black Trees Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Assignment 6

For the final assignment in CS3 you will implement a red black tree. This is a big under-taking. The red black tree is like, a really really big and really complicated thing. Like a nuclear submarine, or another big thing. But, it’s something that you are able to do and then, after you’re done, you’ll feel like “wow!” “I did that!” You’ll try to tell other people in your life, but they maybe won’t be able to appreciate the gravity of the situation. You’ll say, “I implemented a fully functional red black tree with perfect memory management!” and they might say, “what the hell is a red black tree?” Or, “who are you?”

For the first part of the assignment you will need to implement most of the red black tree functions, but they comprise only about 1⁄2 of the total work to be done. Remove() is the most complex function to implement and you will not do that in part 1. Here is a list of what you should implement.

<ul>
<li>A regular constructor</li>
<li>A copy constructor (maybe do this last)</li>
<li>An Insert() function that takes an integer and returns void</li>
<li>A Contains() function that takes an integer and returns a boolean (true if the integer is
somewhere in the tree)
</li>
<li>GetMin() which returns the minimum item in the tree (just the integer value)</li>
<li>GetMax() which returns the maximum item in the tree (just the integer value)</li>
<li>Size() which returns the size of the tree (the number of nodes).
There are three public ToString() variants. For each of these public methods there is a respective private ToString(root)method. You need to put these in the public section and implement the private versions.

• string ToInfixString() const {return ToInfixString(root);};

• string ToPrefixString() const { return ToPrefixString(root);};

• string ToPostfixString() const { return ToPostfixString(root);};

In the private section you should also have two instance variables

• unsigned long long int numItems; • RBTNode *root;
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Video Lecture 6 Part 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
After following these instructions up until this point you probably have a fairly complete header file. However, a lot of the design details in this assignment are left up to you. You can add arbitrary things to your header file and make design choices as you see fit. But, please don’t modify any of the things I’ve specified here. Also, your code will need to pass the tests provided. These tests are minimal and, as always, you should add your own!

The Next Steps

<ol>
<li>Create the header file and Makefile as described above.</li>
<li>Write the RBTNode struct</li>
<li>Create the RedBlackTree.cpp file and write the constructor.</li>
<li>In your cpp file write the ToInfixString() method.</li>
<li>Comment out all the tests in the test file except for the first one:
<pre>     TestSimpleConstructor()
</pre>
</li>
<li>Comment out the necessary things in the header file.</li>
<li>Compile and run the program and pass the first test.</li>
<li>Consider running the program with valgrind to guarantee no memory issues (leaks, invalid
reads/writes, etc.) so far.
</li>
</ol>
There is a lot more to do now. Insert() is complicated! Plan the work out however you want.

You’re done when your program passes all of the provided tests. Again, consider other tests to add. I will grade with many more tests than I provided to you! The rest of this document is a reference of details, edge-cases, and interesting tid-bits that you may or may not find useful. Please consider checking the reference section below if you get stuck / confused. Don’t forget to include a Makefile in your submission!

Recommendations for what to do when you’re stuck, tired, frustrated, confused, etc.:

<ul>
<li>Slam your firsts on the table and yell “ugggh!!? What the f*ck!!!”</li>
<li>Try it again without changing anything and hope that it works for no reason.</li>
<li>Try valgrind on it. I recommend compiling with -g and -Wall flags and then running
valgrind with the –-leak-check=full flag.
</li>
<li>Consider life as a “normal” person that doesn’t know anything about red black trees and is
happy about it.
</li>
<li>Take a walk.</li>
<li>Draw pictures on a piece of paper to diagram what is happening vs what should be happening.</li>
<li>Eat a snack.</li>
<li>Do something mundane and physical, but easy (washing the dishes, do the laundry, etc).</li>
<li>Put in a million print statements to have the program explain what the heck it is doing.</li>
<li>Use gdb on it (again, compile with -g)</li>
<li>Try the simulator: https://www.cs.usfca.edu/~galles/visualization/RedBlack.html</li>
<li>Complain quietly to yourself or loudly to others about the situation.</li>
<li>Consider the long term gains of spending time and effort improving your computer science and
programming skills. Knowledge is compounding. What you are learning about now may seem

pedantic or pointless, but it is not.
</li>
<li>Consult the reference documentation on the final page.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Video Lecture 6 Part 1

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Reference

colors

<ul>
<li>You should represent the colors with integers.</li>
<li>You should use #define COLOR_RED 0 directives at the top of the header file. The
decision about what number corresponds to what color is arbitrary and up to you.
</li>
<li>COLOR_DOUBLE_BLACK will be used in the remove algorithm(s) only.</li>
<li>You will never see anything that actually appears red or black. The colors are only represented as integers.
testing and errors
</li>
</ul>
<ul>
<li>A useful resource is this red black tree simulator: https://www.cs.usfca.edu/~galles/visualization/RedBlack.html

Note that it may sometimes animate / visualize a different process than what we are used to. But, in general the final state of the tree after any operation (insert, remove) is correct. Your program should match the final output, but not necessarily the process to get there.</li>
<li>Pro-tip: write a unit test for every method you write.</li>
<li>Tests may be done for private methods. In RedBlackTree.cpp make a public method
called PrivateTests() which implements a bunch of tests of your various private methods. In RedBlackTreeTests.cpp add a test that calls PrivateTests()
</li>
<li>Public methods should throw exceptions on invalid input (e.g., inserting a duplicate item). Private methods do not need to throw exceptions or do much of any error checking. Private methods are private, so it is safe to assume that all odd / erroneous conditions are handled internally and fully at the public level. It is generally safe to assume that private methods are not passed invalid inputs since you’re the one calling them!</li>
<li>Another pro-tip: the ToString() methods are recursive.</li>
<li>Tricky stuff: If you have a red black tree and you randomly do a RotateLeft() on it at some random point (for example when testing RotateLeft()) you will likely have violated the properties of the red black tree and other operations may not work correctly anymore on that same tree.</li>
<li>Pro-tip: Aim for 100% test coverage. That is, write enough tests so that every line of code in your RedBlackTree.cpp file is executed by your tests at least once.</li>
<li>Many questions about how to implement the methods, or exactly what they should return can be answered by checking the provided minimal tests.
memory stuff
</li>
</ul>
<ul>
<li>nullptr is the best way to implement pointers that point to “nothing”</li>
<li>If you try to do -&gt; on an variable that contains nullptr (nothing) it will cause a segmentation fault without any more information. Many places you should use code such as

if(x != nullptr) { x-&gt;blah } to avoid the issue.</li>
<li>Use valgrind to get a line number / more information when you get a segmentation fault. Don’t forget to include -g in your compile line!</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Video Lecture 6 Part 1

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ul>
<li>Keeping empty “null” nodes in the red black tree is useful for leaves that are yet to be filled. An empty / null / leaf node is considered black.</li>
<li>When you first create the tree and it has no nodes at all, root should be equal to nullptr.</li>
<li>Keep in mind memory allocations. If you have a “new” you will need a corresponding “delete” at some point in the program. Many memory issues will be fully addressed in the next part of this assignment.</li>
<li>Memory issues include leaks as well as invalid reads/writes. If you read or write data that has already been deleted the program may run correctly / as intended or it may crash. The behavior is undefined. You should use valgrind to check:

valgrind –leak-check=full ./rbt-tests

Submission: Your program will be submitted using canvas and git + github.

1) You should create a private github.com repository (repo) with your code in it. You may need to create a github user account and a github repository. To achieve this. The name you choose for the repo and your username are arbitrary but I suggest “HW6” as the repo name.

2) Your repository on github.com should be private and you should add my account as a collaborator by going to “settings” → “manage access” → “invite collaborator” and entering my username: fmresearchnovak

3) On canvas you should upload a link to this github repository

<pre>https://github.com/fmresearchnovak/HW6.git
</pre>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea"></div>
</div>
