# CAS CS 630 - Graduate Algorithms - Fall 2026

---
## Course Staff

<table class="staff-table">
    <tr>
        <td class="role">Instructors</td>
        <td>
            <a href="https://cs-people.bu.edu/edori/">Prof. Dora Erdös</a><br>
            <a href="https://cs-people.bu.edu/januario/">Prof. Tiago Januario</a>
        </td>
    </tr>
    <tr>
        <td class="role">Teaching Fellow</td>
        <td>
            <a href="https://pjalalifr.github.io">Pooria Jalali</a><br>
        </td>
    </tr>
    <tr>
        <td class="role">Grader</td>
        <td>
            <a href="https://www.linkedin.com/in/jerinjoseph121/">Jerin Joseph</a><br>
        </td>
    </tr>
</table>
---

## Communication and Office hours

<div style="display: flex;">
  <div style="flex: 1; padding-right: 10px;">
  <ul>
      <li><a href="https://piazza.com/" target="_blank">Piazza</a> is the <strong>primary platform</strong> for all online discussions, questions, and answers.
      <li><b>Use Piazza for all course communication</b>. Use private Piazza posts for personal matters. Email should be reserved for situations where Piazza is unavailable or inappropriate.</li>        
      </li>
      <li>Your <strong>suggestions</strong> for improving the course are always encouraged and appreciated.</li>
    </ul>
  </div>
  <div style="flex: 1; padding-left: 10px;">
<img src="email.gif" style="width:95%;">
  </div>
</div>

*   Check our [Google Calendar](https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=America%2FNew_York&showPrint=0&mode=WEEK&src=Y180MTRmM2U0Y2JiODU3N2UxYjM0NmZmMDY4YzBkNzY5MTZiOWYxZWE0ZDZkZDIzNmZiYTU3MTk2MjI5MTRjY2M4QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%233f51b5) for our Office hours.

<center>
<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=America%2FNew_York&showPrint=0&mode=WEEK&src=Y180MTRmM2U0Y2JiODU3N2UxYjM0NmZmMDY4YzBkNzY5MTZiOWYxZWE0ZDZkZDIzNmZiYTU3MTk2MjI5MTRjY2M4QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%233f51b5" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>
</center>

---
## Course description

This course examines advanced algorithmic topics and methods for CS graduate students, including   NP-hard problems, approximation techniques, probabilistic algorithms, and algorithms for very large data sets.

The course builds on undergraduate algorithms, including algorithm design, correctness proofs, and running-time analysis.

**Intended audience**: MS and advanced BA students. PhD students should take CS530 instead.

---
## Prerequisites

Students should have completed an algorithms course at the level of **CS330: Introduction to Analysis of Algorithms**.

Expected background includes:

* Proof techniques, e.g. direct proof, proof by contradiction, induction
* Asymptotic analysis of running time, i.e. big-Oh
* Algorithm design paradigms, such as greedy, divide and conquer, dynamic programming, and graph algorithms
* Data structures, e.g. lists, queues, heaps, hash tables, trees, graph adjacency lists
  
If you are unsure whether you have the required background, contact the instructor.

---
## Course platforms

