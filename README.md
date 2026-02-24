markdown
# Shahadat Hussain · Personal Website

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://shahadat-hussain.github.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Personal academic website and portfolio for **Dr. Shahadat Hussain**, Postdoctoral Researcher at Khalifa University specializing in additive manufacturing, shape memory alloys, and mechanical metamaterials.

🌐 **Live site:** [https://shahadat-hussain.github.io](https://shahadat-hussain.github.io)

---

## 📋 About This Website

This is a professional, single-page academic website designed to showcase research, publications, certifications, and professional experience. The site features:

- **Clean, modern design** with responsive layout for all devices
- **Research highlights** with interactive cards
- **Publication list** with live DOI links
- **Certifications section** with verification links
- **Professional navigation** and contact information
- **Schema.org markup** for better SEO visibility

---

## 🚀 Quick Start

### Prerequisites
- A GitHub account
- Git installed on your computer (optional, for local development)

### One-Click Setup

1. **Create a new repository** named `shahadat-hussain.github.io`

2. **Add your files**
   - Upload `index.html` to the repository
   - Add your profile photo as `profile.jpg`
   - (Optional) Add `favicon.ico`

3. **Enable GitHub Pages**
   - Go to repository **Settings** → **Pages**
   - Under "Branch", select `main` and `/ (root)`
   - Click **Save**

4. **Your site is live!** Wait 1-2 minutes, then visit `https://shahadat-hussain.github.io`

---

## 📁 Repository Structure
shahadat-hussain.github.io/
├── index.html # Main website (single HTML file)
├── profile.jpg # Your profile photo
├── favicon.ico # Browser tab icon (optional)
└── README.md # This file

text

The entire website is contained in a single HTML file for simplicity and easy maintenance.

---

## 🛠️ Customization Guide

### Updating Personal Information

Edit `index.html` and modify:

- **Name & Title**: Look for `<h1>` and `.hero-subtitle`
- **Affiliation**: Update the `.hero-affiliation` span
- **Research description**: Edit the `.hero-description` paragraph
- **Email**: Update all instances of `contact@shahadathussain.com`

### Updating Publications

Each publication follows this structure:
```html
<li class="pub-item">
  <span class="pub-year">2025</span>
  <div class="pub-content">
    <strong>Your paper title</strong>
    <div class="pub-venue">Journal Name, Year</div>
    <div class="pub-doi"><a href="DOI_URL">DOI: 10.xxxx/xxxxx</a></div>
  </div>
</li>
Adding/Removing Sections

The site sections are clearly commented:

html
<!-- Research Highlights -->
<!-- Current work at Khalifa University -->
<!-- Publications -->
<!-- Certifications -->
<!-- News / Updates -->
<!-- Footer & Contact -->
To add a new section, copy an existing section block and modify the content.

Updating Social Links

Find the social links in the footer:

html
<div class="social-links">
  <a href="https://github.com/drshahadathussain" target="_blank"><i class="fab fa-github"></i></a>
  <a href="https://scholar.google.com/citations?user=tQNSWaAAAAAJ" target="_blank"><i class="fab fa-google-scholar"></i></a>
  <a href="https://www.linkedin.com/in/shahadathussain" target="_blank"><i class="fab fa-linkedin"></i></a>
  <a href="https://www.researchgate.net/profile/Shahadat-Hussain" target="_blank"><i class="fab fa-researchgate"></i></a>
</div>
