project:
  name: "OMR-AutoEval Dashboard"
  description: >
    A web-based OMR evaluation & scoring system with 
    automated bubble detection, role-based access, and 
    real-time analytics dashboard.

ascii_logo: |
    ____  __  ___   ___       _        _            
   / __ \/  |/  /  /   | ____(_)_____ ( )_____  ___ 
  / / / / /|_/ /  / /| |/ ___/ / ___/ |// ___/ / _ \
 / /_/ / /  / /  / ___ / /__/ (__  )   (__  ) /  __/
/_____/_/  /_/  /_/  |_\___/_/____/  /____/  \___/ 

features:
  - Role-based login (Admin, Evaluator)
  - Dashboard with key metrics (total sheets, avg score, subject analysis)
  - Answer key upload (supports multiple sets)
  - OMR sheet upload & automated evaluation
  - Student-wise & subject-wise reporting
  - Export results as CSV/Excel
  - Modern TailwindCSS based UI
  - Dark/Light theme support

tech_stack:
  frontend: 
    - HTML5
    - TailwindCSS
    - JavaScript
  backend: 
    - Flask / FastAPI
  database: 
    - SQLite / PostgreSQL
  charts: 
    - Chart.js
  utilities: 
    - OpenCV
    - NumPy
    - Pillow
    - Scikit-learn (optional)

project_structure: |
  OMR-AutoEval/
  ├── index.html       # Main Application
  ├── /assets          # Images, logo, static files
  ├── /css             # Tailwind / Custom styles
  ├── /js              # Charts & Scripts
  └── README.yaml      # Documentation (this file)

run_locally:
  clone: git clone https://github.com/username/omr-autoeval.git
  navigate: cd omr-autoeval
  launch:
    mac: open index.html
    linux: xdg-open index.html
    windows: start index.html

demo_credentials:
  admin:
    email: "admin@autoeval.com"
    password: "admin123"
  evaluator:
    email: "evaluator@autoeval.com"
    password: "user123"

screenshots:
  - login page
  - dashboard overview
  - omr upload modal
  - evaluation report

future_enhancements:
  - AI-powered bubble classification for ambiguous marks
  - Multi-batch and historical analytics
  - PDF report auto-generation
  - Integration with ERP/LMS
  - Mobile-first responsive design

  note: "Developed for Innomatics Hackathon 2025 (Theme 1 - CV)"

license: "MIT"
github_star: "⭐ If you like this project, give it a star on GitHub!"
