# Syllogiser

**A Venn and Euler Diagram Tool for Categorical Logic**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-30-green.svg)]()
[![Platform](https://img.shields.io/badge/platform-web-lightgrey.svg)]()

Syllogiser is an interactive, educational web application for visualizing and analyzing categorical propositions and syllogistic arguments using Venn and Euler diagrams. It supports both Boolean and Aristotelian logic systems and provides comprehensive validity checking for syllogisms.

![Syllogiser Screenshot](https://jwilam.github.io/Syllogiser/syllogiser.png)

## 🌟 Features

### Core Functionality
- **Two Operating Modes**
  - **Statement Mode**: Analyze single categorical propositions (A, E, I, O types) with two-circle diagrams
  - **Syllogism Mode**: Analyze categorical syllogisms with three-circle diagrams, including validity checking

- **Dual Diagram Support**
  - Create both **Venn Diagrams** (fixed overlapping circles with shading)
  - Create **Euler Diagrams** (resizable and repositionable circles showing actual relationships)

- **Interactive Canvas**
  - Drag to reposition circles
  - Resize circles by dragging edges
  - Color regions by clicking/tapping
  - Add and move existence markers (X)
  - Touch-friendly for tablets and mobile devices

### Logic Analysis
- **Automatic Proposition Type Detection**: Identifies A, E, I, O proposition types
- **Distribution Badges**: Shows which terms are distributed (D) or undistributed (xD)
- **Syllogistic Figure Detection**: Automatically determines the figure (1-4) of syllogisms
- **Validity Checking**: Identifies all 24 valid syllogistic forms
  - 15 unconditionally valid forms (Boolean & Aristotelian)
  - 9 conditionally valid forms (Aristotelian only)
- **System Proving**: Automated checking of all six validity rules
- **Fallacy Detection**: Identifies specific fallacies when rules are violated

### Educational Features
- **Comprehensive Help System**: Built-in documentation with examples
- **Sorites Support**: Copy functions for analyzing chain syllogisms
- **Alternative Notation**: Shows "No S are P" for E-type propositions
- **Knowledge Tables**: Quick reference for proposition types and figures
- **Web Search Integration**: Quick lookup of syllogistic forms

### User Experience
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Resizable Panels**: Adjust workspace to your preference
- **Dual Diagrams**: Compare different representations side by side
- **Boolean/Aristotelian Toggle**: Switch between logic systems
- **10 Color Options**: Full color palette for diagram shading
- **Layout Options**: Choose upright or inverted diagram orientation

## 🚀 Quick Start

### Online Demo
Visit the live demo at: https://jwilam.github.io/Syllogiser/Syllogiser_v30.html
### Local Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/jwilam/syllogiser.git

2. Navigate to the directory:
   ```bash
   cd syllogiser

3. Open in browser:
   ```bash
   # Simply open index.html in any modern web browser
   open index.html      # macOS
   start index.html     # Windows
   xdg-open index.html  # Linux

No build process, no dependencies, no server required — it’s a single, self-contained HTML file!

### System Requirements
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Minimum screen width: 320px (mobile-friendly)

## 📝 Citation
If you use Syllogiser in your research, teaching, or publications, please cite:

### APA Format
Lam, W. I. (2026). Syllogiser: A Venn and Euler diagram tool for categorical logic [Computer software]. GitHub. https://github.com/jwilam/syllogiser

### MLA Format
Lam, Wai Ip. Syllogiser: A Venn and Euler Diagram Tool for Categorical Logic. Version 30, 2026, github.com/jwilam/syllogiser.

### Chicago Format
Lam, Wai Ip. “Syllogiser: A Venn and Euler Diagram Tool for Categorical Logic.” Computer software. GitHub, 2026. https://github.com/jwilam/syllogiser.

BibTeX
   ```bibtex
   @software{lam2026syllogiser,
     author    = {Lam, Wai Ip},
     title     = {Syllogiser: A Venn and Euler Diagram Tool for Categorical Logic},
     year      = {2026},
     version   = {30},
     publisher = {GitHub},
     url       = {https://github.com/jwilam/syllogiser},
     note      = {Interactive web application for visualizing categorical logic}
   }

## 🤝 Contributing
Contributions are welcome and appreciated! Please read the guidelines below before contributing.

### Ways to Contribute
- Report Bugs: Open an issue describing the bug, steps to reproduce, and expected behavior
- Suggest Features: Open an issue with the “enhancement” label
- Improve Documentation: Fix typos, add examples, or clarify explanations
- Submit Code: Fork, branch, code, test, and submit a pull request
- Share: Tell others about Syllogiser, write tutorials, or create videos

### Reporting Issues
When reporting bugs, please include:

- Browser name and version
- Operating system
- Steps to reproduce the issue
- Expected behavior vs. actual behavior
- Screenshots if applicable
- Console errors if any
