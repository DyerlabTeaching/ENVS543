# ENVS 543: Environmental Data Literacy

> Semester course; 3 lecture hours. 3 credits. Enrollment restricted to students with graduate standing, or those with one course in statistics and permission of instructor. Develop quantitative skills for the visualization, manipulation, analysis and communication of environmental "big data." This course focuses on spatial environmental data analysis, interpretation and communication, using real-time data from the Rice Rivers Center and the R statistical analysis environment.

<img align="right" src="dyer.png"> Hello.  My name is Dr. Rodney Dyer and this is a course I've developed to serve as the entry course for incoming Environmental Studies graduate students and advanced undergraduates.  

The rationale for this class is as follows.  

As both a student and instructor in statistics classes, I found I spent a vast amount of time and effort describing the characteristics of statistics (derivations, expectations, etc.).  This is perfectly fine, it is important on many levels to make sure that practitioners understand the basis and context of all the kinds of analyses they use.  However, the drawback here, in my experience, is that once you've spent a semester or year getting all this knowledge under your belt, and one can easily demonstrate their understanding of the parameters in a model, they cannot actually work with real data.  This class is designed to produce practitioners of data analysis.



## Workflow in Data Analysis

To understand data analytics, one needs to recognize the entire workflow.  Below is a brief graphical depiction of how analysis actually works—in the real world.  In this class, we will work on all of these components using the open-source R language.

- **Collect:** Getting data from an external source into a format that you can use is often the most time-consuming step in the analysis.  The content of this class will provide training in data import from local, online, and database sources.  
- **Visualize:** Visualizing data is key to understanding.  In the image below, notice that the variables X and Y in all the displayed data sets have equivalent means, standard deviations, and correlation up to 2 decimal places!  We will emphasize visualization, both static and dynamic, throughout this class.
- **Transform:** Pulling data into your analysis ecosystem is not sufficient.  Often the data need to be reformatted and reconfigured before it is actually usable.
- **Model:**  The application of models to subsets of data is often the step that takes the least amount of time and effort.  However, the application of a model to data is not the endpoint.  The model must be visualized and, many times, the underlying data or derivate data must be transformed and submitted to subsequent models.
- **Communicate:** The effort we put into research and analyses is meaningless without effective communication of your data and findings to a broad audience.  Here we will focus on how to develop effective data communication strategies and formats.

![Common data analysis workflow schematic.  Notice, it is not a linear process, but one that reticualtes back upon itself.](workflow.png)



## Learning Objectives

The purpose of this course is to help you build your data skills and to develop a foundational understanding upon which subsequent courses will build. The overarching goal here is to develop a working knowledge of the R statistical computing language and enough proficiency to import raw data and then iterate through the visualization, manipulation, and analysis steps in the creation of output that is easily communicated to a scientific audience.

The content of this course is built upon the following general student learning objectives (SLO):

- SLO 1: Identity, manipulate, and summarize numerical, categorical, ordinal, logical, date, string, and spatial data types.
- SLO 2: Create habits and took knowledge to support reproducible research.  
- SLO 3: Create an informative and effective graphical display of various data types of suitable quality for inclusion in published manuscripts.
- SLO 4: Effectively choose appropriate statistical models based upon the types of data at hand and the questions being addressed.
- SLO 5: Demonstrate a general understanding of spatial data types and the creation of both appropriate static and dynamic maps.

## Course Content & Assessment

This course is designed as a sequence of individual, stand-alone modules.  Each is self-contained and includes a lecture, slides, a larger narrative document, a video demonstration, and an assessment. 

Deliverable       | Details                                  | SLO  
------------------|------------------------------------------|-----------
Welcome & Logistics | Setting up the logistics for the class |  NA
Markdown | Learn to use markdown to mix data, analyses, output, graphics, and reserach narratives | 2
Git & Github | Establish a functional working knowledge of git as a collaborative tool for reproducable research | 2
Data Types | Understanding the fundamnetal data types within R and how to easily import, work with, and export raw data | 1,2 
Data Containers | Creation, import, and export of vectors, matrices, data.tables, and lists for reliable data representation | 1,2
Tidyverse | Data manipulation.  Like a boss. | 1, 2
Graphics that DON’T suck | Hello publication quality graphics, using the grammar of graphics approach | 2,3
Confidence on a Mean | Base understanding of statistical inferences and the properties of sampled data | 1,2,4
Biniomial Inferences | Analyses based upon expectations.  | 4
Categorical ~ f(Categorical) | Contingency table and categorical count data | 4
Continuous ~ f(Categorical) | Analysis of Variance (or equality of means) | 4
Continuous ~ f(Continuous) | Correlation & Regression approaches | 4
Categorical ~ f(Continuous) | Logistic regression | 4
Points, Lines, & Polygons | Spatial data as vectors | 3,5 
Raster Data | Continuously distributed spatial data | 3,5
Cartography | Creating usable and understandable maps and symbolic representation of spatial data | 3,4
Census Data | Human data based upon the US census. | 3,4,5
Raytracing | Higher dimensional visualization of spatial extents.  | 3,5

