# astro-blog

An Astro blog where I share projects, experiments, and what I learn while building in public.

Live site: [philippvs.github.io/astro-blog](https://philippvs.github.io/astro-blog/)

## Overview

This repository contains the source code for my personal blog built with Astro. The project is a space to document technical projects, reflect on what I am learning, and publish ideas in public as I build them.[web:42][web:56]

The site is deployed to GitHub Pages through GitHub Actions, which is an officially documented Astro deployment workflow for GitHub-hosted static sites.[web:16][web:121]

## What this project is for

This blog is designed to make my work more visible and more understandable.

It is where I publish:
- Technical projects and experiments
- Build-in-public updates
- Notes on books, ideas, and lessons learned
- Reflections on how I think, not only what I ship

## Tech stack

- [Astro](https://astro.build/) for a content-focused static site architecture.[web:56]
- GitHub Pages for static hosting.[web:16]
- GitHub Actions for automated deployment.[web:115][web:121]
- Markdown and Astro content collections for blog content organization.[web:39][web:42]

## Project structure

```text
/
├── public/
├── src/
│   ├── content/
│   │   └── blog/
│   ├── layouts/
│   ├── pages/
│   └── components/
├── .github/
│   └── workflows/
├── astro.config.mjs
├── package.json
└── README.md
```

This structure follows the common layout used in Astro blog projects, where content lives in `src/content/` and routes are created from files in `src/pages/`.[web:197][web:200]

## Getting started

Clone the repository and install dependencies:

```bash
git clone https://github.com/Philippvs/astro-blog.git
cd astro-blog
npm install
```

Run the development server:

```bash
npm run dev
```

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

A README should make a repository easy to understand and easy to use, so the most important commands are included directly here.[web:199][web:48][web:205]

## Deployment

This project is deployed to GitHub Pages with a GitHub Actions workflow based on Astro’s official deployment guide.[web:16][web:121]

For a project repository such as `astro-blog`, Astro requires the correct GitHub Pages configuration, including the repository base path in `astro.config.mjs` so assets and routes resolve correctly.[web:16]

Example configuration:

```js
import { defineConfig } from 'astro/config';

export default defineConfig({
  site: 'https://philippvs.github.io',
  base: '/astro-blog',
});
```

## License

The source code in this repository is licensed under the MIT License. Written content and media are not covered by that license unless stated otherwise.[web:77][web:89]

## Status

This project is being built in public and will continue to evolve over time. The goal is not only to publish finished work, but also to document the process behind it.

