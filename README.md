# 148024-applications-programming-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [148024 Applications Programming Assignment 2   Solved](https://www.ankitcodinghub.com/product/148024-applications-programming-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;59905&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;148024 Applications Programming Assignment 2&nbsp; &nbsp;Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>Specification</h1>
After a successful trial run of the Assignment 1 timetable system, UTS has decided it would like you to build a graphical user interface for the application using JavaFX.

&nbsp;

<h1>Functionality</h1>
When the application is launched, the “University” window appears which shows a list of students, or the placeholder “No students” if there are no students (as is the case initially):

&nbsp;

&nbsp;

&nbsp;

Clicking “Add Student” brings up the “Add Student” window with a data entry form:

&nbsp;

&nbsp;

&nbsp;

Clicking “Cancel” closes the window without adding a new student. The “Add” button is disabled while the student number is blank, or the student name is blank, or an attendance mode has not been chosen. Clicking “Add” will result in the error “Student already exists” if a student with the given number already exists in the university.

&nbsp;

Otherwise, clicking “Add” will add a new student to the university using the data entered, and the “Add Student” window is closed. The “University” window instantly displays the new student in the list:

&nbsp;

The “Remove Student” and “Login” buttons are enabled only when a student has been selected in the list.

&nbsp;

Clicking “Remove Student” will remove the student from the university and withdraw the student from all activities in which that student is enrolled. The user interface is immediately updated to reflect this change.

&nbsp;

Selecting a student and clicking “Login” will open the “Student” window:

&nbsp;

&nbsp;

&nbsp;

The student’s name, number, attendance and scholarship is shown at the top. The attendance is shown as either “Full Time” or “Part Time”. The scholarship is shown as either “Yes” or “No”. The “My Activities” table displays all the activities that the student is currently enrolled into, or the placeholder “Not enrolled in any activities” if the student is not enrolled in any activities.

&nbsp;

To enrol into an activity, the user first chooses a subject from the ComboBox. After selecting a subject, the table below the ComboBox presents a list of activities in that subject:

&nbsp;

&nbsp;

&nbsp;

The user may then select an activity from that table and click “Enrol”. The “Enrol” button is enabled only when an activity has been selected and there is an available seat in that activity and the student isn’t already enrolled in that activity. Clicking the “Enrol” button results in the student being enrolled into that activity, and being withdrawn from any activity in that subject with the same group as the new activity being enrolled into. The user interface is immediately updated to reflect the new system state. In particular, the “Enrolled” column for the selected activity increases by 1, and the activity appears in the “My Activities” table. If the student was first withdrawn from another activity, the “Enrolled” column for that activity decreases by 1. Buttons should also be appropriately enabled or disabled based on the current state (see above for the when to disable the

“Enrol” button and below for when to disable the “Withdraw” button).

&nbsp;

To withdraw from an activity, the user selects an activity from the “My Activities” table and clicks “Withdraw”. The “Withdraw” button is enabled only when an activity has been selected from the “My Activities” table. Upon clicking “Withdraw”, the user interface is immediately updated to reflect the new system state.

&nbsp;

Clicking “Logout” closes the “Student” window.

&nbsp;

<h1>Layout</h1>
Every window is divided vertically into 3 overall parts: a header section, a content section, and a footer section.

&nbsp;

