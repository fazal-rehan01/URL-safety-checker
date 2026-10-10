# Advanced URL Safety Checker

## Overview
The **Advanced URL Safety Checker** is designed to analyze URLs for potential phishing indicators. Unlike basic keyword matchers, this tool employs heuristic analysis, including protocol verification, keyword boundary detection, and IP address identification, to provide a more accurate risk assessment.

## Features
- **Protocol Verification**: Flags URLs using insecure HTTP protocols.
- **Keyword Analysis**: Uses Regular Expressions to detect suspicious terms within word boundaries, reducing false positives.
- **IP Address Detection**: Identifies URLs that use raw IP addresses instead of domain names, a common tactic in phishing attacks.
- **Risk Scoring System**: Provides a tiered warning system (Low Risk, Caution, High Risk) based on multiple factors.
- **Responsive Design**: Clean, modern UI that works on desktop and mobile devices.

## Technologies Used
- **HTML5**: Structural markup.
- **CSS3**: Styling with Flexbox for layout and modern UI components.
- **JavaScript (ES6+)**: Client-side logic for URL parsing and heuristic analysis.

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone  https://github.com/fazal-rehan01/My-phishing-detector.git
   
