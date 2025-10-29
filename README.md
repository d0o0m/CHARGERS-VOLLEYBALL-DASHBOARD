# CHARGERS-VOLLEYBALL-DASHBOARD
This repository holds the .html for my Volleyball Statistics Dashboard.  This html is being offered free of charge to the Centennial Collegiate Chargers Volleyball coaching staff and players.
Volleyball Stats Dashboard
A comprehensive, real-time volleyball statistics tracking application designed for live match analysis and performance tracking. Built as a single-page Progressive Web App (PWA) optimized for mobile devices and tablets.
Overview
This dashboard provides coaches, players, and statisticians with an intuitive interface to track detailed volleyball match statistics in real-time. The application captures rally-by-rally data, individual player performance metrics, and team dynamics throughout a match.
Key Features
Live Match Tracking

Real-time Scoring: Track scores for both teams with large, easy-to-read displays
Rally-by-Rally Logging: Record every point with customizable tags and notes
Set Management: Automatically tracks set winners and manages best-of-5 match formats
Momentum Tracking: Visual indicators show scoring runs and momentum shifts
Timeout Alerts: Automatic notifications when teams reach timeout thresholds

Player Statistics

Individual Metrics: Track serves (aces, errors, in), attacks (kills, errors, attempts), blocks (stuffs, touches), and digs
Rotation Tracking: Monitor player positions throughout rotations
Libero Management: Dedicated tracking for libero substitutions
Performance Analysis: Calculates hitting percentages, serve efficiency, and other key metrics

Team Analytics

Serve Receive Quality: Track first-ball passing effectiveness
Error Analysis: Record ball-handling errors, net violations, and other team mistakes
Momentum Visualization: Interactive charts showing scoring trends and momentum shifts
Rotation Performance: Analyze team effectiveness by rotation position

Data Management

Local Storage: All data persists in browser localStorage for offline functionality
Import/Export: Complete match data can be exported to JSON and imported later
State Management: Comprehensive undo functionality for recent actions
Sample Data: Load demo data to explore features

Visual Design

Mobile-First: Optimized touch interface for courtside use
Dark Theme: Reduced eye strain for extended use
Responsive Layout: Adapts seamlessly to phones, tablets, and desktop screens
Visual Feedback: Color-coded buttons with haptic-style animations for instant feedback
PWA Ready: Installable on mobile devices with offline capability

Technical Architecture
Single-File Application
The entire application is contained in a single HTML file, making it:

Easy to deploy (no build process required)
Portable (can run from any web server or local file system)
Self-contained (no external dependencies beyond web fonts)

Technology Stack

Vanilla JavaScript: No frameworks, pure ES6+ JavaScript for performance
CSS3: Modern styling with gradients, animations, and responsive design
LocalStorage API: Persistent data storage
Canvas API: Chart rendering for momentum visualization
Web Fonts: Google Fonts (Orbitron) for score displays

Data Structure
The application maintains a comprehensive state object including:

Match metadata (teams, match ID, timestamps)
Full roster with player numbers and names
Rally-by-rally records with rotation snapshots
Individual player events with context
Set-by-set results
Configurable alert thresholds

Use Cases
Coaching & Analysis

Track player performance in real-time during matches
Identify rotation strengths and weaknesses
Make data-driven substitution decisions
Review detailed post-match statistics

Player Development

Self-analysis of individual performance
Track improvement over multiple matches
Understand positional effectiveness
Set personal performance goals

Team Statistics

Maintain season-long statistics
Compare performance across different opponents
Identify team trends and patterns
Generate reports for team meetings

Live Streaming & Broadcasting

Display live stats during streamed matches
Provide viewers with detailed game insights
Track historical performance during broadcasts

Installation & Usage
Quick Start

Open index.html in any modern web browser
Click "New Match" to start tracking
Enter roster information
Set starting lineup
Begin tracking rallies and player actions

Mobile Installation (PWA)

Open in Safari (iOS) or Chrome (Android)
Tap "Add to Home Screen"
Access like a native app with full offline functionality

Deployment

Deploy to any static hosting (GitHub Pages, Netlify, Vercel)
No server-side processing required
No build step or compilation needed

Browser Compatibility
Tested and optimized for:

iOS Safari 14+
Chrome 90+
Firefox 88+
Edge 90+

Copyright & License
Copyright © 2024-2025. All Rights Reserved.
This software and its associated documentation are proprietary and confidential. Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited without explicit written permission from the copyright holder.
Restrictions

No Redistribution: This code may not be copied, distributed, or transmitted in any form or by any means without prior written authorization
No Derivative Works: Creating derivative works based on this software is prohibited without explicit permission
No Commercial Use: This software may not be used for commercial purposes without a separate licensing agreement
Educational Use Only: Any use for educational, personal, or evaluation purposes must maintain all copyright notices and this license text

Disclaimer
THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY ARISING FROM THE USE OF THIS SOFTWARE.
Attribution Requirements
If you have received explicit written permission to use portions of this software, you must:

Retain all copyright notices
Provide clear attribution to the original author
Include a copy of this license with any distribution
Clearly mark any modifications made to the original code

Contact
For licensing inquiries, permissions, or questions regarding this software, please contact the copyright holder through the repository maintainer.

Version History
Current Version

Full-featured stat tracking
PWA capabilities
Export/Import functionality
Momentum visualization
Mobile-optimized interface

Contributing
This is a proprietary project. Contributions, suggestions, and feedback may be submitted through GitHub issues, but all contributions become the property of the copyright holder upon submission. By submitting any contribution, you agree to transfer all rights, title, and interest in the contribution to the copyright holder.
Support
For questions, bug reports, or feature requests, please open an issue in this repository. Please note that support is provided on a best-effort basis with no guaranteed response time.

Built for coaches, players, and volleyball enthusiasts who demand precision statistics and real-time insights.