<ul>
<li>The “University” window shows:
<ul>
<li>A header containing the UTS logo (downloadable from <a href="http://www.uts.edu.au/sites/default/files/logo_2.png">http://www.uts.edu.au/sites/default/files/logo_2.png</a> ) and the heading text “Timetable System”.</li>
</ul>
</li>
</ul>
○ A content section containing a ListView with a preferred width of 300 pixels and a preferred height of 200 pixels. The ListView is centred horizontally within the content section.

○ A footer containing 3 buttons centred horizontally.

<ul>
<li>The “Add Student” window shows:
<ul>
<li>A header containing the heading text “Add new student”.</li>
</ul>
</li>
</ul>
○ A content section containing a form laid out in a GridPane. The grid has 5 rows containing 4 Labels, 2 TextFields, 2 RadioButtons, 1 CheckBox and a Text to display the error message. The error message spans 2 columns and is centred horizontally.

○ A footer containing 2 buttons centred horizontally.

<ul>
<li>The “Student” window shows:
<ul>
<li>A header containing the heading text “Logged in as &lt;student name&gt;” at the top left, and a GridPane at the top right. The GridPane contains 3 Labels in the left column and 3 Texts in the right column.</li>
</ul>
</li>
</ul>
○ A content section containing two subsections:

■ The first section begins with the heading text “My Activities” aligned to the left, and a button aligned to the right. Below both is a TableView.

■ The second section begins with the heading text “Enrol into subject” followed by a ComboBox, both aligned to the left, and a button aligned to the right. Below these is a TableView. ○ A footer containing a button centred horizontally.

&nbsp;

<h1>Style</h1>
The following CSS colours are used:.

<ul>
<li>#0099cc is used as the background colour of the header sections and the buttons. ● #00749b is used as the background colour of the content sections.</li>
<li>#252b2b is used as the background colour of the footer sections.</li>
<li>#333333 is used as the colour of labels.</li>
<li>#ffffff is used as the colour of heading text and button text. ● FIREBRICK is used as the colour of error messages.</li>
<li>#00bfff is used as the background colour of a button during the hover state.</li>
</ul>
The following fonts are used:

<ul>
<li>Heading text is Arial with font size 32px.</li>
<li>Labels use font size 12px.</li>
<li>Label text, Button text and error text is bold. ● Default fonts are used elsewhere.</li>
</ul>
Spacing and padding is also important. While exact measurements are not given in this specification, your application should include spacing and padding roughly equivalent to the screenshots above.

<h1>Code</h1>
Your solution must satisfy the following code requirements:

<ul>
<li>Your solution must follow an MVC architecture.</li>
<li>Your package structure should place the models in a package named “model”, the views in a package named “view” and the controllers in a package named “controller”.</li>
<li>The models must notify the views of changes by correctly applying the JavaFX property patterns and observable lists. Any model data that can change must be observable. Any model data that never changes does not need to be observable.</li>
<li>The attendance mode must be stored in the student’s attendance String property. The value “ft” should be stored to represent Full Time, and the value “pt” should be stored to represent Part Time.</li>
<li>Each view must be defined in FXML.</li>
<li>The “Student already exists” error message must be implemented as an exception. The model should throw an exception, and the controller must catch the exception and show the error message on the view.</li>
</ul>
<h1>Skeleton Code</h1>
Download the skeleton code for Assignment 2 from the Assignment 2 assessment page on PLATE ( https://plate.it.uts.edu.au/ ). Your solution must be based on this skeleton code.

&nbsp;

Included in the skeleton code is a text file called progress.txt which must be filled in by you as you progress through the assignment (see “PLATE marking” and “Submission and Return” below).

&nbsp;

<h1>Expected Workload</h1>
The time to do the assignment to a distinction level (i.e. a mark between 75% to 84%) has been estimated at 15 hours for a student of average ability who has completed all the tutorial and lab exercises.

&nbsp;

<h1>Online Support</h1>
The Assignment 2 discussion board has been set up in ED so that students can ask questions, and other students can reply. The course coordinator will post a reply only if the student response was wrong, or in the case of correcting a mistake in the assignment specification.

<strong>You must not post or share Java code to the discussion board.</strong> The board is there to help you, not to provide the solution. <strong>Posting your code is academic misconduct and will reported</strong>. Each time this rule is violated, the code will be removed and replaced with a comment of the form: “Strike 1: Posting code”. After 3 strikes, the discussion board will be deleted because it did not work.

&nbsp;

FAQs (Frequently Asked Questions) and their answers will be posted in the platform. If you have a question, check the FAQ first; it may already be answered there. You should read the FAQ at least once before you hand in your solution, but to be safe check it every couple of days. Anything posted on the FAQ is considered to be part of the assignment specification. The FAQ will be frozen (no new entries) two days before the due date; no questions will be answered after it is frozen.

&nbsp;

If anything about the specification is unclear or inconsistent, contact the subject coordinator who will try to make it clearer by replying to you directly and posting the common questions and answers to the FAQ. This is similar to working on the job, where you ask your client if you are unsure what has to be done, but then you write all the code to do the task. Email <u>huan.huo@uts.edu.au </u>to ask for any clarifications or corrections to the assignment.

&nbsp;

<h1>Submission to PLATE</h1>
<u>READ THIS ENTIRE SECTION CAREFULLY</u>

PLATE cannot test the behaviour and appearance of a graphical user interface on its own. Instead, Assignment 2 is marked by a combination of PLATE, student peer marking (including peer marking others and marked by others within due time), and the subject coordinator.

Included in the skeleton code is a file called progress.txt which you must fill out as you progress through the assignment 2. A sample of the beginning of this file is shown below:

<h2>Launch the application</h2>
[?] The UTS Logo is shown

[?] The “Timetable System” heading is shown

[?] “No students” is shown in the empty list

[?] “Add Student” appears and is enabled

[?] “Remove Student” appears and is disabled

[?] “Login” appears and is disabled

[?] The layout arranges the header, content and footer sections vertically

[?] All colours and fonts are correct

[?] The spacing and padding look like the screenshots

<h2>Click “Add Student”</h2>
[?] The “Add Student” window is shown

[?] The “Add new student” heading is shown

[?] The student number label and text field are shown

[?] The student name label and text field are shown

[?] The attendance label, “Full Time” radio button and “Part Time” radio button are shown

[?] The scholarship label and checkbox are shown

[?] The “Cancel” button is shown and enabled

[?] The “Add” button is shown and disabled

[?] The layout arranges the header, content and footer sections vertically

[?] The form is laid out in a GridPane

[?] All colours and fonts are correct including the error message

[?] The error message is included in the GridPane, centred horizontally spanning 2 columns [?] The spacing and padding look like the screenshots

<h2>Click “Cancel”</h2>
[?] The “Add Student” window is closed

&nbsp;

This file tells you how to test the functionality of your application. Here is how it works:

<ul>
<li>Each line without a [?] is an action you need to perform on your application.</li>
<li>Each line with a [?] is verification point that you must check. You must replace the [?] by either a [y] (for yes) or a [n] (for no) to record whether or not your application behaves correctly in that respect.</li>
</ul>
&nbsp;

For example, you should first launch the application, and then you should then check that the UTS Logo is shown, the “Timetable System” heading is shown, and so on. If your application does not display the logo, but does display the heading “Timetable System”, then you should fill in that part of the progress.txt file as follows:

&nbsp;

<h2>Launch the application</h2>
[n] The UTS Logo is shown

[y] The “Timetable System” heading is shown

&nbsp;

If a verification point lists multiple things to check, they must all be true for you to give a [y] answer. For example:

[?] “Add Student” appears and is enabled

&nbsp;

This verification point can only be answered [y] if BOTH the “Add Student” button appears AND it is enabled. Before your final submission, you should recheck every answer you gave, to ensure that your answers are accurate.

&nbsp;

There are 85 verification points like this to fill in. Each [y] answer contributes a potential 1 mark to your total, which makes up a maximum of 85 marks out of 100. The mark reported by PLATE when you submit is the&nbsp; provisional mark for peer review, not the final mark.

&nbsp;

You are required to submit your project (including the updated progress.txt file) to PLATE regularly. Serious penalties apply if you do not submit your progress in small increments (See “Penalty” below).

&nbsp;

If you are not sure how to implement a certain feature, in many cases it is possible to skip that feature and come back to it later if it is nonessential to testing the following features.

&nbsp;

For example, style and layout can be refined after you get the application working. Correct enabling and disabling of buttons can be addressed later. Radio buttons and checkboxes can be done later. In such cases where it is possible to continue testing your app after skipping a particular verification point, you are permitted to just enter [n] for that verification point and continue on with the next one.

However, you must perform all actions mentioned in progress.txt in sequence before attempting to check any particular verification point. For example, you cannot just “Launch the application” and then skip to the last verification point shown above and answer [y] that the “Add Student” window is closed. In order to be eligible to answer [y] for that verification point, you must have first also performed the action to open the

“Add Student” window, and then also performed the action to click the “Cancel” button. Only then, if the “Add Student” window is closed, are you eligible to answer [y] that this window was closed.

<h2>Penalty for lack of progress evidence</h2>
You must submit your progress to PLATE in increments of no larger than 25 marks. The penalty for making a submission to PLATE that is N marks higher than your previous best mark, where N &gt; 25 is N marks. Here is an example:

&nbsp;

Submission #1: 5 marks (OK. This is 5 marks higher than the previous best of 0)

Submission #2: 18 marks (OK. This is 13 higher than the previous best of 5)

Submission #3: 15 marks (OK)

Submission #4: 42 marks (“Just” OK. This is 24 higher than the previous best of 18) Submission #5: 85 marks ( Penalty of 43 . This jump is 43 marks higher than 42)

To avoid a penalty, submit your progress in smaller increments. That is, you should not introduce more than 25 new [y] answers in your progress.txt file in a single submission.

<h1>Marking</h1>
Your solution is to be submitted to PLATE at <a href="https://plate.it.uts.edu.au/">https://plate.it.uts.edu.au/</a> under Applications Programming / Assessments / Assignment 2. Your assignment should be submitted as a JAR file that includes:

<ul>
<li>All Java source files required to compile your assignment.</li>
<li>All FXML, CSS and image files required to run your assignment.</li>
<li>The progress.txt file at the top level of your project directory structure.</li>
</ul>
A provisional mark of up to 85 marks is generated immediately from your progress.txt file each time you submit to PLATE.

In your scheduled week 12 lab class, you will be assigned two other students to peer mark based on your reference mark, and two other students will be assigned to peer mark you. The purpose of this peer marking is to mark the functionality of your application which cannot be tested by PLATE. Your marks for functionality will be based on these peer marks after they are moderated by the subject coordinator. Aside from marks for the functionality, the subject coordinator will also mark your code to ensure that all code requirements have been met. If the code requirements have not been met (for example, the observer pattern not used, marks will be deducted for those components). Your final mark will be a combination of marks for functionality and marks for code (See “Marking scheme”). Note that you can only be marked for features that can be demonstrated to work.

There is no scheduled late submission period. An extension of up to one day may be given by the subject coordinator before the due date; you have to supply documentary evidence of your claim. An extension CANNOT be given after the due date. You may also apply for special consideration for reasons including unexpected health, family or work problems. More information about how to apply for special consideration can be found at <a href="http://www.sau.uts.edu.au/assessment/consideration.html">http://www.sau.uts.edu.au/assessment/consideration.html</a> .

Your presence is required at this class. Any student who is not present without being granted prior permission may have up to 50% of their marks for this assignment deducted.

Marking the code and analyzing spoofing, cheating and plagiarism is done in the two weeks following the due date. If you are suspected of Academic Misconduct, I will forward your case to the Misconduct Committee and will notify you by email. Your mark will be finalized within 2 weeks of the due date.

<h1>Marking Scheme</h1>
The marks for the assignment are divided into the following functionality components (detailed description is available in PLATE):

&nbsp;

<table width="378">
<tbody>
<tr>
<td width="189">&nbsp;<strong>Task</strong></td>
<td width="189">&nbsp;<strong>Mark </strong><strong>&nbsp;</strong></td>
</tr>
<tr>
<td width="189">Show main window on launch</td>
<td width="189">6%</td>
</tr>
<tr>
<td width="189">Add a student</td>
<td width="189">19%</td>
</tr>
<tr>
<td width="189">Login</td>
<td width="189">16%</td>
</tr>
<tr>
<td width="189">Enrol</td>
<td width="189">21%</td>
</tr>
<tr>
<td width="189">Withdraw</td>
<td width="189">4%</td>
</tr>
<tr>
<td width="189">Remove a student</td>
<td width="189">5%</td>
</tr>
<tr>
<td width="189">Layout</td>
<td width="189">7%</td>
</tr>
<tr>
<td width="189">Style</td>
<td width="189">7%</td>
</tr>
<tr>
<td width="189">MVC architecture and FXML</td>
<td width="189">5%</td>
</tr>
<tr>
<td width="189">Correct package structure</td>
<td width="189">1%</td>
</tr>
<tr>
<td width="189">JavaFX observable properties and lists</td>
<td width="189">4%</td>
</tr>
<tr>
<td width="189">Attendance mode stored as ft/pt</td>
<td width="189">2%</td>
</tr>
<tr>
<td width="189">Correct use of exceptions</td>
<td width="189">3%</td>
</tr>
</tbody>
</table>
This adds to a mark out of 100 and makes up 30% of your final assessment mark.

&nbsp;
