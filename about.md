````md
# Cursor Task: Build a GitHub Pages Project Homepage

Build a clean academic project homepage for the paper:

**JARVIS: A Just-in-Time AR Visual Instruction System for Cross-Reality Task Guidance**

The format should closely follow the structure and simplicity of this page:

https://minahuh.com/Vid2Coach/

Do not copy its code, images, or text. Only follow the layout style: title, authors, links, teaser, short project summary, abstract, study/design goals/system/evaluation/demo/BibTeX.

---

## 1. Output Files

Create the following files:

```text
index.html
style.css
README.md
assets/
  teaser.png
  study.png
  system.png
  qualitative.png
  evaluation.png
  ratings.png
  demo.mp4
````

Use placeholder images/videos. I will replace them later.

Do not use React, Next.js, Vite, npm, or any build system.
Use only HTML, CSS, and minimal vanilla JavaScript if needed.

---

## 2. Page Style

Make the website simple, clean, and academic.

Follow this structure:

* Centered title
* Centered author list
* Institution / venue line
* Button links
* Large teaser image
* Short bold project summary
* Section title + image + short paragraph
* Horizontal separators between sections
* Demo video
* BibTeX
* Footer

Use a maximum content width around `960px`.

The page should be responsive on mobile.

---

## 3. Paper Metadata

Use the following information.

### Title

```text
JARVIS: A Just-in-Time AR Visual Instruction System for Cross-Reality Task Guidance
```

### Authors

```text
Yusi Sun, Ying Jiang, Jiayin Lu, Yin Yang, Yong-Hong Kuo, Chenfanfu Jiang
```

### Venue

```text
arXiv Preprint, 2026
```

### Links

```text
Arxiv: https://arxiv.org/abs/2604.10108
PDF: https://arxiv.org/pdf/2604.10108
Demo: #demo
Code: #code
Homepage: https://soniasuns.github.io
```

---

## 4. Header Section

Create a centered header.

Content:

```text
JARVIS: A Just-in-Time AR Visual Instruction System for Cross-Reality Task Guidance
```

Author line:

```text
Yusi Sun, Ying Jiang, Jiayin Lu, Yin Yang, Yong-Hong Kuo, Chenfanfu Jiang
```

Venue line:

```text
arXiv Preprint, 2026
```

Button row:

```text
PDF | Demo | Homepage
```

Use rounded academic-style buttons.

---

## 5. Teaser Section

Add a large teaser image:

```html
<img src="assets/teaser.png" alt="JARVIS teaser">
```

Below it, add this project summary in a large, bold paragraph:

```text
JARVIS is a VLM-driven augmented reality system that transforms a single high-level prompt into contextual, step-by-step visual instructions for cross-reality task guidance.
```

---

## 6. Abstract Section

Add section title:

```text
Abstract
```

Use this abstract text:

```text
Many everyday tasks require users to switch between external tutorials and the task environment, increasing cognitive load and interrupting task flow. JARVIS explores how augmented reality, vision-language models, and large language models can support just-in-time guidance for cross-reality tasks. Given a high-level user prompt, JARVIS generates contextual step-by-step AR instructions, monitors task state, verifies progress in real time, and provides adaptive visual feedback. The system is designed for tasks that span physical and virtual workspaces, including real-to-real, real-to-virtual, virtual-to-real, and virtual-to-virtual guidance scenarios.
```

---

## 7. Formative Study Section

Add section title:

```text
Formative Study
```

Add image:

```html
<img src="assets/study.png" alt="Formative study">
```

Add paragraph:

```text
To inform the system design, the project studies how users perform cross-reality tasks and where conventional tutorials fail to provide timely, contextual, and spatially grounded guidance.
```

---

## 8. Design Goals Section

Add section title:

```text
Design Goals
```

Add a simple list:

```text
D1. Generate task instructions from a single high-level user prompt.

D2. Provide situated visual guidance in augmented reality.

D3. Support task transitions across physical and virtual environments.