* **Piazza**: Used for announcements, Q&A, discussion, lecture notes, general information, additional materials, and logistics.
    * [https://piazza.com/bu/fall2026/cs630](https://piazza.com/bu/fall2026/cs630)
* **Gradescope**: Used for worksheet submission, quiz/exam grading, and regrade requests.
    * [[https://www.gradescope.com/courses/1377497](https://www.gradescope.com/courses/1377497)]
    * Entry Code: K8YW73
* **Anki**: Used for studying flashcards with short definitions. You can download a free app at the following link.
    * [https://apps.ankiweb.net](https://apps.ankiweb.net)

The course Anki deck will be posted on Piazza and updated throughout the semester. Quiz questions may draw from posted flashcards.

---

## Textbooks and Resources

There is no single required textbook. Readings will be posted on Piazza or the course website before lectures. Students are encouraged to consult additional public resources. The readings are useful, but they are not a substitute for attending lecture and lab.

Recommended references:

* <span id="KT">KT -</span> [Algorithm Design, by Kleinberg and Tardos](https://www.pearson.com/en-us/subject-catalog/p/algorithm-design/P200000003259/9780137546350?srsltid=AfmBOoohtVV4wxqb0YsNmueTOh672kvs4WnW5B5KNwscHMxVxYfMiqyW)
* <span id="CLRS">CLRS -</span> [Introduction to Algorithms, by Cormen, Leiserson, Rivest, and Stein](https://mitpress.mit.edu/9780262046305/introduction-to-algorithms/)
* <span id="DPV">DPV -</span> [Algorithms, by Dasgupta, Papadimitriou, Vazirani](https://cseweb.ucsd.edu/~dasgupta/book/index.html)
*  <span id="V">V -</span> [Approximation Algorithms, by V. Vazirani](https://link.springer.com/book/10.1007/978-3-662-04565-7)
* <span id="WS">WS -</span> [The Design of Approximation Algorithms, by Williamson and Shmoys](https://www.designofapproxalgs.com)
* [Randomized Algorithms, by Rajeev Motwani and Prabhakar Raghavan](https://www.cambridge.org/core/books/randomized-algorithms/6A3E5CD760B0DDBA3794A100EE2843E8)
* [A First Course in Randomized Algorithms, by Nick Harvey](https://www.cs.ubc.ca/~nickhar/Book1.pdf)

For prerequisite review:

* [Algorithms Illuminated, by Tim Roughgarden](https://www.algorithmsilluminated.org) (the 4th part of the book also contains
material on NP)
* [Algorithms, by Jeff Erickson](https://jeffe.cs.illinois.edu/teaching/algorithms/book/Algorithms-JeffE.pdf)
* [Mathematics for Computer Science by Eric Lehman, Tom Leighton, and Albert Meyer](https://people.csail.mit.edu/meyer/mcs.pdf) - Useful background on discrete mathematics.

---

## Course Structure

  * **Lectures**: Led by one of the two instructors, Prof. Erdös or Prof. Januario.
     * **Meetings**: Tuesdays and Thursdays, 75 minutes each.
     * **Attendance**: Mandatory and tracked through graded worksheets.
     
  * **Discussion Labs**: Led by the Teaching Fellow.
     * **Meetings**: Wednesdays, 50 minutes each.
     * **Attendance**: Mandatory, with occasional graded quizzes.
  * **Office hours**: We will hold multiple office hours throughout the week. The exact office hour schedule is available in the calendar.

  Some material covered in lecture and lab may not be in our textbooks. You are in all cases responsible to be up-to-date on the material. 

---

## Course atmosphere, diversity and inclusion

Class participation and questions are very much encouraged. Please ask as many questions in class, labs and on Piazza as you need. Chances are that your question and answer will be as helpful to your classmates as to you.

We intend to provide a positive and inclusive atmosphere in class and on the associated virtual platforms. Students from a wide range of backgrounds and with a diverse set of perspectives are welcome. We ask that students treat each other with thoughtfulness and respect, and do their part to make all their peers feel welcome. Your suggestions are encouraged and appreciated. Please let us know ways to improve the effectiveness of the course for you personally or for other students or student groups.

If you require particular accommodations for exams or coursework, please contact the instructor (and forward any relevant documentation from Disability and Access Services) in a timely manner. If you are facing unusual circumstances during the semester, please reach out to us early on so that we can find a good arrangement.

---

## Grading

The course grade will be calculated as follows:

|       Component       | Weight |
|          ---          |  ---:  |
|  Worksheet completion |   16%  |
| In-class midterm exam |   20%  |
| Final exam during finals week  |   20%  |
|        Quizzes        |   44%  |


---

## Exam policies

Both exams will consist of problem-solving and short questions about the course material.

* The duration and location of each exam are given in the course schedule.
    * The midterm exam will be during class time and takes 75 minutes, tentatively scheduled for **Tuesday, October 27**.
    * The final exam is 120 minutes, scheduled during the University-assigned final exam slot.
* The content of the final exam is cumulative.
* Exams are closed-book and closed-note unless otherwise announced. Phones, smartwatches, laptops, and other electronic devices are not permitted.
* No collaboration whatsoever is permitted on exams; any violation will be reported to the College.
* Students must score at least 40% on both the midterm and final exams to pass the course. **This will be strictly enforced.**
* Makeup exams will only be given in documented cases of serious illness.
* Exam regrade requests must be submitted through Gradescope within 7 days of grades being posted.
* **Incompletes for this class will be granted according to** [CAS Policy](https://www.bu.edu/cas/faculty-staff/instructors-guide/incomplete-grades/).
* Do not make any travel plans before knowing all dates of your final exams.

---

## Worksheet policies 

In-class worksheets give you a structured way to practice concepts and test your understanding during lecture; therefore, your presence in class is mandatory. Most of the questions covered in worksheets can be found in our textbooks and slides. Read them!

* Printed and online versions of the worksheets will be made available on the day of each lecture.
* Peer collaboration is strongly encouraged for in-class worksheets.
* Once completed, worksheets must be submitted electronically through Gradescope no later than 2:00 PM on the day of the lecture.
* Submit worksheet solutions as **one single PDF file** with high-quality images. 
<!-- * We recommend using [Gradescope mobile app](https://guides.gradescope.com/hc/en-us/articles/22016028459789-Using-the-Gradescope-Mobile-App-for-Students#h_01HH0C6Z9XD5NARRNN5SANHM5C) for [Android](https://play.google.com/store/apps/details?id=com.gradescope.student&hl=en_US) or [iOS](https://apps.apple.com/us/app/gradescope/id1563280912) to scan your worksheets. -->
* Worksheets will be graded by completion, provided that you have clearly attempted to solve them. Writing "I don't know" does not count as a valid attempt.
* You will get full worksheet points at the end of the semester if you complete at least 80% of the worksheets.
* If you end up with x% points, where x < 80, you will get x/80 of the worksheet points.
* There are no makeup worksheets except in cases required by university policy or approved accommodations. Completing 80% of the worksheets is sufficient to receive full credit, which is intended to cover any absence due to illness, travel delays, or emergencies.
  

---

## Quiz policies

In-class quizzes will be used to measure your true individual understanding and provide clear feedback on what you are actually learning.

* There will be 5 quizzes during lab sections. The dates of the quizzes are posted on the schedule.
* Quizzes will be held in labs and will last 20 minutes.
* The quizzes are all cumulative and will feature short written questions based on class material, textbooks, flashcards, practice problems, or a mix of these sources.
* Quizzes are closed-book and closed-note unless otherwise announced. No electronic devices are permitted.
* Submitting partial work is acceptable if you cannot fully complete a quiz.
* **The lowest quiz grade** will be **dropped**.
* After dropping the lowest quiz, the remaining quizzes are weighted equally.
* There are no makeup quizzes except in cases required by university policy or approved accommodations. The dropped quiz is intended to cover ordinary illness, travel delays, or emergencies.
* If, after reviewing the solutions and your answer, you still believe a portion of your quiz was graded in error, you may request a regrade **via Gradescope**, *NOT* through email. One of the staff will consider your request and adjust your grade if appropriate. Note that when we regrade a problem, your score may go up or down. Regrade requests can be submitted up to one week, 7 days, after grades for that quiz have been posted.

Note that the intent of dropping the lowest quiz is to allow you leeway on one **emergency** situation. Do not simply use your free dropped quiz because you feel like it.

**The instructors retain the right to oral explanation of any student work submitted for a grade**. If the student cannot explain the work they have submitted, the instructor will assign a grade of 0 on the entire assignment in question.


---

## Homework Problems

There are no graded take-home homework assignments in this course.

Weekly practice problems will be posted to help students understand the material and prepare for quizzes and exams. These problems may ask students to apply algorithms from class, modify algorithms, prove correctness, analyze running time, and communicate solutions using precise technical language.

Solutions will be posted after students have had time to attempt the problems. Students are strongly encouraged to work on the practice problems seriously and independently before consulting solutions or discussing them with others.

---

## Collaboration and Academic Honesty

Students must follow the BU Academic Conduct Code. Academic misconduct will be reported and may carry a grading penalty.

* **No collaboration is permitted on exams or quizzes.** Students may not use unauthorized notes, books, websites, electronic devices, AI tools, or other unauthorized outside assistance. **Students may not share or discuss quiz or exam questions with students who have not yet taken them.**

* **Peer collaboration is allowed and encouraged on in-class worksheets.** However, each student must submit only work they participated in producing and must be able to explain their submission.

* **Homework problems are provided for learning and are not submitted for credit.** Students are encouraged to attempt them independently before consulting solutions.

---

## Schedule

This schedule is subject, and likely, to change as we progress through the semester. Reading books are referred to by the acronyms of the author names.

<table>
    <thead>
        <tr>
            <th>Date / Lec</th>
            <th>Agenda (Topics, Readings, Homework)</th>
            <th>Instr.</th>
        </tr>
    </thead>
    <tbody>
         <tr>
            <td> <strong>Lab 1</strong><br> Wednesday <br> Sep 2 </td>
            <td> <b> Labs cancelled  </b> 
            </td>
            <td> --- </td>
        </tr>
        <tr>
            <td> <strong>Lec 1</strong><br> Thursday<br> Sep 3 </td>
            <td> <b>Topics</b>: Course info, difficult problems and complexity classes <br>
                 <b>Read</b>: Syllabus,
                 <a href="#KT">KT 1</a>, <a href="#CLRS">CLRS 1.1-2</a>
                 <br>
                 <b>Do</b>: Sign up to websites listed under <a href="#course-platforms">course platforms</a>.
            </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lec 2</strong><br> Tuesday<br> Sep 8 </td>
            <td> <b>Topics</b>: NP-hard and NP-C problems, reductions <br>
                <b>Read</b>: 
                 <a href="#KT">KT 8.1-3</a>, <a href="#CLRS">CLRS 34.1-3</a>
                <!-- <b>Do:</do> -->
            </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lab 2</strong><br> Wednesday <br> Sep 9 </td>
            <td> <b></b> 
            </td>
            <td>Pooria</td>
        </tr>
        <tr>
            <td> <strong>Lec 3</strong><br> Thursday<br> Sep 10 </td>
            <td> <b>Topics</b>: Np-hard continued <br>
                 <b>Read</b>: 
                 <a href="#KT">KT 8.4-5</a>, <a href="#DPV">DPV 8.1-5</a>
            </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lec 4</strong><br> Tuesday<br> Sep 15 </td>
            <td> <b>Topics</b>: Approximation algorithms I: definitions, simple examples; acyclic subgraph, vertex cover, independent set, greedy set cover.<br> 
            <!-- see slides F24/09/24: find acyclic subgraph, VC 2-approx,  IS (D+1)-approx, Set Cover greedy with (k ln n )-approx proof  -->
            <b>Read</b>:  
            <a href="#KT">KT 11.3-4</a>, <a href="#CLRS">CLRS 35.1</a>, <a href="#CLRS">CLRS 35.3</a><br>
            </td>
            <td> Tiago </td>
        </tr>
                     <tr>
            <td> <strong>Lab 3</strong><br> Wednesday <br> Sep 16 </td>
            <td> <b></b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 5</strong><br> Thursday<br> Sep 17 </td>
            <td> <b>Topics</b>: Approximation algorithms II: Load Balancing, 2-approx and 3/2-approx<br> 
            <!-- LB: see slides F22/10/06  -->
            <b>Read</b>:  
            <a href="#KT">KT 11.1</a>
            <br>
            </td>
            <td> Tiago </td>
        </tr>
        <tr>
            <td> <strong>Lec 6</strong><br> Tuesday<br> Sep 22 </td>
            <td> <b>Topics</b>: Center selection problem<br> 
            <!-- see slides F24/09/26  -->
            <b>Read</b>:  
            <a href="#KT">KT 11.2</a>, <a href="#DPV">DPV 9.2</a>
            <br>
            </td>
            <td> Tiago </td>
        </tr>
                     <tr>
            <td> <strong>Lab 4</strong><br> Wednesday <br> Sep 23 </td>
            <td> <b> Quiz 1 </b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 7</strong><br> Thursday<br> Sep 24 </td>
            <td> <b>Topics</b>: Bin packing<br> 
            <!-- see slides F24/10/03  -->
            <b>Read</b>:  
            <a href="#V">V 9</a>, <a href="https://www.designofapproxalgs.com/book.pdf#page=73">WS 3.3</a>
            <br>
            </td>
            <td> Tiago </td>
        </tr>
        <tr>
            <td> <strong>Lec 8</strong><br> Tuesday<br> Sep 29 </td>
            <td> <b>Topics</b>: Traveling Sales Person approximation with MSTs <br> 
            <!-- see slides F24/10/08 - uses MST. quick review of what MST is --> 
            <b>Read</b>:  
            <a href="#CLRS">CLRS 35.2</a>, <a href="#V">V 4</a>
            </td>
            <td> Dora </td>
        </tr>
                     <tr>
            <td> <strong>Lab 5</strong><br> Wednesday <br> Sep 30 </td>
            <td> <b></b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 9</strong><br> Thursday<br> Oct 1 </td>
            <td> <b>Topics</b>: MSTs implementation: union-find, using amortized analysis<br> 
            <!-- MST algos: Kruskal's and Boruvka. Union-find for implementation, amortized analysis of runtime -->
            <b>Read</b>:  
            <a href="#KT">KT 4.5</a>
            </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lec 10</strong><br> Tuesday<br> Oct 6 </td>
            <td> <b>Topics</b>: MST continued <br>
            <b>Read</b>:  
            <a href="#KT">KT 4.6</a>
            </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lab 6</strong><br> Wednesday <br> Oct 7 </td>
            <td> <b>Quiz 2</b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 11</strong><br> Thursday<br> Oct 8 </td>
            <td> <b>Topics</b>: Sorting; worst/best/expected runtime; recurrences; intro probability and randomization<br> 
           <!--  goal: get a better understanding of runtime analysis; especially that while worst case is often bad, we can expect better in practice. How we can quantify/compute this. Intro to some basic notions of probability; basic idea of randomization in algo, expected values. see slides F24/11/12 -->
            <b>Read: </b>
            <a href="#CLRS">CSLR 5.1-5.3</a>, <a href="#CLRS">CSLR 7.1-7.4</a>
            <br>
            </td>
            <td> Tiago </td>
        </tr>
        <tr class="special-event">
            <td style="background-color: LightYellow"> <strong>No Lec</strong><br> Tuesday<br> Oct 13 </td>
            <td style="background-color: LightYellow">
                Substitute Monday Schedule of Classes 
                <div class="agenda-item"> Check the <a
                        href="https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=America%2FNew_York&showPrint=0&mode=WEEK&src=Y180MTRmM2U0Y2JiODU3N2UxYjM0NmZmMDY4YzBkNzY5MTZiOWYxZWE0ZDZkZDIzNmZiYTU3MTk2MjI5MTRjY2M4QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%233f51b5">Google
                        Calendar</a> for the updated office hour schedule </div>
            </td>
            <td style="background-color: LightYellow"> </td>
        </tr>
        <tr>
            <td> <strong>Lab 7</strong><br> Wednesday <br> Oct 14 </td>
            <td> <b></b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 12</strong><br> Thursday<br> Oct 15 </td>
            <td> <b>Topics</b>: Karger's min-cut algorithm <!-- notions of probability, Karger's rnd min-cut algo &amp; analysis<br> In these three lectures you have to introduce the notion of random variables, conditional probability, chain rule, rnd outcome vs random runtime (Monte Carlo vs Las Vegas). Feel free to mix-up the order of topics as you think is best --> </td>
            <td> Tiago </td>
        </tr>
        <tr>
            <td> <strong>Lec 13</strong><br> Tuesday<br> Oct 20 </td>
            <td> <b>Topics</b>: Random Content Resolution </td>
            <td> Tiago </td>
        </tr>
                      <tr>
            <td> <strong>Lab 8</strong><br> Wednesday <br> Oct 21 </td>
            <td> <b> Quiz 3</b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 14</strong><br> Thursday<br> Oct 22 </td>
            <td> <b>Topics</b>: probabilistic algorithms continued<br> <!-- In these three lectures you have to introduce the notion of random variables, conditional probability, chain rule, rnd outcome vs random runtime (Monte Carlo vs Las Vegas). Feel free to mix-up the order of topics as you think is best --> </td>
            <td> Tiago </td>
        </tr>
        <tr>
            <td> <strong>Lec 15</strong><br> Tuesday<br> Oct 27 </td>
            <td> Midterm </td>
            <td>  </td>
        </tr>
                      <tr>
            <td> <strong>Lab 9</strong><br> Wednesday <br> Oct 28 </td>
            <td> <b></b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 16</strong><br> Thursday<br> Oct 29 </td>
            <td> <b>Topics</b>: Randomized Load Balancing, tail bounds<br> <!-- See slides F24/10/24 --> </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lec 17</strong><br> Tuesday<br> Nov 3 </td>
            <td> <b>Topics</b>: hashing, hash table operations<br> <!-- notion of hash function, collisions, separate chaining and load factors. See F24/10/29 --> </td>
            <td> Dora </td>
        </tr>
                      <tr>
            <td> <strong>Lab 10</strong><br> Wednesday <br> Nov 4 </td>
            <td> <b></b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 18</strong><br> Thursday<br> Nov 5 </td>
            <td> <b>Topics</b>: cont hash table operations: linear probing, quadratic probing, potential attacks<br> <!-- (go slow!!!) F24/10/29 ( a little in 10/31) --> </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lec 19</strong><br> Tuesday<br> Nov 10 </td>
            <td> <b>Topics</b>: hash tables: resizing tables, cuckoo hashing<br> <!-- F24/10/31 --></td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lab 11</strong><br> Wednesday <br> Nov 11 </td>
            <td> <b>Quiz 4</b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 20</strong><br> Thursday<br> Nov 12 </td>
            <td> <b>Topics</b>: computing load: balls and bins , power of two choices<br> <!-- F24/10/31 --> </td>
            <td> Tiago </td>
        </tr>
        <tr>
            <td> <strong>Lec 21</strong><br> Tuesday<br> Nov 17 </td>
            <td> <b>Topics</b>: Bloom filters<br> <!-- F24/11/05 notion, real life applications, analysis --> </td>
            <td> Tiago </td>
        </tr>
        <tr>
            <td> <strong>Lab 12</strong><br> Wednesday <br> Nov 18 </td>
            <td> <b></b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 22</strong><br> Thursday<br> Nov 19 </td>
            <td> <b>Topics</b>: Bloom filters continued<br> <!-- Flajolet-Martin: count unique elements: combination of Bloom filters and intro to streaming algos --> </td>
            <td> Tiago </td>
        </tr>
        <tr>
            <td> <strong>Lec 23</strong><br> Tuesday<br> Nov 24 </td>
            <td> <b>Topics</b>: fun topic pre-Thanksgiving </td>
            <td> Tiago </td>
        </tr>
        <tr>
            <td> <strong>Thanksgiving</strong><br> Thursday<br> Nov 26 </td>
            <td> Thanksgiving break </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 24</strong><br> Tuesday<br> Dec 1 </td>
            <td> <b>Topics</b>: streaming and sketching: reservoir sampling, frequent items<br> <!-- goal: appreciate the notion of streaming data, lack of storage capacity, current best result keeping.  - Dora's CS565 slides --> </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lab 13</strong><br> Wednesday <br> Dec 2 </td>
            <td> <b>Quiz 5</b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 25</strong><br> Thursday<br> Dec 3 </td>
            <td> <b>Topics</b>: count-min-sketch<br> <!-- Dora's CS565 slides --> </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lec 26</strong><br> Tuesday<br> Dec 8 </td>
            <td> <b>Topics</b>: mtx sketching: rnd, CUR, frequent directions<br> <!--  Dora's CS565 slides -->  </td>
            <td> Dora </td>
        </tr>
        <tr>
            <td> <strong>Lab 14</strong><br> Wednesday <br> Dec 9 </td>
            <td> <b></b> 
            </td>
            <td>  </td>
        </tr>
        <tr>
            <td> <strong>Lec 26</strong><br> Thursday<br> Dec 10 </td>
            <td> <b>Topics</b>: final lecture  </td>
            <td> Tiago </td>
        </tr>
    </tbody>
</table>


<!--We have prearranged the following date and time for students with final exam conflict:

* Alternative Final exam date: December 16th
* Time: 3:00 PM – 5:00 PM
* Location: STHB19

Students with exam accommodations, regardless or their final exam conflict, will take the final exam at same day and initial time of the other students at CDS 801.
-->

