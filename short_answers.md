# Short Answer Questions

Shaniah Nizzar
A01199153
midterm for 1620 October 21, 2020


##Q1 Explain what Git and GitHub are. How are they different?

Git is a version control tool where it saves different versions of what you've been working on; it saves your history of working on a project.
GitHub is a tool based on the cloud where you can edit code on a web-based platfrom from anywhere but is
based around Git; it makes it easier for individuals to use Git (platform for it).

##Q2 What is a 'Branch' in Git? How could you create a new branch and what would you commonly use a branch for? 

A branch is what you make when you need to make a change to your work; it's a way for things not to get messy. This keeps things ordered in case
you need to see where you went wrong, it's like saving your work as you go, but with meaningful branch names. You would create a new branch by opening up the command line and making sure you're in the right folder. Once in that folder, you would type "git checkout -b "branch name"". You would use a branch whenever you want to make changes to your work. 

##Q3 What is the http status code you get when a resource is not found? What category of status code does this belong to (other status codes that start with the same number)? Does this status code indicate if the representation is permanent? 

The status code you get when a resource is not found is 404. The error codes that are in the 400s usually have something to do with an error with the client request and that there was a problem with it. The status code 404 means that the resource that was requested was not found and usually this means that it does not exist; so yes, the code should mean that it's permanent. 

##Q4 What is not correct about styling of the given h2 element in the code below? Which color will the h2 be and why? 

The styling is being put into the same area as the h2 element; it should be done in the styling section of the document. It should have been done in correspondence to where the '#school' part is if they wanted the id to be styled in that way. The color of h2 will be red because this is put into the actual code part so it will override what is written in the style section of the code. 

##Q5 List and briefly describe the parts of a URL:

The protocol is the first part of the URL - it is the part that is either "https" or "http". It tells the browser which communication protocol is going to be used in the request. The next part is the domain name and this is the part of the URL that will specify which site you want to go to (eg. google). The top level domain is the part of the URL where it says ".net" or ".com" at the end; it is the last part of the domain name. The last part is called the path because it tells your browser to specifically go someplace and it is placed after the top level domain part (eg.http://google.com/dog_photos). Also, just wanted to mention that the "www." stands for world-wide web and this part usually comes after the protocol. 

##Q6 What is an http header? Provide examples of three http header fields and briefly describe what each does:

HTTP headers allow for communication between the client and server along with a request or response. An example of a header would be the authentication header which you send with a username and password to prove to the server that you belong (eg. Authorization: <type> <credentials>).
Another example would be the clear-site-data header which you would use to clear all history in relation to the website (cookies etc.). The last example is keep-alive which keeps the connection going for as long as you need.

##Q7 Describe the CSS box model? From inside to outside what are the different parts of the box model?

The CSS box model describes the design and layout which is around each HTML element in the document. The box model starts with the content area in the middle where your data (text/images) would be. Next, is the padding area which creates space after the content area. Then, there is the border which wraps around the padding including the content area. Lastly, there is the margin which is similar to padding but creates space around the border.

##Q8 Briefly describe the 4 CSS Combinator selectors that we looked at in class. Provide an example of each. 

The first subject that I'm going to discuss is called the descendant combinator. It is used when you need to choose all descendants of a particular element. Here's an example, it chooses all h1 elements inside of the div element:
`div h1 {
    color: green;
}`
The second one I'm going to discuss is called the child combinator. It is used when you need to choose children of an element. Here's an example that chooses all h1 elements that are children of the div element:
`div > h1 {
    color: green;
}`
The third one I'm going to discuss is the adjacent sibling combinator. It is used when you need to choose all elements which have the same parent and are immediately following. Here's an example that chooses all h1 elements that immediately follow div elements.
`div + h1 {
    color: green;
}`
The last one is called the general sibling combinator. It is used when you need to choose all siblings of a particular element. Here's an example that chooses all h1 elements that are siblings with div elements:
`div ~ h1 {
    color: green;
}`

##Q9 Will these two paragraphs appear on two separate lines? Why? 

The two paragraphs will appear on seperate lines because they are each closed with their own </p> tags. This means that whatever comes next, needs to start on a new line as it will be a different instance of that element (in this example). 

##Q10 Identify and explain two of the errors that exist in the code snippet below. 

The first error is in the img tag because it doesn't have the "alt" part of it. The alt needs to be there in order to describe what the picture is if there was trouble loading it. The second error is in the link tag, it should be <a href="https://bcit.ca">bcit site</a>. There is no title part needed in this as it will make the text that's visible on the page show some of your code. 