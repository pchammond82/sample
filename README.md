<form class="form-signin" method="POST" action="https://pchammond82.github.io/sample/endpoint_example">
  <h2 class="form-signin-heading">Please sign in</h2>
  <input class="form-control" type="text" required name="email" placeholder="Email address">
  <input class="form-control" type="password" required name="password" placeholder="Password">
  <label class="checkbox"></label>
  <button class="btn btn-lg btn-primary btn-block" type="submit">Sign in</button>
</form>




# WELCOME TO MY LANDING PAGE
<html>
<body>

<h2>Please submit the form to save your information in my database</h2>
<div class="container-fluid">
	<div class="row">
		<div class="col-md-12">
<form id="form" action="https://forms.hubspot.com/uploads/form/v2/2211982/406681a7-9be2-4477-909d-1daf6a76fe08" method="POST">
  First name:<br>
  <input type="text" name="firstname" placeholder="First Name"><br>
  Last name:<br>
  <input type="text" name="lastname" placeholder="Last Name"><br>
  Email:<br>
  <input type="email" name="email" placeholder="Your Email"><br>
  
  <input type="submit" value="Submit"> 
</form>
		</div>
	</div>
</div>

<script>
	//Javascript for the form
	//when the user submits the form we want to wait until the API responds (AJAX call), and if it's ok let's show a nice message to the user
	//reference: https://blog.garstasio.com/you-dont-need-jquery/ajax/#posting
	
	//let's save a reference to the form on a variable
	var formElement = document.getElementById('form');
	
	//Add an event listener whenever the form is submitted
	formElement.addEventListener("submit", function(e){
        	//let's prevent HTML's default form functionality when form is submitted (in this case the redirection)
		e.preventDefault();
		//let's save the form data on a variable using the FormData constructor 
        	var data = new FormData(formElement); 
        	
		//Here we create the XML request object which will give us all the functionality to deal with the AJAX call
        	var request = new XMLHttpRequest();
        
		//Whenever this request 
		request.onreadystatechange = function(){
		  //document.getElementById("result").innerText = request.responseText
		  console.log('request.responseText',request.responseText);
		}
        	
		//Lets open a request and send the data
		request.open(formElement.method, formElement.action);
		request.send(data);
      });
</script>

</body>
</html>


