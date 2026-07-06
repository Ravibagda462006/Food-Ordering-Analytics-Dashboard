# Food Ordering Behaviour & Customer Trends - Analytics Dashboard

A premium, highly responsive data analytics portfolio website that showcases the findings and interactive Tableau visuals for the **Food Ordering Behaviour and Customer Trends** project. Designed with a dark theme, modern typography, glassmorphism card layouts, and smooth micro-interactions.

Live Demo Link: *[Insert your GitHub Pages URL here once deployed]*

## Project Overview

This project analyzes transactional data from on-demand food delivery platforms to evaluate customer demand cycles, logistics timelines, courier distribution profiles, and regional trends. The analysis combines data preparation in Python (Pandas, NumPy) and SQL, culminating in interactive Tableau visualizations.

## Key Project Features

- **Interactive Dashboard:** Dynamic exploration of platform throughput across cuisines, delivery times, and driver ratings.
- **Guided Data Story:** A slide-by-slide data narrative tracing order trajectories, bottleneck zones, and peak congestion timings.
- **Documented Insights:** Comprehensive write-ups on analytical objectives, KPIs, dataset variables, and recommended platform improvements.
- **Premium SaaS Aesthetics:** Tailored styling with responsive flex grids, glassmorphic blur cards, radial glow designs, and scroll-linked animation transitions.

## Technology Stack

- **Data Cleaning & Preparation:** Python (Pandas, NumPy), SQL (MySQL/PostgreSQL), Microsoft Excel
- **Visualization Canvas:** Tableau Desktop / Tableau Public
- **Frontend Architecture:** HTML5 (Semantic Structure), CSS3 (Custom Variables, Transitions, Glassmorphism, Layouts), JavaScript (IntersectionObserver, Count-up animations, navigation controllers)
- **External Typography & Graphics:** Google Fonts (Poppins & Inter), Font Awesome Icons

## Project Architecture

```
Food-Ordering-Analytics-Dashboard/
│
├── index.html                  # Homepage (Hero, Live KPI Counters, Tool badging, Dashboard features)
├── dashboard.html              # Tableau Dashboard container (styled responsive frame)
├── story.html                  # Tableau Story canvas container (styled narrative frame)
├── about.html                  # In-depth Project documentation & insights
│
├── assets/
│   ├── css/
│   │   └── style.css           # Custom variables, layout models, responsive breakpoints, animations
│   ├── js/
│   │   └── app.js              # Active nav state highlight, fade-in scroll trigger, count-up animation
│   ├── images/                 # Image assets (can be populated if required)
│   └── icons/                  # Icon assets (can be populated if required)
│
└── README.md                   # Technical repository documentation
```

## How to Integrate Your Tableau Embed Code

To embed your finished Tableau Dashboard and Story:

1. **Get the Embed Code:**
   - Go to your published dashboard on Tableau Public or Tableau Cloud.
   - Click the **Share** button in the toolbar.
   - Copy the **Embed Code** HTML snippet.

2. **Paste in Dashboard Page:**
   - Open `dashboard.html` in your code editor.
   - Find the `<div class="embed-inner">` container.
   - Replace the placeholder `<div class="tableau-placeholder-visual">...</div>` with your copied Tableau embed snippet.

3. **Paste in Story Page:**
   - Open `story.html` in your code editor.
   - Find the `<div class="embed-inner">` container.
   - Replace the placeholder `<div class="tableau-placeholder-visual">...</div>` with your copied Tableau Story embed snippet.

## Deploying to GitHub Pages

This portfolio is built using static HTML, CSS, and JS, making it fully ready for direct deployment on GitHub Pages:

1. Create a repository on GitHub named `Food-Ordering-Analytics-Dashboard`.
2. Commit and push all files to your repository's default branch (e.g. `main`).
3. Navigate to **Settings** -> **Pages** in your repository's GitHub menu.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose your branch (usually `main`) and folder (`/ (root)`), then click **Save**.
6. GitHub will generate a deployment URL for your portfolio within a few minutes.
