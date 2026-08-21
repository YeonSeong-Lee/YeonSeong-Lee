<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=YeonSeong%20Lee&fontColor=ffffff&fontSize=58&fontAlignY=38&desc=Software%20Engineer&descAlignY=60&descSize=22" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3200&pause=800&color=36BCF7&center=true&vCenter=true&width=720&lines=Full-Stack+Product+Engineer;42+Seoul+%C2%B7+8-person+team+%E2%86%92+1%2C000%2B+users;AI+Workflow+with+Claude+Code;Build+%C2%B7+Ship+%C2%B7+Operate)](https://git.io/typing-svg)

<a href="https://github.com/YeonSeong-Lee"><img src="https://komarev.com/ghpvc/?username=YeonSeong-Lee&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" /></a>
<a href="https://github.com/YeonSeong-Lee?tab=followers"><img src="https://img.shields.io/github/followers/YeonSeong-Lee?label=Followers&style=social" alt="followers" /></a>

[한국어](./README.md) · **English**

</div>

---

## About Me

Full-stack engineer building operational tools and AI products. I like taking work people repeat every day and turning it into a system — then shipping it, running it, and refining it with real feedback.

- **AI product design — Solar Canvas**: Designed and built a spec-first AI workflow editor that extracts fields from contracts. It ships an adjustable confidence slider, arithmetic-rule-based review referral (human-in-the-loop) that runs independent of the model's score, an execution-monitoring dashboard, and real-time collaboration via Yjs. A preliminary evaluation (N=20 synthetic contracts, live API) caught 7 of 7 injected document errors. Private repository — happy to share details on request.
- **10x with AI tooling**: Introduced Claude Code + SuperClaude + Serena to my team to standardize pre-PR code-impact analysis and review. Documented codebase-specific anti-patterns as shared rules, cutting off repeat occurrences of the same class of bug.
- **Operations automation / internal tools**: Built an unattended checkout/return system for the Jiphyeonjeon library, extending operating hours from 6 to 24 (weekly checkouts up 30 → 50, +67%). Automated a paper work-schedule that social-welfare-facility staff used to check by printout into a desktop viewer. Shipped a Chrome extension automating an evaluation-application workflow (published on the Chrome Web Store).
- **Full-stack collaboration**: Developed and operated Jiphyeonjeon, used by 1,000+ people, on an 8-person team — backend (2023–2024) then frontend (2024–2025) in sequence, over two years. Shared stability work such as a raw-query-to-TypeORM migration and an error-handling middleware rollout at conferences and internal talks.

---

## Tech Stack

#### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

#### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)

#### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

