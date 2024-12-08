#  AI base Alzheimer's care and Cognitive Support Mobile App - 24-25J-304
# Project ID - 24-25J-304

### Group Leader - IT21228094 - Mendis A.R.P. (randinimendis)/ Component 1 -Monitor Alzheimer's symptoms using cognitive activities.
### Member 2 - IT21225024  - Bhagya P.S (it21225024)/ Component 2  - Innovations in Speech Recognition Technology for Improved Alzheimer's Care and AI Based Support Systems
### Member 3 - IT21215292 - Madhusanka J.A.A. (ashen0909)/ Component 3 - Visual and Auditory Reminders on Adherence to Daily Routines in Alzheimer's Patients
### Member 4 - IT21231100 - Sandaruwan W.M.I.M. (ImalMS)/ Component 4 -Emotional Well-being for Alzheimer's Patients through AI-Driven Personalization and Social Connections

#### This research focuses on developing an *AI-powered smartphone application* to improve the quality of life for *Alzheimer's patients* and their *caregivers. The project aims to address critical challenges faced by patients, including cognitive decline, emotional distress, and difficulty adhering to daily routines. By leveraging advanced technologies like **Natural Language Processing (NLP), **speech recognition, and **machine learning*, the system provides a holistic approach to Alzheimer's care.

# System Architectural Diagram
![Untitled Diagram drawio](https://github.com/user-attachments/assets/7c5a35a0-6153-406e-8d88-480d629015ac)

# Dependencies
#### Front-End Development*
   - *Flutter*: A UI toolkit for building natively compiled applications for mobile from a single codebase.
     - flutter: The main dependency for the framework.
   - *Dart*: The programming language used by Flutter.
     - dart: The core dependency for Dart language features and compiler.
#### Back-End Development*
   - *Firebase*: A suite of cloud services for backend management (e.g., authentication, database, cloud functions).
     - firebase_core: Core functionality for Firebase.
     - firebase_auth: For user authentication.
     - cloud_firestore: For Cloud Firestore database to store user data and application information.
     - firebase_messaging: For push notifications.
     - firebase_storage: For storing user-uploaded content (e.g., photos, documents).
   - *Python*: For machine learning and AI-related tasks.
     - flask: For creating the back-end API (if needed).
     - firebase-admin: To connect Firebase services with the back-end (Python).
#### AI & Machine Learning*
   - *TensorFlow*: A machine learning library for building and training models, especially useful for speech and image recognition.
     - tensorflow: For implementing machine learning models such as speech analysis, pattern recognition, and emotion detection.
     - tensorflow_hub: For pre-trained models if needed for NLP or other AI tasks.
   - *NLP Models*: Natural Language Processing models for speech analysis and AI-based assistant functionality.
     - transformers: A popular NLP library for using pre-trained transformer models like BERT or GPT for speech processing and analysis.
     - nltk: Natural Language Toolkit for text processing and sentiment analysis.
   - *Speech Recognition*: Tools for processing and recognizing speech patterns.
     - speech_recognition: A library to perform speech-to-text conversion and analyze speech.
     - pyaudio: For capturing audio input for real-time speech recognition.
####  *Data Analytics and Pattern Recognition*
   - *Pandas*: For data manipulation and analysis, especially useful for tracking cognitive scores and analyzing trends.
     - pandas: For handling data frames and performing statistical analysis.
   - *NumPy*: For numerical computing, especially when dealing with large datasets from speech analysis or game score tracking.
     - numpy: For numerical array handling.
   - *Scikit-learn*: For machine learning models, particularly for prediction and classification tasks like early detection of cognitive decline.
     - scikit-learn: For classification, regression, and clustering algorithms.
    
###  *Database & Cloud Services*
   - *SQLite*: A lightweight SQL database for storing app-related data locally on the device (for offline functionality).
     - sqflite: For SQLite database integration in Flutter.
   - *Cloud Storage*: Firebase Storage or a similar service for storing media and user-generated content.
     - firebase_storage: For managing file storage.

###  *User Interface Enhancements*
   - *Flutter Packages*: For additional UI elements and accessibility features.
     - flutter_local_notifications: For visual and auditory reminders/notifications for medication or routines.
     - provider: For state management in Flutter, handling user data and updates in real-time.
     - flutter_tts: For text-to-speech functionality, useful for reminders or feedback.
     - cached_network_image: For efficient image loading from network sources (e.g., medication images).

###  *Security and Privacy*
   - *Encryption*: Libraries to ensure user data is stored securely.
     - crypto: For encrypting sensitive data.
     - flutter_secure_storage: For securely storing tokens, passwords, and other sensitive information on the device.

###  *Real-Time Communication & Notifications*
   - *Firebase Cloud Messaging (FCM)*: For push notifications to users and caregivers regarding reminders, updates, or alerts.
     - firebase_messaging: For sending and receiving notifications.
   - *WebSockets (Optional)*: For real-time communication between caregivers and patients.
     - web_socket_channel: To enable real-time data exchange.

###  *Testing and Debugging*
   - *Flutter Testing Tools*: For unit testing and integration testing within the Flutter framework.
     - flutter_test: For testing Flutter widgets and functionality.
   - *Mocking and Dependency Injection*: For testing various back-end services.
     - mockito: For mocking dependencies during tests.


