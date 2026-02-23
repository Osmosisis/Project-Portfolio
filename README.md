# Osmond Lim – Technical Project Portfolio

This repository contains selected past projects I have contributed to, demonstrating backend development, AI, and full-stack engineering skills.

---

## 🚀 Featured Projects

### 1. CareConnect – A multi-module web application built for seniors - School Project
**Description:** A multi-module web application built for seniors to manage daily tasks, medications, appointments, health records and social events—all in one place.

**Tech Stack:** 
- Node.js & Express
- Microsoft SQL Server (via mssql)
- Authentication: bcrypt + jsonwebtoken (JWT)
- Validation: joi
- Front-end: static HTML/CSS/JS (served from /public)
- FullCalendar javascript API : Interactive drag & drop calendar interface for reminders
- Cloudinary API: easy to access database for image uploadds 

**My Contributions:** 
- Medication Manager: track dosages & schedules
- Emergency Quick-Dial : allows user to easily check and find emergency contacts and details

🔗 Repository: [https://github.com/Osmosisis/BED-Assignment](https://github.com/s10270089/BED-Assignment-Team.git)

---

### 2. FED-ASSG2 – E-Commerce Marketplace Website - School Project
**Description:** A fully functional front-end e-commerce website that allows users to browse products, create listings, manage a shopping cart, and complete a simulated checkout process. The platform focuses on user experience, intuitive navigation, and interactive client-side functionality.

**Tech Stack:** 
- HTML5  
- CSS3  
- JavaScript  
- jQuery  
- Figma (Wireframing & Prototyping)

**My Contributions:** 
- Implemented user authentication interface (sign up / sign in flows)  
- Developed dynamic product listing and product detail pages  
- Built interactive shopping cart functionality (add/remove items, total updates)  
- Implemented client-side checkout validation logic  
- Conducted manual cross-browser and responsive testing  
- Designed UI flow and wireframes using Figma  

🔗 Repository: [https://github.com/Osmosisis/Frontend_Development_Project](https://github.com/Yoshi-np/FED-ASSG2.git)

---

### 3. Aviation Sentiment Classification System (PyTorch NLP Pipeline) - School Project
**Description:** A modular NLP-based sentiment classification system built in Python using PyTorch to analyse aviation-related passenger feedback. The project focuses on designing a clean end-to-end text processing pipeline, implementing and improving recurrent neural network architectures, and evaluating model performance through structured experimentation and validation.

**Tech Stack:** 
- Python
- PyTorch (Embedding, RNN, GRU, CrossEntropyLoss, Adam Optimizer)
- Scikit-learn (class weighting, metrics)
- NumPy
- Jupyter Notebook / Google Colab
- Matplotlib (training curve visualisation)

**My Contributions:** 
- Designed and implemented a full text preprocessing pipeline (tokenisation, vocabulary mapping, sequence padding, tensor conversion)
- Structured the model using object-oriented design with custom nn.Module classes
- Implemented both baseline (Vanilla RNN) and improved (GRU) architectures with configurable hyperparameters
- Integrated class-weighted loss to handle dataset imbalance
- Built reusable training and evaluation loops with device management (CPU/GPU support)
- Performed structured experimentation, validation tracking, and error analysis using confusion matrices
- Documented architectural decisions and iterative improvements for maintainability and reproducibility

🔗 Repository: [https://github.com/Osmosisis/Sentiment_Classification_Sysytem](https://github.com/karotalol/CVNL-Assignment.git)

---

### 4. AI-Driven MRT Route Planning & Operational Intelligence System - School Project
**Description:** An AI-powered decision support system that models Singapore’s MRT network under both Today and Future (TEL/CRL/T5) configurations. The system integrates graph search algorithms for route optimisation, resolution-based logical inference for service rule validation, and a Bayesian Network for crowding risk prediction under uncertainty.

**Tech Stack:** 
- Python
- Graph Search Algorithms (BFS, DFS, GBFS, A*)
- Propositional Logic & Resolution-Based Inference
- Bayesian Network (Probabilistic Reasoning)
- NetworkX (graph modelling)
- Jupyter Notebook
- Data from LTA / data.gov.sg

**My Contributions:** 
- Designed and implemented the logical inference engine using propositional logic and resolution
- Modelled MRT operational constraints (segment availability, network mode, T5 readiness) as CNF rules
- Implemented contradiction detection to validate advisory consistency
- Developed route validation logic to detect invalid routes under service rules
- Built rule-violation identification using clause-removal strategy for explainable reasoning
- Designed and tested multiple inference scenarios across Today and Future MRT modes

🔗 Repository: [https://github.com/Osmosisis/AICT_Logical_Inference](https://github.com/Aurora-2512/AICT_Assg1.git)


---

### 5. Branch Escalation & Smart Kiosk Queue System - School + OCBC Project
**Description:** A full-stack enquiry escalation system that bridges digital and physical customer journeys. Users submit enquiries through a chatbot, receive a QR code, and scan it at a physical branch kiosk to automatically generate a context-aware queue ticket. The system ensures seamless handover from chatbot to branch staff without requiring customers to repeat their issue.

**Tech Stack:** 
- Frontend: React (Vite), JavaScript, HTML/CSS
- Backend: Node.js, Express.js
- Database: PostgreSQL
- APIs: RESTful APIs (custom-built), QR payload validation
- DevOps & Tools: Docker, Docker Compose, GitHub, Postman
- Architecture: MVC-inspired backend structure, modular service layers

**My Contributions:**
- Designed and implemented the kiosk queue ticketing system, linking QR-based digital enquiries to physical branch queue tickets to ensure seamless escalation from chatbot to branch
- Built backend endpoints for `/kiosk/scan`, including:
  - QR payload validation (`enquiryId`, `branchId`, timestamp checks)
  - Enquiry and branch verification against the database
  - Duplicate scan prevention logic to block multiple active tickets
  - Transaction-safe ticket generation with proper error handling
- Designed and structured key database tables (`branch`, `branch_daily_counter`, `kiosk_session`, `queue_ticket`) with primary/foreign keys, constraints, and relationships to maintain data integrity and enforce business rules
- Implemented atomic transaction handling (`BEGIN` / `COMMIT` / `ROLLBACK`) to ensure consistent ticket creation and prevent partial writes during failures
- Developed logic to prevent multiple active tickets for the same enquiry on the same day, including expiry and status validation checks
- Integrated the frontend kiosk interface with backend APIs using environment-based configuration for clean separation between development and deployment environments
- Containerised the full stack using Docker and Docker Compose to enable consistent local development, testing, and deployment workflows

🔗 Repository: [https://github.com/Osmosisis/Full_Stack_Development_Project](https://github.com/ernestangg/FSDP-Team22.git)

---

## 📌 Other Projects

- First ever front end project → [https://github.com/Osmosisis/Frontend_Development_Assignment_1](https://github.com/Osmosisis/FED-ASSG-1-Osmond.git)
- Kiosk Queue System → [https://github.com/Osmosisis/kiosk_prototype](https://github.com/Osmosisis/kiosk-prototype-v2.git)
