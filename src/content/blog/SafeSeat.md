---
title: "SafeSeat"
description: "This project aims to ensure the safety of babies and young children through environmental monitoring and a notifying app."
pubDate: "Nov 16, 2025"
heroImage: "/SafeSeat.png"
---

#### Inspiration
When my older sibling was younger, they went into a car to take a nap during the summer. They almost didn't make it out. When they woke up, the air temperature inside the car had exceeded the milder temperatures outside. They barely even had the strength to make it out of the car. I was further inspired by the stories of parents who, in a lapse of judgement, leave an infant in a car leading to the child's death. According to No Heat Stroke, even in mild temperatures ~70º F, cars can heat up to over 100ºF.
#### What it does
This project uses the temperature and air quality sensors to measure the environment it is in and uses a buzzer to notify surrounding people when these measurements are out of the safe range for a child. Furthermore, the companion app is able to notify the parent when the device is detecting unsafe conditions.
#### How we built it
I built this using an Arduino along with companion sensors. Using a web server from the Arduino, I was able to deliver these metrics to the app. I used Android Studio to program and test the app.
#### Challenges we ran into
It was a challenge connecting the Arduino to the internet since most connections forced you into a captive portal. I ended up having to use a personal hotspot to get around that. I also had trouble getting the hotspot to connect and I realized that I had to decrease the frequency to match the Arduino. Another challenge I faced was connecting the Android Studio emulator to the web server. I tried everything to get it to connect including trying to get the emulator to connect to eduroam and changing the DNS domains. Eventually I realized it was just that I declined Android Studio access to local network devices 3 months ago. 
#### Accomplishments that we're proud of
Finishing this. My team left me to play badminton.
#### What we learned
I picked up skills programming an Arduino and interpreting sensor data through this project. 
For this project I read a couple articles on how to design alarms to get the most attention. Single pitch alarms with no stops tend to get tuned out so its important to alternate pitches and add stops. I also learned about how people who are hard of hearing are often left unconsidered by alarm systems so I made sure the alarm I desgined would cycle to lower pitches to be easier for disabled and elderly people to hear and help. When I was testing my alarm, no body at the 24 hour hackathon was left unalerted.
#### Built With
``android``
``android-studio``
``arduino``
``cpp``
``kotlin``
``webserver``
``Grove Sensors``

<iframe width="560" height="315" src="https://www.youtube.com/embed/aofgM6MmL-s?si=8wIiKY3NDI1YWFQu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>