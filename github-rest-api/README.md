# github rest api

Write a script which uses GitHub’s REST API to retrieve the following information from a 
public, Teradici-owned GitHub repository: 
1. Display the “Author Name” and total number of commits for the user who has made the 
most commits for all time 
2. Count the number of commits which occurred during the period from June 1, 2019 – May 
31, 2020 and print the total.
3. Create a Dockerfile that allows us to build a docker container and execute the tool with docker run without having any dependencies other than docker installed 

The above information must be retrieved from the GitHub repository at 
https://github.com/teradici/deploy. Please note that these APIs can be accessed anonymously 
and do not require authentication. The following resources will be useful: 
- GitHub commits API: https://developer.github.com/v3/repos/commits/ 
- general GitHub API documentation: https://developer.github.com/v3/ 
- Python requests library to help with making HTTP requests: http://docs.python-
requests.org/en/master/ (if you are using Colaboratory, this library is already available to be imported; otherwise you will need to install it locally in some fashion) 