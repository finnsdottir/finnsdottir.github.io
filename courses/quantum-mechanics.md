---
layout: page
title: "Quantum Mechanics"
---

#### Course Information

[Course Outline](/courses/quantum-mechanics/Sample_Course_Outline.pdf)

#### Lecture Notes

[Lecture 1](/courses/quantum-mechanics/Sample_Lecture_Notes.pdf)

[Lecture 2](/courses/quantum-mechanics/Sample_Lecture_Notes.pdf)

[Lecture 3](/courses/quantum-mechanics/Sample_Lecture_Notes.pdf)

#### Homework

[Homework 1](/courses/quantum-mechanics/Sample_Lecture_Notes.pdf)

[Homework 2](/courses/quantum-mechanics/Sample_Lecture_Notes.pdf)

[Homework 3](/courses/quantum-mechanics/Sample_Lecture_Notes.pdf)

#### Midterms

[Midterm 1](/courses/quantum-mechanics/Sample_Midterm.pdf)

[Midterm 2](/courses/quantum-mechanics/Sample_Midterm.pdf)

#### Exams

[Exam 1](/courses/quantum-mechanics/Sample_Exam.pdf)


code for reading through courses
<div class="row g-5 mb-5">
  <div>
    <h3 class="fw-bold border-bottom pb-3 mb-5">Courses</h3>
    {% for course in site.data.settings.courses %}
      <p><a href="{{ site.github.url }}/courses/{{ course.url}}">{{ course.name }}</a></p>
    {% endfor %}
  </div>
</div>

and in the settings page: 
courses:
- {name: 'Vector Calculus', url: 'vector-calculus'}
- {name: 'Quantum Mechanics', url: 'quantum-mechanics'}
- {name: 'Stellar Structures', url: 'stellar-structures'}

<div class="row g-5 mb-5">
  <div>
    <h3 class="fw-bold border-bottom pb-3 mb-5">Undergraduate Courses</h3>
      <p><a href="./courses/syllabi/SOCI215_syllabus.pdf">Class and Social Inequality</a></p>
      <p><a href="./courses/syllabi/SOCI438_syllabus.pdf">Special Topics in Sociology: Democratic Decline, Citizenship, and Gender</a></p>
      <p><a href="./courses/syllabi/SOC340H1S_syllabus.pdf">Comparative Political Sociology</a></p>
      <p><a href="./courses/syllabi/SOC360H1S_syllabus.pdf">Social Movements</a></p>
    </div>
</div>

<div class="row g-5 mb-5">
  <div>
    <h3 class="fw-bold border-bottom pb-3 mb-5">Workshops</h3>
      <p><a href="https://finnsdottir.github.io/openrefine_fall2025/">Introduction to OpenRefine</a></p>
      <p><a href="https://finnsdottir.github.io/intro_r_fall2025/">Introduction to R & RStudio</a></p>
  </div>
</div>

