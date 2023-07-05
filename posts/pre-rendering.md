---
title: 'My Projects'
date: '2020-12-01'
---

These are my Project that i made using React JS: **Barangay Information System** and **PNP Clearance System**. The difference is in **when** it generates the HTML for a page.

- **Barangay Information System** is the pre-rendering method that generates the HTML at **build time**. The pre-rendered HTML is then _reused_ on each request.
- **PNP Clearance System** is the pre-rendering method that generates the HTML on **each request**.

Importantly, Next.js lets you **choose** which pre-rendering form to use for each page. You can create a "hybrid" Next.js app by using Static Generation for most pages and using Server-side Rendering for others.
