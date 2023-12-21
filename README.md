# Gemini Prototype

## What is this?

This is a prototype of a proof of concept for a recommendation to Google. It is a web application that uses Gemini to generate announcements based on inputs such as product change newsletters and different employee positions and regions.

## Getting started

1. Create or open a project in [Google Cloud](https://console.cloud.google.com/)
2. Enable the [Generative Language API](https://console.cloud.google.com/apis/api/generativelanguage.googleapis.com/)
3. Create credentials and copy the API key
4. Add your API key in the `index.html` file, where the `API_KEY` variable is declared
5. Open the `index.html` file in your browser

## Using the program

1. Make sure you are running it from [one of the countries](https://ai.google.dev/available_regions#available_regions) supported by the API
2. Select a newsletter from the dropdown menu
3. Click the `Submit` button
4. Wait 10-15 seconds for the text to be generated
5. Navigate the different combinations of employee position and region by selecting the dropdown menu on the top left
6. Ask any questions you may have to the generated text in the text area and click the `Submit` button next to it
7. Wait 10-15 seconds for the text to be generated
