# VHS 3D Printing Training Guide

An interactive, mobile-friendly web guide for the Original Prusa i3 MK3S at Vancouver Hackspace (VHS).

## What it is

A static HTML instructional guide to the Prusa printers at the Vancouver.

There is no server, no database, and no installation required. It runs entirely in the browser. Progress is not saved between sessions.

## Files

| File | Description |
|------|-------------|
| `index.html` | Training guide — 5 tasks, knowledge checks, self-assessment |

## Features

**Training guide (`index.html`)**

- How This Printer Works — mental model and labelled diagram
- Filament guide with decision framework
- 5 step-by-step tasks with tappable checklists
- WHY explanations for every step (expandable)
- Good vs bad first layer assessment
- Live Adjust Z and cancel-or-continue guidance
- Knowledge check — 10 questions across all 5 tasks
- Am I Ready? — self-assessment checklist with links back to tasks
- What's Next — after your first print

## Usage

Open `index.html` in any browser. No installation, no server, no dependencies required.

To use at the printer: host on GitHub Pages and generate a QR code pointing to the URL. Tape the QR code to the printer.

## Editing

All content is plain JavaScript objects at the top of each file. Open in any text editor, find the relevant array (`TASKS`, `TROUBLESHOOTING`, `FILAMENT_GUIDE`, etc.), and edit the text strings directly.

No build step required. Save the file and refresh the browser to see changes.

## Hosting on GitHub Pages

1. Push `index.html` to the root of a public GitHub repository
2. Go to Settings → Pages → Source → Deploy from a branch → main → / (root)
3. Your guide will be live at `https://yourusername.github.io/repository-name`

## Printer

Original Prusa i3 MK3S — Vancouver Hackspace  
Document number: VHS-3DP-PRUSAMK3

## License

Creative Commons Zero v1.0 Universal (CC0) — public domain. Use, adapt, and share freely.

## Built with

React (via CDN) and plain HTML.