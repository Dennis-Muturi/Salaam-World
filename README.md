

HTML:

```
<!DOCTYPE html>
<html>
<head>
	<title>Scudway Captive Portal</title>
</head>
<body>
	<h1>Welcome to Scudway Network</h1>
	<p>Please read and accept our terms of use before gaining access to the network.</p>
	<hr>
	<h2>Terms of use</h2>
	<p>By using this network, you agree to the following terms:</p>
	<ol>
		<li>You will use the network for legal purposes only.</li>
		<li>You will not engage in any illegal activities on the network.</li>
		<li>You will not share your login information with others.</li>
		<li>You will follow all rules and regulations of the network.</li>
	</ol>
	<hr>
	<h2>Payment Options</h2>
	<p>The following payment options are available:</p>
	<ul>
		<li>$5 for 1 hour of access</li>
		<li>$10 for 3 hours of access</li>
		<li>$15 for 6 hours of access</li>
	</ul>
	<form>
		<h3>Select payment option:</h3>
		<input type="radio" name="payment" value="5">$5 for 1 hour<br>
		<input type="radio" name="payment" value="10">$10 for 3 hours<br>
		<input type="radio" name="payment" value="15">$15 for 6 hours<br><br>
		<input type="submit" value="Pay">
	</form>
</body>
</html>
```

CSS:

```
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

h1 {
	text-align: center;
	margin-top: 50px;
}

h2 {
	margin-top: 50px;
}

ol li {
	margin: 10px 0;
}

ul li {
	margin: 10px 0;
}

form {
	margin-top: 50px;
	text-align: center;
}
```

This code provides a basic layout with network and payment information. It also includes a radio button form allowing users to select their desired payment option. However, integration with payment processing and login authentication would need to be added separately.
