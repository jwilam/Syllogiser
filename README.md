# Syllogiser

**A Venn and Euler Diagram Tool for Categorical Logic**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-30-green.svg)]()
[![Platform](https://img.shields.io/badge/platform-web-lightgrey.svg)]()

Syllogiser is an interactive, educational web application for visualizing and analyzing categorical propositions and syllogistic arguments using Venn and Euler diagrams. It supports both Boolean and Aristotelian logic systems and provides comprehensive validity checking for syllogisms.

![Syllogiser Screenshot](https://jwilam.github.io/Syllogiser/syllogiser.png)

---

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

---

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

---

## 📘 Usage Guide

### Statement Mode

Statement Mode is designed for analyzing individual categorical propositions.

1. Switch to **Statement Mode** using the toggle at the top of the left panel.
2. Enter terms in the **Premise** row:
   - Type the subject term (e.g., “dogs”)
   - Type the predicate term (e.g., “mammals”)
3. Select logical operators:
   - Quantifier: “All” or “Some”
   - Copula: “are” or “are not”
4. View the proposition type: the type (**A, E, I, O**) is automatically displayed.
5. Create a diagram: use the canvas on the right to visualize the proposition.
6. Copy to syllogism: use the copy buttons to transfer premises to **Syllogism Mode**.

### Syllogism Mode

Syllogism Mode is designed for analyzing categorical syllogisms.

1. Switch to **Syllogism Mode** using the toggle (default mode).
2. Enter **Premise 1**:
   - Subject term (e.g., “men”)
   - Predicate term (e.g., “mortal”)
   - Select quantifier and copula
3. Enter **Premise 2**:
   - Subject term (e.g., “Greeks”)
   - Predicate term (e.g., “men”)
   - Select quantifier and copula
4. Select **Conclusion** terms from the dropdown menus:
   - The system requires exactly **3 unique terms** across both premises.
   - Subject and Predicate dropdowns are populated automatically.
5. Check validity: click the **Check Validity** button to analyze.
6. View results: see the mood–figure code, traditional name, and validity status.
7. Use **System Proving**: click to see detailed rule-by-rule analysis.

---

## ✍️ Creating Diagrams

### Basic Operations

| Action                 | Mouse            | Touch                   |
|------------------------|------------------|-------------------------|
| Color a region         | Click on region  | Tap on region           |
| Paint multiple regions | Click and drag   | Touch and drag          |
| Move a circle          | Drag from center | Touch and drag from center |
| Resize a circle        | Drag from edge   | Touch and drag from edge   |
| Move existence marker  | Drag the **X**   | Touch and drag the **X**   |

### Toolbar Functions

- **Color Palette**: Select a color before clicking on regions
- **Clear All**: Remove all coloring from the diagram
- **Add Existence**: Place an **X** marker on the canvas
- **Clear Existence**: Remove all **X** markers
- **Boolean/Aristotelian Toggle**: Switch logic systems

### Tips for Effective Diagrams

- Use **Diagram 1** for premise visualization
- Use **Diagram 2** for conclusion or comparison
- For **Euler diagrams**: resize and reposition circles to show containment or exclusion
- For **Venn diagrams**: shade regions to show empty sets
- The transparent color (white button) acts as an eraser

---

## 🔗 Sorites (Chain Syllogisms)

Syllogiser supports the analysis of sorites through copy functions:

1. In **Statement Mode**:
   - “Premise → Syllogism P1”: Copies current statement to Premise 1
   - “Premise → Syllogism P2”: Copies current statement to Premise 2
2. In **Syllogism Mode**:
   - “Conclusion → P1”: Copies the conclusion to Premise 1 for chaining
3. Workflow for sorites:
   - Analyze first pair of premises
   - Check validity
   - Copy conclusion to P1
   - Enter next premise in P2
   - Repeat until final conclusion

---

## 🤝 Contributing
Contributions are welcome and appreciated! 

### Support the Project
If you find Syllogiser useful:

- Star the repository on GitHub
- Share it with colleagues and students
- Cite it in your publications
- Report bugs and suggest improvements

### Ways to Contribute
- Report Bugs: Open an issue describing the bug, steps to reproduce, and expected behavior
- Suggest Features: Open an issue with the “enhancement” label
- Improve Documentation: Fix typos, add examples, or clarify explanations
- Submit Code: Fork, branch, code, test, and submit a pull request
- Share: Tell others about Syllogiser, write tutorials, or create videos

### Feedback
We welcome your feedback to improve Syllogiser! You can:

- Open an issue on GitHub
- Send an email with suggestions
- Share your use cases and experiences

### Reporting Issues
When reporting bugs, please include:

- Browser name and version
- Operating system
- Steps to reproduce the issue
- Expected behavior vs. actual behavior
- Screenshots if applicable
- Console errors if any

---

## ☎️ Contact & Support
### Getting Help
Documentation: Read this README and the built-in Help modal

### 👤 Author
LAM Wai Ip 林葦葉

- Institution: Faculty of Education, The University of Hong Kong (HKU)
- Official Website: https://web.edu.hku.hk/faculty-academics/jwilam
- Personal Website: https://jwilam.com
- Email (Official): jwilam@hku.hk
- Email (Personal): jwilam@gmail.com

---

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
