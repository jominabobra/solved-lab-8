Download Link: https://assignmentchef.com/product/solved-lab-8
<br>
<strong>Instructions:</strong>

<ul>

 <li>Upload your solution to the link provided on the course page.</li>

 <li>Create one NetBeans project for the 2 problems below.  The project name should be          Project Name:  Lab8_&lt;lastname_firstname&gt;</li>

</ul>

Example:         <strong>Lab8_Blanco_Maria</strong>

<ul>

 <li>Compress the NetBeans project into .rar or .zip format.</li>

 <li>The class names to be created are specified in each problem.</li>

 <li>There should only be one main class (the class that contains the main method) where the implementation of the 2 problems will be done. Name it as <strong>Lab8Main</strong>.  Follow the project structure below.</li>

 <li><strong>Only NetBeans project compressed in .rar or .zip format will be accepted.</strong></li>

</ul>

<ol>

 <li><strong> Extending StudentRecord</strong></li>

</ol>

<strong> </strong>Class Names:      <strong>Lab8Main (main class)</strong>

<strong>StudentRecord</strong>

<strong>                             ComputerScienceStudentRecord</strong>

<strong> </strong>The StudentRecord class is given for your reference.  The following are your tasks:

<ul>

 <li><em>Overload</em> the StudentRecord constructor with one that accepts 4 parameters namely the name, mathGrade, englishGrade and scienceGrade.</li>

 <li>Create a class that will inherit the attributes and methods of the StudentRecord class and name it ComputerScienceStudentRecord. Use the <strong>extends</strong> keyword for inheritance.</li>

 <li>The ComputerScienceStudentRecord class will only have a comprogGrade attribute of double data type.  Its constructor should accept 5 parameters namely the name, mathGrade, englishGrade, scienceGrade and comprogGrade.</li>

 <li>Inside the ComputerScienceStudentRecord constructor, use the <strong>super</strong> keyword to call on the constructor of the StudentRecord and be able to assign the first 4 parameters. The value of the last parameter will be assigned to comprogGrade.</li>

 <li><em>Override</em> the computeAverageGrade method of the StudentRecord class in the ComputerScienceStudentRecord class. The result should be the average grade from the 4 subjects, Math, English, Science and Computer Programming.</li>

 <li>Create a class that would contain the main method and name it Lab8Main. In the main method, instantiate a ComputerScienceStudentRecord object that has 5 parameters.   The sample output is shown below.</li>

</ul>

public class StudentRecord {

//these are the attributes

private String name;

private double mathGrade;

private double englishGrade;

private double scienceGrade;

//this is the constructor

public StudentRecord(){

this.name=””;

this.mathGrade=0;

this.englishGrade=0;

this.scienceGrade=0;

}

<table width="714">

 <tbody>

  <tr>

   <td rowspan="2" width="359"></td>

   <td width="132">Course Code</td>

   <td width="222">Type Course Code Here</td>

  </tr>

  <tr>

   <td width="132">Description</td>

   <td width="222">Computer Programming 2</td>

  </tr>

  <tr>

   <td width="359">College / Department:<strong>Online Education</strong></td>

   <td width="132">LaboratoryExercise No.</td>

   <td width="222">008</td>

  </tr>

  <tr>

   <td colspan="2" width="492"><strong>LABORATORY EXERCISE</strong></td>

   <td width="222">Page 2 of 4</td>

  </tr>

 </tbody>

</table>

//these are the mutators and accessors

public String getName() {

return name;

}

public void setName(String name) {

this.name = name;

}

public double getMathGrade() {

return mathGrade;

}

public void setMathGrade(double mathGrade) {

this.mathGrade = mathGrade;

}

public double getEnglishGrade() {

return englishGrade;

}

public void setEnglishGrade(double englishGrade) {

this.englishGrade = englishGrade;

}

public double getScienceGrade() {

return scienceGrade;

}

public void setScienceGrade(double scienceGrade) {

this.scienceGrade = scienceGrade;

}

//custom method

public double computeAverageGrade(){

return (this.mathGrade + this.englishGrade + this.scienceGrade)/3;

}

}




<table width="714">

 <tbody>

  <tr>

   <td rowspan="2" width="359"></td>

   <td width="132">Course Code</td>

   <td width="222">Type Course Code Here</td>

  </tr>

  <tr>

   <td width="132">Description</td>

   <td width="222">Computer Programming 2</td>

  </tr>

  <tr>

   <td width="359">College / Department:<strong>Online Education</strong></td>

   <td width="132">LaboratoryExercise No.</td>

   <td width="222">008</td>

  </tr>

  <tr>

   <td colspan="2" width="492"><strong>LABORATORY EXERCISE</strong></td>

   <td width="222">Page 3 of 4</td>

  </tr>

 </tbody>

</table>

Sample Output:




<table width="714">

 <tbody>

  <tr>

   <td rowspan="2" width="359"></td>

   <td width="132">Course Code</td>

   <td width="222">Type Course Code Here</td>

  </tr>

  <tr>

   <td width="132">Description</td>

   <td width="222">Computer Programming 2</td>

  </tr>

  <tr>

   <td width="359">College / Department:<strong>Online Education</strong></td>

   <td width="132">LaboratoryExercise No.</td>

   <td width="222">008</td>

  </tr>

  <tr>

   <td colspan="2" width="492"><strong>LABORATORY EXERCISE</strong></td>

   <td width="222">Page 4 of 4</td>

  </tr>

 </tbody>

</table>

<ol start="2">

 <li><strong> The Shape Abstract Class</strong></li>

</ol>

<strong> </strong>Classes Names: <strong>Lab8Main (main class)</strong>

<strong>Shape</strong>

<strong>                                Circle</strong>

<strong>                                Square</strong>

<strong> </strong>Create an abstract class called Shape with abstract methods getArea() and getName().  Write two of its subclasses Circle and Square.  Override these methods in the Circle and Square classes.  In the main method (LabExercise8 class), instantiate an object of the Circle class of radius 4 units, and an object of the Square class of side 5 units.  The sample output is shown for your reference.

Sample Output: