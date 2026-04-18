# Asem Hisham — Android Developer Portfolio

A personal portfolio website for **Asem Hisham Aboheba**, an Android Developer based in Cairo, Egypt. The site is a single-file, self-contained HTML portfolio with a dark, modern aesthetic, bilingual support (English & Arabic), and smooth UI interactions.

---

## 🌐 Live Preview

Open [Portfolio](https://portfolio-delta-one-73.vercel.app/) directly in any modern web browser — no server or build step required.

---

## ✨ Features

- **Bilingual (EN / AR)** — Full English and Arabic support with RTL layout switching via a language toggle button
- **Custom Cursor** — Animated dot + ring cursor that reacts to hoverable elements (hidden on touch devices)
- **Smooth Scroll & Fade Animations** — Sections animate in using the Intersection Observer API
- **Responsive Design** — Mobile-first breakpoints at 900px and 600px, with a hamburger menu for small screens
- **Grid Background Overlay** — Subtle green-tinted grid pattern for a tech-forward look
- **No Dependencies** — Pure HTML, CSS, and vanilla JavaScript; no frameworks, no build tools

---

## 📄 Sections

| # | Section | Description |
|---|---------|-------------|
| — | **Hero** | Name, tagline, CTA buttons (View Work / Contact), and key stats |
| 01 | **About** | Background, education, GPA, contact details, and philosophy quote |
| 02 | **Skills** | Skill cards covering Languages, Architecture, Data & Storage, UI/UX, Tooling, and Problem Solving; plus ECPC achievement highlight |
| 03 | **Projects** | Three featured Android projects |
| 04 | **Contact** | Email, LinkedIn, and phone contact links |

---

## 🗂️ Projects Showcased

1. **Eqtebasaty** — Data management & financial tracking app using Kotlin, Room Database, MVVM, and Material Design Bottom Sheets
2. **RESTful API Integration App** — Dynamic content app consuming REST APIs with Retrofit, JSON parsing, and LiveData
3. **Cloud-Synced Mobile App** — Firebase-backed app with real-time sync and offline support via Room Database (MVI architecture)

---

## 🛠️ Tech Stack

**Languages:** Kotlin, Java, XML  
**Architecture:** MVVM, MVI, Clean Architecture  
**Data & Storage:** Room Database, Firebase, RESTful APIs, JSON  
**UI/UX:** Material Design, XML Layouts, Bottom Sheets, Jetpack  
**Tooling:** Android Studio, Git, Gradle  
**Web (this portfolio):** HTML5, CSS3, Vanilla JavaScript

---

## 📁 File Structure

```
asem_portfolio.html   ← Entire site in a single self-contained file
README.md             ← This file
```

All styles, scripts, and content are embedded inline in the HTML file.

---

## 🚀 Usage

1. Clone or download the repository
2. Open `asem_portfolio.html` in a browser
3. No installation, no build step, no internet connection required (fonts load from Google Fonts if online)

---

## 🌍 Internationalization

The site supports **English** and **Arabic** out of the box. Switching languages:

- Toggles `lang` and `dir` attributes on the `<html>` element (`ltr` / `rtl`)
- Swaps all `data-en` / `data-ar` content attributes across every element
- Switches fonts between **Roboto** (English) and **Cairo** (Arabic)

---

## 📬 Contact

| Channel | Details |
|---------|---------|
| Email | asemhishamzsc@gmail.com |
| LinkedIn | [linkedin.com/in/asem-hisham](https://linkedin.com/in/asem-hisham) |
| Phone | +201093567911 |
| Location | Cairo, Egypt |

---

## 📜 License

This portfolio is personal work by Asem Hisham Aboheba. All rights reserved. Feel free to use it as inspiration, but please do not redistribute it as your own.
