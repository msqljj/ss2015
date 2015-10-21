 	Parsons The New School for Design
	Master in Design and Technology
	**Creative Coding: Shader Studio** - 7040 - PGTE 5566 - B
	Wednesdays at D 1208 (6 E 16th ST) from 1900 to 2140 hours

Welcome to **Shader Studio FALL 2015**, [here](https://github.com/patriciogonzalezvivo/ss2015) you will find the class syllabus, assignments and materials.

## Course Description
This studio course will focus on acquiring advance graphical programming skills using OpenGL/WebGL Shading Language to modify the rendering pipeline. Students are free to use the tool, library or framework they most feel comfortable with such as: Processing, openFrameworks, Cinder, Three.js, Shadertoy or other. In particular, this course will cover GLSL pixel (or fragment) shaders.

Students will learn how to do cool graphics using parallel programming instead of functional or object oriented programming paradigms. Expect to do (and be comfortable with) linear algebra and trigonometry - this will be a math intensive course.

We will start by reviewing the OpenGL/WebGL pipeline and how to setup a basic vertex and fragment shader. Then we will learn
about the basic types and functions of shading language together with default uniforms. Using basic mathematical functions, we will go from drawing gradients to composing shapes. We will learn about matrices, patterns and noise. 

In the second part of the semester you will learn how to incorporate pixel shaders into your own projects, for example: image processing (such as matrix convolutions, blurs, LUT, filter and other effects) and simulations (conway, ripples, watercolor, reaction diffusion and voronoi).

Think of this course as a drawing studio course where you will exercise and train your abilities by sketching over and over. Different computational techniques and mathematical principles will be presented and it will be up to you to gradually incorporate them into your sketches. This course will require you to practice at home. Expect to do a LOT of homework from week to week.

## Course Outline

| WEEK | DATE  | TOPIC                  | Assignment          |
|:----:|:-----:|:----------------------:|:-------------------:|
|  01  | 09/02 | Presentation & setup: Introduce the course, instructor and students, review syllabus, discuss technical requirements and tools for shader coding, and present basics of GLSL. | Read chapters 1,2, 3, 4, 5 & do the exercises |
|  02  | 09/09 | Shaping Functions: Explore and analyze the variety of mathematical formulae used to shape position, color, animation and other data in shader code. | Read chapter 6 & do the exercises |
|  03  | 09/16 | Color: Explore and understand the creation and modification of color in GLSL, including gradients, stepped colors and time-based animations. | Read chapter 7 & do the exercises |
|  04  | 09/30 | Shapes: Learn to use specialized GLSL methods and functions to create a variety of geometric shapes in shaders, from basic circles and squares to highly complex forms and patterns. | Read chapter 8 & do the exercises |
|  05  | 10/07 | Matrices: Understand the basic concepts and structure of matrix operations, then learn to implement matrices in GLSL for translation, rotation, scaling and time-based animation. | Read chapter 9 & do the exercises |
|  06  | 10/14 | Patterns: Learn to use and combine all previously-covered tools to create complex visual patterns in shaders. This class may include a guest presentation on implementing GLSL patterns in digital maps and geographic imagery. | Read chapter 10 & do the exercises |
|  07  | 10/21 | Mid-course Review: To help prepare for midterm projects, this session will review and further explore any concepts covered up to this point, as requested by students. | Prepare midterm project |
|  08  | 10/28 | MIDTERM PROJECT: Students will present their midterm projects and receive critiques and feedback from instructor and fellow students. | Read chapter 11 & do the exercises |
|  09  | 11/04 | Noise: Learn about noise algorithms: concept and principles, how they work and their use in GLSL; then learn the implement noise functions in shaders. | Read chapter 12 & do the exercises|
|  10  | 11/11 | Fractals: Explore the creation of recursive forms, images and animations on the GPU through GLSL code. | Read chapter 13 & do the exercises |
|  11  | 11/18 | Image operations: Learn to import preexisting graphic files into shaders and apply previously learned GLSL methods to manipulate the images. | Read chapter 14 & do the exercises |
|  12  | 11/25 | Simulations: Examine the use of shaders and GLSL for simulation of natural and real-world phenomena, such as terrain, waves, explosions, flocking, etc. Implement sample simulations that demonstrate key principles. | Read chapter 15 & do the exercises |
|  13  | 12/02 | Final project workshop: Work session for development, feedback and troubleshooting as students develop final projects. Some class time may also be reserved for guest presentations on specialized topics within GLSL and shader fields. | Read chapter 16 & do the exercises |
|  14  | 12/09 | Final project workshop: (Same as above)	| Prepare final project |
|  15  | 12/16 | FINAL PROJECT: Students will present their final projects, and receive critiques and feedback from the instructor, fellow students and potentially guest critics. | Celebrate |

## Learning Outcomes
By the successful completion of this course, students will be able to:

* Be able to program and run their own GLSL Shaders in different platforms and frameworks.

* Have an understanding of how parallel programming works and how different well known algorithms could be adapted to it.

* Be comfortable talking about their work in front of other students.

## Materials and Supplies

Hardware:

* Computer with dedicated GPU Card (NVidia/ATI) running MacOSX or Linux

or

* [RaspberryPi 2](http://www.adafruit.com/products/2358) + [everything you need to use it](http://www.adafruit.com/products/2129)

Software tools:

* [**glslCanvas**](https://github.com/patriciogonzalezvivo/glslCanvas):Simple tool to load GLSL shaders on HTML Canvas using WebGL.

* [**glslViewer**](http://patriciogonzalezvivo.com/2015/glslViewer/) Live GLSL coding render for MacOS and Linux 

* [**SublimeText**](http://www.sublimetext.com/): don’t need introductions. Probably one of the best free text editors. You probably one to install the following packages: DashDoc, Color Highlighter, OpenGL Shading Language (GLSL) and MarkdownEditing.

* [**SublimeText GlslViewer Plugin**](https://packagecontrol.io/packages/glslViewer) Sublime Text 2/3 plugin for live coding GLSL Shaders

* **Grapher**: Comes for free in your OS X distribution. This handy tool let you visualize math function

* [**Shadershop**](http://tobyschachman.com/Shadershop/) an interface for programming GPU shaders in the mode of a direct manipulation image editor like Photoshop. It is an experiment in leveraging the programmer’s spatial reasoning the way that coding today leverages the programmer’s symbolic reasoning.

* [**Spectrum**](http://www.eigenlogik.com/spectrum/mac): Nice color scheme tool that let you extract color palettes and insert them in your code easily.

* [**Mou**](http://mouapp.com/): is important to document well your projects. Get a nice Markdown editor like [Mou](http://mouapp.com/) or [AiWriter](http://www.iawriter.com/mac/)

* [**ShaderToy**](https://www.shadertoy.com/): important openSource gallery of impressive fragments shaders.

Texts:

* [**The Book of Shaders**](http://thebookofshaders.com) We are going to follow the chapters order of this book, also you can use the [**Shader Editor**](http://patriciogonzalezvivo.com/2015/thebookofshaders/edit.html), [**Function Editor**](http://patriciogonzalezvivo.com/2015/thebookofshaders/function.html) and [**Glossary**](http://patriciogonzalezvivo.com/2015/thebookofshaders/glossary/) from it

* [OpenGL Introduction](https://open.gl/introduction)

* [The 8th edition of the OpenGL Programming Guide (also known as the red book)](http://www.amazon.com/OpenGL-Programming-Guide-Official-Learning/dp/0321773039/ref=sr_1_1?s=books&ie=UTF8&qid=1424007417&sr=1-1&keywords=open+gl+programming+guide)

* [WebGL: Up and Running](http://www.amazon.com/WebGL-Up-Running-Tony-Parisi/dp/144932357X/ref=sr_1_4?s=books&ie=UTF8&qid=1425147254&sr=1-4&keywords=webgl)

* [3rd Edition of Mathematics for 3D Game Programming and computer Graphics](http://www.amazon.com/Mathematics-Programming-Computer-Graphics-Third/dp/1435458869/ref=sr_1_1?ie=UTF8&qid=1424007839&sr=8-1&keywords=mathematics+for+games)

* [2nd Edition of Essential Mathematics for Games and Interactive Applications](http://www.amazon.com/Essential-Mathematics-Games-Interactive-Applications/dp/0123742978/ref=sr_1_1?ie=UTF8&qid=1424007889&sr=8-1&keywords=essentials+mathematics+for+developers)


## Final Grade Calculation
* 10% participation
* 20% attendance 
* 30% homework 
* 20% mid term
* 20% final project

## Assignments

* Homework will be provided weekly and available on Canvas.

* The midterm project will consist on choosing three design rules (like for example *diversity*, *simplicity* and *elegance*) and make a GLSL library (group of custom functions) to make simple shapes (no less than 5) and ways to combine them in a **series of procedural [patterns](https://www.pinterest.com/patriciogonzv/paterns/)** (no less than 10). Make a project on OF, P5, three.js or other framework (Unity, Tangram, etc) to show off the qualities you choose. Your project have to be documented and sharable over the internet as a video or webpage.

* For you final project create and combine at least teen shaders according to you own design guides (like the midterm project) to apply them on: a [**map**](https://www.pinterest.com/patriciogonzv/cartography/), a [**HUD**](https://www.pinterest.com/patriciogonzv/huds/), a **game** or [**interactive art**](https://www.pinterest.com/patriciogonzv/art-installations/). The project have to be well documented and sharable over the internet as a video or webpage.

## Grading Standards

- A	Work of exceptional quality 
- A-	Work of high quality
- B+	Very good work
- B 	Good work; satisfies course requirements 
Satisfactory completion of a course is considered to be a grade of B or higher.
- B-	Below-average work
- C+ 	Less than adequate work
- C 	Well below average work
- C-	Poor work; lowest possible passing grade
- F	Failure
- GM	Grade missing for an individual

Grades of D are not used in graduate level courses.

### Grade of W
The grade of W may be issued by the Office of the Registrar to a student who officially withdraws from a course within the applicable deadline. There is no academic penalty, but the grade will appear on the student transcript. A grade of W may also be issued by an instructor to a graduate student (except at Parsons and Mannes) who has not completed course requirements nor arranged for an Incomplete.

### Grade of WF
The grade of WF is issued by an instructor to a student (all undergraduates and all graduate students) who has not attended or not completed all required work in a course but did not officially withdraw before the withdrawal deadline. It differs from an “F,” which would indicate that the student technically completed requirements but that the level of work did not qualify for a passing grade. The WF is equivalent to an F in calculating the grade point average (zero grade points), and no credit is awarded.

### Grades of Incomplete 
The grade of I, or temporary incomplete, may be granted to a student under unusual and extenuating circumstances, such as when the student’s academic life is interrupted by a medical or personal emergency. This mark is not given automatically but only upon the student’s request and at the discretion of the instructor. A Request for Incomplete form must be completed and signed by student and instructor. The time allowed for completion of the work and removal of the “I” mark will be set by the instructor with the following limitations: 

**Graduate students** Work must be completed no later than one year following the end of the class. Grades of “I” not revised in the prescribed time will be recorded as a final grade of “WF” (for Parsons and Mannes graduate students) or “N” (for all other graduate students) by the Office of the Registrar. The grade of “N” does not affect the GPA but does indicate a permanent incomplete. 

### Divisional, Program and Class Policies

● **Responsibility**
Students are responsible for all assignments, even if they are absent. Late assignments, failure to complete the assignments for class discussion and/or critique, and lack of preparedness for in-class discussions, presentations and/or critiques will jeopardize your successful completion of this course.  

● **Participation** 
Class participation is an essential part of class and includes: keeping up with reading, assignments, projects, contributing meaningfully to class discussions, active participation in group work, and coming to class regularly and on time.  

● **Attendance**
Parsons’ attendance guidelines were developed to encourage students’ success in all aspects of their academic programs. Full participation is essential to the successful completion of coursework and enhances the quality of the educational experience for all, particularly in courses where group work is integral; thus, Parsons promotes high levels of attendance. Students are expected to attend classes regularly and promptly and in compliance with the standards stated in this course syllabus. 

While attendance is just one aspect of active participation, absence from a significant portion of class time may prevent the successful attainment of course objectives. A significant portion of class time is generally defined as the equivalent of three weeks, or 20%, of class time. Lateness or early departure from class may be recorded as one full absence. Students may be asked to withdraw from a course if habitual absenteeism or tardiness has a negative impact on the class environment.

● **Electronic Devices** 
The use of electronic devices (phones, tablets, laptops, cameras, etc.) is permitted when the device is being used in relation to the course's work. All other uses are prohibited in the classroom and devices should be turned off before class starts.

● **Academic Honesty and Integrity**
The New School views “academic honesty and integrity” as the duty of every member of an academic community to claim authorship for his or her own work and only for that work, and to recognize the contributions of others accurately and completely. This obligation is fundamental to the integrity of intellectual debate, and creative and academic pursuits. Academic honesty and integrity includes accurate use of quotations, as well as appropriate and explicit citation of sources in instances of paraphrasing and describing ideas, or reporting on research findings or any aspect of the work of others (including that of faculty members and other students). Academic dishonesty results from infractions of this “accurate use”. The standards of academic honesty and integrity, and citation of sources, apply to all forms of academic work, including submissions of drafts of final papers or projects. All members of the University community are expected to conduct themselves in accord with the standards of academic honesty and integrity. Please see the complete policy in the Parsons Catalog.

It is the responsibility of students to learn the procedures specific to their discipline for correctly and appropriately differentiating their own work from that of others.  Compromising your academic integrity may lead to serious consequences, including (but not limited to) one or more of the following: failure of the assignment, failure of the course, academic warning, disciplinary probation, suspension from the university, or dismissal from the university.  

● **Student Disability Services** (SDS)
In keeping with the University’s policy of providing equal access for students with disabilities, any student with a disability who needs academic accommodations is welcome to meet with me privately.  All conversations will be kept confidential.  Students requesting any accommodations will also need to meet with Jason Luchs in the Office of Student Disability Services, who will conduct an intake, and if appropriate, provide an academic accommodation notification letter to you to bring to me.  SDS assists students with disabilities in need of academic and programmatic accommodations as required by the Americans with Disabilities Act of 1990 (ADA) and Section 504 of the Federal Rehabilitation Act of 1973. http://www.newschool.edu/studentservices/disability/.
