# CraftMyCV - Resume Builder Web Application

![Status](https://img.shields.io/badge/status-active-brightgreen)

CraftMyCV is a dynamic and user-friendly resume builder that empowers users
to create professional resumes effortlessly using customizable, pre-defined
templates — with instant client-side PDF export.

## What it does

- Choose from pre-defined, customizable resume templates.
- Fill in your details and see the resume update live.
- Export the finished resume as a PDF with one click, generated entirely in
  the browser via `html2canvas` — no server round-trip needed.

## Stack

| Layer    | Tech |
|----------|------|
| Frontend | React |
| Export   | html2canvas (client-side PDF/image export) |

## Getting Started

Requires **Node.js with npm** installed.

```bash
cd resume-builder
npm install
npm run dev
```

Then open the app at the local URL shown in the terminal (typically
http://localhost:5173 or http://localhost:3000, depending on the dev
server).

## Usage

1. Pick a template from the available options.
2. Enter your resume details — the preview updates as you type.
3. Click download/export to save your resume as a PDF.

## Live Demo

Link: https://rahulkr2511.github.io/ResumeBuilder/
