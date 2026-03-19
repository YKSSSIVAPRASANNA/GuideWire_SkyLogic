# GuideWire_SkyLogic
AI-Powered Insurance for India’s  Gig Economy
----------------
Problem Statement
------------------
Gig workers such as delivery partners working with platforms like Zomato, Swiggy, Amazon, Zepto, and Dunzo rely on daily deliveries for their income. However, environmental conditions such as heavy rain, extreme temperatures, pollution, or natural disasters can reduce their working hours and lead to income loss.
Most gig workers currently lack insurance coverage or financial safety nets to protect them from such disruptions. Additionally, traditional insurance systems involve manual and time-consuming claim processes.
This project aims to develop a smart parametric insurance system that automatically compensates gig workers when predefined environmental conditions occur. Using AI, real-time environmental data, and automated payouts, the system ensures fast, transparent, and reliable income protection.

Overview
-----------
Gig workers such as delivery partners working with platforms like Zomato, Swiggy, Amazon, Zepto, and Dunzo play a crucial role in supporting India’s rapidly growing digital economy. These workers depend heavily on daily deliveries for their income. However, their earnings are strongly influenced by external environmental conditions such as extreme weather, high pollution levels, or natural disasters.

When such disruptions occur, gig workers often experience reduced working hours or are unable to work at all. This can lead to a significant income loss, sometimes ranging from 20% to 30%. Despite facing these risks regularly, most gig workers currently do not have access to financial protection mechanisms during such events.

To address this issue, this project proposes an AI-enabled parametric insurance platform designed specifically for gig workers. The platform provides automated income protection whenever environmental disruptions affect their ability to work.

The system utilizes real-time environmental data, AI-based risk analysis, and automated payout mechanisms to deliver quick financial support. By offering a simple and affordable weekly insurance model, the platform ensures that gig workers receive timely compensation without complicated claim procedures

Key Features :
---------------
•	Weekly Micro-Insurance Subscription
Gig workers can enrol in a low-cost weekly insurance plan designed to suit their daily income patterns.
•	Parametric Triggers Based on Environmental Data
The system monitors real-time environmental conditions such as rainfall, temperature, pollution levels, and natural disasters to determine when coverage should activate.
•	Automated Payout System
When predefined environmental conditions are met, compensation is automatically processed without requiring manual claim submissions.
•	AI-Driven Fraud Detection
Artificial Intelligence analyses user activity and data patterns to identify and prevent fraudulent claims.
•	AI-Based Risk Prediction and Premium Calculation
Machine learning models evaluate environmental risk patterns and worker activity data to determine fair and dynamic insurance premiums.
•	Mobile-First Platform
A user-friendly mobile application allows gig workers to easily subscribe, track coverage, receive alerts, and access payouts.

Persona-Based Scenario
--------------------------------
Persona 1: Shiva – Food Delivery Partner
Profile
•	Age: 26
•	Platform: Swiggy
•	Weekly Income: ₹5000
Scenario
Due to heavy rainfall in the city, Shiva is unable to complete many deliveries. As a result, his weekly earnings decrease.
Category	Amount
Normal Weekly Earnings	₹5000
Actual Earnings During Disruption	₹3500
Income Loss	₹1500
Since the rainfall level exceeds the predefined parametric threshold, the platform automatically triggers an insurance payout of ₹500 to support Shiva during the disruption.

Application Workflow
-----------------------
1.User Registration
The gig worker registers on the platform using their mobile number.
2.Insurance Subscription
The worker subscribes to a weekly micro-insurance plan available on the platform.
3.Environmental Data Collection
The system continuously collects real-time environmental data (weather, pollution, disasters) from external APIs.
4.AI-Based Risk Monitoring
The AI engine analyzes the data to detect potential environmental disruptions that may affect gig workers.
5.Trigger Detection
If predefined parametric trigger conditions (e.g., heavy rainfall or high pollution levels) are met, the system activates the insurance process.
6.Automatic Payout
The compensation amount is automatically transferred to the worker’s account via UPI without requiring a manual claim process.

