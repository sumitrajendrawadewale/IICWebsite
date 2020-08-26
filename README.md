**Registration Page**

<!doctype html>
<html>
 <head>
  <title> QuickTreat</title>
  <style type="text/css">
  {
  margin:0;
  padding:0;
  }
  body
  {
  background-image:url(wallpaper.jpg);
  background-position:center;
  background-size:cover;
  font-family:sans-serif;
  margin-top:40px;
  }
  .regform{
  width:600px;
  background-color:rgb(0,0,0,6);
  margin:auto;
  color:#FFFFFF;
  padding:5px 0px 5px 0px;
  text-align:center;
  border-radius:15px 15px 0px 0px;
  }
  .main
  {
  background-color:rgb(0,0,0,0.5);
  width:600px;
  margin:auto;
  color:#FFFFFF;
  }
  
  </style>
 </head>
 <body>
  <div class="regform">
  <center><h1><br>REGISTRATION</h1></center>
  </div>
  <div class="main">
   <form>
   <table background >
    <div id="name">
	<br>
	 <tr>
	 <td><center><h3 class="name">Enter Hospital Name</h3></center></td>
	 <td><center><input class="name" type="text" name="name"></center></td>
	 </tr>
	 
	 <tr>
	 <td><center><h3 class="number">Enter Hospital contact Number</h3></center></td>
	 <td><center><input class="code" type="text" name="number"></center></td>
	 </tr>	
	 
     <tr>
	 <td><center><h3 class="number">Enter Hospital Email</h3></center></td>
	 <td><center><input class="code" type="text" name="number"></center></td>
	 </tr>
	 
	 <tr>
	 <td><center><h3 class="number">Enter Password</h3></center></td>
	 <td><center><input class="code" type="text" name="number"></center></td>
	 </tr>
	 
	 <tr>
	 <td><center><h3 class="email">Conform Entered Password</h3></center></td>
	 <td><center><input class="email" type="text" name="email"></center></td>
	 </tr>
	 
   	</table>
	
	<br>
	
	<table> 
	 <tr>
	 <td><input type="checkbox" id="hospital" name="hospital" value="check">
     <label for="hospital"> Governed by “The Indian Nursing Council, 1985”,.</label></td>
	 </tr>

	 <tr>
	 <td><center><input type="checkbox" id="hospital" name="hospital" value="check">
     <label for="hospital"> Registration with the Municipal Authorities </label></center></td>
	 </tr>
	
	 <tr>
	 <td><center><br><button type="submit">REGISTER</button></td>
	 <td><center><button type="submit">LOG IN</button></center></td>
	 </tr>
	 
	</table>
    </div>
   </form>   
  </div>   
 </body> 
</html>


############################################################################################################################################################################

**LOG IN PAGE**

<!doctype html>
<html>
 <head>
  <title> QuickTreat</title>
  <style type="text/css">
  {
  margin:0;
  padding:0;
  }
  body
  {
  background-image:url(wallpaper.jpg);
  background-position:center;
  background-size:cover;
  font-family:sans-serif;
  margin-top:40px;
  }
  .regform{
  width:600px;
  background-color:rgb(0,0,0,6);
  margin:auto;
  color:#FFFFFF;
  padding:5px 0px 5px 0px;
  text-align:center;
  border-radius:15px 15px 0px 0px;
  }
  .main
  {
  background-color:rgb(0,0,0,0.5);
  width:600px;
  margin:auto;
  color:#FFFFFF;
  }
  
  </style>
 </head>
 <body>
  <div class="regform">
  <center><h1><br>LOG IN</h1></center>
  </div>
  <div class="main">
   <form>
   <table background >
    <div id="name">
	<br>
	 <tr>
	 <td><center><h3 class="name">Enter Hospital Name</h3></center></td>
	 <td><center><input class="name" type="text" name="name"></center></td>
	 </tr>
	 
	 
	 <tr>
	 <td><center><h3 class="number">Enter Password</h3></center></td>
	 <td><center><input class="code" type="text" name="number"></center></td>
	 </tr>
	 
   	</table>
	
	<br>
	
	<table> 
	 
	 <tr>
	 <center><button type="submit">LOG IN</button></center>
	 </tr>
	 
	</table>
    </div>
   </form>   
  </div>   
 </body> 
