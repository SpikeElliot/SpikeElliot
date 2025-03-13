# I'm Spike!
- 🎓 Third-year Computer Science Undergrad @ Goldsmiths, University of London

- 💭 I'm interested in Software Engineering and have a passion for Machine Learning and Data Mining

- 🎯 My skills include: Python, Tensorflow, Scikit-learn, JavaScript, Node/Express, Java, OOP

- 🪛 I'm currently working on an electric guitar "rhythm game" that leverages pre-trained ML models for
guitar separation and pitch detection to help users learn to play their favourite songs

# Projects

## [🎸 Guitaraoke](https://github.com/SpikeElliot/Guitaraoke)

### Overview

A standalone Python application, this software implements open-source pre-trained Machine Learning models
and audio libraries to provide a gamified environment for electric guitarists to learn to play new songs.

### Features

- The user can select a local audio file to add to their library, which will initiate guitar separation
through use of the [6-stem HT Demucs MSS model](https://github.com/adefossez/demucs), followed by pitch
detection of the song's guitar track using [Spotify's Basic Pitch library](https://github.com/spotify/basic-pitch).

- A scoring algorithm compares the user and guitar tracks' predicted note event information during playback
to determine a performance score and note accuracy rate that is updated and displayed in real-time.

- A responsive and user-friendly GUI with aesthetic CSS styling was built using PyQt5.

- Separating processes through QThreads and the threading module allows the application to handle
sounddevice I/O audio streaming, real-time scoring in an audio recording and processing loop, and the GUI
concurrently with minimal latency and no blocking/freezing.

- The practice mode provides helpful audio playback controls such as looping, a guitar track volume slider,
a play/pause button, a custom-made interactable waveform that updates the song playhead position, and more.

### Technologies Used

**Python • PyQt5 • NumPy • Pandas • Librosa • CSS**

---

## [🏃 Fitter](https://github.com/SpikeElliot/Fitter)

### Overview

A web development project that showcased full-stack development skills, producing a prototype for a 
fitness-themed social media platform with Strava API integration and functionality for posting activities,
following users, liking, commenting, and more.

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
