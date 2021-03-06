+++
# Date this page was created.
# date = "2016-04-27"

# Project title.
title = "Avadhuta"

# Project summary to display on homepage.
summary = "A Wayfinding tool for indoor tracking"

# Optional image to display on homepage (relative to `static/img/` folder).
# image_preview = "singing.png"

# Optional image to display on project detail page (relative to `static/img/` folder).
# image = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["wayfinding"]

# Optional external URL for project (replaces project detail page).
# external_link = ""

# Does the project detail page use math formatting?
# math = false

+++
Avadhuta: a way finding solution for indoor environments was developed by my team at Singapore-India Hackathon held at Nanyang Technlogical University. The motivation to design this system was to resolve the issue of finding locaton of any department inside a building. 
The Global Positioning System (GPS) does not work in indoor environments.
Also, Wi-Fi Received Signal Strength(RSSI) indicator data is unreliable in Non-line of sight conditions.
To resolve this issue, our system used GPS data outdoors and integrated indoor tracking into it. To map the indoor radiation patterns of Wi-Fi signals in each building, a machine learning technique was used. Our GUI provides a provision for scanning QR codes located at selected landmarks.
It can also give directions to the user through the pictures taken by the mobile phone using image processing and pattern recognition.
The main advantage of our system is that we didn't use extra hardwares for indoor tracking except for the QR codes placed at some landmarks.
Our system also considered the obstructions in the Wi-Fi signals by concrete walls and partitions by training a system.
In the absence of Wi-Fi signals, we got other options like
QR codes,
Image Processing from mobile camera,
Sound signatures to verify the correctness of path.

