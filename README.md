
# CommentCrafter : NLP Based YouTube Sentiment Analysis Tool

### Seamless Sentiment Analysis:

CommentCrafter is a web application designed for the effortless sentiment analysis of social media comments, focusing on platforms like YouTube.

### User-Friendly Interface:

The application features an intuitive and user-friendly interface, ensuring a smooth user experience for individuals seeking insights into the sentiment of online comments.

### Input Flexibility:

Users can input post or YouTube video links directly into CommentCrafter, streamlining the process of extracting and analyzing sentiment from relevant comments.

### Advanced Machine Learning Models:

Leveraging advanced Python-based machine learning models, CommentCrafter employs sophisticated algorithms to evaluate and categorize sentiments expressed in comments accurately.

### Efficient Data Management with SQL:

SQL is utilized for efficient data management, ensuring a robust and organized system for handling the vast amount of comments extracted during the sentiment analysis process.

## Features
### YouTube API Integration:
Utilizes the YouTube API to seamlessly fetch comments from YouTube videos, allowing users to analyze sentiments expressed by the audience.
### NLP Model:
Employs advanced Natural Language Processing (NLP) models to accurately evaluate and categorize sentiments within the extracted YouTube comments.
### YouTube Video Transcription:
Provides the functionality to transcribe YouTube videos, offering users the ability to access written content for sentiment analysis alongside the comments.
### YouTube Video Statistics:
Retrieves and displays essential statistics about YouTube videos, enabling users to gain insights into the popularity and engagement levels of the content.
### YouTube Video Summarization:
Summarizes YouTube videos, offering a concise overview of the video's content to aid users in understanding the context surrounding the comments.
### MySQL Database Integration:
Integrates with MySQL for efficient data management, ensuring a robust and organized structure for storing and retrieving data related to sentiment analysis.
### Flask-Powered Backend:
The backend is developed using Flask, a lightweight and extensible web framework in Python, ensuring a responsive and scalable application.
### Python and Machine Learning:
Leverages Python for application development, combining it with machine learning techniques to enhance the accuracy and effectiveness of sentiment analysis.
### Open Source Collaboration:
CommentCrafter is an open-source project, inviting developers and researchers to contribute to its evolution and improvement.

## Operating Enviroment
The Sentiment Analysis system developed in this project has specific hardware and software requirements to operate efficiently.

### Hardware Requirements:

1. A computer system with a multi-core processor (Intel Core i3 or higher)
2. Minimum 8 GB RAM
3.  Database files Stable internet connectivity

### Software Requirements:
1. Operating System: Windows 10 or Higher
2. Python 3 with required libraries, including NLP
3. MySQL Connector MySQL Server 8.0 or higher
4. Flask for developing the GUI interface

## Getting Started
### Prerequisites:
Install Python and Flask
Obtain YouTube API key
Set up MySQL database

### Installation:
1. Clone the repository.
```bash
https://github.com/your-username/CommentCrafter.git
```
2. Install dependencies.
```bash
pip install -r requirements.txt
```
3. Configure YouTube API key and MySQL database settings.
```bash
# Add API key to config.py
YOUTUBE_API_KEY = "your_api_key"

# Configure MySQL database settings in config.py
MYSQL_HOST = "your_host"
MYSQL_USER = "your_user"
MYSQL_PASSWORD = "your_password"
MYSQL_DB = "your_database"
```
4. Run the application.
```bash
python app.py
```
5. Visit in your browser to access CommentCrafter.
```bash
http://localhost:5000 
```


## Screenshots
### Class Digram
This is the class Digram for CommentCrafter
  
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/UML/Class%20Diagram/Class_Diagram_IO_File.png?raw=true)

### ER Digram
This is the ER Digram for CommentCrafter

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/UML/ER/ER_CommentCrafter.png?raw=true)

### Use Case Digram
This is the Data Collection Module for CommentCrafter

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/UML/Use_Case/Data_Collection.png?raw=true)

This is the Deployment Module for CommentCrafter

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/UML/Use_Case/Deployment_Module.png?raw=true)

This is the Sentiment Analysis Module for CommentCrafter

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/UML/Use_Case/Sentiment_Module.png?raw=true)

This is the Summarization Module for CommentCrafter

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/UML/Use_Case/Summary_Module.png?raw=true)

This is the Transcript Module for CommentCrafter

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/UML/Use_Case/Transcript_Module.png?raw=true)

This is the Visualization Module for CommentCrafter

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/UML/Use_Case/Visualization_Module.png?raw=true)

## Project Screenshots

### Home Page

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/HomePage.png?raw=true)

### Sentiment Module

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Sentiment_HomePage.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Sentiment_HomePage_2.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Sentiment_HomePage_3.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Sentiment_HomePage.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Sentiment_HomePage_4.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Sentiment_HomePage_5.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Sentiment_HomePage_6.png?raw=true)

### Transcript Module 

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Transcript_1.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Transcript_2.png?raw=true)

### Visualization Module

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Visualization_1.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Visualization_2.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Visualization_3.png?raw=true)

### Summary Module

![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Summary_1.png?raw=true)
![](https://github.com/SanskarWagavkar/CommentCrafter/blob/master/Summary_2.png?raw=true)


## Contributing
We welcome contributions! Feel free to fork the repository and submit pull requests to enhance the functionality or fix issues.

## Conclusion

The identified drawbacks, including complexity in configurations, reliance on external APIs, and potential scalability challenges, underscore the need for enhancements. By addressing these challenges, the module can evolve into a more user-friendly, adaptable, and efficient solution.
The proposed enhancements, such as intuitive configuration wizards, enhanced scalability features, and a standardized data exchange format, aim to mitigate current limitations and provide users with a more robust and flexible integration experience. These improvements focus on simplifying user interactions, ensuring security, and optimizing performance, ultimately enhancing the module's overall effectiveness.

