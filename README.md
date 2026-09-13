# Deviyad — Senior Software Engineer & System Architect 👋

<p align="center">
  <img src="./assets/banner.png" alt="Deviyad banner" width="100%" />
</p>

<p align="center">
  <a href="https://your-resume-link.com">Resume</a> ·
  <a href="https://www.linkedin.com/in/your_linkedin">LinkedIn</a> ·
  <a href="mailto:your.email@example.com">Email</a>
</p>

---

<p align="left">
  <img src="./assets/avatar.jpg" alt="avatar" width="120" style="border-radius:50%; vertical-align:middle; margin-right:16px;">
  <strong style="font-size:1.25rem;">Deviyad</strong><br>
  Senior Software Engineer • Systems & Architecture • Scalable, secure web platforms<br>
  Open to leadership, consulting, and strategic partnerships
</p>

---

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://img.shields.io/badge/Status-Available-brightgreen" alt="status"/><br>
      <strong>Availability</strong><br>Consulting & Leadership
    </td>
    <td align="center" width="33%">
      <img src="https://img.shields.io/badge/Experience-10%2B%20yrs-blue" alt="exp"/><br>
      <strong>Experience</strong><br>Backend & Cloud-native systems
    </td>
    <td align="center" width="33%">
      <img src="https://img.shields.io/badge/Domain-Enterprise%20SaaS-orange" alt="domain"/><br>
      <strong>Domain</strong><br>High-throughput platforms
    </td>
  </tr>
</table>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=deviyad&show_icons=true&theme=dark&hide_border=true" alt="GitHub stats" height="140"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=deviyad&layout=compact&theme=dark&hide_border=true" alt="Top languages" height="140"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=deviyad&theme=radical&no-frame=true" alt="trophies" />
</p>

---

## Professional Summary
I design and deliver production-grade systems that scale reliably under real-world load. I focus on API-first architectures, observability, security-by-design, and improving engineering delivery through automation and strong processes.

- System architecture, distributed systems, and performance engineering
- API design, microservices, event-driven pipelines, and data platforms
- Cloud-native deployments (Kubernetes, Terraform), cost & reliability optimization
- Engineering leadership: mentoring, code reviews, and technical roadmaps

---

## Technical Stack
<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="js"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="ts"/>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="py"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white" alt="go"/>
  <img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white" alt="node"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white" alt="k8s"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="docker"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white" alt="aws"/>
</p>

---

## Selected Projects — pinned recommendations
(Each card links to the repo, includes a one-line problem→solution→impact summary, and the primary tech.)

<div align="center">

| Project | Description & Impact | Technologies |
|---|---:|---|
| <img src="https://raw.githubusercontent.com/deviyad/e-plant/main/assets/icon.png" width="220" alt="e-plant"/> <br> **E-Plant** <br> https://github.com/deviyad/e-plant | E‑commerce PWA for plants: designed a performant, PWA-enabled storefront with offline support and robust product/checkout flow — production-ready UX and caching strategies. | React, Vite, Tailwind, PWA |
| <img src="https://raw.githubusercontent.com/deviyad/time_tracker/main/assets/icon.png" width="220" alt="time-tracker"/> <br> **Time Tracker** <br> https://github.com/deviyad/time_tracker | Cross-platform time & productivity app: precise time logging, analytics dashboard, and export/backup features — optimized for reliability across devices. | Flutter, Dart, Material 3 |
| <img src="https://raw.githubusercontent.com/deviyad/paradise-nursery/main/public/icons/icon-192.png" width="220" alt="paradise-nursery"/> <br> **Paradise Nursery** <br> https://github.com/deviyad/paradise-nursery | Plant marketplace PWA with advanced caching, service workers, and modern frontend architecture — focused on performance, accessibility, and conversion. | React, Vite, Tailwind, Redux |
| <img src="https://raw.githubusercontent.com/deviyad/foodie/main/assets/icon.png" width="220" alt="foodie"/> <br> **Foodie** <br> https://github.com/deviyad/foodie | Recipe management mobile app (Expo): discover, save, and manage recipes with offline-first support and polished mobile UX. | React Native, Expo, Firebase |

</div>

Notes about images: if any of the raw.githubusercontent.com image links above 404, replace with local files under assets/ (project screenshots or icons). Visuals increase recruiter engagement.

---

## How I present each pinned repo (recommended README structure for each)
1. One-line elevator pitch.  
2. Problem → Solution → Impact (1–3 short lines with concrete outcomes).  
3. Quick start (3 lines max) + demo / screenshot.  
4. Tech stack + tests + CI badges.  
5. Key metrics or business outcome (if available).  

---

## Live demo / GIFs & architecture
- Add demo GIFs and architecture SVGs under assets/ and embed like:
  <img src="./assets/demo.gif" alt="demo" />
  <img src="./assets/arch.svg" alt="architecture" width="100%" />

---

## Assets to include (assets/ folder)
- banner.png — 1280×360 (simple branded banner with title + role)
- avatar.jpg — 400×400 (professional headshot)
- project-e-plant.png / project-time_tracker.png / project-paradise-nursery.png / project-foodie.png — 1280×720 or 16:9 screenshots
- demo.gif — short 5–12s demo (<2MB ideally)
- arch.svg — high-level system diagram vector

---

## Quick publish steps (ready-to-run commands)
1) Create the profile repo locally + push (replace resume/link/email in README before push):
```bash
# create profile repo and publish
gh repo create deviyad --public --description "Professional profile README for Deviyad" --confirm
git init
git checkout -b main
# Save the README content into README.md, create assets/ and add asset files
git add README.md assets/
git commit -m "chore(profile): add professional profile README with assets"
git remote add origin https://github.com/deviyad/deviyad.git
git push -u origin main