Weekly Premium Model
Gig workers generally prefer small and flexible payments that match their weekly earning patterns. Therefore, the platform offers low-cost weekly insurance plans.
Example Insurance Plans
_--------------------------------_
|Weekly Premium	|Coverage Amount|
| ₹20	          |₹500   payout  |
| ₹40	          |₹1000  payout  |
| ₹60	          |₹1500  payout  |
_-------------------------------_
Advantages of the Weekly Model
•	Affordable for gig workers with daily income patterns
•	Flexible, allowing workers to easily subscribe or cancel plans
•	Aligned with weekly income cycles, making payments convenient and manageable

Parametric Insurance Triggers
-------------------------------
Instead of verifying individual claims, the system uses predefined environmental thresholds to automatically trigger insurance payouts when disruptions occur.
Example Triggers
1. Rainfall Trigger
Condition: Rainfall > 120 mm in a day
Real-time example:
If a city like Hyderabad or Mumbai receives very heavy rainfall, roads may become flooded and delivery services slow down. When rainfall exceeds 120 mm, the platform automatically triggers insurance payouts for registered gig workers in that location.

2. Heatwave Trigger
Condition: Temperature > 45°C
Real-time example:
During extreme summers in cities like Delhi or Nagpur, temperatures sometimes rise above 45°C. Such heat conditions make outdoor work risky for delivery partners. Once this threshold is crossed, the system automatically compensates workers.

3. Air Pollution Trigger
Condition: AQI > 400
Real-time example:
In winter, cities such as Delhi often experience severe smog where the Air Quality Index (AQI) exceeds 400, which is considered hazardous. When this level is reached, the system triggers payouts to protect gig workers exposed to harmful air conditions.

4. Disaster Alert Trigger
Condition: Official flood, cyclone, or disaster warning issued
Real-time example:
If a cyclone alert is issued in coastal cities like Chennai or Visakhapatnam, delivery operations may stop for safety reasons. Once the official disaster warning is released, the platform automatically provides compensation to affected workers.

Once any of these conditions are met, the system automatically activates the payout, ensuring that eligible gig workers receive quick compensation without submitting manual claims.

AI / ML Integration
----------------------
Artificial Intelligence and Machine Learning are used in the platform to improve pricing, detect fraud, and predict environmental risks.
1. Premium Calculation
Machine learning models analyze various data sources to determine optimal insurance premium pricing.
Data analyzed:
•	Historical weather data
•	Frequency of environmental disruptions
•	Gig workers’ earnings patterns
Using this data, the system calculates fair and dynamic premium amounts that match the risk level in a particular location.

2. Fraud Detection
AI models monitor system activity to identify suspicious or fraudulent behavior.
Examples of suspicious activities:
•	Fake or manipulated location data
•	Duplicate user accounts
•	Abnormal claim patterns
Techniques used:
•	Anomaly detection
•	Classification models
•	Behavioral pattern analysis
These techniques help ensure that only genuine workers receive compensation.

3. Risk Prediction
AI models predict potential future environmental disruptions.
Data sources used:
•	Weather forecasting systems
•	Pollution trend analysis
•	Disaster prediction models
This helps the platform adjust insurance pricing dynamically and improve overall risk management for gig workers.

Platform Choice
-------------------
The proposed system will follow a mobile-first platform approach.
Reasons for Choosing a Mobile Platform
•	Smartphone Usage: Most gig workers depend on smartphones for their daily work.
•	GPS Integration: Mobile apps can easily use GPS services to track location and verify environmental triggers.
•	Push Notifications: Workers can receive instant alerts about disruptions, policy updates, and payouts.
•	Ease of Access: A mobile application allows workers to quickly subscribe, manage their plans, and track compensation.
Administrator Dashboard
In addition to the mobile app, a web-based dashboard will be developed for administrators.
This dashboard will help in:
•	Monitoring environmental risks and trigger conditions
•	Tracking insurance subscriptions and payouts
•	Analyzing system performance and platform activity
This combined approach ensures easy access for gig workers and efficient management for administrators.

