<!-- markdownlint-disable MD012 MD013 -->

# Aneesh Ajayakumar — AI/ML Portfolio

![Portfolio](https://img.shields.io/badge/Portfolio-AI%2FML%20Engineer-ffb727?style=for-the-badge)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

## About the Website

This repository contains my personal portfolio website, created to present my background, experience, technical skills, certifications, and project work in Artificial Intelligence, Machine Learning, Generative AI, and web development.

I am an MSc Artificial Intelligence graduate with experience in Python, machine learning, deep learning, LLM applications, RAG, LangChain, LangGraph, AI agents, TensorFlow, Keras, and full-stack web technologies.

The website serves as an interactive version of my CV and gives recruiters, collaborators, and developers a clear overview of my work.

## Main Features

- Responsive design for desktop, tablet, and mobile screens
- Professional introduction and About section
- Complete online resume with education and work experience
- Categorised technical skills and tools
- Filterable project showcase
- Detailed project modals with technologies and achievements
- Certifications and professional training gallery
- Downloadable CV
- Direct links to GitHub, LinkedIn, email, phone, and WhatsApp
- Smooth navigation, animations, counters, and image previews

## Website Sections

| Section | Description |
| --- | --- |
| Home | Introduction, professional title, CV download, and navigation |
| About | Career profile, AI/ML focus, contact details, and key statistics |
| Resume | Professional summary, skills, education, certifications, experience, and projects |
| Services | Machine learning, generative AI, data analysis, and web application capabilities |
| Projects | Filterable project cards with complete details, technology stacks, and results |
| Certifications | AI, analytics, MATLAB, web development, Android, and cybersecurity training |
| Contact | Email, phone, WhatsApp, LinkedIn, GitHub, and contact form |

## Featured Projects

### 1. TravelMind — AI-Powered Travel Planner

An AI travel assistant that creates personalised itineraries using destination, budget, duration, traveller type, and interests.

- Built with Python, LangChain, OpenAI API, JavaScript, and Netlify Functions
- Uses a secure serverless function to protect the API key
- Produces structured daily itineraries and magazine-style PDF travel plans
- Includes accommodation, food, transport, packing, budget, and travel suggestions

[View TravelMind](https://travel-mind-ai-planner.netlify.app/)

### 2. Fruit Recognition System Using CNN

A deep-learning image classification system trained to recognise multiple fruit categories from the Fruits-360 dataset.

- Built with TensorFlow, Keras, OpenCV, NumPy, and Python
- Uses image preprocessing and data augmentation
- CNN architecture includes convolution, pooling, dense, and dropout layers
- Achieved 96% test accuracy

[View Repository](https://github.com/Aneesh236/Fruit-recognition-system-using-CNN)

### 3. Fake Automobile Insurance Detection

My MSc research project focused on detecting fraudulent automobile insurance claims while addressing severe class imbalance.

- Compared Random Forest, XGBoost, and Support Vector Machine models
- Applied SMOTE and ADASYN oversampling methods
- Evaluated results using Accuracy, Precision, Recall, F1 Score, and ROC-AUC
- Improved the reported prediction accuracy from 98.55% to 99.87%

[View Repository](https://github.com/Aneesh236/Fake-insurance-detection-using-ADASYN-and-SMOTE)

### 4. Alleppey Pub ERP

A restaurant and pub management application covering customer ordering, administration, billing, and AI-supported sales insights.

- Customer menu, cart, checkout, and order-confirmation workflow
- Admin, employee, menu-management, and order-management interfaces
- JavaScript and LocalStorage-based frontend data handling
- FastAPI REST backend designed for AI sales analysis

### 5. Human Blood Directory

A database-driven platform designed to connect blood donors and recipients during emergencies.

- Donor search using blood group, location, and availability
- Responsive user interface and administrative features
- Built with HTML, CSS, JavaScript, PHP, and MySQL
- Designed to improve access to donor information and emergency response

### 6. Cybersecurity Prediction Suite

A collection of machine-learning projects for predicting common cybersecurity threats.

- Brute-force attack prediction
- Ransomware prediction
- DDoS attack prediction
- Malware prediction
- Network intrusion prediction

The projects include data preparation, feature engineering, model comparison, and evaluation using Python, Pandas, NumPy, scikit-learn, and SQL.

## Technical Skills Represented

### Artificial Intelligence and Machine Learning

`Generative AI` `Large Language Models` `RAG` `LangChain` `LangGraph` `AI Agents` `Prompt Engineering` `TensorFlow` `Keras` `scikit-learn` `Deep Learning` `CNN` `Predictive Modelling`

### Programming and Data

`Python` `JavaScript` `Java` `C++` `SQL` `PHP` `Pandas` `NumPy` `Data Analysis` `Feature Engineering` `Model Evaluation`

### Frontend and Tools

`HTML5` `CSS3` `Bootstrap` `Git` `GitHub` `VS Code` `Jupyter Notebook` `Gradio` `Hugging Face`

## Website Technology Stack

- HTML5 for the page structure and content
- CSS3 and Bootstrap for layout and responsive styling
- JavaScript for navigation, filters, project interactions, and animations
- Bootstrap Icons and Boxicons for interface icons
- GLightbox for image previews
- Isotope for portfolio filtering
- Swiper for responsive sliders
- PureCounter for animated statistics
- PHP contact-form structure for supported web servers

## Project Structure

```text
aneesh_web/
├── index.html
├── inner-page.html
├── portfolio-details.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── img/
│   │   ├── intern/
│   │   ├── portfolio/
│   │   └── testimonials/
│   ├── js/
│   │   └── main.js
│   └── vendor/
├── forms/
│   └── contact.php
└── README.md
```

## Run the Website Locally

No package installation or build process is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/Aneesh236/My-personal-website.git
   ```

2. Open the project directory:

   ```bash
   cd My-personal-website
   ```

3. Start a local development server:

   ```bash
   python -m http.server 8000
   ```

4. Open the following address in a browser:

   ```text
   http://localhost:8000
   ```

You can also open `index.html` directly, although a local server provides more consistent browser behaviour.

## Deployment

As a static portfolio, the website can be deployed using:

- GitHub Pages
- Netlify
- Vercel
- Hostinger or another standard web host

For GitHub Pages, open the repository's **Settings → Pages**, choose **Deploy from a branch**, select the main branch and root folder, and save.

> [!NOTE]
> GitHub Pages hosts static files only. The included PHP contact form requires a PHP-enabled server and mail configuration. On a static host, the direct email, LinkedIn, phone, and WhatsApp contact options will continue to work.

## Future Improvements

- Add live deployment links for every completed project
- Connect the contact form to a serverless form service
- Add dark and light theme options
- Improve accessibility and automated performance testing
- Add project screenshots and short demonstration videos
- Continuously update the portfolio with new AI/ML projects

## Contact

**Aneesh Ajayakumar**  
AI/ML Engineer  
Bangalore, Karnataka, India

- Email: [aneesh.ajay39@gmail.com](mailto:aneesh.ajay39@gmail.com)
- LinkedIn: [linkedin.com/in/aneesh-ajayakumar](https://www.linkedin.com/in/aneesh-ajayakumar)
- GitHub: [github.com/Aneesh236](https://github.com/Aneesh236)
- Portfolio repository: [My-personal-website](https://github.com/Aneesh236/My-personal-website)

## Credits

The website is based on the **Laura** portfolio template by [BootstrapMade](https://bootstrapmade.com/laura-free-creative-bootstrap-theme/) and has been customised with my own content, projects, resume information, styling, and functionality.

Please review the [BootstrapMade licence terms](https://bootstrapmade.com/license/) when redistributing or modifying the original template assets.

---

If you find my work interesting or would like to collaborate on an AI/ML project, feel free to connect with me through LinkedIn or email.
