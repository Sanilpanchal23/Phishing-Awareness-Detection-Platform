Phishing Awareness & Detection Platform
An interactive, single-page web application designed to educate users on the dangers of phishing by simulating a realistic attack, from the initial bait to the post-breach analysis. This project aims to tackle one of the most common vectors for cyber attacks by providing a safe, hands-on learning environment.

Try the Live Demo Here!
Key Features
Realistic Phishing Simulation: A convincing fake corporate login page, complete with a mimicked browser UI and a deceptive URL, to create an authentic-looking threat.

Immediate Feedback Mechanism: A visual animation demonstrates how credentials are exfiltrated in real-time upon submission, providing a powerful and memorable consequence for the user's actions.

In-depth Educational Debrief: A dedicated page that breaks down the specific red flags of the phishing attempt (e.g., URL obfuscation, spelling errors, urgent language), turning the simulation into a valuable training tool.

Dynamic Campaign Dashboard: A management-level dashboard that visualises key performance indicators (KPIs) of the phishing campaign, including compromise rates and a live feed of user actions.

Fully Responsive & Self-Contained: The entire experience is built within a single, static file, making it highly portable and accessible on any device without requiring a backend.

Visual Showcase
<!--
INSTRUCTIONS:
1. Take screenshots of your application at the key stages listed below.
2. Name the files exactly as specified in the placeholders (e.g., phishing-login-page.png).
3. Place the image files in a folder named screenshots within your project directory.
4. Update the path if you use a different folder structure.
-->

The Bait: Malicious Login Portal

The Consequence: Credential Theft





The Lesson: Educational Debrief

The Analysis: Campaign Dashboard





Technology Stack
This project was built from the ground up using fundamental web technologies, with a focus on a modern, clean user interface.

HTML5: For the core structure and content of the application.

Tailwind CSS: For a utility-first approach to styling, enabling a rapid and responsive design process.

JavaScript (ES6+): For all client-side logic, including DOM manipulation, state management, and event handling to create the interactive simulation.

Core Concepts & Skills Demonstrated
This project showcases a blend of frontend development expertise and a strong understanding of fundamental cybersecurity principles.

Cybersecurity Awareness & Principles
Social Engineering: Demonstrates a practical understanding of how attackers use psychological manipulation (e.g., urgency, authority) to deceive users.

Phishing Vector Analysis: The ability to deconstruct a phishing attack, identifying and explaining common red flags like deceptive domain names, spelling errors, and non-standard links.

Threat Visualisation: Translating an abstract cyber threat into a tangible, visual experience to enhance user understanding and retention.

Security Education: Proves an ability to develop tools that contribute to improving an organisation's security posture through user training.

Frontend Development & UI/UX
Dynamic DOM Manipulation: Extensive use of JavaScript to control the user journey, switching between pages, updating dashboard metrics, and creating animations without page reloads.

State Management: Client-side logic to track the state of the simulation (e.g., users compromised, users reported) and reflect it accurately across the UI.

CSS Animations & Transitions: Implementation of fluid animations for page transitions and the credential theft sequence to create a polished, professional user experience.

Responsive Design: A mobile-first approach ensuring the simulation is effective and accessible across desktops, tablets, and smartphones.

User Journey Mapping: Thoughtfully designing the application flow from the initial phishing page to the final educational debrief, ensuring a logical and impactful learning path.

How It Works
The simulation follows a clear, multi-stage user journey:

The Bait: The user is presented with the phishing-page, a fake login portal designed to harvest credentials.

The Decision: The user can either:

Enter their details and click "Sign In", triggering the credential theft sequence.

Wisely identify the threat and click "Report this Page".

The Consequence & Lesson: If compromised, the user is shown the theft-animation followed by the education-page, which details the mistakes made.

The Analysis: The user is then guided to the dashboard-page, where their action (compromised or reported) is added to a live feed, demonstrating how such campaigns are tracked.

Local Development
As this is a self-contained static application, no complex build process is required.

Clone the repository:

git clone [https://github.com/your-username/phishing-awareness-platform.git](https://github.com/your-username/phishing-awareness-platform.git)

Navigate to the directory:

cd phishing-awareness-platform

Open the index.html file in your browser.
You can do this directly from your file explorer or use a simple live server extension in your code editor for the best experience.

Future Enhancements
This platform serves as a strong foundation that could be expanded with further features:

Multiple Campaign Templates: Introduce different phishing scenarios (e.g., fake parcel delivery, tax rebate scam) to broaden the training scope.

User Scoring System: Implement a system to score users based on their actions, gamifying the learning process.

Backend Integration: Connect the platform to a backend service and database (e.g., using Node.js and PostgreSQL) to persist campaign results and manage user data for real-world organisational use.