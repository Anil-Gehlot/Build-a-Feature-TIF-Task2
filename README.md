# Hiring Process Automation: Multi-Step Form with Live Preview

This project is a small module for automating the hiring process, featuring a multi-step form that allows real-time preview updates based on user input. The main goal is to create a seamless experience where recruiters can input job requisition details, job details, and interview settings while previewing and validating their input in real-time.

## Tech Stack

- **TypeScript**
- **Next.js** (Framework)
- **Chakra UI** (Component Library)
- **Formik** (Form Handling)

## Features

1. **Multi-Step Form Navigation**
   - **Tabs**: The form is divided into three tabs:
     - **Requisition Details**
     - **Job Details**
     - **Interview Settings**
   - **Validation**: Each form step requires successful validation before moving to the next step.
   - **Persistence**: On navigating back to a previous tab, previously filled values remain saved.

2. **Live Draft Preview**
   - A draft card displays a live preview of the form data as users type, enabling instant feedback.
   - All form values across tabs are shown in real-time, dynamically updating with each input.


