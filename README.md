🐾 Pawsitive Pet Academy

Tagline: Caring for pets. Building confident owners.

Location: Durban, South Africa

Established: 2023 (Founded by Sarah Smith)

Module: Work-Integrated Learning (XHAW5112) – Task 3 Final Submission

Group: 3 Peas In a Pod

📖 Project Overview

Pawsitive Pet Academy is a responsive, multi-page web platform designed to bridge educational gaps in pet care, animal behaviour, emergency first aid, grooming, and pet-related business management. Built to mirror the academy's native mobile application and Figma wireframes, the website allows everyday pet owners and aspiring animal-care professionals to explore curricula, compare programmes, calculate automated multi-course quotations (with volume discounts and 15% South African VAT), and submit validated inquiries.

👥 Team Members (Group: 3 Peas In a Pod)

Name

Role

Student Number

Israa Williams

Team Leader & Documentation Lead

ST10501763

Shaun Stroebel

Team Secretary & Lead Web Developer

ST10507489




✨ Key Features & Functionality

Centralized Course Catalogue (JS/script.js): Uses a structured JavaScript array (coursesData) storing IDs, names, categories, durations, and tuition fees for all 7 academy courses.

Automated Multi-Course Quotation Engine:

Dynamically computes subtotals via Array.reduce().

Applies tiered multi-course volume discounts (0% for 1 course, 5% for 2 courses, 10% for 3 courses, 15% for 4+ courses).

Computes 15% South African VAT and renders an itemized quotation breakdown table without reloading the page.

Flexible Client-Side Validation & Error Handling:

Normalizes South African and international telephone formats (stripping spaces, dashes, brackets, and +27 prefixes) prior to regex verification.

Displays real-time inline field errors and alert banners on both the Fee Calculator and Contact Us pages.

Responsive Navigation & Drop-Down Menu: Sticky header featuring a CSS hover drop-down menu providing direct access to all 6-Month Professional Programmes and 6-Week Short Courses.

Cohesive Visual Identity: Built with semantic HTML5 and a unified external stylesheet (CSS/style.css) utilizing Flexbox/Grid layouts and the official brand palette (Terracotta #DA6F43, Teal #268D81, Navy #285062, and Cream #F8F9FA).

📂 File Structure

PeasInAPod/ (Root Repository)
│
├── index.html                  # Home Page (Hero banner, promotional video, services overview, footer)
├── About.html                  # About Us (Academy history, founder Sarah Smith, mission & vision)
├── Services.html               # Courses Catalogue & Responsive Course Fee Comparison Table
├── calculator.html             # Interactive Fee Calculator, Discount Tiers & Itemized Quote Output
├── Contact.html                # Validated Inquiry Form, Durban Campus Details & Embedded Map
├── Presentation.html           # Task 3 Slide Deck Presentation
├── README.md                   # Project Documentation, File Structure & Changelog
│
├── CSS/
│   └── style.css               # Global Stylesheet (Flexbox/Grid, Brand Palette, Dropdown Menu, Forms)
│
├── JS/
│   └── script.js               # Course Array Data, Fee Calculator Logic, Discounts, VAT & Validation
│
├── Media/
│   ├── logo.jpeg               # Official Pawsitive Pet Academy Logo
│   ├── logo-no-background.jpg  # Transparent/Header Logo Variant
│   ├── hero1.jpg               # Home Page Hero Imagery
│   └── Video.mp4               # Academy Promotional Video Showcase
│
└── Courses/                    # Individual Course Curriculum Pages
    ├── canine-obedience.html   # Professional Programme (12 Weeks Practical / R1,500)
    ├── pet-grooming.html       # Professional Programme (12 Weeks Practical / R1,500)
    ├── animal-behaviour.html   # Professional Programme (12 Weeks Practical / R1,500)
    ├── pet-business.html       # Professional Programme (12 Weeks Practical / R1,500)
    ├── puppy-care.html         # Short Course (6 Weeks / R750)
    ├── pet-first-aid.html      # Short Course (6 Weeks / R750)
    └── dog-walking.html        # Short Course (6 Weeks / R750)


🛠️ Course Offerings & Pricing Matrix

Course Title

Category

Duration

Tuition Fee

Canine Obedience Training

Professional Programme

6 Months (12 Weeks Practical)

R1,500.00

Pet Grooming

Professional Programme

6 Months (12 Weeks Practical)

R1,500.00

Animal Behaviour

Professional Programme

6 Months (12 Weeks Practical)

R1,500.00

Pet Business Management

Professional Programme

6 Months (12 Weeks Practical)

R1,500.00

Puppy Care

Short Course

6 Weeks

R750.00

Pet First Aid

Short Course

6 Weeks

R750.00

Basic Dog Walking

Short Course

6 Weeks

R750.00

📝 Changelog (Task 1 → Task 3 Evolution)

[v3.0.0] – Task 3 Final Submission & Rubric Optimization

Added: Centralized JS/script.js containing the coursesData array and .reduce() summation logic for automated fee calculations.

Added: Multi-course volume discount tiers (5%, 10%, 15%) and 15% VAT calculation with dynamic itemized quotation table rendering.

Added: Flexible regex phone number normalization (replace(/[\s\-\(\)\+]/g, '')) supporting local South African formats (082...) and international prefixes (+27...).

Added: Sticky header navigation with an interactive CSS hover Courses Drop-Down Menu across all 12 HTML pages.

Added: Structured Course Comparison & Fee Table on Services.html.

Fixed: Prevented unintended page reloads on calculator.html during fee calculation by resolving form submit event handling (event.preventDefault() / type="button").

Fixed: Replaced duplicated "About Us" placeholder text on animal-behaviour.html with dedicated animal psychology curriculum content.

Fixed: Corrected misplaced <header> elements inside <head> tags on index.html and standardized footers site-wide.

[v2.0.0] – Task 2 Mobile App & Interactive Prototyping

Added: 12 high-fidelity mobile application screens in Figma aligned with the desktop design system.

Added: Linked interactive user flows (Home → Courses → Course Details → Quote → Enrolment → Confirmation).

Added: Initial React Native mobile application repository (PawsitiveApp) and unlisted YouTube video walkthrough.

[v1.0.0] – Task 1 Discovery, Branding & Wireframing

Added: Brand identity guidelines, custom logo (paw print + graduation cap + plus sign), and colour palette.

Added: 12 low- and high-fidelity desktop wireframes in Figma covering core user journeys and accessibility standards (WCAG 2.2).

🚀 How to Run Locally

Clone the repository:

git clone https://github.com/ShaunTheBeast/XHAW5112_THE_LAST_SUBMISSION/


Navigate into the project directory:

cd PeasInAPod


Open index.html directly in any modern web browser (Google Chrome, Microsoft Edge, Firefox, or Safari), or launch via the Live Server extension in Visual Studio Code.
