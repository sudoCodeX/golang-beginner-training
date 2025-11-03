# 📚 Go (Golang) Comprehensive Master Guide

## Project Overview

This repository contains a dynamic, single-page application designed to serve as a comprehensive training, reference, and interview preparation guide for the Go programming language (Golang). The content is organized into individual Markdown files, which are compiled and rendered into a beautiful, navigable guide using a custom index.html file and GitHub Pages.

The master guide covers core concepts from basic syntax to advanced topics like Concurrency, Error Handling, and Building/Deployment.

## 🚀 Live Documentation

The complete, rendered guide is available online via GitHub Pages:

[View the Go Master Guide Live Here](https://sudocodex.github.io/golang-beginner-training/#)

## ✨ Key Features

* **Single-Page Application:** All content is loaded asynchronously for fast, seamless navigation.
* **Dynamic Table of Contents (TOC):** The TOC on the left automatically updates based on the headers (H2, H4) in the Markdown files.
* **Responsive Design:** Optimized for viewing on mobile, tablet, and desktop devices.
* **Active Link Tracking:** The TOC highlights the chapter you are currently reading as you scroll.

## 🛠️ Local Development & Setup

If you want to view, modify, or debug the guide locally, you must serve the files using a local HTTP server to avoid browser security restrictions (`CORS errors`).

### Prerequisites

#### Option 1: Using VS Code's Live Server (Recommended)

* Install the "Live Server" extension by Ritwick Dey in Visual Studio Code.
* Open the repository folder in VS Code.
* Right-click on `index.html` and select "Open with Live Server."
* This will automatically open your guide in your web browser at a local address (e.g., `http://127.0.0.1:5500`).

#### Option 2: Using Python's Simple HTTP Server

* Open your terminal or command prompt.
* Navigate to the root directory of this repository:
```bash
cd golang-beginner-training
```
* Start the server using the Python 3 module:

```bash
python -m http.server 8000
```

* Open your web browser and navigate to: `http://localhost:8000/index.html`

## 📂 File Structure

The guide's content is controlled by two main files:

* `index.html`: The main application file containing all the HTML, CSS (Tailwind), and JavaScript logic for fetching and rendering the Markdown.
* `DOC_FILES.txt`: The manifest file. It is crucial that the file names listed in this document match the actual Markdown file names in the repository exactly, including spacing and numbering.
* `*.md`: The individual chapter files containing the Go programming content.