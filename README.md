# IELTS Score Calculator

This project is a simple console application to calculate the average IELTS (International English Language Testing System) score for the academic version. Based on the scores entered by the user for each of the four IELTS components—Listening, Reading, Speaking, and Writing—the application calculates an overall average score and provides an English proficiency level.

## Features

- **Score Input:** Users can input their scores for Listening, Reading, Speaking, and Writing.
- **Automatic Rounding:** Scores are averaged, then rounded based on IELTS scoring rules:
  - Rounded to the nearest half-band (e.g., 7.25 rounds to 7.5, while 7.75 rounds to 8).
- **Proficiency Level Mapping:** Based on the average score, the user is assigned an English proficiency level:
  - **Expert**
  - **Very Good**
  - **Good**
  - **Competent**
  - **Modest**
  - **Incompetent** (if the score is below 5)
  
## Getting Started

### Prerequisites

- .NET SDK (version 5.0 or later)


