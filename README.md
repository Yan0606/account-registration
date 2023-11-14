#Firebase + Vanilla JavaScript Project
Overview
This repository contains a web application developed using Firebase and Vanilla JavaScript. The project focuses on managing data related to clients, suppliers, and products, storing this information in Firebase Firestore. This README provides information on setting up the project and highlights key features.

Features
Client Management: Capture and store client details, including name, contact information, and other relevant data.
Supplier Management: Record and manage supplier information, such as company name, contact details, and product offerings.
Product Management: Keep track of product details, including name, description, and supplier information.
Firebase Integration: Utilize Firebase Firestore to store and retrieve data, ensuring a scalable and reliable backend for the application.
Getting Started
Prerequisites
Firebase Account: Ensure you have a Firebase account and create a new project on the Firebase Console.

Firebase Configuration:

Obtain your Firebase project configuration (API key, authDomain, projectId, etc.) from the Firebase Console.
Replace the placeholder values in the firebaseConfig object located in js/firebase.js with your actual configuration.
Enable Firebase Services:

Enable Firestore in your Firebase project.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
Open the index.html file in your preferred web browser or host the project on a web server.

Usage
Open the web application in your browser.

Use the provided forms to add, edit, or delete client, supplier, and product data.

The data will be automatically synchronized with Firebase Firestore in real-time.

Folder Structure
css/: Contains stylesheets for the project.
js/: Includes JavaScript files, such as app.js for application logic and firebase.js for Firebase configuration and setup.
index.html: The main HTML file for the web application.
Contributing
Feel free to contribute to the project by submitting bug reports, feature requests, or code improvements. Please follow the contribution guidelines.

License
This project is licensed under the MIT License.

Acknowledgments
Special thanks to the Firebase and JavaScript communities for their valuable resources and support.

Happy coding! 🚀 
