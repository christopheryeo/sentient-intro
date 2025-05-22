# Sentient Intro

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fchristopheryeo%2Fsentient-intro)
[![Vercel Status](https://vercel-badge-ochre.vercel.app/?app=sentient-intro)](https://vercel.com/christopheryeo/sentient-intro)

A corporate introduction and partnership site for Sentient, designed to present Sentient as a valuable, innovative partner to enterprises.

## Purpose

This project introduces Sentient.io’s strengths, solutions, and value proposition for enterprise and government clients. It is intended for partnership, business development, and executive engagement—not for reseller training.

### Recent Changes
- **Content Overhaul:** All reseller training, quizzes, and checklist content have been removed. The site now features concise, marketing-driven sections focused on SmartChat’s differentiators, technical strengths, security, compliance, business impact, and partnership value.
- **Image Assets:** All images from the sales-enablement project have been copied to `static/images` for use in this site.
- **Modern Structure:** The project is organized for easy updates to content and assets, supporting enterprise and partnership marketing needs.
- **Markdown Source of Truth:** As of April 2025, `content/content.md` has been fully synchronized with the latest content and structure from `index.html`. All main sections (Welcome, About, Company Overview, Value, Solutions, SmartChat, Partners, Case Studies, Team, Contact) are now maintained in markdown for ease of editing and future updates. This ensures consistency between the HTML and markdown content. Further edits to the website content should be made in `content/content.md` going forward.
- **April 2025 UI/Content Update:**
    - Updated the "Domain Expertise" text in the "Our Value to Enterprises" section to match `content.md`.
    - Fixed vertical alignment of paragraph text in the four value panels for consistent appearance.
    - Improved the visual consistency of the "Our Value to Enterprises" section with enhanced CSS for the cards.

## Project Structure
- `src/` – HTML files for the website
- `content/` – Markdown content for the website (About, Solutions, Value Proposition, etc.)
- `static/` – Static assets such as CSS, images (`static/images/`), and JavaScript
- `templates/` – HTML templates for rendering the site
- `tests/` – Test scripts (if any site logic or automation is added)

## Usage
Open `src/index.html` in your browser to view the introduction site. You can customize the content in `content/content.md` and extend the design or features as needed for your enterprise or partnership presentations.

### Technical Notes
- **Custom Markdown Parsing:** The About Us page uses a custom markdown parser (instead of marked.js) to ensure correct formatting for headings and bullet points.
- **Image Management:** Place or update images in `static/images/` as needed for your marketing content.

## Git Versions

| Commit Hash | Date       | Description                                                        | Author    |
|:------------|:-----------|:-------------------------------------------------------------------|:----------|
| fb7bbbd     | 2025-05-23 | Update team section with professional backgrounds and README fixes | Chris Yeo |
| c258b87     | 2025-05-21 | Updated company investors and partners list                      | Chris Yeo |
| a4f94c6     | 2025-05-21 | Add Vercel deployment status badge to README                       | Chris Yeo |
| b4c62df     | 2025-05-21 | Added RTF in company facts page                                    | Chris Yeo |
| 82bea4d     | 2025-05-18 | Reorganized project structure and Vercel config                    | Chris Yeo |
| a71d23e     | 2025-04-30 | Adjusted Differentiators section                                   | Chris Yeo |
| 6a75170     | 2025-04-30 | Fixed Singapore map name                                           | Chris Yeo |
| bd07837     | 2025-04-30 | Final Version 1.0 of Sentient-intro                                | Chris Yeo |
| 28a7418     | 2025-04-29 | Visual improvements                                                | Chris Yeo |
| 03ce3f1     | 2025-04-29 | Website content and visual tweaks                                  | Chris Yeo |
| 6f7c580     | 2025-04-29 | Thematic sentient website                                          | Chris Yeo |
| 2a93f16     | 2025-04-29 | Created new content for sentient.io                                | Chris Yeo |
| cd89cda     | 2025-04-29 | Initial project setup                                              | Chris Yeo |

## Contact
For partnership inquiries or to request a demo, contact [Sentient.io](mailto:contact@sentient.io).
