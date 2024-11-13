# Project: Guess the Famous Quote

**Project Description**:  
Students will develop a small interactive application where users are presented with a random quote and must guess who said it by selecting from a list of options. The app will send requests to an external API to retrieve famous quotes. This project introduces students to handling HTTP requests and working with APIs, allowing them to experience request methods and interaction with a RESTful endpoint.

## Key Features

1. **Quote Retrieval**:
   - Use a public API to retrieve a random quote.

2. **Answer Options**:
   - Automatically generate a set of answer options, with one correct answer.

3. **User Scoring**:
   - Track the user’s score by adding points for each correct answer.

4. **Immediate Feedback**:
   - Provide instant feedback after each attempt, indicating whether the selected answer was correct or not.

## Learning Objectives

- **API Request Handling**: Send HTTP requests to a RESTful API to fetch external data.
- **API Response Processing**: Extract and display data from the API response.
- **Application Interactivity**: Manage user responses and update the interface dynamically.
- **State Management**: Track scores and attempt counts in an application without using frameworks.

## Technical Specifications

- **API**: Use the Quotable Quotes API or another public quote API to retrieve famous quotes.
- **User Interface**:
  - Build a simple UI using HTML and CSS to display the quote and provide answer options.
- **HTTP Requests**: Use the `fetch` API to send HTTP requests and retrieve quotes.
- **Interactive Feedback**:
  - Provide instant feedback to the user for each response and update the score accordingly.

### Resources

- **Quotable API Documentation**: [https://github.com/lukePeavey/quotable](https://github.com/lukePeavey/quotable)
- **MDN fetch() Documentation**: [https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
- **JavaScript Event Handling**:
  - MDN Docs on Event Handling: [https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
- **Basic JavaScript State Management**:
  - Article on managing state in Vanilla JavaScript: [https://dev.to/josephlbarnett/simple-state-management-with-vanilla-javascript-3f76](https://dev.to/josephlbarnett/simple-state-management-with-vanilla-javascript-3f76)
