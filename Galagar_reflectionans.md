# Reflection Answers

## 1. What is the difference between GET and POST?
GET is used to request or retrieve data from the server. 
You can see the data in the URL like (?email=test@email.com). 
POST is used to send data to the server and it is hidden 
in the request body so it is more secure than GET.

## 2. Why do we use @csrf in forms?
We use @csrf to protect our form from hackers. 
It adds a hidden token in the form that Laravel checks 
before accepting the form submission. If the token is 
missing or wrong, Laravel will reject the request.

## 3. What is session used for in this activity?
Session is used to save the list of emails temporarily. 
Even if the page reloads, the emails are still there 
because they are stored in the session. Its like a 
temporary memory for the user.

## 4. What happens if session is cleared?
If the session is cleared, all the emails we saved 
will be gone and the list will be empty again. 
It is like the app forgot everything we entered.