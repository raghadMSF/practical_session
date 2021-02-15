<!DOCTYPE html>
<html lang="en">
  <head>
    <title>PHP Basics</title>
    <style>
      body {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background-color: lightcoral;
      }

      h1,
      p,
      button {
        color: white;
      }

      button {
        height: 30px;
        width: 100px;
        color: blue;
        border-color: blue;
        border-radius: 10px;
      }

      h1 {
        color: black;
      }

      .fullstack{
        color:yellow;
      }

    </style>
  </head>
  <body>
    <h1>Raghad Alsharafi</h1>
    <p id="myparagraph"></p>
    <button onclick="printDate()">Button</button>


  <?php

  class Student {
    public $id;
    public $name;
    public $finished_courses;
    function __construct($id,$name,$finished_courses) {
      $this->id = $id;
      $this->name = $name;
      $this->finished_courses = $finished_courses;
    }
  }

  $student1 = new Student(1,'omar',['Data Structures','Computer Ethics','Calculus I']);
  $student2 = new Student(2,'mohammed',['Fundmentals of Web Design','Interactive Media','Physics I']);
  $student3 = new Student(3,'abdullah',['Operating Systems','Data Structures','Programming Fundmentals']);
  $student4 = new Student(4,'saeed',['Calculus II','Advanced Web Programming','Linear Algebra']);

  $studentsArray = [$student1,$student2,$student3,$student4];

  foreach ($studentsArray as $student) {

    echo "<p>Name: ".$student->name."</p>";
    echo "<p>Id: ".$student->id."</p>";
    
    echo "<ul>";  
    foreach ($student->finished_courses as $course){
      echo "<li>" . $course. "</li>";
    }
    if(in_array('Advanced Web Programming', $student->finished_courses)){
      echo "<p class='fullstack'>This student is full stack developer!</p>";
    }
    echo "</ul>";
  }
  ?>
    <script>
      function printDate() {
        document.getElementById("myparagraph").innerHTML = new Date();
      }
    </script>
  </body>
</html>

    