## Logistics

- Course Instructor:  Professor Rodney Dyer 
- Email: [rjdyer@vcu.edu](mailto://rjdyer@vcu.edu) 
- Webpage: [dyerlab.org](https://dyerlab.org). 
- Office Hours:  Online each Tuesday & Thursday from 10-11 am via zoom or by appointment.
- Credit Hours: 3
- Meeting Times: T/R 12:00 - 13:45
- 

## Required Materials
This course requires that you bring your own laptop or other computing devices that is capable of running RStudio and the R statistical language.  There is no required book and all content is provided via online resources.

## Assignments & Grading Policy

The grade for this course is based upon the totality of the points gained for all assignments as well as a single large data analysis project that will be due at the end of the semester.  This final will account for 10% of your overall grade.  Grades will be determined using the normal 10% scales: 
- A (>= 90%),  
- B (>= 80% & < 90%),  
- C (>= 70% & < 80%), 
- D (>= 60% & < 70%), and 
- F (< 60%).  

All percentages are concrete and acores will be rounded to the appropriate whole number.  No extra credit will be given.

## Late Policy

All of the content in this class is given as take-home assignments and tests.  You will have a full 7 days to complete and turn in the work.  The intention here is to give you more than sufficient time to complete the work because we do not rush data analysis.  On the due date, I post the answers so you can check your work.  After the answers are posted, there will be no points awarded for late work.

## Attendance Policy

All content is provided as slides, handouts, and video content.  Much of the work in this class will be conducted during the in-class session.  As such, you must show up to class if you intend to get the content.  Data analysis is a hands-on experience and the more doing it you engage in, the more efficient you will become.

## Disclaimer

Note that the specifics of this Course Syllabus may be changed at any time during the semester.  You will be responsible for abiding by any such changes that are communicated to you via email, course announcement, and/or posting in the course discussion forums.

## VCU Policies

Students should visit http://go.vcu.edu/syllabus and review all syllabus statement information. The full university syllabus statement includes information on safety, registration, the VCU Honor Code, student conduct, withdrawal, and more.

Use [VCU Libraries](https://www.library.vcu.edu) to find and access library resources, spaces, technology and services that support and enhance all learning opportunities at the university.

<h3 style="margin-top: 1em;">Health and safety</h3>
<p><strong>Public health information</strong><br>Health advisories, including information about COVID-19 testing, vaccination, supplies and other public health measures, can be found at <a href="https://srm.vcu.edu/health-advisories/">the Safety and Risk Management website</a>. Visit this site to stay informed about recommendations for VCU and surrounding communities. Additional links to health, wellness and safety information are on the <a href="https://www.vcu.edu/life-at-vcu/health-wellness-safety/">Life at VCU webpage</a>.</p>
<strong>Public health information</strong>
<br>
Health advisories, including information about COVID-19 testing, vaccination, supplies and other public health measures, can be found at 
<a href="https://srm.vcu.edu/health-advisories/">the Safety and Risk Management website</a>
. Visit this site to stay informed about recommendations for VCU and surrounding communities. Additional links to health, wellness and safety information are on the 
<a href="https://www.vcu.edu/life-at-vcu/health-wellness-safety/">Life at VCU webpage</a>
.
<p><strong>Public health information</strong><br>Health advisories, including information about COVID-19 testing, vaccination, supplies and other public health measures, can be found at <a href="https://srm.vcu.edu/health-advisories/">the Safety and Risk Management website</a>. Visit this site to stay informed about recommendations for VCU and surrounding communities. Additional links to health, wellness and safety information are on the <a href="https://www.vcu.edu/life-at-vcu/health-wellness-safety/">Life at VCU webpage</a>.</p>
<p><strong>Campus emergency information</strong><br><a href="https://alert.vcu.edu/signup/">Sign up to receive at VCU Alerts</a>. It is essential to keep your information up-to-date within VCU Alert and to keep your permanent address and emergency contact information current in <a href="https://bansso.vcu.edu/ssomanager/c/SSB">eServices</a>. VCU uses a variety of communication methods to alert the campus community about emergency situations and safety threats. Learn more about <a href="https://alert.vcu.edu/know/types-of-alerts/">types of alerts</a> online. Know the emergency phone number for the VCU Police (828-1234), and report suspicious activities and objects.</p>
<p><strong>Managing stress</strong><br>Students may experience situations or challenges that can interfere with learning and interpersonal functioning including stress, anxiety, depression, alcohol and/or other drug use, concern for a friend or family member, loss, sleep difficulties, feeling hopeless or relationship problems. There are numerous campus resources available to students including <a href="https://counseling.vcu.edu/">University Counseling Services</a> (804-828-6200 MPC Campus, 804-828-3964 MCV Campus) which provides brief therapy treatment, <a href="https://health.students.vcu.edu/">University Student Health Services</a> (MPC 804 828-8828, MCV Campus 804 828-9220) and the <a href="https://recwell.vcu.edu/">Department of Recreation &amp; Well-Being (RecWell)</a> (804-828-9355). 24 hour emergency mental health support is available by calling (804) 828-6200 or utilizing the <a href="https://988lifeline.org/?utm_source=google&amp;utm_medium=web&amp;utm_campaign=onebox">National Suicide Prevention Lifeline</a> (dial 988).</p>
<p><strong>Mandatory responsibility of faculty members to report incidents of sexual misconduct</strong><br>All VCU faculty members are Responsible Employees as defined by University policy. Responsible employees have a duty to report alleged policy violations to the Title IX Coordinator. This includes incidents of sexual harassment, sexual assault, dating &amp; domestic violence, stalking, sexual exploitation, and related retaliation. Responsible employees may report information through this form or by emailing <a href="mailto:titleix@vcu.edu">titleix@vcu.edu</a>. For confidential support, contact <a href="https://counseling.vcu.edu/">University Counseling Services</a>, (804-828-6200 for MP Campus/804-828-3964 for MCV Campus) For more information, visit <a href="http://equity.vcu.edu/title-ix/">our Title IX webpage</a>.</p>
<p><strong>Reading Days</strong><br>No classes or exams are held on Reading Day (Friday, Oct. 21, 2022) except in instances where a student is involved in clinical and field placements, practica, co-ops, internships and other work-related experiential learning activities. Faculty may not give an examination or an assignment on those days. Instead, students are encouraged to use these days for relaxation, study and/or review of class materials.</p>
<h3>Academic Success and Integrity</h3>
<p><strong>Honor System: upholding academic integrity</strong><br>The VCU Honor System policy describes the responsibilities of students, faculty and administration in upholding academic integrity. According to this policy, "Members of the academic community are required to conduct themselves in accordance with the highest standards of academic honesty, ethics and integrity at all times." <a href="https://conduct.students.vcu.edu/vcu-honor-system/">Students are expected to read the policy in full and learn about requirements</a>.</p>
<p><strong>Early academic alerts</strong><br>VCU’s <a href="https://semss.vcu.edu/for-faculty-and-staff/early-notification-programs/#:~:text=VCU's%20Early%20Notification%20Programs%20help,students%20early%20in%20the%20semester.">Early Notification Program</a> supports student success. If as an instructor I am concerned about your academic engagement or performance in the first few weeks of class, you may receive a Progress Report email encouraging you to reach out to me after class or during student hours (office hours) for additional support. As a community of care, your <a href="https://uaa.vcu.edu/services/appointments/">academic advisor</a>, the <a href="https://writing.vcu.edu/">Writing Center</a>, and the <a href="https://clc.vcu.edu/">Campus Learning Center</a> may also follow up to provide additional layers of support.</p>
<p><strong>Students with disabilities</strong><br>VCU is committed to ensuring that all students maintain equal access to all aspects of the university, including educational experiences through the provision of reasonable accommodations and academic adjustments. In addition to being a requirement under Section 504 of the Rehabilitation Act of 1973 and the Americans with Disabilities Act, this speaks directly to VCU's mission of inclusion, equity, and access. To receive accommodations or other disability-related supports, students must register with the Office of Student Accessibility and Educational Opportunity on the Monroe Park Campus (828-2253) or the Division for Academic Success on the MCV campus (828-9782). Students and faculty can visit the <a href="https://saeo.vcu.edu/">Student Accessibility and Educational Opportunity website</a> and/or the <a href="https://das.vcu.edu/">Division for Academic Success website</a> for additional information. Once students have completed the registration process, they will be provided with a letter of accommodation. They should provide a copy to their instructor(s) and attempt to schedule a meeting to discuss the implementation of accommodations as early in the semester as possible.</p>
<p><strong>Career Services</strong><br>Looking for ways to tie what you are learning in your class to your future career or professional goals? <a href="http://www.careers.vcu.edu/">VCU Career Services</a> provides career planning services for all current VCU students and alumni. Career Services can help students with finding a work-study job on/off campus, resume writing, internship development, interviewing, preparing for graduate school, networking, or job searching. Students are invited to attend career events and workshops, and schedule individualized career advising appointments.</p>
<h3>Registration, Attendance and Financial Responsibilities</h3>
<p><strong>Class registration required for attendance</strong><br>Students may attend only those classes for which they have registered. Faculty may not add students to class rosters. If students are attending a class for which they have not registered, they must stop attending.</p>
<p><strong>Attendance and consequences of poor attendance</strong><br>The instructional programs at VCU are based upon a series of class meetings involving lectures, discussions, field experiences, special readings and reporting assignments. Therefore it is important for each student to be in attendance on a regular basis. A student who misses a class session is responsible for completing all material covered or assignments made during the absence.</p>
<ul>
<li>Students having attendance problems should contact their instructor to explain the reasons for nonattendance and to discuss the feasibility of continuing in the course. If the student has fallen so far behind that the successful completion of the course is impossible, the student should withdraw from the course before the end of the first 10 weeks of classes (by Oct. 28, 2022).</li>
<li>If the student continues to miss class and does not officially withdraw from the course, the instructor may withdraw the student for nonattendance with a mark of “W'' before the end of the first 10 weeks of classes or may assign an academic grade at the end. Withdrawals are not permitted after the end of the first 10 weeks of classes. For classes that do not conform to the semester calendar, the final withdrawal date occurs when half of the course has been completed.</li>
</ul>
<p><strong>Withdrawal from classes</strong><br>Before withdrawing from classes, students should consult their instructor as well as other appropriate university offices. Withdrawing from classes may negatively impact a student’s financial aid award and his or her semester charges. To discuss financial aid and the student bill, contact the <a href="https://sfmc.vcu.edu/contactsfmc/ramq/">Student Financial Management Center (RAMQ)</a> regarding the impact on your financial aid.</p>
<p><strong>Military short-term training or deployment</strong><br>If military students receive orders for short-term training or for deployment/mobilization, they should inform and present their orders to Military Student Services and to their professor(s). For further information on policies and procedures contact <a href="https://militaryservices.vcu.edu/">Military Student Services</a> at 828-5993.</p>
<p><strong>Students representing the university – excused absences</strong><br>Students who represent the university (athletes and others) do not choose their schedules. All student athletes should provide their schedules to their instructors at the beginning of the semester. The Intercollegiate Athletic Council strongly encourages faculty to treat missed classes or exams (because of a scheduling conflict) as excused absences and urges faculty to work with the students to make up the work or exam.</p>
<p><strong>Student financial responsibility</strong><br><a href="https://sfmc.vcu.edu/contactsfmc/ramq/">Students assume the responsibility of full payment</a> of tuition and fees generated from their registration, all charges for housing and dining services and other applicable miscellaneous charges. Students are ultimately responsible for any unpaid balance on their account as a result of the University Financial Aid Office or their third party sponsor canceling or reducing their award(s).</p>
<h3>Technology</h3>
<p><strong>Computer and network use</strong><br>All students are expected to know and comply with <a href="https://policy.vcu.edu/universitywide-policies/policies/computer-and-network-resources-use.html">VCU's Computer and Network Use policy.</a></p>
<p><strong>Student email standard</strong><br>Email is considered an official method for communication at VCU. Students are expected to check their official VCU email on a frequent and consistent basis (the university recommends daily) in order to remain informed of university-related communications. Students are responsible for the consequences of not reading, in a timely fashion, university-related communications sent to their official VCU student email account. Mail sent to the VCU email address may include notification of university-related actions, including disciplinary action. <a href="https://ts.vcu.edu/media/technology-services/assets/content-assets/university-resources/ts-groups/information-security/StudentEmailStandard.pdf">Students must read this standard in its entirety.</a></p>
<p><strong>Faculty communication about students</strong><br>VCU instructional faculty, administrators and staff maintain confidentiality of student records and disclose information in accordance with the Family Educational Rights and Privacy Act (FERPA). This means that VCU officials may disclose student record information without the consent of the student in certain situations. To support university operations, for example, VCU officials share information about students with other educational officials as necessary to perform their job duties. FERPA permits this disclosure to school officials who have a legitimate educational interest in the student information. In addition, VCU officials have obligations to report information shared by a student depending on the content of that information, for example, in compliance with VCU’s policy on the duty to report. Unless FERPA permits a certain disclosure, VCU generally requires consent from a student to disclose information from their education record to another individual. You may find additional information on the <a href="https://rar.vcu.edu/records/family-educational-rights-and-privacy-act/">VCU FERPA website.</a></p>
<h3>Important dates</h3>
<p>Important dates for the current and future semesters are listed in the <a href="https://academiccalendars.vcu.edu/">VCU Academic Calendar.</a></p>

