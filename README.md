# Web-Development
Used: HTML,CSS,HTML other medium to create web development
Password Strength Checker - Information File
===========================================

How It Works
-----------
This tool analyzes passwords in real-time using 5 key security criteria:

1. Length Check (8+ characters)
2. Lowercase Letter (a-z)
3. Uppercase Letter (A-Z)
4. Number (0-9)
5. Special Character (!@#$% etc.)

Scoring System:
- Each requirement met = +20 points
- Max score = 100 points

Strength Levels:
0-39%   = Weak (Red)
40-79%  = Medium (Yellow)
80-99%  = Strong (Green)
100%    = Very Strong (Blue)

Key Features:
----------------
🔒 Real-time analysis
👁️ Password visibility toggle
📊 Visual strength meter
📝 Automatic suggestions
📋 One-click copy

Technical Implementation:
-------------------------
Frontend:
- HTML5/CSS3 with responsive design
- Vanilla JavaScript (no frameworks)
- CSS variables for easy theming
- SVG icons for crisp rendering

Security Notes:
---------------
⚠️ This tool runs 100% in your browser
⚠️ No passwords are sent to servers
⚠️ All processing happens locally

Usage Instructions:
-------------------
1. Type your password in the input field
2. View strength meter and feedback
3. Toggle visibility with the eye icon
4. Copy suggested stronger passwords

For Developers:
---------------
Files included:
- index.html (Main structure)
- styles.css (All styling)
- script.js (Core functionality)
- info.txt (This file)

Customization:
- Change colors in :root CSS variables
- Modify requirements in script.js
- Adjust scoring thresholds as needed
