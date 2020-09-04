## Hi there 👋 Welcome to my GitHUB
I'm Federico Macchi, a Software Engineer with a strong UI focus; passionate about cooking, cocktails and (aero)space, I love coding, creating devices, and taking part in hackathons.  

I'm currently finishing my Master Degree in HCID - Human-Computer Interaction and Design offered by EIT Digital, at the University of Trento (Trento, IT) and Aalto University (Helsinki, Finland); my thesis dissertation is scheduled for Wed the 21st of Oct, 2020.  
My Master Thesis is about automating the Visual Testing of Advanced Map-based Interfaces, used within the context of Flight Simulators.

My research interests are mainly related to UIs and Software Engineering/Architecture; I would like to learn more about advanced emergent User Interfaces such as Augmented/Mixed/Virtual Reality especially applied to the fields of defence and aerospace.

Need to know more? Head over to https://fedemitic.github.io/ for my complete résumé and portfolio.

### A brief presentation of my GitHUB
Most of my repository are small ones, created to complete personal projects and school's coursework; professional projects, such as the ones described in my portfolio, are not here unfortunately :(
However, if you want to have an idea about my way of coding things, you can check the following repos:
- Website (Super basic HTML, CSS, JS)
  - https://github.com/FedeMITIC/fedemitic.github.io, résumé and portfolio website - mainly HTML and CSS with some quick JS to load projects and generate cards
- Python: 
  - https://github.com/FedeMITIC/RingReaderEUI, device to extract texts from images and read it back to the user with a synthesized voice (for the Aalto Course CS-E4200 Emergent User Interface)
  - https://github.com/FedeMITIC/data-analysis-project, ML project to classify songs between 10 genres
- JavaScript:
  - https://github.com/FedeMITIC/auth0-users, small package used HomebrewLab, to retrieve user data from Auth0's servers, given its JWT
  - https://github.com/Lykos94/js-draggable-console, to display a browser-like console on mobile, for quick testing of phone-gap apps (Contributed)
  - https://github.com/FedeMITIC/cli-assignment, nodeJS CLI (for the Aalto Course CS-E5220 User Interface Construction)
- C++:
  - https://github.com/FedeMITIC/MultisensoryInteractiveSystems, for the Trento Course Multisensory Interactive Systems, we realized a TUI (Tangible User Interface) to control an element (a rolling ball) on a screen (C++ used to control sensors and motors connected through Arduino, Pure Data (PD) to bridge the low-level C++ to the Processing high-level interface through OSC messages, and Processing to realize the interface shown on the computer screen)

Additionally, not included in my Github, I used Java for both my Bachelor and Master thesis.

#### Currently working on
I'm currently finishing my Master Thesis, writing tests using Java, OpenCV, TesseractOCR and Selenium APIs + HTML/CSS/JS to create a website which automatically parses and displays the results of the tests.  

I'm learning Spring Boot by creating a clone of Google Keep (repo here: https://github.com/FedeMITIC/TODOsAPI)

#### Open Source and other contributions
Other things I contributed to:
- Homebrewlab (described here in Italian (Google Translate is your friend) https://hopadvisor.it/2017/08/20/homebrewlab-verso-un-software-nuovo-per-pianificare-gli-esperimenti-birrari/), current website: https://homebrewlab.cloudno.de/; I contributed to this open source app for almost two years, from the initial phases. In particular, I was the leader of the back-end team, that built the backend infrastructure, originally based on the Google Cloud Platform (with a Linux Machine). It featured:
  - a NodeJS app, with RESTful APIs
    - ExpressJS for routing and endpoints
    - Authentication realized through JWT and Auth0, and a RBAC (Role-based Access Control) library that I wrote to differentiate standard users from admins and moderators (each group had different permissions)
    - Persistence with MongoDB
    - Versioning with GitHUB
  - a reverse proxy (NGINX) to connect to the application through HTTPS only (certificate obtained from https://letsencrypt.org/)
  - PM2 (https://pm2.keymetrics.io/) to manage the process and ensure it stays up even after a crash

  Additionally, I set up the front-end to authenticate users, save their token in the local/session storage and create a small utility with functions to call the backend APIs, so that my teammates on the front-end could completely focus on the interface and user-interactions.
  
- AIrsound, an AI-based app built with Python in the context of a 1-month long hackathon (My team and I won the 2nd place) hosted by Leonardo (https://www.leonardocompany.com/en/home). The purpose of the application is to aid operators in performing the Tapping Test; this test verifies that a component (of an aircraft usually) is not damaged and ready to fly, by hitting its surface with a small hammer and listening to the sound produced. Through a KNN classifier, we realized this python application that can analyze the sound, retrieved using a microphone, and tell the operator if the piece is damaged or not. In particular, I realized the user interface of the software, while my team focused more on the AI part.


<!--
**FedeMITIC/FedeMITIC** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