System Architecture
The system architecture illustrates how different components interact to provide automated parametric insurance for gig workers.
___________________________________
Gig Worker Mobile App
        │
        │
Backend API (Node.js / Express)
        │
        │
AI Risk Analysis Engine
        │
        │
Environmental Data APIs
(Weather / AQI / Disaster Alerts)
        │
        │
Parametric Insurance Engine
        │
        │
Automated Payment Gateway
(UPI / Razorpay)
______________________________
Component Explanation
1. Gig Worker Mobile App
The mobile application allows gig workers to register, subscribe to insurance plans, receive notifications, and track payouts.
2. Backend API (Node.js / Express)
The backend server handles user authentication, data processing, API communication, and system logic.
3. AI Risk Analysis Engine
This module uses machine learning models to analyze environmental risks, detect fraud, and predict disruption probabilities.
4. Environmental Data APIs
External APIs provide real-time data such as:
•	Weather conditions
•	Air Quality Index (AQI)
•	Disaster alerts
5. Parametric Insurance Engine
This component checks whether environmental thresholds (triggers) are exceeded and determines when payouts should be activated.
6. Automated Payment Gateway
Once a trigger condition is satisfied, the system automatically transfers compensation through UPI or payment services like Razorpay.

Tech Stack
-------------
Frontend
•	React Native (Mobile Application)
•	React.js (Admin Dashboard)
Backend
•	Node.js
•	Express.js
Database
•	PostgreSQL
•	Firebase
AI / ML
•	Python
•	Scikit-learn
•	TensorFlow
External APIs
•	OpenWeather API
•	AQI Pollution API
•	Government disaster alerts
Payments
•	Razorpay / UPI integration
Cloud Infrastructure
•	AWS / Google Cloud

Development Plan
------------------
The development of the platform will be carried out in five phases to ensure systematic implementation and testing.
Phase 1 – Research and Data Collection
•	Collect historical weather and pollution data
•	Identify environmental disruption thresholds for triggers
Phase 2 – Minimum Viable Product (MVP)
•	Implement user registration system
•	Develop weekly insurance subscription model
•	Build environmental trigger monitoring module
Phase 3 – AI Integration
•	Develop AI-based fraud detection model
•	Implement risk prediction models for environmental disruptions
Phase 4 – Automated Payout System
•	Integrate payment gateway (UPI / Razorpay)
•	Implement automatic compensation mechanism
Phase 5 – Testing and Deployment
•	Simulate disruptions using historical environmental data
•	Conduct pilot testing with selected sample users before full deployment.

Future Enhancements
---------------------
•	Integration with Gig Platforms
Connect the system directly with platforms like Swiggy and Zomato APIs to automatically verify worker activity and improve insurance coverage accuracy.
•	Personalized Insurance Plans
Offer custom insurance plans based on individual worker activity, delivery frequency, and earning patterns.
•	Predictive Alerts for Workers
Provide AI-based alerts that notify gig workers about upcoming risks such as heavy rain, heatwaves, or high pollution levels so they can plan their work safely.
•	Nationwide Scalability
Expand the platform to support gig workers across multiple cities in India, making the system scalable and widely accessible.

Impact
---------
This solution can provide several benefits for gig workers and the gig economy ecosystem.
•	Improved Financial Security
Helps gig workers receive compensation during environmental disruptions, reducing financial stress.
•	Stronger Trust Between Workers and Platforms
Transparent and automated insurance payouts can improve trust between gig workers and digital platforms.
•	Reduced Income Volatility
Provides financial support when workers face reduced earnings due to extreme weather or environmental conditions.
•	Stronger Gig Economy Ecosystem
By protecting workers financially, the system contributes to a more stable and sustainable gig economy.


























