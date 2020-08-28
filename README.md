# form-elements
<h2>Application Form</h2>

<form action="/action_page.php">
  <label for="name">Name:</label><br>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="number">Phone Number:</label><br>
  <input type="number" id="fnumber" name="fnumber"><br><br>
  <label for="Choice of Course">Choice of Course:</label><br>
  <label> Bachelors </label> 
  <input type="radio" id="rbachelors" name="Bachelors" name="Bachelors"><br>
  <label> Masters </label> 
  <input type="radio" id="rmasters" name="Masters" name="Masters"><br>
<h3>Description</h3>
<form action="/action_page.php">
   <textarea name="message" rows="5" cols="10">
   My name is Navya Palle.
   </textarea>
<h4>Subjects Interests</h4>
<form action="/action_page.php">
   <label>VLSI</label>
   <input type="checkbox" id="development"value="interest_development"name="VLSI">
   <label>OC</label>
   <input type="checkbox" id="development"value="interest_development"name="OC">
    <label>AWP</label>
   <input type="checkbox" id="development"value="interest_development"name="AWP"><br></br>
<input type="submit" value="Submit">
</form>

</body>
</html>
