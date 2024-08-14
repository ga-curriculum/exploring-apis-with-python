<h1>
  <span class="headline">Exploring APIs with Python</span>
  <span class="subhead">Evaluating APIs</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to critically evaluate API documentation, identify key elements such as API keys, rate limits, endpoints, and data formats, and assess the usability and functionality of APIs through hands-on testing and exploration.

| Lesson          | Duration |
| --------------- | -------- |
| Evaluating APIs | 50 min   |

## Read the Docs

Every API is unique — you will have to explore its documentation to figure out what data you want to access and what URL to use in order to send requests. However, there are a few standard details to check for in any API:

1. Do I need an API key?

   - If so, are there rate limits or charges for requests?
   - How do I include the key in my requests?

2. What are the available endpoints for data?

   - What URL format can search for specific data?

3. What will the response data look like?
   - Typically, the response will be JSON.

## Group Exercise: API Scavenger Hunt 30 min TKTK

APIs open up a whole world of new information to our Python programs. Let’s see just how much information you can find in **Section 7.2** of the workbook.

## Guided Walk-Through: Let's Go API Shopping 15 min TKTK

Using APIs listed in the public-apis project, let's see what to expect from documentation sources.

Here are a few collections of third-party APIs to explore:

- [Awesome APIs](https://github.com/public-apis/public-apis)

- [Public APIs](https://publicapis.dev/)

- [Rapid API](https://rapidapi.com/)

Pro Tips when Evaluating an API:

**Understand the Documentation**: When you first encounter an API, start by exploring the documentation. Focus on the "getting started" section to understand how to make basic GET requests and any key policies you need to follow.

**Assess Usability**: Evaluate how easy the API is to use. Look for clear examples and straightforward instructions. Consider the API's pricing model—does it offer a free tier or have reasonable charges?

**Test the API**: Once you’ve reviewed the documentation, try sending a few test requests to see how the API responds. This will give you a hands-on understanding of its functionality.

**Use Tools Like Postman**: Postman is a great tool for quickly sending requests and evaluating APIs. It provides an intuitive interface that can help you understand how to interact with APIs before writing any code.
