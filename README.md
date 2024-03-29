# Youtube-Watcher
The YouTube Watcher Application is a Python-based tool designed to monitor the view count of a YouTube video and notify the user via email when a specified threshold is crossed. This application is particularly useful for tracking the popularity of videos during events  for retrieving live data for analytical purposes.
*Web_DA project has code for the website and web scraping
*DA project is code just for webscarping with comments for understanding
# Features
-YouTube URL Input: Users can provide the URL of the YouTube video they wish to monitor through a user-friendly interface. This URL serves as the source for extracting view count data.

-Threshold Setting: Users can define a threshold value that triggers an email notification when the view count surpasses it. This feature enables users to stay updated on the popularity of a video and react promptly.

-CSV Logging: The application automatically logs the view count and timestamp data into a CSV file for later analysis. This feature allows users to track the video's performance over time and conduct further statistical analysis.

-Email Notification: When the view count exceeds the defined threshold, the application sends an automated email to the user. This email provides real-time information about the video's popularity, ensuring users can make informed decisions quickly.

# Libraries Used
The YouTube Watcher Application utilizes the following Python libraries:

Beautiful Soup: Used for web scraping, Beautiful Soup enables the application to extract relevant data from the YouTube video page, such as the view count.

Requests: The Requests library is used to send HTTP requests to the YouTube website and retrieve the necessary HTML content for parsing with Beautiful Soup. It facilitates the communication between the application and the YouTube server.

SMTP: The SMTP library is employed for sending email notifications. It enables the application to connect to an email server and deliver messages to the user's specified email address.

Time: The Time library allows for scheduling the execution of the script at regular intervals, ensuring the application continually monitors the view count.

CSV: The CSV library is used to store the view count and timestamp data in a structured format. This enables users to access historical data for analysis and tracking purposes

Flask: Flask is a web framework for Python that allows you to build web applications. It provides tools and libraries to handle routing, request handling, template rendering, and more, making it easier to develop web-based applications.

Threading: The threading module is a built-in Python library that allows you to create and manage threads in your application. Threads are used to execute multiple tasks concurrently, allowing for improved performance and responsiveness in certain scenarios

# How to use:
To use the YouTube Watcher Application, follow these steps:
1)Clone the project
2)
# Contribution
Contributions to the YouTube Watcher Application are welcome! If you encounter any issues, have suggestions for improvements, or would like to add new features, please submit a pull request on GitHub. Your contributions will help enhance the functionality and usability of the application.

# License
The YouTube Watcher Application is open-source software released under the MIT License. Feel free to modify and distribute the application, ensuring to include the original license and attribution.

# Disclaimer
The YouTube Watcher Application is not affiliated with or endorsed by YouTube. It is an independent tool created for personal use, and users should comply with YouTube's terms of service and guidelines when utilizing this application.

Enjoy monitoring YouTube videos effortlessly with the YouTube Watcher Application! If you have any questions or feedback, please don't hesitate to reach out.

# Link for finding the right password to avoid authentication error
https://www.getmailbird.com/gmail-app-password/
Use the app-password generated in this and not your normal login password

I have added some sample screenshots of the csv file and email I have receieved
