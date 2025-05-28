# I'm Spike!
- 🎓 Third-year Computer Science Undergrad @ Goldsmiths, University of London

- 💭 I'm interested in Software Engineering and have a passion for Machine Learning and Data Science

- 🎯 My skills include: Python, Tensorflow, Scikit-learn, JavaScript, Node/Express, Java, OOP

- 🪛 I'm currently working on a guitar practice tool that leverages pre-trained ML models for
guitar separation and automatic music transcription to help users learn to play their favourite songs by ear!

# Projects

## [🎸 Guitaraoke](https://github.com/SpikeElliot/Guitaraoke)

### Overview

A standalone gamified guitar practice application for Windows: built in Python and incorporating
pre-trained machine learning models for MSS and AMT, a GUI framework, and libraries for audio streaming and data processing.

### Features

- Select any local audio file to perform, initiating guitar separation through use of the [6-stem HT Demucs MSS model](https://github.com/adefossez/demucs),
followed by pitch and onset detection of the song's separated guitar track using [Spotify's Basic Pitch library](https://github.com/spotify/basic-pitch).

- A scoring algorithm compares the user input and guitar tracks' predicted note events during playback
to display a real-time note accuracy rate, performance score, and swing display (indicating rushing or dragging).

- A responsive, easy-to-use GUI with aesthetic minimalist CSS styling was built with the PyQt6 framework.

- Using separate processes with Python's concurrent.futures module allows the application to handle audio playback manipulation,
real-time scoring in an audio recording and processing loop, and updating the GUI concurrently with no blocking or freezing.

- The practice mode provides helpful playback controls such as: a guitar track volume slider,
a play/pause button, a custom-made interactive waveform and playhead that allows seeking,
section looping with user-set markers, and more.

### Technologies Used

**Python • PyQt6 • NumPy • Pandas • Librosa • sounddevice**

---

## [🏃 Fitter](https://github.com/SpikeElliot/Fitter)

### Overview

A web development project that showcased full-stack development skills, producing a prototype for a 
fitness-themed social media platform with Strava API integration and functionality for posting activities,
following users, liking, commenting, and more.

### Features

- Integration with Strava API allows a user to connect their Fitter and Strava accounts through OAuth 2.0,
providing access to their recent activities. An activity can optionally be linked to a post, "embedding"
relevant exercise data in the post's body, allowing a user to share their performance with others.

- CSS styling creates an aesthetic, consistent, and intuitive user experience for the web app. A sidebar
provides easy navigation to important pages such as the user's profile, their likes, and the home page.
A sticky header displays a search bar and a dropdown menu relating to user functionality such as connecting
to Strava or logging out.

- SQL queries in the Express middleware call Stored Procedures that are performed internally by the database.
This gives: efficiency, as operations are faster; readability, as queries don’t need to be chained in the
middleware; better separation of concerns between the application and data tiers.

- Security and data integrity: All forms are validated and sanitised using express-validator to prevent
XSS attacks, all SQL queries are parameterised to avoid injection attacks, users' passwords are encrypted
and hash salted with bcrypt.

### Technologies Used

**JavaScript • Node/Express • MySQL • HTML • CSS**

---

## [🎵 Karaoke and Rhythm Game](https://github.com/sahas036211/p5-Karaoke-and-Rhythm-Game)

### Overview

A proof of concept built using the p5.js library that features a keyboard-controlled
rhythm game, a karaoke game using microphone input, and a music player providing
audio playback controls and various visualisers to select from.

### Features

The rhythm game features procedural real-time note generation synchronised to the song's tempo,
an in-depth scoring system, difficulty options that adjust note spawn rates, and 3D graphics
rendering of game environment.

The music player showcases various visualisations, audio playback controls, a clickable progress
bar, and a webcam input integrated visualisation through use of p5's FFT functions.

### Technologies Used

**JavaScript • p5.js**

---

## [🧑‍🏫 Bookit: Room Booking Application](https://github.com/jbrun001/roombooking)

### Overview

A collaborative group project to develop a responsive room booking web application for a university.

### Technologies Used

**JavaScript • Node/Express • MySQL • HTML • CSS**

---

## [🇭 Hangman Game](https://github.com/SpikeElliot/Java-Hangman-Game)

### Overview 

An endless hangman game with a simple score system designed as a small test application to demonstrate 
proficiency with Java Swing. 

### Technologies Used

**Java**

<!--

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
