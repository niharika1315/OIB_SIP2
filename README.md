# OIB_SIP2
#  Password Generator & Security Analysis (All-in-One)

This project is a complete Python-based suite for **password generation**, **analysis**, and **security visualization**.  
It combines command-line tools, a graphical interface, data visualization, and entropy-based strength analysis to demonstrate practical cybersecurity concepts.

---

##  What This Project Does

- Generates secure random passwords
- Provides a user-friendly GUI for password creation
- Analyzes password composition (letters, numbers, symbols)
- Measures password strength using **entropy**
- Visualizes results with clear charts

This project is designed to show **how passwords are created, evaluated, and strengthened**.

---

##  Features

###  Password Generation
- Custom password length
- Optional inclusion of:
  - Letters (uppercase & lowercase)
  - Numbers
  - Symbols

###  GUI Password Generator
- Built with **Tkinter**
- Checkbox-based options
- Input validation with error dialogs
- Clipboard copy support

###  Password Composition Visualization
- Counts character types in a password
- Displays distribution using bar charts
- Helps understand password structure

###  Password Entropy Analysis
- Uses the formula:

  \[
  \text{Entropy (bits)} = \text{Length} \times \log_2(\text{Character Pool Size})
  \]

- Plots **Entropy vs Password Length**
- Demonstrates how longer passwords improve security

---

##  Technologies Used
- Python 3
- `string`
- `random` / `secrets`
- `math`
- `tkinter`
- `matplotlib`

---

##  Project Structure

password-security-project/
│
├── password_generator_cli.py
├── password_generator_gui.py
├── password_distribution_visualization.py
├── password_entropy_analysis.py
└── README.md

##  Key Insights

Password length increases entropy linearly

Larger character pools help, but length matters more

Passwords longer than 12 characters are significantly stronger

Visualization makes security concepts easier to understand

## Learning Outcomes

Secure password generation

GUI development with Tkinter

Data visualization using Matplotlib

Entropy-based security analysis

Clean and modular Python coding practices

## Future Enhancements

Password strength meter

Dark mode GUI

Encrypted password storage

Crack-time estimation

Export charts as images or PDFs
