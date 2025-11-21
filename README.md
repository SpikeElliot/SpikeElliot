# Spike is...
- **A First Class Honours Computer Science graduate** from Goldsmiths, UoL with a final average of 86%
- **In love with the field of machine learning**: currently reading François Chollet's _DLWP 3rd Edition_, completing ML courses, tackling Kaggle datasets, joining an MSc programme next year
- **Proficient in ML frameworks** such as Scikit-Learn, Keras, and TensorFlow
- **A hobby full-stack developer**: currently building a MERN stack personal journal web application
- **A reader, runner, gym-goer, lifelong learner, caffeine addict, guitarist, and [djent](https://en.wikipedia.org/wiki/Djent) enthusiast**

# Projects

## [Guitaraoke](https://github.com/SpikeElliot/Guitaraoke)

<a href="https://github.com/SpikeElliot/Guitaraoke">
  <img alt="An image of Guitaraoke's splash screen" src="https://github.com/user-attachments/assets/e37c0968-8779-45c9-87a7-12c687d8b53e" width=100%>
</a>

### My undergraduate final project

A novel guitar practice application for Windows, built with PyQt6: leverages **pre-trained convolutional models** for music source separation 
and automatic music transcription to provide guitarists with gamified, karaoke-style performance scoring _in real time_.

### Project Details

- Select _any_ local audio file to perform, initiating guitar separation through use of the [6-stem HT Demucs MSS model](https://github.com/adefossez/demucs),
followed by pitch and onset detection of the song's separated guitar track using [Spotify's Basic Pitch library](https://github.com/spotify/basic-pitch).

- A scoring algorithm compares the user input and guitar tracks' predicted note events during playback
to display a **real-time note accuracy rate, performance score, and swing display (indicating rushing or dragging)**.

- The practice mode provides **helpful audio playback controls** such as: a guitar track volume slider,
a play/pause button, a custom interactive waveform and playhead with seeking functionality,
section looping with user-defined markers, and more.

- Using separate processes with Python's _concurrent.futures_ module allows the application to handle audio playback manipulation,
real-time scoring in an audio recording and processing loop, and updating the GUI concurrently with **no blocking or freezing**.

---

## [Fitter](https://github.com/SpikeElliot/Fitter)

<a href="https://github.com/SpikeElliot/Fitter">
  <img alt="A screenshot of Fitter's home page" src="https://github.com/user-attachments/assets/dded6c4a-cfec-4983-a69c-833a72538ea4" width=100%>
</a>

### An undergraduate web dev project

A prototype fitness-themed social media platform with Strava API integration and functionality for posting activities,
following users, liking, commenting, and more.

### Project Details

- **Integration with Strava API**: allows a user to access their recent activities by connecting their Fitter and
Strava accounts through OAuth 2.0. An activity can be optionally "embedded" into a post, rendering relevant exercise
data in the post's body, allowing a user to share their performance with others.

- **Custom CSS**: a sidebar provides easy navigation to important pages such as the user's profile, their likes, and the home page;
a sticky header displays a search bar and dropdown menu containing helpful quick actions.

- SQL queries in the Express middleware call **Stored Procedures** that are performed internally by MySQL.
This is more efficient and readable (as queries are no longer chained in the middleware).

- **Security and data integrity**: All forms are validated and sanitised with _express-validator_ to prevent
XSS attacks, all SQL queries are parameterised to avoid injection attacks, and users' passwords are encrypted
and hash salted with _bcrypt_.

---

## [Karaoke and Rhythm Game](https://github.com/sahas036211/p5-Karaoke-and-Rhythm-Game)

<a href="https://github.com/sahas036211/p5-Karaoke-and-Rhythm-Game">
  <img alt="A screenshot of the application's rhythm game" src="https://github.com/user-attachments/assets/04288dd0-1f28-4f4c-a40a-bc2a8fbc72d8" width=100%>
</a>

### A collaborative first-year undergradute project

A POC application built with the _p5.js_ library in collaboration with [sahas036211](https://github.com/sahas036211):
features a rhythm game with keyboard controls, a karaoke game using microphone input, and a music player with playback
controls and visualisers.

### Project Details

- **Rhythm game**: procedural real-time note generation _synchronised to the song's tempo_, a scoring system based on user accuracy and timing,
**difficulty options** that modify note spawn rate, and 3D graphics rendering of game environment.

- **Karaoke game**: implements a _pre-trained machine learning model_ for pitch detection of the song and microphone input; provides
a pitch accuracy-based scoring system and synchronised lyrics display; and offers a **fun webcam mode** with overlay filters.

- **Music player**: various **3D and 2D animated visualisers** to choose from, audio playback controls (play/pause, skip, song speed, looping, etc.),
a volume bar, and a _seek-able_ song progress bar.

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
