# Review, Research, and Discussion

### - What's the difference between PUT and PATCH?
**PUT** is a method of modifying resource where the client sends data that updates the entire resource .

**PATCH** is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

### - Provide links to 3 services or tools that allow you to "mock" an API for development like json-server

1- [Nock](https://circleci.com/blog/api-mock-testing-nock/)

2- [Postman Mock Server](https://learning.getpostman.com/docs/postman/mock-servers/setting-up-mock/) 

3- [Mockmoon](https://blog.shanelee.name/2021/08/29/mocking-a-rest-api-the-api-first-way-with-mockoon/)

### - Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?  


400 Bad Request – client sent an invalid request, such as lacking required request body or parameter
401 Unauthorized – client failed to authenticate with the server
403 Forbidden – client authenticated but does not have permission to access the requested resource
404 Not Found – the requested resource does not exist
412 Precondition Failed – one or more conditions in the request header fields evaluated to false
500 Internal Server Error – a generic error occurred on the server
503 Service Unavailable – the requested service is not available


### - Compare and contrast SOAP and ReST

- **SOAP** has it langauge, platform and transport-independent, its more standardized, there is built-in error in SOAP API.
- **REST** more efficient. REST uses smaller messages formats like JSON. on the other hand, SOAP uses XML. its faster the SOAP API.

### Discussions

- Which 3 things had you heard about previously and now have better clarity on?  
    APIs , React , async/await 
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?  
    Callbacks , data structure , Promises
- What are you most excited about trying to implement or see how it works?  
    SQL 

### Preparation Materials

- [An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
- [What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)
- [What is TDD?](https://www.agilealliance.org/glossary/tdd/)
- [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

### Bookmark

- [nodeJS docs](https://nodejs.org/en/docs/)
- [npm docs](https://docs.npmjs.com/)
- [express docs](https://expressjs.com/en/4x/api.html)
- [http status codes](https://www.restapitutorial.com/httpstatuscodes.html)
- [supertest](https://github.com/visionmedia/supertest)
