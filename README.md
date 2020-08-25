<!doctype html>
<html>
 <head>
  <title>QuickTreat</title>
 </head>
 <body>
  <div class="regform">
  <center><h1>REGISTRATION FORM</h1></center>
  </div>
  <br>
  <br>
  <div class="main">
   <form>
    <div id="name">
	
	 <center><h3 class="name">Enter Hospital Name</h3></center>
	 <center><input class="name" type="text" name="name"></center><br>
	 
	 <center><h3 class="email">Enter Hospital Email</h3></center>
	 <center><input class="email" type="text" name="email"></center><br>
	 
	 <center><h3 class="number">Enter Hospital contact Number</h3></center>
	 <center><input class="code" type="text" name="email"></center><br><br>
	 
	 <center><input type="checkbox" id="hospital" name="hospital" value="check">
     <label for="hospital"> governed by “The Indian Nursing Council, 1985”,.</label></center><br>
	  
	 <center><input type="checkbox" id="hospital" name="hospital" value="check">
     <label for="hospital"> Registration with the municipal authorities </label></center><br> 
	 
    </div>
   </form>   
  </div>   
 </body> 
</html>  
############################################################################################################################################################################
 Status Updation Form
 
 <!DOCTYPE html>
<html>
<head>
	<style >
		form {
  text-align: center;
}
h2{
	text-align: center;
}

	</style>


</head>
<body>

<h2>Hospital Status Updation Form</h2>

<form >

  <label for="regnum">Registration Number: </label>
  <input type="text" id="regnum" name="regnum" ><br>
 
  <label for="Ventilators">Ventilators Available: </label>
    <input type="Number" id="ventnum" name="ventnum" ><br> 
<label for="GenBeds">General Beds Available: </label>
    <input type="Number" id="bednum" name="bednum" ><br> 
    <label for="Isolatward">Isolation Wards Available: </label>
    <input type="Number" id="isonum" name="isonum" ><br> 
     <label for="ICU">ICU: </label>
     <input type="radio" id="icu" name="avbl" value="icu">
  <label for="icu">Yes</label>
  <input type="radio" id="icu" name="avbl" value="icu">
  <label for="icu">No</label>
   <label for="ICU"> Number of Available: </label>
  <input type="Number" id="icu1num" name="icu1num" ><br> 
 

    <h4> Other Facilities</h4>
    
<input type="checkbox" id="Facility2" name="Facility2" value="Laboratory">
  <label for="Facility2"> Laboratory</label><br>
 
  <input type="checkbox" id="Facility3" name="Facility3" value="  PICU (Pediatrics ICU)">
  <label for="Facility3">   PICU (Pediatrics ICU)</label><br>


  <label for="specialistavbl">Available Specialist: </label>
  <select name = "dropdown"> 
  <option value = "Orthopedic Sergon" selected>Orthopedic Sergon</option>
  <option value = "Eye Specialist">Eye Specialist</option>
  <option value = "NeuroSergon">NeuroSergon</option> 

 
   <br>
   <br>
   <br>


   <input type="submit" value="Submit"><br>

  
</form> 

</body>
</html>



