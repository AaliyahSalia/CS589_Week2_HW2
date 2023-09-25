
**Google Slides: **

# Customer Support Chatbot

This is a web-based chatbot created for a CS589 class assignment to answer customer questions about a website.

## Overview

The chatbot uses:

- Node.js for the web server  
- OpenAI's GPT-3 API for natural language processing
- React for the front-end UI

Users can ask questions through a browser interface. The chatbot queries GPT-3 to generate answers based on example website FAQs and conversations provided in the training data.

## Steps

The steps I took were:

1. Set up a Python script to query GPT-3.

2. Create a Node.js webserver with Express.

3. Build a React front-end for the chat UI.

4. Connect the React front-end to the Node.js back-end.

5. Deploy the web server on Ubuntu.

## Usage 

To run the chatbot locally:

1. Clone the repo
2. Install dependencies with `npm install`
3. Update API Key in `.env` file 
4. Install dependencies with `npm install`
5. Run the project with `npm run dev`
6. Go to `http://localhost:3000` in a browser

## References

References: https://hc.labnet.sfbu.edu/~henry/sfbu/course/machine_learning/chatgpt/slide/exercise_chatgpt.html
https://hc.labnet.sfbu.edu/~henry/sfbu/course/machine_learning/chatgpt/slide/quickstart.html#Quickstart%20-%20Node.js
https://hc.labnet.sfbu.edu/~henry/sfbu/course/javascript/node_js/course/nodeschool/learnyounode/node_python.html

