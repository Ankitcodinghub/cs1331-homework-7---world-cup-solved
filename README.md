# cs1331-homework-7---world-cup-solved
**TO GET THIS SOLUTION VISIT:** [CS1331 Homework 7 – World Cup Solved](https://www.ankitcodinghub.com/product/cs1331-homework-7-world-cup-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109898&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1331 Homework 7 - World Cup Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Introduction

In this assignment, you’ll practice – implementing interfaces, – using generics, – and implementing a simple data structure.

Problem Description

Eventually you hope to develop your code into a complex betting system that’ll keep track of custom brackets, and help you escape the perils of academia.

Solution Description

The classes below have been provided for you. You are responsible for implementing most of TeamSet to help you keep track of all of the teams participating.

TeamSet.java

Implements the Set interface.

● Has the following instance variables:

❍ private T[] backingArray: the array in which all objects in this set are stored.

❍ private int size: represents the number of objects currently stored in this set. This variable must be updated when objects are added to or removed from this set.

● Has one no-args constructor that sets the backingArray to be of length 10.

In addition to the provided Javadocs, be sure to look at the API to see all of the details for each methods expected behavior, some methods are expected to throw exceptions under certain circumstances.

You must provide implementation for the following methods:

● public boolean add(E e)

● public boolean addAll(Collection&lt;? extends E&gt; c)

● public void clear()

● public boolean remove(Object o)

● public boolean contains(Object o)

● public boolean containsAll(Collection&lt;? extends E&gt; c)

● public boolean equals(Object o)

● public Iterator&lt;E&gt; iterator()

● public Object[] toArray()

● public int size()

● public boolean isEmpty()Notice that the Set interface has more methods, however you are not required to provide implementation for public &lt;T&gt; T[] toArray(T[] a), public boolean removeAll(Collection&lt;?&gt; c), public int hashCode(), and public boolean retainAll(Collection&lt;?&gt; c).

● You must complete any missing/incomplete Javadocs for this class.

Player.java

This file represents a player, which you will be using to fill your TeamSet.

WorldCup.java

This tester has been provided for you. Feel free to supplement it with additional checks.

● Running our tester does not guarantee you a 100. We encourage you to write your own test cases to fully test your homework files.

Javadocs

You will need to write Javadoc comments and watch for checkstyle errors with your submission.

● Every class should have a class level Javadoc that includes @author &lt;GT Username&gt; and @version

&lt;version number&gt;.

● Every public method should have a Javadoc explaining what the method does and includes any of the following tags if applicable:

❍ @param &lt;parameter name&gt; &lt;brief description of parameter&gt;

❍ @return &lt;brief description of what is returned&gt;

See the CS 1331 Style Guide on Canvas for details.

Checkstyle

For each of your homework assignments we will run checkstyle and deduct one point for every checkstyle error, with the points deducted being capped.

● You can run checkstyle on your code by using the jar file found on Canvas that includes xml configuration file specifying our checks. To check the style of your code run java -jar

checkstyle-6.2.2.jar *.java.

● To check your Javadocs run java -jar checkstyle-6.2.2.jar -j *.java.

● Note that the command for checking code and the command for checking Javadocs are different.

You will have to run both commands to fully test for style errors.

● Javadoc errors are the same as checkstyle errors, as in each one is worth a single point and they are counted towards the checkstyle cap.

● You will be responsible for running checkstyle on ALL of your code.

● Depending on your editor, you might be able to change some settings to make it easier to write style-compliant code. See the Customization Tips on Canvas for more information.

Collaboration

● What general strategies or algorithms you used to solve problems in the homework

● Parts of the homework specification you are unsure of and need more explanation

● Online resources that helped you find a solution

● Key course concepts and Java language features used in your solution

Examples of approved/disapproved collaboration:

OKAY: “Hey, I’m really confused on how we are supposed to implement this part of the homework. What strategies/resources did you use to solve it?”

Submission

● Submit your TeamSet.java file for this homework as an attachment to the Homework 7 assignment on Canvas. You can submit as many times as you want, so feel free to submit as you make substantial progress on the homework. We only grade your last submission, meaning we will ignore any previous submissions.

● If you submit multiple times Canvas will append a number to your zip file (TeamSet.java becomes TeamSet-1.java). Do not worry about this, we will fix the file name before compiling and running your code.

● Non-compiling code will be given a score of 0. For this reason, we recommend submitting early and then confirming that you submitted ALL of the necessary files by re-downloading your file(s) and compiling/running them.

● Files that contain inappropriate language and/or profanity will receive a 0.

Good Luck! (°□°)/
