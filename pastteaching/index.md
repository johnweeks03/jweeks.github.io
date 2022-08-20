<head> 
<!--#include virtual="/head.html"--> 
<style type="text/css"> 
.contactsearch { 
visibility:hidden; 
} 
</style> 
</head> 
 

<body> 
<!--#include virtual="/includes/1colUser.inc.html" --> 
 

<!-- ==================== BEGIN YOUR CONTENT HERE ==================== --> 
 

<h1 class="pageTitle">Past Teaching: MATH-142-504 - Spring 2020</h1> 
 

<h3>Important Links</h3> 
<ul style="margin-top: 2px"> 
<!-- 
  Link to your teaching pages. 
  Create new sub directories mathMMM_2014c and mathNNN_2014a 
  under your public_html directory for Fall and Spring, 2014, 
  respectively.  Create index.html files in each directory. 
  --> 
<li><a href="https://webassign.net/tamu/login.html">Webassign Access</a></li> 
<li><a href="https://mlc.tamu.edu/Help-Services/MLC-Help-Sessions#M142">Help Session Info (UPDATED)</a></li> 
<li><a href="https://mlc.tamu.edu/Help-Services/MLC-Week-in-Review">Week-in-Review Info (UPDATED)</a></li> 
<li><a href="https://www.desmos.com/calculator">Desmos Graphing Calculator</a></li> 
 

<p>This class runs on a mix of lecture and flipped-class teaching styles. You can find the videos giving 
the necessary examples this class will use below.</p> 
 

