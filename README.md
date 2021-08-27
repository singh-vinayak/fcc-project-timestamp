
# [Timestamp Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice)
This is a Node.js (with Express.js) little application which is part of the FCC Back End Certification. It takes a date string and gives you back a JSON with Unix value and natural format for the given date.
> Cheers from Kanpur (India), Vinayak Singh

# User stories:
> 1. I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016)
> 2. If it does, it returns both the Unix timestamp and the natural language form of that date.
> 3. If it does not contain a date or Unix timestamp, it returns null for those properties.

Example usage:
```
https://boilerplate-project-timestamp.vinayaksingh530.repl.co/api/December%2015,%202015
https://boilerplate-project-timestamp.vinayaksingh530.repl.co/api/1450137600
```
Example output:
```
{ "unix": 1450137600, "natural": "December 15, 2015" }