# code2040
Code 2040 Fellows

About APIs

APIs are essential to building interesting software. An API, or Application Programming Interface, allows one system to communicate with another. By agreeing on a common set of vocabulary -- the “interface” -- these systems can be built and maintained by completely different people, at completely different times.

Github

Setting up a Github repository for a software project makes it easy to keep track of your changes and share your work with employers. To get started, create a new public repository for the code you’ll use in this project. If you’re new to Github, this guide will help you get your project online.

Make sure your project shows off code for each step of the challenge you complete. If you build an interesting user interface, make sure to include screenshots in your repository’s readme file.

Step I: Registration

To get started, you’re first going to connect to the registration endpoint. It lives here:

http://challenge.code2040.org/api/register

The registration endpoint expects a JSON dictionary with two keys, token and github. This JSON should be sent in the body of your HTTP request.

For token, pass in a string with the token you see above. For github, pass in the URL of the repository you created in the last step.

Hint: HTTP has a few types of “methods.” The registration endpoint is going to be expecting you to use POST to send your JSON.