<p>For these videos, I recommend the following regimen: 
<ul style="margin-top: 2px"> 
<li>Pause the video and write down the problem before seeing any work.</li> 
<li>Work as much as the problem as you can (which may be none, but you won't know until you try!).</li> 
<li>Watch through the solution, taking notes as you need (they may be useful for in-class assignments).</li> 
<li>Go back to your work. What went right? What's missing? Make the changes you need to get to the right answer dependably.</li> 
</ul></p> 
 

<p>You are encouraged to take notes on this videos; from time to time you will be allowed to use them on assignments.</p> 
 

<!-- 
<h3>What's My Grade if I Take the Final?</h3> 
<form name="gradeForm1" oninput="grade.value=calcGradeReplaceFinal()"> 
<table> 
   <tbody><tr> 
      <td> Exam I: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_i" size="3" value="0">% 
      </td> 
 

<td> Exam II: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_ii" size="3" value="0">% 
      </td> 
 

</tr> 
   <tr> 
      <td> Exam III*: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_iii" size="3" value="0">% 
      </td> 
 

<td> Final exam*: </td> 
      <td> 
         <input type="text" maxlength="5" id="final_exam" size="3" value="0">% 
      </td> 
 

</tr> 
   <tr> 
      <td> Quizzes+: </td> 
      <td> 
         <input type="text" maxlength="5" id="quiz" size="3" value="0">% 
      </td> 
 

<td> Homework+: </td> 
      <td> 
         <input type="text" maxlength="5" id="hw" size="3" value="0">% 
      </td> 
   </tr> 
   <tr> 
      <td> Assignments+: </td> 
      <td> 
<input type="text" maxlength="5" id="assignment" size="3" value="0"> 
      </td> 
   </tr> 
</tbody></table> 
<output name="grade" for="exam_i exam_ii exam_iii final_exam quiz hw assignment">Your course grade is 0%.</output> 
 

<script type="text/javascript"> 
function calcGradeReplaceFinal() { 
   var exam_i = parseFloat(document.getElementById("exam_i").value,10) || 0; 
   var exam_ii = parseFloat(document.getElementById("exam_ii").value,10) || 0; 
   var exam_iii = parseFloat(document.getElementById("exam_iii").value,10) || 0; 
   var final_exam = parseFloat(document.getElementById("final_exam").value,10) 
      || 0; 
   var quiz = parseFloat(document.getElementById("quiz").value,10) || 0; 
   var hw = parseFloat(document.getElementById("hw").value, 10) || 0; 
   var assignment = parseFloat(document.getElementById("assignment").value,10) || 0; 
   submitOK = "true"; 
 

if (isNaN(exam_i)|| exam_i < 0 || exam_i > 110 
       || isNaN(exam_ii) || exam_ii < 0 || exam_ii > 105 
       || isNaN(exam_iii) || exam_iii < 0 || exam_iii > 105 
       || isNaN(final_exam) || final_exam < 0 || final_exam > 109 
       || isNaN(quiz) || quiz < 0 || quiz > 100 
       || isNaN(hw) || hw < 0 || hw > 100 
       || isNaN(assignment) || assignment < 0 || assignment > 100) { 
      return "Each entry must be a number in [0,100]. " 
         + "The midterm exams may have values up to 110."; 
   } 
 

// replace lowest midterm with final 
   var arg_min = 0; 
   var min = -1; 
   arg_min = 1; 
   min = exam_i; 
   if (exam_ii < exam_i) { 
      arg_min = 2; 
      min = exam_ii; 
   } 
   if (exam_iii < min) { 
      arg_min = 3; 
      min = exam_iii; 
   } 
   if (arg_min == 1 && exam_i < final_exam) { 
      exam_i = final_exam; 
   } else if (arg_min == 2 && exam_ii < final_exam) { 
      exam_ii = final_exam; 
   } else if (arg_min == 3 && exam_iii < final_exam) { 
      exam_iii = final_exam; 
   } 
 

var grade = .15*(exam_i + exam_ii + exam_iii + quiz) 
      +.12*(hw)+.10*(assignment); 
   grade = Math.round(grade * 100) / 100; 
   return "Your course grade is " + grade + "%."; 
} 
</script> 
 

<h3>What's My Grade if I Don't Take the Final?</h3> 
<form name="gradeForm2" oninput="grade.value=calcGrade()"> 
<table> 
   <tbody><tr> 
      <td> Exam I: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_i" size="3" value="0">% 
      </td> 
 

<td> Exam II: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_ii" size="3" value="0">% 
      </td> 
 

</tr> 
   <tr> 
      <td> Exam III*: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_iii" size="3" value="0">% 
      </td> 
 

<td> Quizzes+: </td> 
      <td> 
         <input type="text" maxlength="5" id="quiz" size="3" value="0">% 
      </td> 
   </tr> 
 

<tr> 
      <td> Homework+: </td> 
      <td> 
         <input type="text" maxlength="5" id="hw" size="3" value="0">% 
      </td> 
 

<td> Assignments+: </td> 
      <td> 
<input type="text" maxlength="5" id="assignment" size="3" value="0">% 
      </td> 
   </tr> 
</tbody></table> 
<output name="grade" for="exam_i exam_ii exam_iii quiz hw assignment">Your course grade is 0%.</output> 
 

<script type="text/javascript"> 
function calcGrade() { 
   var exam_i = parseFloat(document.getElementById("exam_i").value,10) || 0; 
   var exam_ii = parseFloat(document.getElementById("exam_ii").value,10) || 0; 
   var exam_iii = parseFloat(document.getElementById("exam_iii").value,10) || 0; 
   var quiz = parseFloat(document.getElementById("quiz").value,10) || 0; 
   var hw = parseFloat(document.getElementById("hw").value, 10) || 0; 
   var assignment = parseFloat(document.getElementById("assignment").value,10) || 0; 
   submitOK = "true"; 
 

if (isNaN(exam_i)|| exam_i < 0 || exam_i > 110 
       || isNaN(exam_ii) || exam_ii < 0 || exam_ii > 105 
       || isNaN(exam_iii) || exam_iii < 0 || exam_iii > 105 
       || isNaN(quiz) || quiz < 0 || quiz > 100 
       || isNaN(hw) || hw < 0 || hw > 100 
       || isNaN(assignment) || assignment < 0 || assignment > 100) { 
      return "Each entry must be a number in [0,100]. " 
         + "The midterm exams may have values up to 110."; 
   } 
 

var grade = .21*(exam_i + exam_ii + exam_iii) +.15*(quiz) 
      +.12*(hw)+.10*(assignment); 
   grade = Math.round(grade * 100) / 100; 
   return "Your course grade is " + grade + "%."; 
} 
</script> 
</form> 
--> 
<h3>What's My Grade If I Take The Final?</h3> 
<form name="gradeForm2" oninput="gradef.value=calcGradef()"> 
<table> 
   <tbody><tr> 
      <td> Exam I: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_if" size="3" value="0">% 
      </td> 
 

<td> Exam II: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_iif" size="3" value="0">% 
      </td> 
 

</tr> 
   <tr> 
      <td> Exam III*: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_iiif" size="3" value="0">% 
      </td> 
 

<td> Final exam*: </td> 
      <td> 
         <input type="text" maxlength="5" id="final_examf" size="3" value="0">% 
      </td> 
 

</tr> 
   <tr> 
      <td> Quizzes+: </td> 
      <td> 
         <input type="text" maxlength="5" id="quizf" size="3" value="0">% 
      </td> 
 

<td> Homework+: </td> 
      <td> 
         <input type="text" maxlength="5" id="hwf" size="3" value="0">% 
      </td> 
   </tr> 
   <tr> 
      <td> Assignments+: </td> 
      <td> 
         <input type="text" maxlength="5" id="assignmentf" size="3" value="0">% 
      </td> 
   </tr> 
</tbody></table> 
 

<output name="gradef" for="exam_if exam_iif exam_iiif final_examf quizf hwf">Your course grade is 0%.</output> 
 

<script type="text/javascript"> 
function calcGradef() { 
   var exam_if = parseFloat(document.getElementById("exam_if").value,10) || 0; 
   var exam_iif = parseFloat(document.getElementById("exam_iif").value,10) || 0; 
   var exam_iiif = parseFloat(document.getElementById("exam_iiif").value,10) || 0; 
   var final_examf = parseFloat(document.getElementById("final_examf").value,10) 
      || 0; 
   var quizf = parseFloat(document.getElementById("quizf").value,10) || 0; 
   var hwf = parseFloat(document.getElementById("hwf").value, 10) || 0; 
   var assignmentf = parseFloat(document.getElementById("assignmentf").value, 10) || 0; 
   submitOK = "true"; 
 

if (isNaN(exam_if)|| exam_if < 0 || exam_if > 110 
       || isNaN(exam_iif) || exam_iif < 0 || exam_iif > 110 
       || isNaN(exam_iiif) || exam_iiif < 0 || exam_iiif > 110 
       || isNaN(final_examf) || final_examf < 0 || final_examf > 100 
       || isNaN(quizf) || quizf < 0 || quizf > 100 
       || isNaN(hwf) || hwf < 0 || hwf > 100 
       || isNaN(assignmentf) || assignmentf < 0 || assignmentf > 100) { 
      return "Each entry must be a number in [0,100]. " 
         + "The midterm exams may have values up to 110."; 
   } 
   // replace lowest midterm with final 
   var arg_minf = 0; 
   var minf = -1; 
   arg_minf = 1; 
   minf = exam_if; 
   if (exam_iif < exam_if) { 
      arg_minf = 2; 
      minf = exam_iif; 
   } 
   if (exam_iiif < minf) { 
      arg_minf = 3; 
      minf = exam_iiif; 
   } 
   if (arg_minf == 1 && exam_if < final_examf) { 
      exam_if = final_examf; 
   } else if (arg_minf == 2 && exam_iif < final_examf) { 
      exam_iif = final_examf; 
   } else if (arg_minf == 3 && exam_iiif < final_examf) { 
      exam_iiif = final_examf; 
   } 
 

var gradef = .15*(exam_if + exam_iif + exam_iiif)+.18*(final_examf) 
      +.12*(hwf)+.10*(assignmentf)+.15*(quizf); 
   gradef = Math.round(gradef * 100) / 100; 
   return "Your course grade is " + gradef + "%."; 
} 
</script> 
 

<!-- ===================== END YOUR CONTENT HERE ===================== --> 
  </form> 
<h3>What's My Grade If I Don't Take The Final?</h3> 
<form name="gradeForm1" oninput="grade.value=calcGrade()"> 
<table> 
   <tbody><tr> 
      <td> Exam I: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_i" size="3" value="0">% 
      </td> 
 

<td> Exam II: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_ii" size="3" value="0">% 
      </td> 
 

</tr> 
   <tr> 
      <td> Exam III*: </td> 
      <td> 
         <input type="text" maxlength="5" id="exam_iii" size="3" value="0">% 
      </td> 
 

</tr> 
   <tr> 
      <td> Quizzes+: </td> 
      <td> 
         <input type="text" maxlength="5" id="quiz" size="3" value="0">% 
      </td> 
 

<td> Homework+: </td> 
      <td> 
         <input type="text" maxlength="5" id="hw" size="3" value="0">% 
      </td> 
   </tr> 
   <tr> 
      <td> Assignments+: </td> 
      <td> 
         <input type="text" maxlength="5" id="assignment" size="3" value="0">% 
      </td> 
   </tr> 
</tbody></table> 
<output name="grade" for="exam_i exam_ii exam_iii final_exam quiz hw">Your course grade is 0%.</output> 
 

<script type="text/javascript"> 
function calcGrade() { 
   var exam_i = parseFloat(document.getElementById("exam_i").value,10) || 0; 
   var exam_ii = parseFloat(document.getElementById("exam_ii").value,10) || 0; 
   var exam_iii = parseFloat(document.getElementById("exam_iii").value,10) || 0; 
   var quiz = parseFloat(document.getElementById("quiz").value,10) || 0; 
   var hw = parseFloat(document.getElementById("hw").value, 10) || 0; 
   var assignment = parseFloat(document.getElementById("assignment").value, 10) || 0; 
   submitOK = "true"; 
 

if (isNaN(exam_i)|| exam_i < 0 || exam_i > 110 
       || isNaN(exam_ii) || exam_ii < 0 || exam_ii > 110 
       || isNaN(exam_iii) || exam_iii < 0 || exam_iii > 110 
       || isNaN(quiz) || quiz < 0 || quiz > 100 
       || isNaN(hw) || hw < 0 || hw > 100 
       || isNaN(assignment) || assignment < 0 || assignment > 100) { 
      return "Each entry must be a number in [0,100]. " 
         + "The midterm exams may have values up to 105."; 
   } 
 

var grade = .21*(exam_i + exam_ii + exam_iii) 
      +.12*(hw)+.10*(assignment)+.15*(quiz); 
   grade = Math.round(grade * 100) / 100; 
   return "Your course grade is " + grade + "%."; 
} 
</script> 
 

</form> 
 

<h2> 
The videos can no longer be found at this link. Here is a sample video: 
<a href="https://youtu.be/AUHcxcDk188">Area and Definite Integrals</a> (2:07:12) Three problem sets. 
</h2> 
<!-- 
<p> The first two videos have low audio quality; transcriptions of these videos have been provided. The rest have closed captioning available. Please request permission before repurposing or redistributing any video below, either in part or in full.</p> 
 

<p><a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work by <a xmlns:cc="http://creativecommons.org/ns#" href="https://math.tamu.edu/~jweeks03/" property="cc:attributionName" rel="cc:attributionURL">John Weeks</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br /></p> 
 

<ul style="margin-top: 10px"> 
<li><a href="142videos.pdf">Video Questions</a>. Unit 2 begins on page 68; Unit 3 begins on page 114 (pages 123-130 belong to the optional video, and we will not cover pages 172-174).</li> 
</ul> 
 

<ul style="margin-top: 10px"> 
<li><a href="https://youtu.be/LDXOp_FsrSQ">Intro 1: Basic Arithmetic</a> (31:08) <a href="https://docs.google.com/document/d/1EXAr0gpfpE_z9kCb4Ma8rxE6z8nfuH9Cug5bArt4Wos/edit?usp=sharing">Transcription</a></li> 
<li><a href="https://youtu.be/ru5e3cLESMQ">Intro 2: Basic Functions</a> (37:26) <a href="https://drive.google.com/open?id=167MPGmjbxfQgxvtuGWGjA6dCgBq1_MpmJDYtqthNIQc">Transcription</a></li> 
</ul> 
 

--UNIT 1-- 
<ul style="margin-top: 10px"> 
<li><a href="https://youtu.be/CTZcvJO5LZ0">Basics</a> (1:57:43) Four problem sets.</li> 
</ul> 
 

<ul style="margin-top: 10px"> 
<li><a href="https://youtu.be/LsYgx4EsWsw">Limits</a> (1:13:32) Two problem sets.</li> 
</ul> 
 

<ul style="margin-top:10px"> 
 

<li><a href="https://youtu.be/90vARJTKO7I">Derivative Definition</a> (1:30:16) Three problem sets.</li> 
<li><a href="https://youtu.be/lFg-k6FLa1E">Derivative Definition II</a> (32:15) Extension of third problem set.</li> 
</ul> 
 

<ul> 
<li><a href="https://youtu.be/4M5mX2A-6zo">Derivative Rules I</a> (1:48:27) Three problem sets.</li> 
</ul> 
--UNIT 2-- 
<ul style="margin-top:10px"> 
<li><a href="https://youtu.be/4CGE9693fas">Derivative Rules II</a> (1:24:24) Two problem sets.</li> 
<li><a href="https://youtu.be/xATxz8hCcR8">Where do the derivative rules come from?</a> (1:55:18) Optional video.</li> 
</ul> 
 

<ul style="margin-top:10px"> 
<li><a href="https://youtu.be/iTsv1W79vc8">Curve Sketching I</a> (1:33:49) Two problem sets.</li> 
<li><a href="https://youtu.be/yce-c4R57J0">Curve Sketching II</a> (2:14:18) Three problem sets.</li> 
</ul> 
 

<ul style="margin-top:10px"> 
<li><a href="https://youtu.be/ChogObR1Ch8">Exam 2 Review</a> (1:19:19)</li> 
</ul> 
--UNIT 3-- 

<ul style="margin-top:10px"> 
<li><a href="https://youtu.be/IqF8U5dNwes">Implicit Differentiation and Related Rates</a> (1:08:53) Optional video.</li> 
</ul> 
 

<ul style="margin-top:10px"> 
<li><a href="https://youtu.be/2aKp6m7PsjQ">Optimization</a> (1:17:49) One problem set.</li> 
<li>Extra videos from the department: <a href="https://youtu.be/N5Hkyl-KtAs"> Optimization I.</a> <a href="https://youtu.be/cvMzlOP25h4"> Optimization II.</a></li> 
</ul> 
 

<ul style="margin-top:10px"> 
<li><a href="https://youtu.be/mHBQDWkqY54">Integrals and u-Substitution</a> (1:48:02) Two problem sets.</li> 
<li><a href="https://youtu.be/AUHcxcDk188">Area and Definite Integrals</a> (2:07:12) Three problem sets.</li> 
<li><a href="https://youtu.be/hpvVPcb4r7g">Area Between Curves</a> (50:35) One problem set.</li> 
</ul> 
--Lectures-- 
<ul style="margin-top:10px"> 
<li><a href="https://youtu.be/Vc7uWYuW1AU">3-23-20</a>.</li> 
<li><a href="https://youtu.be/fDCDKAzIJ7g">3-25-20</a>. <a href="142lecture32520.png">Notes</a>.</li> 
<li>EXAM 2 3-27-20.</li> 
<li><a href="https://youtu.be/Gq2h-bY9U1M">3-30-20</a>. <a href="142lecture33020.png">Notes</a>.</li> 
<li><a href="https://youtu.be/7CnRfe5KtVA">4-1-20</a>. <a href="142lecture4120.png">Notes</a>.</li> 
<li><a href="https://youtu.be/9DntroO69vM">4-3-20</a>. <a href="142lecture4320.png">Notes</a>.</li> 
<li><a href="https://youtu.be/yOvS_NQb_LM">4-6-20</a>. <a href="142lecture4620.png">Notes</a>.</li> 
<li><a href="https://youtu.be/t8q8OZq8r6U">4-8-20</a>. <a href="142lecture4820.png">Notes</a>.</li> 
<li>No class 4-10-20.</li> 
<li><a href="https://youtu.be/VlO1YtdN07E">4-13-20</a>. <a href="142lecture41320.png">Notes</a>.</li> 
<li><a href="https://youtu.be/Ow7eonCiaOQ">4-15-20</a>. <a href="142lecture41520.png">Notes</a>.</li> 
<li><a href="https://youtu.be/kASJ9c3QbOE">4-17-20</a>. <a href="142lecture41720.png">Notes</a>.</li> 
<li><a href="https://youtu.be/_qYxIZwp0a0">4-20-20</a>. <a href="142lecture42020.png">Notes</a>.</li> 
<li><a href="https://youtu.be/eh14IWzjnXs">4-22-20</a>. <a href="142lecture42220.png">Notes</a>.</li> 
<li>EXAM 3 4-24-20.</li> 
<li><a href="https://youtu.be/5MwetUdSLlA">4-27-20</a>.</li> 
<li><a href="https://youtu.be/cTHdkqj_jlY">4-28-20</a>. <a href="142lecture42820.png">Notes</a>.</li> 
<li><a href="https://youtu.be/mPVpa4ofRj4">5-4-20 (Review)</a>. <a href="142review5420.png">Notes</a>.</li> 
</ul> 
 

<li><a href="https://youtu.be/yjFGZQAi4Ts">Derivative 1: Webassign 3.2 (part 1) Derivative as Abstraction: Rates of Change</a> (33:57)</li> 
<li><a href="https://youtu.be/OqZLSWMSgGw">Derivative 2: Webassign 3.2 (part 2) Derivative as Function: Slopes of Tangent Lines</a> (27:02)</li> 
<li><a href="https://youtu.be/_33o4j21adI">Derivative 3: Webassign 3.3 Derivative as Algebraic Definition: Definition of the Derivative</a> (40:47)</li> 
<li><a href="https://youtu.be/7Sv0FzKVVzE">Derivative 4: Webassign 4.1 (part 1) Derivative Rules: Constant, Sum, Difference, Euler's Constant</a> (42:33)</li> 
<li><a href="https://youtu.be/7Mct6a7PMdQ">Derivative 5: Webassign 4.1 (part 2) Business Applications of the Derivative</a> (17:58)</li> 
<li><a href="https://youtu.be/7o3tK42WAvE">Derivative 6: Webassign 4.2 Derivative Rules: Product and Quotient</a> (22:22)</li> 
<li><a href="https://youtu.be/sWXB4g7ljKg">Derivative 7: Webassign 4.3 Derivative Rules: Chain</a> (46:14)</li> 
<li><a href="https://youtu.be/U7Pux0UhthM">Derivative 8: Webassign 4.4 Derivative Rules: Exponentials and Logarithms (30:47)</li> 
 

</ul> 
 

<ul style="margin-top: 2px"> 
<li><a href="https://youtu.be/I3wlhCfjzZ0">Applications 1: Webassign 5.1 (part 1) Finding Local Extrema and First Derivative Test</a> (38:08)</li> 
<li><a href="https://youtu.be/I4iSK-9oksI">Applications 2: Webassign 5.1 (part 2) and 5.2 The Second Derivative and Concavity</a> (46:14)</li> 
<li><a href="https://youtu.be/A3YT5xQHFfY">Applications 3: Webassign 5.3 Limits at Infinity</a> (45:35)</li> 
<li><a href="https://youtu.be/ljebEWt6xvM">Applications 4: Webassign 5.4 Curve Sketching</a> (34:51)</li> 
<li><a href="https://youtu.be/nMbnMPviAT8">Applications 5: Webassign 5.5 Finding Absolute Extrema</a> (47:06)</li> 
<li><a href="https://youtu.be/WbAytkOK4JM">Applications 6: Webassign 5.6 (part 1) Optimization 1</a> (47:06)</li> 
<li><a href="https://youtu.be/aM8m1tYHBkA">Applications 7: Webassign 5.6 (part 2) Optimization 2</a> (29:55)</li> 
<li><a href="https://youtu.be/_BvCf082Sdg">Applications 7b: Webassign 5.6 (part 3) Optimization 3</a> (11:48)</li> 
<li><a href="https://youtu.be/uyrBUcPJfvE">Applications 8: Webassign 5.8 (part 1) Implicit Differentiation</a> (34:31)</li> 
<li><a href="https://youtu.be/lShu2_cPF4Q">Applications 9: Webassign 5.8 (part 2) Related Rates</a> (23:59)</li> 
</ul> 
 

<ul style="margin-top: 2px"> 
<li><a href="https://youtu.be/-zrW6wO6tNY">Integral 1: Webassign 6.1 Antiderivatives</a> (47:37)</li> 
<li><a href="https://youtu.be/ozQwzUbw5Fk">Integral 2: Webassign 6.2 Indefinite Integrals </a> (41:19)</li> 
<li><a href="https://youtu.be/4bqjQfq5djk">Integral 3: Webassign 6.3 Estimating Distance Traveled </a> (36:37)</li> 
<li><a href="https://youtu.be/bOmzF4Mqhss">Integral 4: Webassign 6.4 The Definite Integral as Area</a> (32:56)</li> 
<li><a href="https://youtu.be/OCfnWnqXnZE">Integral 5: Webassign 6.5 (part 1) The Definite Integral as Antiderivative and the Fundamental Theorem of Calculus</a> (45:00)</li> 
<li><a href="https://youtu.be/N807EQDsYPw">Integral 6: Webassign 6.5 (part 2) and 6.6 Average Value and Area Between Two Curves</a> (48:09)</li> 
<li><a href="https://youtu.be/efHbpKjLq0M">Integral 7: Webassign 6.7 Producers' and Consumers' Surplus</a> (39:03)</li> 
</ul> 
 

<ul style="margin-top: 2px"> 
<li><a href="https://youtu.be/a9wInbxyChw">Optional 1: Using the Limit Definition to Prove Constant, Sum, Product, Quotient Rules</a> (25:17)</li> 
</ul> 
--> 
<!-- <h3>Research Interests</h3> 
<ul style="margin-top: 2px"> 
<li>Interest 1</li> 
<li>Interest 2</li> 
</ul> 
 

<h3>Publications</h3> 
<ul style="margin-top: 2px"> 
<li>Publication 1</li> 
<li>Publication 2</li> 
</ul> 
 

<h3>Pre-prints</h3> 
<ul style="margin-top: 2px"> 
<li>Pre-print 1</li> 
<li>Pre-print 2</li> 
</ul> --> 
 

<!-- ==================== External Personal Pages ====================  --> 
<!-- == It's your call on how much personal information to put here == --> 
<!-- <h3>Personal</h3> 
<ul style="margin-top: 2px"> 
<li><a href="http://www.facebook.com/YOUR_FB_PAGE">My Facebook Page</a></li> 
<li><a href="http://www.twitter.com/YOUR_TW_PAGE">My Twitter Page</a></li> 
</ul> --> 
 

<!-- ======= Remove next line when you've customized your page. ====== --> 
<!-- <p><i>This is a template web page for the user.</i></p> --> 
 

<!-- ========== HTML Validator - You may remove this section ========= --> 
<!-- 
<p style="text-align:center"> 
<a href="http://validator.w3.org/check?uri=referer"><img 
   src="http://www.w3.org/Icons/valid-xhtml11" 
   alt="Valid XHTML 1.1" height="31" width="88" /></a> 
<a href="http://jigsaw.w3.org/css-validator/check/referer"><img 
   style="border:0;width:88px;height:31px" 
   src="http://jigsaw.w3.org/css-validator/images/vcss-blue" 
   alt="Valid CSS!"/></a> 
</p> 
 

--> 
<!-- ===================== END YOUR CONTENT HERE ===================== --> 
<!--#include virtual="/includes/footerSubpage.inc.html"--> 
