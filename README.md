<a href="https://warriorwhocodes.com"><img src="repo_images/header.jpg"></a>

<p align="center">
  <a href="https://ankushsinghgandhi.github.io">
    <img src="https://img.shields.io/badge/Website-3b5998?style=flat-square&logo=google-chrome&logoColor=white" />
  </a>
  <a href="http://twitter.com/ankushsgandhi">
    <img src="https://img.shields.io/badge/-Twitter-blue?style=flat-square&logo=twitter&logoColor=white" />
  </a>
   <a href="https://www.linkedin.com/in/ankush-singh-gandhi-2487771aa/">
    <img src="https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat-square&logo=Linkedin&logoColor=white" />
  </a>
  <a href="https://dev.to/@ankushsinghgandhi">
    <img src="https://img.shields.io/badge/-Dev.to-grey?style=flat-square&logo=dev.to&logoColor=white"/>
  </a>
  <a href="https://stackoverflow.com/users/13790266/ankush-singh">
    <img src="https://img.shields.io/badge/-Stackoverflow-orange?style=flat-square&logo=stackoverflow&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/ankushsinghgandhi/">
    <img src="https://img.shields.io/badge/-Leetcode-yellow?style=flat-square&logo=Leetcode&logoColor=white"/>
  </a>
    <a href="https://www.hackerrank.com/ankushsgandhi">
    <img src="https://img.shields.io/badge/-HackerRank-green?style=flat-square&logo=Hackerrank&logoColor=white"/>
  </a>
    <a href="https://www.hackerearth.com/@bhanusinghank">
    <img src="https://img.shields.io/badge/-Hackerearth-purple?style=flat-square&logo=Hackerearth&logoColor=white"/>
  </a>
</p>


# ASG ATS Resume Template (LaTeX)

📄 A clean, one-page, ATS-friendly **resume template** built with LaTeX.  
Designed for software developers, engineers, and tech professionals who want a professional-looking resume with **perfect alignment, section separators, and consistent formatting**.  

---

## ✨ Features
- **One-page layout** – recruiter-friendly and ATS-readable  
- **Minimalist design** – no clutter, no unnecessary graphics  
- **Tinos font** (requires XeLaTeX or LuaLaTeX)  
- **Thin section dividers** for clear separation  
- **Bold section titles & project names**  
- **Custom macros** for sections, job lines, and consistent bullet formatting  
- **Overleaf-ready** and GitHub-hosted  

---

## 📂 Files
- `resume.tex` → Main LaTeX source file  
- `resume.pdf` → Example compiled resume  
- `template.tex` → Blank version with placeholders (`Company Name`, `Project Title`, etc.)  
- `LICENSE` → MIT License (free to use and adapt)  

---

## 🚀 How to Use

### Option 1: Overleaf
1. Open [Overleaf](https://overleaf.com/)  
2. Create a new project → "Upload Project"  
3. Upload the `.tex` file (and optional `.pdf` preview)  
4. Compile with **XeLaTeX** or **LuaLaTeX**  

### Option 2: Local (TeX Live / MikTeX)
```bash
# Compile with XeLaTeX
xelatex resume.tex
````

---

## 🛠️ Customization

* **Header**: Replace name, phone, email, LinkedIn, GitHub, etc.
* **Sections**: Modify `\Section{}` commands for *Summary, Experience, Projects, Skills...*
* **Spacing**: Adjust `\renewcommand{\baselinestretch}{}` and list item spacing in preamble.
* **Font**: Change `\setmainfont{Tinos}` to any system font (requires XeLaTeX).

---

## 📸 Preview

![Resume Preview](resume-preview.png)

*(Screenshot of the compiled PDF)*

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and share.

---

## 🙌 Credits

Created by [Ankush Singh Gandhi](https://warriorwhocodes.com/)
Published on **GitHub** + **Overleaf** for the community 🚀
