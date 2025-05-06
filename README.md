# database-management-lab-3-solved
**TO GET THIS SOLUTION VISIT:** [Database-Management Lab 3 Solved](https://www.ankitcodinghub.com/product/database-management-lab-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97723&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Database-Management Lab 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Consider the hospital management systems used in assignment for Lab Day 2. For this system, we need to answer the set of query requirements mentioned below. Accordingly, update the ER-Diagram you have drawn and submitted against Lab Day 2 assignment. From the ER-Diagram, derive the tables using correct rules for relational model generation from ER model. Draw the current ER diagram and the tables on a piece of paper. For the ER diagram, do NOT use Crow’s feet notation. Clearly mark the columns, primary keys and foreign keys as appropriate for each table. This forms your database schema.

Create the tables as drawn on the paper in the database using appropriate Create table SQL statements. You may choose appropriate data types for each column. Write SQL statements to answer the queries given below. You may test the SQLs by inserting appropriate rows in the tables. Note that, your database schema must correspond to the (updated) ER-Diagram you are submitting.

No need to do anything on ERDPlus.

Write your roll number and name on the piece of paper where you draw the ER diagram and database schema.

Through Moodle, submit a zip file containing the image files for the ER Diagram &amp; the database schema and a text file containing your Create &amp; Select SQL statements. (Name it as Lab3_&lt;Roll_no&gt;.zip).

[10 Marks for ER model + 20 Marks for Database schema + 10 Marks for Create Table SQLs + (5×8=40 marks for Select SQLs)]

<ol>
<li>List the patients (Patient_Id, Name) so far admitted under each doctor (Doctor_Id, Name).</li>
<li>List the patients (Patient_Id, Name) currently admitted under each doctor (Doctor_Id, Name), i.e., the
patients who have been admitted but not yet been released.
</li>
<li>List the patients (Patient_Id, Name) so far admitted under each doctor (Doctor_Id, Name) who have
been admitted under more than one department
</li>
<li>List the patients (Patient_Id, Name) so far admitted under each doctor (Doctor_Id, Name) who have not
been admitted in the same department to which the doctor belongs.
</li>
<li>List the patients (Patient_Id, Name) so far admitted under each doctor (Doctor_Id, Name) who have
been admitted in at least one department to which the doctor does not belong.
</li>
<li>List the visit details of patients (Patient_Id, Name, Date of Admission, Date of Release). Date of Release
will be NULL if the patient is currently admitted. Note that, if the same person visits the hospital more than once, we need to display details of each visit (hint: if the same patient visits the hospital again, he/she will be given the same patient id). Bonus of 10 Marks if you can handle the situation in which a patient is admitted on a day, released on the same day and is again admitted on the same day (total for today’s assignment cannot exceed full marks with the bonus).
</li>
<li>List for each doctor (Doctor_Id, Name), the number of patients currently admitted under him.</li>
<li>For each state, for each department having more than 5 wards, list the number of patients currently
admitted (Only for those departments which have more than 2 patients currently admitted).
</li>
</ol>
[Penalty for plagiarism/copying: You will be awarded 0 for all the problems for the lab day and an additional 5 marks will be deducted out of the total of 40 in Lab. All persons involved will be awarded the same penalty irrespective of who has copied from whom]

</div>
</div>
</div>
