Dental Assistant Training: Anxious Patient Scenarios
This repository contains a single-page interactive learning module designed for dental assistants and healthcare staff. It focuses on identifying behavioral cues of patient anxiety and practicing evidence-based communication strategies to improve patient comfort and clinical outcomes.

🎯 Learning Objectives
By completing this activity, learners will be able to:

Identify non-verbal and verbal cues of patient distress (e.g., rapid speech, avoidance, skepticism).

Apply de-escalation techniques such as the "Stop Signal" and "Validation vs. Avoidance."

Navigate professional boundaries by knowing when to escalate concerns to the Dentist.

🛠️ Technical Stack
HTML5/CSS3: Structured for accessibility and clean layout.

Tailwind CSS: Used for rapid, responsive UI development.

Lucide Icons: Provides a modern, consistent visual language for scenario triggers.

JavaScript (Vanilla): Powers the "reveal" logic for tips and responses without the need for heavy frameworks.

🧩 Key Features for Learning Designers
Scaffolded Feedback: Each scenario includes a "Get a Tip" button to provide pedagogical guidance before the learner views the "Correct" response.

Progressive Disclosure: Uses accordion-style reveals to manage cognitive load and prevent learners from seeing answers prematurely.

Role-Play Simulation: High-fidelity quotes and behavioral descriptions simulate real-world chairside interactions.

Mobile-First Design: The responsive grid ensures the training can be accessed on tablets or smartphones during clinic breaks.

🚀 How to Use
Clone or Download: Save the index.html file to your local machine.

Open: Double-click the file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).

Deployment: Since this is a standalone file with CDN-linked dependencies (Tailwind and Lucide), it can be easily hosted on GitHub Pages, a company intranet, or uploaded as a web object to an LMS like Articulate Storyline or Canvas.

🎨 Customization
The module uses a custom CSS root for branding. To align with your clinic's brand, update the following variables in the <style> block:

CSS
:root {
    --brand-primary: #532A8C;   /* Main Header/Icons */
    --brand-accent: #7ABF49;    /* Response Buttons */
    --brand-bg: #F2F2F2;        /* Background */
}
Developed for healthcare professionals to bridge the gap between clinical knowledge and patient empathy.
