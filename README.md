Project Title

GigShield - AI-Driven Financial Guard for Gigs

1.Problem Definition

Gig Work, defined as the earning of income based on completing work for someone else,
often referenced as "labor as a service", has become a significant and growing source of
income for many. Examples of gig work include working as a delivery agent using
applications like Swiggy, Zomato, Amazon, and Zepto, which provide you the ability to pick
up food, grocery, or package deliveries based on your availability. However, there are many
factors outside of a gig worker's control that can prevent him or her from working, resulting in
a financial loss, e.g., heavy rain, flooding, pollution, traffic restrictions, or governmentimposed curfews.
The current situation does not provide gig workers with any form of insurance to protect
them from the financial loss due to uncontrollable events. When an uncontrollable event
occurs, the gig worker loses the income he or she may have expected to earn while
completing work for someone else without any form of support. GigShield is a project
designed to address this issue through the use of an AI-powered parametric insurance
platform that automatically compensates gig workers for lost income due to uncontrollable
external disruptions.

2.Goals of the Project

The objective of this project is to develop a digital platform that protects gig worker income
due to:
Identifying controllable external disruptions (e.g., extreme weather, pollution)
Automatically calculating the estimated amount of lost income
Triggering the payment of a claims payout by the insurance company automatically
Providing immediate income payments to gig workers
All functions of the platform are focused solely on protecting the income of gig workers
without providing any form of insurance for accidents, health care, or vehicle repairs.

3.Target Audience (User Type)

Our primary users will be gig economy delivery partners, including:
Food delivery partners (Swiggy, Zomato)
E-commerce delivery partners (like Amazon, Flipkart)
Quick commerce delivery partners (such as Blinkit, Zepto)
These workers commonly earn on a daily or weekly basis, making their livelihoods very
vulnerable to sudden disruptions.

4.Primary Features of the App
A. Worker Sign-up
Workers have to create an account on our site by providing the following information:
Name and phone number
Which delivery platform they work for (e.g., Swiggy, Zomato, etc.)
Delivery area/zone
Type of vehicle (bike, car, etc.)
Weekly income through deliveries.
The information workers provide us about themselves will be used for the purposes of
assessing risk and setting the insurance premium.
B. AI-Driven Risk Analysis
In addition to the Workers' responses, the system performs analysis on a variety of external
factors, including:
Weather
Flood-prone areas
Pollution
Traffic restrictions.
Using the data from all four of these external risk factors, the AI calculates a risk score for
each Worker and therefore what their weekly insurance premium should be.
C. Weekly Insurance Product
The product developed for the Workers to purchase is a weekly premium, to coincide with
the Workers' earning cycle.
Example plans:
Basic Plan: ₹20/week (up to ₹2,000 coverage)
Standard Plan: ₹25/week (up to ₹3,000 coverage)
Premium Plan: ₹35/week (up to ₹5,000 coverage)
Workers will choose a plan based on their income level.
D. Disruption Detection
The platform has contact with a number of external data sources on a constant basis
including the following:
Weather APIs
Traffic providers
Local authorities that provide notification of emergencies
When a disruption occurs in the worker's delivery area, it is detected by the platform
automatically.
E. Automatic Claim Trigger
Once verification of a disruption has taken place, the platform will automatically:
Detect that deliveries are down
Estimate how many hours the worker has not received work
Calculate how much the worker is out of pocket
A claim is automatically created and does not require an employee to manually submit one.
F. Instant Payout System
When the claim is verified, the worker will receive payment through the following methods:
UPI
Bank transfer
Digital wallet
The worker can also download a receipt for payment from their dashboard.
G. Fraud Detection
Fraud detection using AI will help ensure that the system is not misused. The AI will
accomplish this using the following audit processes:
GPS Location verification
Weather event validation
Duplicate claim detection
Detection of anomalies in claims
H. Dashboard and Analytics
Worker Dashboard
A worker can see the following information on their dashboard:
Active insurance policy information
Weekly premiums
Disruption alerts
How many claims the worker has made
Where the receipt for any payout is located
Admin Dashboard
An administrator can see the following on their dashboard:
Total users
Frequency of claims
Disruption trends
Predicted risks for the upcoming week

5. Workflow of an Application

The workflow typically starts with that of a worker registering. Then the worker will add their
profile and delivery zone, after which the application will utilize AI to calculate their risk score
and provide them with a recommendation on what their premium would be on a weekly
basis. The next step of the process would be for the worker to purchase an insurance plan.
Once the insurance plan has been purchased, the application will monitor the potential for
external events that could disrupt their ability to deliver. For example, if there were heavy
rain on any given day, the application would monitor the weather conditions until it
determines that an external event is occurring. At that point, it will utilize AI to estimate the
worker's income loss and automatically trigger a claim and send the worker an
instantaneous payout.

6. Our Application Technology Stack

Front End: React js/Mobile App User Interface (UI)
Back End: Node js/Spring Boot Backend
Databases: MySQL/MongoDB (relational/non-relational)
APIs: Weather, Traffic, Payment (Razorpay/UPI/mobile wallet)
AI/Machine Learning: Risk Prediction Models, Fraud Detection Algorithms, Data Analysis for
Predicting Disruptions

7. Innovations from Our Solution

The following are innovations that we have created:
AI Risk-Based Pricing for the worker
Automated Claim Triggering
Real-time Detection of Disruptions
Instantaneous Payouts Without Manual Claim Submission
Creating a Simple and Reliable Safety Net for Gig Workers

8. Future Enhancements

Future versions of the platform could include:
More Advanced Predictive Risk Models
Additional Methods for Calculating Premiums
Integration with Delivery Platform API's
Multi-City Disruption Analysis
To sum up, Gigshield is an effective and scalable way to provide support to Gig Workers
who suffer a sudden loss of their income from external events being affected. The
combination of AI-based Risk Assessment, Parametric Insurance Trigger Solutions and
Immediate Payouts will provide the necessary financial security and stability for a worker in
need of daily deliveries to earn a living.

This video demonstrates the working of our system and key features:
https://youtu.be/sfoiwxi1NGY?si=quSuei6kDecIeGVA
