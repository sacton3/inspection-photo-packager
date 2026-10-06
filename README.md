# Inspection Photo Packager

A single-file, mobile-first web app for property managers. Drag in a batch of
inspection photos, compress them into one ZIP that stays **under 25 MB** (so it
can be emailed), and optionally edit each photo first.

## Features

- **Drag & drop** (or tap to pick) — everything runs in the browser; no photos
  are uploaded to any server.
- **Property name** field — used to name the ZIP and the email subject.
- **Auto-compression** to fit a batch under the 25 MB email limit (JPEG quality
  and resolution are stepped down automatically until it fits).
- **Download ZIP**, **Email** (native share sheet on mobile attaches the ZIP; a
  `mailto:` fallback on desktop), and **Edit Photos**.
- **Per-photo editor**: zoom, brightness, and contrast sliders, plus text / box /
  circle annotations in several colors. Annotations can be dragged to reposition.
- **Dark Metro-style UI**.

## Usage

Open `index.html` in any modern browser — desktop or phone. No build step, no
dependencies to install (JSZip and FileSaver load from a CDN).

## Live site

Served via GitHub Pages from `index.html` at the repository root.