</html>  
 
 
############################################################################################################################################################################
 
 **Status Updation Form**
 
 <!DOCTYPE html>
<html>

<head>
  <title>QuickTreat</title>
  <style type="text/css">
  {
  margin:0;
  padding:0;
  }
  body
  {
  background-image:url(Background.jpg);
  background-position:center;
  background-size:cover;
  font-family:sans-serif;
  margin-top:40px;
  }
  .updtform{
  width:600px;
  background-color:rgb(0,0,0,6);
  margin:auto;
  color:#FFFFFF;
  padding:5px 0px 5px 0px;
  text-align:center;
  border-radius:15px 15px 0px 0px;
  }
  .content
  {
  background-color:rgb(0,0,0,0.5);
  width:600px;
  height: 450px;
  padding:25px 0px 5px 0px;
  margin:auto;
  color:#FFFFFF;
  }
  
  </style>
</head>
<body>
  <div class="updtform">
<h2>Hospital Status Updation Form</h2>
</div>
<div class="content">
<form action="confirmupdation.html"><center>
  <table background >
    <div id="name">
  
<tr>
 <td> <label for="regnum">Registration Number: </label> </td>
  <td> <input type="text" id="regnum" name="regnum" > <br></td>
 </tr>
<tr>
     <td><label for="specialistavbl">Available Specialist: </label></td>
  <td><select name = "dropdown"> 
  <option value = "Orthopedic Sergon" selected>Orthopedic Sergon</option>
  <option value = "Eye Specialist">Eye Specialist</option>
  <option value = "NeuroSergon">NeuroSergon</option>  
  <option value = "Gynacologist">Gynacologist</option>
 <option value = "ENT">ENT Specialist</option></td>
  </tr>

 <tr>
   <td><label for="Ventilators">Ventilators Available: </label> </td>
   <td>  <input type="Number" id="ventnum" name="ventnum" > <br> </td>
    </tr>


    <tr>
 <td><label for="GenBeds">General Beds Available: </label> </td>
    <td> <input type="Number" id="bednum" name="bednum" ><br>  </td>
    </tr>
    <tr>
   <td><label for="ctscan">CT Scan Machine Available: </label> </td>
   <td>  <input type="Number" id="CTnum" name="CTtnum" > <br> </td>
    </tr>

    <tr>
   <td> <label for="Isolatward">Isolation Wards Available: </label></td>
    <td><input type="Number" id="isonum" name="isonum" ><br> </td>
</tr>
<tr>
     <td><label for="ICU">ICU: </label></td>
    
  <td><input type="Number" id="icu1num" name="icu1num" ><br> </td>
     </tr>
     

  <tr>
     <td><label for="specialistavbl">Blood Availability: </label>
      <select name = "dropdown"> 
  <option value = "a" >A+</option>
  <option value = "b">A-</option>
  <option value = "c">B+</option>
  <option value = "c">B-</option> 
  <option value = "c">AB+</option> 
  <option value = "c">AB-</option> 
  <option value = "c">O+</option> 
  <option value = "c">O-</option>  </td>
  <td> <input type="Number" id="Blood" name="Blood" ><br>  </td>

  </tr>
     </table>

    <h4> Other Facilities:</h4>
     <table>
    <tr>
<td><input type="checkbox" id="Facility2" name="Facility2" value="Laboratory"></td>
  <td><label for="Facility2"> Laboratory</label><br></td>
 </tr>
 <tr>
 <td> <input type="checkbox" id="Facility3" name="Facility3" value="  PICU (Pediatrics ICU)"></td>
 <td> <label for="Facility3">   PICU (Pediatrics ICU)</label><br></td>
</tr>
 </table>
 <table>
  <tr>
  <td><label for="addfacility">Add other facilities available: </label> </td>
  <td> <input type="text" id="addfacility" name="addfacility" > <br></td>
</tr>
</table>
  <br>


   <input type="submit" value="Submit"><br>

  </center>
</div>
</form> 
</div>
</body>
</html>
########################################################################################################
**Confirm updation Message**

<!DOCTYPE html>
<html>
<head>
	<title>QuickTreat</title>
</head>
<body>
<h3> Thank You for updating the status of your hospital. Soon, overall network of QuickTreat will get updated with latest status.</h3>
</body>
</html>

 


