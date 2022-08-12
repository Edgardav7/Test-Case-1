# Test-Case-1
Test-Case-1
Sign up window				
Number	Name	Steps	Expected Result	Status
1	Create Account	click on Sign in	the Log in to Cointrack tab opens	passed
		click on sign up next to the input tab	the Create Account tab opens	passed
				
				
				
Number	Name	Steps	Expected Result	Status
2	Registration with non-existent mail	Fill in the email field  " edgardav1234@gmail.com "	mail field is filled	passed
		fill in the password field " 123456 "	password field is filled	passed
		click on Sign Up	registration failed	failed
				
				
				
Number	Name	Steps	Expected Result	Status
3	Registering with an existing password	fill in the email field  " edgardavidyan88@gmail.com "	mail field is filled	passed
		fill in the password field " 123456 "	password field is filled	passed
		click on Sign Up	registration completed successfully	passed
				
				
				
Number	Name	Steps	Expected Result	Status
4	Register password with less than 6 characters	fill in the email field  " edgardavidyan86@gmail.com "	mail field is filled	passed
		fill in the password field " 000 "	"a warning appears
""At least 6 characters"""	passed
				
				
				
Number	Name	Steps	Expected Result	Status
5	"Registration with a password that does not contain Latin letters
"	fill in the email field  " edgardavidyan87@gmail.com "	mail field is filled	passed
		fill in the password field " Армения "	"a warning appears
""Password must contain latin letters"""	failed
				
				
				
Number	Name	Steps	Expected Result	Status
6	Authorization check	click on Sign in	the Log in to Cointrack tab opens	passed
		fill in the email field  " edgardavidyan88@gmail.com "	mail field is filled	passed
		fill in the password field " 123456 "	password field is filled	passed
		click on Log in	account login in progress	passed
				
				
				
Number	Name	Steps	Expected Result	Status
7	Password reset	click on " Sign in "	the Log in to Cointrack tab opens	passed
		click on " forgot password ? "	password recovery tab opens	passed
		fill in the email field  " edgardavidyan88@gmail.com "	mail field is filled	passed
		click on the "Recover Password" button	text appears check your mail	passed
		go to the received letter	an email opens with a link to reset your password	passed
		click on the link in the email	password reset window opens	passed
		fill in the password field " D123asd "	password field is filled	passed
		fill in the confirm password field " D123asd "	confirm password field is filled	passed
		click on " Reset "	password changed succesfully	passed
				
				
				
Number	Name	Steps	Expected Result	Status
8	Correct login with capital letters	click on " Sign in "	the Log in to Cointrack tab opens	passed
		fill in the email field  " EDGARDAVIDYAN88@GMAIL.COM "	mail field is filled	passed
		fill in the password field " D123asd "	password field is filled	passed
		click on Log in	Invalid credentials	failed
				
				
				
Number	Name	Steps	Expected Result	Status
9	Correct password with capital letters	click on " Sign in "	the Log in to Cointrack tab opens	passed
		fill in the email field  " edgardavidyan88@gmail.com "	mail field is filled	passed
		fill in the password field " D123ASD "	password field is filled	passed
		click on Log in	Invalid credentials	passed
				
				
Comprehensive check				
Number	Name	Steps	Expected Result	Status
10	"Correct login - incorrect password
"	click on " Sign in "	the Log in to Cointrack tab opens	passed
		fill in the email field  " edgardavidyan88@gmail.com "	mail field is filled	passed
		fill in the password field " d123asd "	password field is filled	passed
		click on Log in	Invalid credentials	passed
				
				
				
Number	Name	Steps	Expected Result	Status
11	"Correct password - incorrect login
"	click on " Sign in "	the Log in to Cointrack tab opens	passed
		fill in the email field  " edgardavidyan77@gmail.com "	mail field is filled	passed
		fill in the password field " D123asd "	password field is filled	passed
		click on Log in	Invalid credentials	passed
				
				
				
Number	Name	Steps	Expected Result	Status
12	Correct username and password - all capital letters	click on " Sign in "	the Log in to Cointrack tab opens	passed
		fill in the email field  " EDGARDAVIDYAN88@GMAIL.COM "	mail field is filled	passed
		fill in the password field " D123ASD "	password field is filled	passed
		click on Log in	Invalid credentials	passed
