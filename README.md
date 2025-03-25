API Projects Through Postman
This repository contains a collection of Postman projects demonstrating various API testing scenarios, including REST and SOAP APIs. Additionally, it showcases the use of Newman, Postman's command-line collection runner, for automated testing.​

Repository Contents
Basic GET Request: A simple collection to demonstrate a basic GET request using Postman.​

E2E Scenario #1: An end-to-end testing scenario covering multiple API interactions.​
Postman Blog
+2
Postman API Platform
+2
GraspIT | Maciej Głownia
+2

Project #1: API Testing - JSON Server (Dummy API): A project utilizing JSON Server to test CRUD operations on a dummy REST API.​

Project #2: SOAP: Demonstrates how to test SOAP APIs using Postman.​
Medium
+4
Postman Blog
+4
Postman Blog
+4

Project #3: Restful Booker (API): A project focused on testing the Restful Booker API, a popular REST API for testing purposes.​

Project #4: Data-Driven Testing: Showcases how to perform data-driven testing in Postman by parameterizing requests with external data sources.​

Working with REST and SOAP APIs in Postman
Postman provides robust support for testing both REST and SOAP APIs.​

REST APIs
REST (Representational State Transfer) is an architectural style that uses standard HTTP methods (GET, POST, PUT, DELETE) for communication. Postman simplifies the process of sending requests and inspecting responses for REST APIs.​
Postman Blog

Example: Sending a GET request in Postman

Open Postman and create a new request.​
Medium
+1
Brian Cline
+1

Set the request method to GET.​

Enter the API endpoint URL.​
Medium

Click "Send" to execute the request and view the response.​

SOAP APIs
SOAP (Simple Object Access Protocol) is a protocol for exchanging structured information in web services. Postman can be used to send SOAP requests by configuring the request method, headers, and body appropriately.​
GraspIT | Maciej Głownia
+1
Postman Blog
+1

Example: Sending a SOAP request in Postman

Create a new request in Postman.​

Set the request method to POST.​

Enter the SOAP API endpoint URL.​
Postman API Platform

In the Headers tab, set Content-Type to text/xml.​

In the Body tab, select "raw" and enter the SOAP XML request.​
Medium

Click "Send" to execute the request and view the response.​

For more detailed guidance on making SOAP requests using Postman, refer to this Postman Blog article.​
Postman Blog
+5
Postman Blog
+5
Postman Blog
+5

Using Newman for Automated Testing
Newman is Postman's command-line collection runner that allows you to run and automate tests created in Postman. It's particularly useful for integrating API tests into CI/CD pipelines.​

Installing Newman

To install Newman, ensure you have Node.js and npm installed, then run:​

bash
Copy
Edit
npm install -g newman
Running a Collection with Newman

To run a Postman collection using Newman:​
Medium
+2
Postman API Platform
+2
GraspIT | Maciej Głownia
+2

bash
Copy
Edit
newman run <collection-file>.json
Replace <collection-file>.json with the path to your Postman collection file.​

Example: Running a Collection with Environment Variables

If your collection requires environment variables:​

bash
Copy
Edit
newman run <collection-file>.json -e <environment-file>.json
This command runs the specified collection using the provided environment variables.​

For more information on using Newman, visit the official Postman documentation.​

Conclusion
This repository serves as a practical guide for testing various APIs using Postman and Newman. By exploring the included projects, you can gain hands-on experience with REST and SOAP APIs, as well as learn how to automate your testing workflows effectively.​