D4. Verify user progress and task state in real time.

D5. Provide adaptive feedback when users need correction or confirmation.

D6. Reduce the need to switch between external tutorials and the task workspace.
```

Use clean spacing, similar to Vid2Coach.

---

## 9. System Section

Add section title:

```text
System
```

Add image:

```html
<img src="assets/system.png" alt="JARVIS system overview">
```

Add paragraph:

```text
JARVIS interprets a user’s task prompt, decomposes it into step-level instructions, grounds the instructions in cross-reality context, and presents just-in-time AR visual feedback. The system combines task planning, visual state understanding, real-time verification, and adaptive instruction generation.
```

---

## 10. Cross-Reality Guidance Section

Add section title:

```text
Cross-Reality Task Guidance
```

Add image:

```html
<img src="assets/qualitative.png" alt="Cross-reality task guidance examples">
```

Add paragraph:

```text
JARVIS supports four types of cross-reality guidance: real-to-real, real-to-virtual, virtual-to-real, and virtual-to-virtual. These categories describe how task information and user actions move between physical objects, digital interfaces, and virtual content.
```

---

## 11. Evaluation Section

Add section title:

```text
Evaluation
```

Add image:

```html
<img src="assets/evaluation.png" alt="Evaluation setup">
```

Add paragraph:

```text
The evaluation examines how JARVIS affects task performance, usability, workload, and user perception of AR visual guidance across representative cross-reality tasks.
```

Add another image:

```html
<img src="assets/ratings.png" alt="Evaluation results">
```

Add caption:

```text
User ratings and task outcomes can be visualized here after the final results figures are prepared.
```

---

## 12. Demo Video Section

Add section title with id:

```html
<h2 id="demo">Demo Video</h2>
```

Add video:

```html
<video controls width="100%">
  <source src="assets/demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

---

## 13. Code Section

Add section title with id:

```html
<h2 id="code">Code</h2>
```

Add text:

```text
Code will be released soon.
```

---

## 14. BibTeX Section

Add section title:

```text
BibTeX
```

Add this BibTeX block:

```bibtex
@article{sun2026jarvis,
  title={JARVIS: A Just-in-Time AR Visual Instruction System for Cross-Reality Task Guidance},
  author={Sun, Yusi and Jiang, Ying and Lu, Jiayin and Yang, Yin and Kuo, Yong-Hong and Jiang, Chenfanfu},
  journal={arXiv preprint arXiv:2604.10108},
  year={2026}
}
```

---

## 15. Footer

Add footer:

```text
This page was built for GitHub Pages.
```

Add homepage link:

```html
<a href="https://YOUR_GITHUB_USERNAME.github.io/">Back to homepage</a>
```

---

## 16. README.md

Create a concise README with:

```md
# JARVIS Project Page

This repository contains the project homepage for:

**JARVIS: A Just-in-Time AR Visual Instruction System for Cross-Reality Task Guidance**

## Edit Content

Edit `index.html` to update the title, authors, abstract, links, and section text.

## Replace Media

Place final images and videos in the `assets/` folder:

- `teaser.png`
- `study.png`
- `system.png`
- `qualitative.png`
- `evaluation.png`
- `ratings.png`
- `demo.mp4`

## Deploy with GitHub Pages

1. Create a GitHub repository, for example `jarvis-project-page`.
2. Upload all files.
3. Go to repository `Settings`.
4. Open `Pages`.
5. Choose `Deploy from a branch`.
6. Select `main` and `/root`.
7. Save.

The page will be available at:

`https://YOUR_GITHUB_USERNAME.github.io/jarvis-project-page/`
```

---

## 17. Important Requirements

* Keep the page simple.
* Do not add unnecessary sections.
* Do not add animations.
* Do not use heavy styling.
* Do not use external libraries.
* Do not invent extra claims.
* Make the layout visually similar to a concise academic project page.
* Make all placeholder media easy to replace.

```
::contentReference[oaicite:0]{index=0}
```
