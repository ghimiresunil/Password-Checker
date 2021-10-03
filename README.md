# Password-Checker

In this python program, I developed a script that one can use most securely to check if their password has been hacked. 

Many big companies get hacked with data breaches and passwords get leaked all the time. We can check if our password has been leaked through haveibeenpwned but entering our password on another website to check it is not a wise idea. So, I used API provided by haveibeenpwned. The API checks the password through K-anonymity technique so we hash the password and send it to the api through this technique without worrying about the security. 

The script then returns the number of times the password has been found.
