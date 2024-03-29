# Resume Ranking System

## Overview

The Resume Ranking System is a powerful tool designed to streamline the recruitment process by automatically evaluating and ranking resumes based on relevant criteria.

## Architecture

<p align="center">
  <img src="./assets/architecture.png" alt="Architecture" />
  <br>
  <em>System Architecture</em>
</p>

## PPT

[PPT](https://www.canva.com/design/DAF90kFVr0U/IcGPnaQfF6a9zd5PVgEB9w/view?utm_content=DAF90kFVr0U&utm_campaign=designshare&utm_medium=link&utm_source=editor).

## Video 

[Video](https://youtu.be/AqkNJVWGXc8).
## Features

- **Job Analysis**:

  - Manage JDs
  - Analyze JDs to standard forma
  - Multilingual Support.
  - Average runtime: 30 seconds

- **Candidate Analysis**:

  - Upload and manage CVs (PDF/ Word)
  - Extract Personal information.
  - Analyze CVs to standard format.
  - Multilingual Support.
  - Average runtime: 60 seconds

- **Matching Analysis**:

  - Manage candidates & jobs with a
    many-to-many relationship
  - Analyze and score candidate based
    on each key field.
  - Average runtime: 30 seconds

- **Score, Rank & Comment**:
  - Provides a summary analysis of the
    matching between candidates and
    jobs
  - Score and rank candidate.



## Getting Started

Follow these steps to get the Resume Ranking System up and running:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/AmanGuptaCoder/Resume-Ranking-System.git
   ```

2. **Update environment**:

   - Update **OPENAI_API_KEY** in `backend/.env.api.local`

     ```bash
     OPENAI_API_KEY="your-key"
     ```

   - Update **IP Address** in `frontend/.env.production`
     ```bash
     NEXT_PUBLIC_API_URL=http://<your-ip-address>/backend
     ```

3. **Install Dependencies**:

   ```bash
   cd resume-ranking
   docker compose build
   ```

4. **Run the System**:

   ```bash
   docker compose up
   ```


