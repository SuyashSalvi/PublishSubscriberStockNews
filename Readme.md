Stock Market Notifications System Using Publisher-Subscriber Mechanism

Overview

This project implements a real-time stock market notification system using a Publisher-Subscriber (Pub-Sub) mechanism to deliver instant stock updates to traders and investors. The system is built with Express.js, Spring Boot, React.js, and MongoDB, ensuring scalability, efficiency, and low-latency updates. It is deployed on AWS EC2 for high availability and performance.

Key Features
	•	Real-time Stock Alerts – Sends notifications based on user-defined stock preferences.
	•	Scalable Pub-Sub Architecture – Efficient message distribution across multiple subscribers.
	•	Dynamic Data Streams – Continuously fetches and updates stock price data.
	•	Event-Driven Backend – Uses Spring Boot & Express.js for concurrent stock data processing.
	•	Interactive UI – Built with React.js for stock monitoring and subscription management.
	•	Cloud Deployment – Hosted on AWS EC2 to ensure reliability and performance.

Technologies Used

Backend
	•	Express.js – API handling, user authentication, and notification distribution.
	•	Spring Boot – Manages stock data processing and event-driven notifications.
	•	MongoDB – Stores subscription details and historical stock data.

Frontend
	•	React.js – Provides an intuitive dashboard for monitoring stocks and managing subscriptions.

Infrastructure & Cloud
	•	AWS EC2 – Ensures scalable deployment and high performance.

How It Works
	1.	Stock Data Collection – Fetches real-time stock price updates from external APIs.
	2.	Publisher-Subscriber Mechanism – The backend publishes stock updates, which are received by multiple subscribers.
	3.	Real-Time Alerts – Users receive notifications when stock prices reach predefined thresholds.
	4.	Cloud Deployment – Hosted on AWS EC2 for optimal scalability and availability.

Project Structure

📦 Stock-Market-Notifications  
 ┣ 📂 backend  # Express.js & Spring Boot Backend  
 ┣ 📂 broker   # Handles Pub-Sub Mechanism  
 ┣ 📂 frontend # React.js User Interface  
 ┣ 📜 .vscode  
 ┣ 📜 .idea  
 ┣ 📜 Readme.md  
 ┗ 📜 final-updates  

Future Enhancements
	•	Integration with WebSockets for even faster real-time updates.
	•	Enhanced stock trend analytics using machine learning.
	•	Push notifications for mobile and desktop users.
	•	Multi-user authentication & portfolio tracking.

Getting Started
	1.	Clone the Repository:

git clone https://github.com/SuyashSalvi/stock-market-notifications.git
cd stock-market-notifications

	2.	Install Dependencies:

cd backend
npm install  # Install backend dependencies

cd ../frontend
npm install  # Install frontend dependencies

	3.	Run the Backend Server:

cd backend
npm start

	4.	Run the Frontend Application:

cd frontend
npm start

License

This project is open-source and licensed under the MIT License. Contributions, modifications, and improvements are welcome.

If you have any suggestions, feel free to open an issue or submit a pull request.
