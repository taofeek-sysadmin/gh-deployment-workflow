# GitHub Pages Deployment Project

          GitHub Pages Deployment with GitHub Actions

A CI/CD pipeline using GitHub Actions to automatically deploy a static website to GitHub Pages.
Designed to demonstrate hands-on experience with continuous integration, conditional deployments, and workflow automation.

          🚀 What It Does

Automatically deploys a static site to GitHub Pages

Triggers only when index.html changes

Runs on every push to the main branch

Publishes updates to a live public URL

          🧠 Why It Matters

This project demonstrates:

Practical CI/CD pipeline design

GitHub Actions workflow authoring

Conditional workflow execution (path-based triggers)

Automated static site deployment

Real-world GitHub Pages usage

          Relevant to:
DevOps · Cloud · Platform · SRE · Software Engineering roles

          🛠️ Tech Stack

GitHub Actions

GitHub Pages

YAML-based workflow configuration

Static HTML

          ⚙️ Workflow Logic

Push to main

GitHub Actions checks if index.html changed

If changed:

Workflow runs

Site is deployed to GitHub Pages

          📂 Repository Structure
.
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml

          📌 Key Skills Demonstrated

CI/CD fundamentals

GitHub Actions workflows

Conditional deployments

Infrastructure automation

Version-controlled deployments

          🔮 Stretch / Future Enhancements

Static site generator (Hugo, Jekyll, Astro)

Personal portfolio deployment

Environment-based workflows

Cache optimization

Multi-branch deployments

          👤 Author

Taofeek Komolafe
DevOps • CI/CD • Automation
