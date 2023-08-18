# Time Tracker App: Evaluate Yourself and Boost Productivity

## Overview

The Time Tracker app is a user-friendly tool designed to help you evaluate your daily activities and boost your productivity. This app allows you to track the time you spend on different tasks, helping you become more aware of how you allocate your time and make informed decisions to enhance your efficiency.

## Time Tracker App:
### Features

Activity Tracking: Record the start and end times of your activities, along with a brief description.
Evaluation: View your activity data for the current day or the past week to analyze your time usage.
Excel Integration: Data is stored in an Excel spreadsheet, making it easy to manage and analyze your activities.

### Getting Started

Follow these steps to get started with the Time Tracker app:

Install Dependencies: Make sure you have Python, Kivy, Pandas and OpenPyXL installed on your system.
Or, use the code below: 

	pip install -r requirements.txt

##### You dont need to use our thelab.kv file
##### The main.py file takes care of everything

Run the App: Open a terminal or command prompt and navigate to the app's directory. Run the app using the following command: 

	python main.py

Record Activities: On the main screen, input the start and end times of your activities, along with a description. Press the "Submit" button to save the data.

Evaluate Data: Press the "Evaluate Today" button to see a summary of your activities for the current day. Use the "Evaluate Past Week" button to analyze your activities over the past week.

Open Excel Sheet: To view and further analyze your data, press the "Open Excel Sheet" button to read the Excel file (time_tracker.xlsx) containing your activity records.

## Boosting Your Productivity

The Time Tracker app can be a valuable tool for boosting your productivity:

Awareness: By tracking your activities, you become more aware of how you spend your time. This awareness allows you to identify time-wasting habits and make necessary adjustments.

Time Management: Analyzing your activity data helps you identify areas where you can optimize your time management. You can allocate more time to productive tasks and reduce time spent on less important activities.

Goal Setting: Use the insights gained from evaluating your activities to set specific goals for improving your productivity. Set targets for the amount of time you spend on key tasks.

Efficiency Analysis: Reviewing your activity history lets you assess the efficiency of different tasks. You can identify tasks that consistently take longer than expected and work on finding ways to streamline them.

## Feedback and Contributions

Your feedback is valuable! If you have suggestions, bug reports, or feature requests, please open an issue in the GitHub repository.

## Building the APK

You can easily build an apk using this simple kivy code. The esiest way is to use the google colab method. You can follow any tutorial. Use the buildozer.spec file given in this repository or read it and make the necessary changes required. The recommended commands on google colab are as follows:

	!pip install buildozer
#
 	!pip install cython
#
  	!sudo apt-get install -y \
    python3-pip \
    build-essential \
    git \
    python3 \
    python3-dev \
    ffmpeg \
    libsdl2-dev \
    libsdl2-image-dev \
    libsdl2-mixer-dev \
    libsdl2-ttf-dev \
    libportmidi-dev \
    libswscale-dev \
    libavformat-dev \
    libavcodec-dev \
    zlib1g-dev

#
	!sudo apt update
#
 	!sudo apt upgrade
#
	!sudo apt update
#
	!sudo apt install -y git zip unzip openjdk-17-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev libssl-dev
#
	!pip3 install --upgrade Cython==0.29.33 virtualenv  # the --user should be removed if you do this in a venv
#
	!sudo apt-get install -y \
    libgstreamer1.0 \
    gstreamer1.0-plugins-base \
    gstreamer1.0-plugins-good
#
	!sudo apt-get install autopoint
#
 	!sudo apt-get install libffi-dev
#
  	!buildozer init
##### Change the buildozer.spec file as per the one in the repository. Save it, and enter the following command:

	!buildozer -v android debug
