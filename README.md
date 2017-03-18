# Today-I-Learned
A collection of concise write-ups on small things I learn day to day.

1. **[January 23, 2017](#)** [Creating an Alexa skill, AWS Lambda, Localization in Robotics](#).  
Today I learned how to create custom Alexa skills using AWS Lambda for the Amazon Echo. I developed a skill which sends you a random design quote from the website: [quotesondesign](http://quotesondesign.com). Wrote a Lambda function using NodeJS which calls their API. [This video](https://www.youtube.com/watch?v=zt9WdE5kR6g) explains a lot of stuff quickly to get you started. Also started the [Artificial Intelligence for Robotics](https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373) course on Udacity. Learned about Localization, inaccurate vs exact robot motion, robot sense and movement. You can find more info in the [Lesson 1 Notes](https://storage.googleapis.com/supplemental_media/udacityu/48739381/Lesson1Notes.pdf). Loving the course!

2. **[January 24, 2017](#)** [Chrome extension, SSH Tunelling, 2D Localization](#).  
Created a small chrome extension which waits for changes on a webpage and extracts a url once a particular div has changed and sends a push notification on my phone. Used [extensionizr](http://extensionizr.com/) to quickly create a boilerplate and get started on the extension. Used [onesignal](https://onesignal.com/) for push notifications. Created my own VPN using AWS EC2 and SSH Tunelling. Very useful if your college internet has a lot of restrictions. Follow [this](https://www.comparitech.com/blog/vpn-privacy/how-to-make-your-own-free-vpn-using-amazon-web-services/) article to quickly get started. Also learned 2D Localization.

3. **[January 31, 2017](#)** [2D Localization, Android app to publish ROS Commands](#).  
Wrote code in python for 2D Localization. Basically computing the probability of a robots position based on movement and sensing. Code available at [localization_2d.py](https://gist.github.com/ahhda/95a82080d2df5abf1dd2b3f1173ebcec). Also made an android app to control a [lizi robot](http://wiki.ros.org/lizi_robot) using Gyroscope by publishing a [Twist command](http://docs.ros.org/api/geometry_msgs/html/msg/Twist.html) to cmd_vel topic over a network.

4. **[February 1, 2017](#)** [1D Kalman Filter](#).  
Wrote code in python for implmenting a 1D Kalman Filter. The Kalman filter is a popular technique for estimating the state of a system. Kalman filters estimate a continuous state and gives a
uni­modal distribution. The code takes two functions, update and predict, and feeds them into a sequence of measurements and motions. Code available at [kalmanfilter_1d.py](https://gist.github.com/ahhda/05cd395f1c95b89e391d07ac8de979ba).

5. **[February 10, 2017](#)** [Particle Filter, Hector SLAM](#).  
Wrote code in python for implmenting Particle Filter. Particle Filters are a sequence of algorithms for estimating the state of a system. They are really easy to code and work for multimodal distribution. However they scale exponentially. Code available at [particle_filter.py](https://gist.github.com/ahhda/9fb89a42750c1b33cc913f2a27f610b0). Also setup Hector SLAM and Hector navigation for Lizi robot. Wrote a small blog post at: [geekinsideyou.com/hector-slam-ros](http://geekinsideyou.com/hector-slam-ros/). 

6. **[February 10, 2017](#)** [Windows Form App, Nodejs Chat App](#).  
Wrote a simple chat app in Nodejs and hosted on [heroku](https://limitless-island-41567.herokuapp.com/). Followed the tutorial on [deploy on heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs#deploy-the-app) and [nodejs chat](https://enlight.ml/nodejs-chat).