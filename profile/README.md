- # 🎮 DCIST-T2 Organization

  Welcome to the DCIST-T2 organization! This organization serves as a central hub for policy collection and evaluation across multiple academic institutions.

  ## 🔗 Quick Links
  - [GAMMS Repository](https://github.com/GAMMSim/gamms)
  - [GAMMS Documentation](https://gammsim.github.io/gamms/start/)
  - [The League Repository](https://github.com/GAMMSim/League)
  - [The League Documentation](https://mdgleague.notion.site/)
  - [Game Rules](https://mdgleague.notion.site/Game-Rules-1a10355f26b9805696fec54b13cf857f)

  ## 🏆 Leaderboard

  | Rank | Attacker  Policy | Defender Policy |
  | ---- | ---------------- | --------------- |
  | 1    |                  |                 |
  | 2    |                  |                 |
  | 3    |                  |                 |
  
  ## 📋 Table of Contents
  - [Organization Structure](#-organization-structure)
  - [Repository Overview](#-repository-overview)
  - [Getting Started](#-getting-started)
  - [Important Notes](#%EF%B8%8F-important-notes)
  
  ## 📁 Organization Structure
  
  ```bash
  DCIST-T2
  ├── The League
  ├── (Team Name)
  │   └── submission
  │       ├── attacker_policy
  │       │   └── (...policy.py)
  │       └── defender_policy
  │           └── (...policy.py)
  └── (Other Teams)
  ```
  
  ## 📑 Repository Overview
  
  ### The League Repository
  - Contains the mass evaluation code used to run and evaluate submitted policies
  - Maintains transparency in the evaluation process
  
  ### Team Repositories
  Each participating team has their own repository with the following structure:
  - A `submission` folder containing:
    - `attacker_policy`: For attacker policy submissions
    - `defender_policy`: For defender policy submissions
  - Teams can submit multiple policies
  - Additional folders and files can be used for testing and debugging, but only policies in the `submission` folder will be evaluated
  
  ## 🚀 Getting Started
  
  ### 1. Joining the Organization
  If you're not yet a member of the DCIST-T2 organization:
  - [Email the admin](mailto:billy.qi03@gmail.com) with the following information:
    - Your GitHub username
    - Your email address
    - Your team name
  - Alternatively, have an existing team member invite you
  
  ### 2. Access and Permissions
  - After joining, you'll be assigned to your team's repository
  - You'll have access to your team's repository and public repositories within the organization
  
  ### 3. Submitting Policies
  1. Clone your team's repository
  2. Add your policy files to the appropriate folder under `submission/`
     - Attacker policies go in `submission/attacker_policy/`
     - Defender policies go in `submission/defender_policy/`
  3. Commit and push your changes before the submission deadline
  
  ## ⚠️ Important Notes
  - Only policies in the `submission` folder will be evaluated
  - Teams can use other parts of their repository for testing and development
  - The evaluation process will automatically pull from all repositories
  
  Thank you for participating in the DCIST-T2 project! Good luck with your submissions! 🌟
