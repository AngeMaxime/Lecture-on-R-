# 📊 R & RStudio for Data Science — Lecture Notes & Scripts

> A curated collection of R Markdown lecture notes covering the fundamentals and applied techniques of Statistical analysis using R and RStudio.

---

## 🧭 Introduction

Welcome to this repository! This space is dedicated to sharing **practical, lecture-based learning materials** for data analysis using the **R programming language** and **RStudio** as the development environment.

The materials here were originally developed and delivered as academic lectures, covering a wide range of topics: from the very basics of R syntax to more advanced data manipulation, visualization, and statistical modeling workflows. Whether you are a student, a self-learner, or a practitioner looking to sharpen your R skills, this repository is designed to be a clear and accessible resource.

All content is written in **R Markdown (`.Rmd`)** format, which combines narrative explanations, executable R code, and rendered outputs in a single, readable document. This format allows you to not only read but also **run, modify, and experiment** with the code directly in your own RStudio environment.

---

## 💡 Utility of this Repository

This repository serves several important purposes:

- **Educational resource**: Each file corresponds to a structured lecture, walking you through concepts step by step with explanations and real code examples.

- **Reproducible learning**: Because the materials use R Markdown, every example is fully reproducible. You can knit the files to generate HTML, PDF, or Word reports with results embedded.

- **Reference material**: Beyond learning, these files can serve as a reference you come back to when working on your own data science projects. Need a reminder on how to reshape data or build a ggplot2 visualization? The answer is in these notes.

- **Hands-on practice**: The code chunks are designed to be run interactively. You are encouraged to modify them, break things, and experiment — that is how real learning happens.

- **Open and free**: All materials are publicly available. There are no paywalls, no sign-ups required. Download, use, share, and build on them freely.

---

## 🛠️ How to Use this Repository

Follow the steps below to get the most out of these materials:

### 1. Prerequisites

Make sure you have the following installed on your machine:

- [**R**](https://cran.r-project.org/) (version 4.0 or higher recommended)
- [**RStudio**](https://posit.co/download/rstudio-desktop/) (free Desktop version)
- The **`rmarkdown`** and **`knitr`** packages (install with `install.packages(c("rmarkdown", "knitr"))`)

Additional packages may be required depending on the lecture. Each `.Rmd` file lists the packages it uses at the top — you can install them all with `install.packages()`.

### 2. Download the Materials

You can get the files in two ways:

**Option A — Clone the repository (recommended):**
```bash
git clone https://github.com/AmgeMaxime/Lecture-on-R.git
```

**Option B — Download as a ZIP:**  
Click the green **`Code`** button at the top of this page → **Download ZIP** → extract the folder on your machine.

### 3. Open in RStudio

1. Launch RStudio.
2. Go to **File → Open Project** (if a `.Rproj` file is present) or **File → Open File** to open an individual `.Rmd` file.
3. Once the file is open, you can:
   - **Run individual code chunks** by clicking the green ▶ button on each chunk.
   - **Run the entire document** interactively from top to bottom.
   - **Knit the document** (using the **Knit** button) to produce a rendered HTML, PDF, or Word output.

### 4. Follow the Lectures in Order

The files are named and numbered sequentially (e.g., `Lecture1_Operators_in_R.Rmd`, `lecture2_packages_R.Rmd`, etc.). It is recommended to follow them **in order**, especially if you are a beginner, as each lecture may build on concepts from the previous one.

---

## 📝 Remarks

A few important notes to keep in mind:

- **R version compatibility** — These materials were developed and tested with recent versions of R (4.x). If you are using an older version, some functions or syntax may behave differently. Keeping R and your packages up to date is always a good practice.

- **Package versions** — R packages are updated frequently. If you encounter an error after installing a package, it may be a version compatibility issue. The session info at the end of each knitted document lists the exact package versions used.

- **Operating system differences** — File paths work slightly differently on Windows vs. macOS/Linux. Pay attention to any path-related code and adjust the separator (`\` vs `/`) if needed — or use the `file.path()` function which handles this automatically.

- **This is a living repository** — Materials will be updated and new lectures will be added over time. If something is unclear or seems outdated, check whether a newer version of the file has been pushed.

- **These are lecture notes, not textbooks** — The `.Rmd` files are meant to guide learning interactively, not to replace a comprehensive textbook. For deeper theoretical backgrounds, references and further reading will be suggested inside each file where relevant.

---

## 🚀 Things to Improve

This repository is a work in progress. Here are areas actively being worked on or planned for future updates:

- [ ] **Add more advanced topics** — including machine learning workflows with `tidymodels`, time series analysis, and text mining with `tidytext`.
- [ ] **Improve consistency** — standardize formatting, code style, and level of detail across all lecture files.
- [ ] **Add a companion dataset folder** — centralize all datasets used across the lectures into a single `/data` directory for easier access.
- [ ] **Add rendered HTML previews** — publish knitted versions of the lectures via GitHub Pages so visitors can read the materials without needing to download and run anything.
- [ ] **Include exercises and solutions** — add practice problems at the end of each lecture, with a separate solutions file.
- [ ] **Add a table of contents** — a master index listing all lectures with a short description of what each one covers, to make navigation easier.
- [ ] **Translate to French** — given that many learners in Francophone regions may benefit, a French version of the materials is being considered.

---

## 🤝 Contributing & Feedback

Feedback, suggestions, and corrections are very welcome! Feel free to open an **Issue** on this repository if you spot an error, have a question, or want to suggest a topic for a future lecture.

---

*Happy coding with R! 🎉*