#### AI / Data
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![Claude](https://img.shields.io/badge/Anthropic%20Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

#### DevOps / Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---
## Featured Projects

<table>
<thead>
<tr><th width="22%">Project</th><th>Description</th><th width="28%">Tech</th></tr>
</thead>
<tbody>

<tr>
<td>

**Solar Canvas**

`Solo` · `Private repository`

</td>
<td>

An AI workflow editor that extracts parties, dates, amounts, and clauses from contracts. Extraction pipelines are composed on a node-based canvas; an adjustable confidence slider plus arithmetic-rule-based referral (unit price × quantity = total, 10% VAT, business-registration-number checksum) catches wrong answers hiding behind a passing score. Includes an execution-monitoring dashboard and real-time collaboration via Yjs. Preliminary evaluation (N=20 synthetic contracts, live API): 7 of 7 document errors detected, 11 of the implicated fields carried a passing automatic flag.
<br/>AI workflow · spec-first design · private (shared on request)

</td>
<td>

![Next.js](https://img.shields.io/badge/-Next.js%2016-000?logo=nextdotjs&logoColor=white&style=flat-square)
![TS](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square)
![ReactFlow](https://img.shields.io/badge/-React%20Flow-FF0072?logo=react&logoColor=white&style=flat-square)
![Yjs](https://img.shields.io/badge/-Yjs-000?style=flat-square)
![Postgres](https://img.shields.io/badge/-Postgres-4169E1?logo=postgresql&logoColor=white&style=flat-square)
![Vitest](https://img.shields.io/badge/-Vitest-6E9F18?logo=vitest&logoColor=white&style=flat-square)

</td>
</tr>

<tr>
<td>

**[Jiphyeonjeon](https://github.com/jiphyeonjeon-42/frontend)**

`Full-stack` · `2023–2025`

</td>
<td>

42 Seoul's official library checkout/return/reservation system. On an 8-person team (3 FE / 5 BE), I owned backend (2023–2024) then frontend (2024–2025) in sequence, serving 1,000+ users over two years. Replaced hours tied to librarian staffing (10am–4pm) with a QR + 42 OAuth unattended system running 24 hours (weekly checkouts up 30 → 50, +67%). Iterated continuously on librarian and patron feedback.
<br/>Full-stack · operations automation · 2 years in production

</td>
<td>

![TS](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square)
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black&style=flat-square)
![Express](https://img.shields.io/badge/-Express-000?logo=express&logoColor=white&style=flat-square)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white&style=flat-square)
![Jest](https://img.shields.io/badge/-Jest-C21325?logo=jest&logoColor=white&style=flat-square)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat-square)
![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?logo=swagger&logoColor=black&style=flat-square)

</td>
</tr>

<tr>
<td>

**[RallyLens](https://github.com/YeonSeong-Lee/rallylens)**

`Solo`

[![stars](https://img.shields.io/github/stars/YeonSeong-Lee/rallylens?style=flat-square&label=stars)](https://github.com/YeonSeong-Lee/rallylens/stargazers)

</td>
<td>

A CLI pipeline that automatically analyzes badminton match footage. YOLO11-pose estimates player poses, ByteTrack tracks multiple objects, TrackNetV3 detects shuttlecock trajectory, and a Kalman filter smooths the noise. An LLM summarizes the results into a rally-by-rally report.
<br/>AI/ML pipeline · trajectory analysis

</td>
<td>

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square)
![YOLO](https://img.shields.io/badge/-YOLO11--pose-00FFFF?logo=yolo&logoColor=black&style=flat-square)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=flat-square)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&logoColor=white&style=flat-square)

</td>
</tr>

<tr>
<td>

**[Sseuregi King](https://github.com/YeonSeong-Lee/sseuregi-king)**

[`Live Demo`](https://sseuregi-king.vercel.app) · `Hackathon winner`

</td>
<td>

A waste-sorting guide for foreign residents. Built full-stack on Next.js 16 and deployed to Vercel; splits object recognition and instruction generation into a two-stage Claude API pipeline so each stage can be verified independently. Region-specific disposal rules are mapped by geocode, so coverage extends by adding data alone; supports four languages (EN, 中, 日, RU) via next-intl. **1st place (grand prize) among 12 finalist teams at the Vibe Coding Hackathon** — built solo in 4 hours.
<br/>Next.js full-stack deploy · 4 languages · hackathon winner

</td>
<td>

![Next.js](https://img.shields.io/badge/-Next.js%2016-000?logo=nextdotjs&logoColor=white&style=flat-square)
![React](https://img.shields.io/badge/-React%2019-61DAFB?logo=react&logoColor=black&style=flat-square)
![TS](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square)
![Tailwind](https://img.shields.io/badge/-Tailwind%204-06B6D4?logo=tailwindcss&logoColor=white&style=flat-square)
![Claude](https://img.shields.io/badge/-Claude%20API-D97757?logo=anthropic&logoColor=white&style=flat-square)

</td>
</tr>

<tr>
<td>

**[OpenUmbrella](https://github.com/YeonSeong-Lee/OpenUmbrella)**

`Self-initiated` · `2 years in production`

[![stars](https://img.shields.io/github/stars/YeonSeong-Lee/OpenUmbrella?style=flat-square&label=stars)](https://github.com/YeonSeong-Lee/OpenUmbrella/stargazers)

</td>
<td>

A shared-umbrella service for the 42 Seoul campus. I identified the problem of lost umbrellas myself, pitched it to the Innovation Academy foundation, secured about ₩1M worth of umbrella sponsorship, and built and operated a QR-based unattended checkout/return system on Angular + FastAPI. 1,656 cumulative checkouts over two years of operation.
<br/>Self-initiated · operations automation · 2 years in production

</td>
<td>

![Angular](https://img.shields.io/badge/-Angular-DD0031?logo=angular&logoColor=white&style=flat-square)
![TS](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square)

</td>
</tr>

</tbody>
</table>

---

## Side Projects & Packages

- **[42 Benefit](https://github.com/42Benefit/benefit)** — a site collecting benefits available to 42 Seoul students
- **[seonbi-talk](https://github.com/YeonSeong-Lee/seonbi-talk)** — an MCP server that suggests formal, persuasive KakaoTalk replies for conversations with superiors. `Python`
- **[Bluebird Workshift Viewer](https://github.com/YeonSeong-Lee/bluebird_workshift_viewer)** — automated a paper work-schedule that social-welfare-facility staff used to print and check into a desktop viewer, with chokidar detecting Excel changes and auto-syncing to Google Drive. Built Oct–Dec 2024 and deployed to 32 facility staff (12 releases). `Electron` `JavaScript`
- **[tiny_render](https://github.com/YeonSeong-Lee/tiny_render)** — a software 3D renderer with no GPU dependency. `C++17` `CMake`
- **[HufsLifeAcademy_app](https://github.com/YeonSeong-Lee/HufsLifeAcademy_app)** — an Android app for an education community. `Java` `Android`
- **[RedKiKi](https://github.com/helloAlgorithms/RedKiKi)** — a Slack bot that manages a daily algorithm-practice study group. `Python` `GitHub Actions`

#### npm Packages

- **[@yeonseong/magic-loading](https://www.npmjs.com/package/@yeonseong/magic-loading)** — a loading animation shaped like a fantasy magic circle, generated from input text.
  <a href="https://www.npmjs.com/package/@yeonseong/magic-loading"><img src="https://img.shields.io/npm/v/@yeonseong/magic-loading?style=flat-square&logo=npm&color=CB3837" alt="@yeonseong/magic-loading version" /></a>
- **[az-generator](https://www.npmjs.com/package/az-generator)** — generates Korean dad jokes.
  <a href="https://www.npmjs.com/package/az-generator"><img src="https://img.shields.io/npm/v/az-generator?style=flat-square&logo=npm&color=CB3837" alt="az-generator version" /></a>
  <a href="https://www.npmjs.com/package/az-generator"><img src="https://img.shields.io/npm/dt/az-generator?style=flat-square&label=downloads" alt="az-generator downloads" /></a>
- **[korean-random-names-generator](https://www.npmjs.com/package/korean-random-names-generator)** — generates Korean random nicknames like "똑똑한 호랑이" (clever tiger).
  <a href="https://www.npmjs.com/package/korean-random-names-generator"><img src="https://img.shields.io/npm/v/korean-random-names-generator?style=flat-square&logo=npm&color=CB3837" alt="korean-random-names-generator version" /></a>
  <a href="https://www.npmjs.com/package/korean-random-names-generator"><img src="https://img.shields.io/npm/dt/korean-random-names-generator?style=flat-square&label=downloads" alt="korean-random-names-generator downloads" /></a>

---

## Open Source Contributions

<table>
<thead>
<tr><th width="24%">Project</th><th>Contribution</th><th width="14%">PR</th></tr>
</thead>
<tbody>

<tr>
<td rowspan="3">

**[webgpufundamentals](https://github.com/webgpu/webgpufundamentals)**

[`Official WebGPU learning resource`](https://webgpufundamentals.org)

</td>
<td>Added a Korean README — wrote a Korean translation of the project docs and linked it into the language list</td>
<td>

[#285](https://github.com/webgpu/webgpufundamentals/pull/285) `merged`

</td>
</tr>
<tr>
<td>Fixed awkward Korean phrasing and typos in the multisampling doc, unified technical terminology</td>
<td>

[#208](https://github.com/webgpu/webgpufundamentals/pull/208) `merged`

</td>
</tr>
<tr>
<td>Added a Korean translation of the WebGPU multisampling article</td>
<td>

[#207](https://github.com/webgpu/webgpufundamentals/pull/207) `merged`

</td>
</tr>

<tr>
<td>

**[playcanvas/editor](https://github.com/playcanvas/editor)**

`PlayCanvas 3D editor`

</td>
<td>Added an attribute reference to the Mipmaps field in the texture inspector so its tooltip documentation shows up</td>
<td>

[#1694](https://github.com/playcanvas/editor/pull/1694) `merged`

</td>
</tr>

</tbody>
</table>

---

## GitHub Stats

<div align="center">

<img height="170" src="https://streak-stats.demolab.com/?user=YeonSeong-Lee&theme=tokyonight&hide_border=true" />

</div>

---

## Coding Activity

[![Solved.ac profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=dltjddus2)](https://solved.ac/dltjddus2)

[![wakatime](https://wakatime.com/badge/user/2f42ecac-18b3-4aea-9e84-70d3d28d0008.svg)](https://wakatime.com/@2f42ecac-18b3-4aea-9e84-70d3d28d0008)

---

## Talks & Knowledge Sharing

Things I've shared with teams.

| Talk | Topic |
| --- | --- |
| [Migrating from raw queries to TypeORM](https://github.com/YeonSeong-Lee/presentation_material/tree/main/migrate_raw_to_typeorm) | Incrementally moving a production service's raw SQL to TypeORM |
| [Error handling](https://github.com/YeonSeong-Lee/presentation_material/tree/main/error_handling) | A consistent backend error-handling strategy |
| [DB backups](https://github.com/YeonSeong-Lee/presentation_material/tree/main/db_backup) | Designing and operating database backups |
| [Inverse CDF sampling](https://github.com/YeonSeong-Lee/presentation_material/tree/main/inverse_cdf_method) | How to sample from a probability distribution |
| [CSG and HDR](https://github.com/YeonSeong-Lee/presentation_material/tree/main/csg_hdr) | CSG and HDR rendering in computer graphics |

#### Media
- [2024 Innovation Academy showcase conference (INNO-CON)](https://www.youtube.com/live/qcIf8i1QRio?t=2984s)
- [2022 INNO-CON (Platum article)](https://platum.kr/archives/198709)

---

## Contact

<a href="mailto:yeonseong.dev@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.youtube.com/@yeonseong42"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
<a href="https://github.com/YeonSeong-Lee"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer" width="100%" />

</div>
