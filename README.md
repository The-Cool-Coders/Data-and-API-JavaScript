# Data and APIs in JavaScript

### What is an API?

<i>“In computer programming, an application programming interface (API) is a set of subroutine definitions, protocols, and tools for building application software. In general terms, it is a set of clearly defined methods of communication between various software components”</i>

<b>In general, APIs define the rules that programmers must follow in order to interact with a programming language, a software library, or any other software tool.</b> Lately though, the term API is most often used to describe a particular kind of web interface. These Web APIs are a set of rules for interacting with a webserver (such as a Salesforce server), with the most common use case being data retrieval. API’s provide mechanisms for CRM customers to access and manipulate data stored by the API provider (Salesforce in this example). The user makes a “request” to a Salesforce webserver, that webserver accesses a Salesforce database (with the customers data), and returns it to the requester in a “response”.

This same request/response cycle is used when you access webpages in your browser. The major difference between an “API request” and a “webpage request” is what kind of data is provided in the response. A website returns HTML, CSS, and JavaScript which work together with your browser to render a webpage. Web APIs respond with data in a raw format, not intended to be rendered by a browser into a user experience. JSON and XML are the most common formats used for this raw data, and they are both flexible text formats for storing data. Nearly all programming languages have libraries that can “parse” JSON and XML, making them friendly choices for developers. Most modern APIs favor JSON over XML.

### Part 1 : JavaScript Fetch API

- [Fetch API](https://www.javascripttutorial.net/javascript-fetch-api)
- [Promises, Async-Await](https://javascript.info/async)

### Part 2 : Fetching Data from CSV file

- Load CSV File
- Manual Parsing
- HTML Canvas
- [Chart.js](https://www.chartjs.org)


