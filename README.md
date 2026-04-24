About This Project
The AI Network Anomaly Dashboard is a web-based prototype that demonstrates how artificial intelligence can be used to monitor network traffic in real time, detect suspicious activity, and alert IT operators through a clean, interactive interface.
The goal was to make network security more accessible — giving students, IT teams, and network engineers a tool that surfaces threats clearly and recommends actions, without requiring deep technical expertise to understand what's happening on the network.

What It Does

Displays real-time alerts for suspicious network events, ranked by severity (High, Medium, Low)
Shows a live network traffic chart that updates continuously
Provides detailed alert views with source/destination IPs, affected devices, AI confidence scores, and recommended responses
Includes a searchable network log with 25 simulated events and CSV export
Lets users acknowledge alerts and track which threats have been reviewed
Features a settings panel for notification preferences, detection sensitivity, and two-factor authentication


Purpose
This project was built to explore how AI and data visualization can work together to make cybersecurity tools more intuitive and actionable. Rather than presenting raw logs that require expert interpretation, the dashboard translates network events into clear, prioritized alerts with guidance on what to do next.
The prototype uses simulated data to demonstrate the full user experience. In a real-world deployment, it would connect to a backend capturing live network packets and running a trained machine learning model for anomaly detection.

Innovation
Most network monitoring tools are designed for experts and present overwhelming amounts of raw data. This dashboard takes a different approach — using AI severity classification, confidence scoring, and plain-language recommendations to make threat detection accessible to anyone responsible for a network, including students learning cybersecurity for the first time.

Deliverables

Functional web dashboard prototype (this repository)
Network logs view with search and pagination
Alert detail and acknowledgement system
Settings panel with notification and security controls
SIP poster and project presentation


Credits
Built with HTML, CSS, JavaScript, and Chart.js.
Fonts by Google Fonts.
