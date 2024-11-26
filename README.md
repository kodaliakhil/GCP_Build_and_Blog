![image](https://github.com/user-attachments/assets/2ec40a54-cd15-4fc9-9447-66fce0a9f30b)


# Personalized Chatbot
In today’s digital age, information is abundant, and efficient access to it is crucial. A website can provide a lot of information, but navigating through the website can be time-consuming. In this blog post, we’ll explore how to build a smart chatbot using Google Cloud Platform (GCP) to make website interactions more efficient and user-friendly.

# Understanding the Problem:
Time-consuming searches: Manually searching through a website for specific information can be tedious and inefficient.
Difficulty in extracting specific information: Finding specific information within a website can be challenging, especially for complex websites like Wikipedia.
Solution: A customized Chatbot for the website

By leveraging the power of Google Cloud Platform, we can create a chatbot that can:

- **Process PDFs**: Upload and store PDFs in a Google Cloud Storage bucket.
- **Extract Text**: Use Google Cloud’s Vertex AI to extract text from PDFs.
- **Understand Queries**: Employ natural language processing techniques to understand user queries.
- **Provide Relevant Answers**: Search through the extracted text to find relevant information and provide concise answers.
# Technical Implementation:
- **Google Cloud Storage**: Create a storage bucket to store the PDFs related to the website.
Use the Google Cloud Storage API to upload and download PDFs.
- **Google Cloud Vertex AI**: Use the Vertex AI API to extract text from PDFs.
Configure the Vertex AI processor to handle multiple PDFs.
- **Dialogflow**: Create a Dialogflow agent to handle user interactions.
Define intents and entities to understand user queries.
Implement fulfillment logic to fetch information from the PDF and provide responses.
- **Frontend**:
Build a web or mobile frontend to interact with the chatbot.
Integrate the Dialogflow agent to display the chatbot interface.

**Deployed at**: https://storage.googleapis.com/rbi-chatbot/GCP_Build_and_Blog/index.html

- Here we took RBI reports to train our chatbot.
- And, we have also taken extra information about RBI from different data sources.
**Reference**: https://www.rbi.org.in/

# Benefits of a Customized Chatbot:
- **Improved User Experience**: Faster and more accurate access to information related to a website.
- **Increased Efficiency**: Automate routine tasks and reduce manual effort.
- **Enhanced Productivity**: Focus on more important tasks by delegating information retrieval.
- **Scalability**: Easily handle increasing numbers of users and documents.
# Project Go Through (Outcome):
https://www.youtube.com/watch?v=u28G7fOsHfc&t=35s
# Conclusion:
By combining the power of Google Cloud Platform and natural language processing, we can create a smart PDF chatbot that can significantly improve the way we interact with websites. This solution can be applied to various industries, including legal, healthcare, and finance, to streamline workflows and enhance productivity.
