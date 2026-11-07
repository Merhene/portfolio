---
title: XEFI
displayTitle: XEFI — Front-End Development
typeLabel: Professional Experience
publishDate: 2025-11-01 00:00:00
img: /assets/xefi.webp
img_alt: XEFI project illustration
description: |
  Front-end contributions to a B2B marketplace and DailyUp, including API-driven interfaces, server-side data tables, search, a leaderboard, and infinite-scroll lists.
seoTitle: XEFI — Front-End Development | Merwan SI TAYEB
seoDescription: Front-end development at XEFI using Vue.js, Nuxt, TypeScript, and Vuetify, covering API-driven interfaces, server-side tables, infinite scrolling, and the RecipeVault onboarding project.
tags:
  - Vue.js
  - Nuxt
  - TypeScript
  - Vuetify
---

## Introductory Summary

At XEFI, I contributed to a B2B marketplace and the DailyUp application, developing interfaces with Vue.js, Nuxt, TypeScript, and Vuetify.

My work focused on features that connect user interactions with application data: navigation, search, a leaderboard, server-side tables, and infinite-scroll lists. Beyond their visual presentation, these interfaces required API integration and careful handling of loading states and displayed results.

## Application Context and Contribution

My contribution centred on the front-end layer of existing applications. I implemented interface features within their established technical environment, connecting components to API data and translating user actions into updates to the interface.

The work ranged from shared navigation elements to data-driven views. These features served different interaction patterns: moving between application sections, finding information, comparing ranked entries, browsing structured records, and progressively loading additional content.

## Navigation and Search

I developed navigation components and menus, along with a search bar to help users access relevant information.

These interfaces connect user input and navigation choices with the application’s displayed content. The implementation involved more than positioning controls on a page: it also required handling the interactions and loading states associated with retrieving and presenting data.

## Server-Side Data Tables

I implemented tables with server-side data handling. In this model, the front end displays a portion of the dataset supplied by the back end rather than treating every record as a collection already loaded in the browser.

The interface must keep its controls and displayed rows aligned with the data returned by the API. Loading behaviour is also part of the feature: the table needs to communicate when data is being retrieved and make the resulting records readable within a structured view.

This work brought together API integration, table components, and the interface state surrounding data retrieval.

## Infinite-Scroll Lists

I also implemented infinite-scroll lists, where additional results are loaded progressively as the user browses.

Unlike a table that changes the currently displayed set of rows, this interaction extends an existing list. The front-end responsibility is to integrate newly retrieved results into the content already displayed while keeping the loading interaction understandable.

This required coordinating API data with the growing list and the interface states associated with loading more content.

## Leaderboard

I developed a leaderboard interface to present ranked information in a structured, readable format.

The feature combined API integration with the presentation of ordered entries. Its purpose was to make relative position and the associated information easy to understand within the application’s existing design language.

## Technologies and Interface Development

Vue.js and Nuxt formed the front-end application environment, with TypeScript used for typed development and Vuetify for interface components.

Across these contributions, my work connected component behaviour, user interactions, and API-provided data. The technical focus was on implementing usable application features within an existing codebase, rather than producing isolated visual mockups.

---

## Onboarding Project — RecipeVault

As part of XEFI’s onboarding programme, I developed RecipeVault, a recipe management application using Nuxt, Laravel, and MySQL.

The project covered creating and viewing recipes, managing favourites, and handling images. It also provided an opportunity to work across the front-end and back-end boundary through authentication, role-based permissions, and feature tests.

Authentication used Laravel Sanctum, while roles and permissions were managed with Spatie. Feature tests checked access rights for users and administrators, addressing whether protected operations were accessible to the appropriate role.

RecipeVault was an onboarding exercise rather than a client-facing production product. It is presented here separately from my contributions to the marketplace and DailyUp.

## Technology Stack

**Professional front-end work**

Vue.js · Nuxt · TypeScript · Vuetify

**RecipeVault onboarding project**

Nuxt · Laravel · MySQL · Laravel Sanctum · Spatie Permission
