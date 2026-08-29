AdminLTE — Bootstrap 5 Admin Dashboard
npm version Packagist cdn version License: MIT Discord Invite Netlify Status

AdminLTE is the most popular open-source admin dashboard template — fully responsive, built on Bootstrap 5.3 with vanilla JavaScript (no jQuery), highly customizable, and easy to use. It fits every screen from small mobile devices to large desktops, and it's MIT-licensed.

Live Demo · Documentation · Framework Editions · Premium Templates

AdminLTE 4 dashboard — light mode AdminLTE 4 dashboard — dark mode

Framework editions
The same AdminLTE 4 dashboard, officially integrated for the framework you know best — you're looking at the HTML / Bootstrap core:

HTML React Next.js Vue Nuxt Angular Laravel Symfony Django ASP.NET Drupal Docs
Edition	Repository	Live demo	Install
HTML / Bootstrap (this repo)	AdminLTE	themes/v4	npm install admin-lte
React & Next.js — 30+ typed components, RSC-ready, ⌘K palette	adminlte-react	themes/next-react	see repo
Vue 3 & Nuxt — 45+ typed components, composables, SSR-safe theming	adminlte-vue	themes/vue-nuxt	see repo
Laravel — Blade components, config-driven menu, auth scaffolding	adminlte-laravel	laravel.adminlte.io	composer require colorlibhq/adminlte-laravel
Django — reusable app, menu filter pipeline, themed admin	adminlte-django	django.adminlte.io	pip install django-adminlte4
Symfony — Twig Components, AssetMapper, config-driven menu, EasyAdmin theme	adminlte-symfony	see repo	composer require colorlibhq/adminlte-symfony
Angular 22 — 44 standalone signal components, dark mode, ⌘K palette	adminlte-angular	see repo	npm i @adminlte/angular
ASP.NET Core (.NET 10) — Blazor components + MVC/Razor Pages Tag Helpers	adminlte-aspnet	see repo	dotnet add package ColorlibHQ.AdminLTE.AspNetCore
Drupal — admin theme for Drupal 10.3+/11, themed admin UI	adminlte-drupal	see repo	see repo
Docs — guides, components, and API reference for every edition	docs.adminlte.io	docs.adminlte.io	—
Every edition ships the full AdminLTE 4 design — Bootstrap 5.3, dark mode, RTL — with idiomatic integrations for its stack (components, routing, auth, theming).

Quick start
CDN — no build step:

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/admin-lte@4/dist/css/adminlte.min.css">
<script src="https://cdn.jsdelivr.net/npm/admin-lte@4/dist/js/adminlte.min.js"></script>
npm:

npm install admin-lte@4
Composer:

composer require almasaeed2010/adminlte
Then start from the Getting Started guide or copy one of the demo pages.

Developing AdminLTE itself
Install dependencies: npm install
Start the dev server: npm start (opens http://localhost:3000 with live reload)
Build: npm run build — or npm run production for the full lint + optimize + bundlewatch pipeline
All npm scripts
What's new in v4
