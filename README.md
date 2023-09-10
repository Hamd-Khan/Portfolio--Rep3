

# Obituary Generator 

### Overview

The Obituary Generator Service is a web application built using React and AWS services that allows users to generate obituaries for individuals, whether fictional or real. This service utilizes a combination of technologies, including ChatGPT for obituary generation, Amazon Polly for text-to-speech conversion, and Cloudinary for storage of obituary audio and images.

## Getting Started

To get started with the Obituary Generator Service, follow these steps:

1.Clone this repository to your local machine.

2.Ensure you have Node.js and npm (Node Package Manager) installed.

3.Install the project dependencies

4.Set up your AWS account and obtain necessary API keys and credentials for ChatGPT, Amazon Polly, and Cloudinary 

5.Configure the application as needed

6.Start the development server

### Features

Obituary Generation:Users can input details about the deceased, including name, date of birth and date of passing.The service utilizes ChatGPT to generate an obituary based on the provided information.

Text-to-Speech Conversion: Generated obituaries can be converted into speech using Amazon Polly, creating a more interactive and accessible obituary experience.

Cloud Storage: The obituary audio and an image of the deceased are stored on Cloudinary for easy access and sharing.
Technologies Used

The Obituary Generator Service is built using the following technologies:

React: A JavaScript library for building user interfaces.

AWS: Amazon Web Services, including AWS Lambda, AWS API Gateway, and S3 for serverless architecture and cloud computing.

ChatGPT: Utilized for generating obituaries based on user input.

Amazon Polly: Used for text-to-speech conversion of generated obituaries.

Cloudinary: A cloud-based image and video management platform used for storing audio files and images.