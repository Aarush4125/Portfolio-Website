**Aarush Kukade - The Developer's Path 🚀**

Welcome to the source code for my interactive portfolio website! Instead of a traditional resume, I wanted to create a more engaging experience. This project presents my professional journey as a simple, gamified timeline that you can explore.

Portfoilo Link: https://portfolio-website-five-xi-99.vercel.app

About The Project
"The Developer's Path" is a minimalist gamified resume where visitors can navigate through the key milestones of my career using a simple character interface. As you move the character along the progress bar, different sections of my resume—from my skills and projects to my work experience—are displayed in a clean, modern content box.

The goal was to build something fun, memorable, and lightweight, all within a single deployable file.

Features ✨
Interactive Navigation: Use the left and right arrow keys to move the animated character between checkpoints.

Animated Character: The player character features custom-coded idle and run animations powered by JavaScript and sprite sheets.

Dynamic Content: All resume information is loaded from a simple JavaScript object, making it easy to update.

Sleek UI: A clean, dark-mode aesthetic with a "Press Start 2P" pixel font and subtle gradient effects for a retro-modern feel.

Zero Dependencies: The entire project runs in a single index.html file with no external libraries (besides Tailwind CSS via CDN).

Built With 🛠️
This project was built from scratch using core web technologies:

HTML5

CSS3 (with Tailwind CSS for rapid styling)

JavaScript (ES6) for all game logic, animations, and interactivity.

Getting Started
Because this project uses JavaScript to load image assets, you'll need to run it from a local server to avoid browser security (CORS) errors.

Prerequisites
You should have a modern web browser.

Installation & Running
Clone the repository:

git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)

Navigate to the project directory:

cd your-repo-name

Add Assets: Place your warrior_idle.png and warrior_run.png sprite sheets in the same directory as index.html.

Run a local server. The easiest way is using the serve package:

npx serve

Open your browser and go to the local address provided (usually http://localhost:3000).

How to Customize
All resume content is stored in the resumeData constant within the <script> tag in index.html. You can easily edit the title and content for each section to update the portfolio with your own information.
