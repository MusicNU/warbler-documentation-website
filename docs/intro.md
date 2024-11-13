---
sidebar_position: 1
---

# MusicNU Project Overview

Let's explore **MusicNU in just a few minutes**.

## Getting Started

Get started by **setting up the MusicNU development environment**.

Or **explore MusicNU features** to see how it enhances musicians' practice sessions.

### What You'll Need

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above
  - When installing Node.js, select all recommended checkboxes for dependencies.
- [AWS CLI](https://aws.amazon.com/cli/) for managing cloud resources
- **GitHub Account** for code collaboration and version control

## Setting Up Your Development Environment

Begin by cloning the MusicNU repository and installing dependencies:

```bash
git clone https://github.com/yourusername/musicnu.git
cd musicnu
npm install
```

### Configuring AWS and Vercel

For core infrastructure, configure your AWS account with S3 and DynamoDB services. Vercel will be used for frontend deployment.

1. **AWS CLI Setup**: Ensure you have access to S3 and DynamoDB.
2. **Vercel Deployment**: Connect the MusicNU repository to Vercel for automatic deployment.

## Running MusicNU Locally

After configuring, start the local development server:

```bash
npm run dev
```

This command launches a local server so you can view the site at [http://localhost:3000/](http://localhost:3000/).

Make changes to `src/pages` or `src/components` to customize MusicNU. The site **reloads automatically** with each change.

## Key Features

- **Sheet Music Upload**: Upload PDFs or MusicXML files for analysis
- **Performance Feedback**: Receive feedback on rhythm, pitch, and dynamics
- **Anonymous Access**: New users can try core features without an account
- **Real-Time Feedback**: Fast response time for in-session feedback

## Project Goals

The primary objective of MusicNU is to give musicians accessible, immediate feedback during practice. By integrating feedback on dynamics, rhythm, and accuracy, MusicNU reduces the need for live instructor feedback, enhancing solo practice efficiency.

## Deployment

MusicNU is deployed on **Vercel**, with core services on **AWS**. The setup uses **GitHub Actions** for continuous integration.

### Commands Overview

To start developing and deploying with MusicNU, here are some key commands:

```bash
# Start local development
npm run dev

# Build for production
npm run build

# Deploy to Vercel (linked project)
vercel --prod
```

Happy practicing with **MusicNU**!
