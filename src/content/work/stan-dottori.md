---
title: Stan Dottori
displayTitle: Stan Dottori — Tattoo Artist Website
publishDate: 2020-03-02 00:00:00
img: /assets/stock-1.jpg
img_alt: Stan Dottori logo over iridescent blue and pink liquid
description: |
  Custom React website for a tattoo artist, featuring administrable galleries, bilingual content, scroll-based animations, and an independently managed homepage carousel.
seoTitle: Stan Dottori — React Website | Merwan SI TAYEB
seoDescription: A custom React and TypeScript website for tattoo artist Stan Dottori, with bilingual content, administrable galleries, and a homepage carousel managed through the administration interface.
websiteUrl: https://standottori.com/
tags:
  - React
  - TypeScript
  - Vite
  - Supabase
  - i18next
  - Vercel
---

## Project Overview

I designed and deployed a custom website for Stan Dottori, a tattoo artist based in Lyon, to give him an online presence that reflects his artistic identity and a tool he can maintain independently.

The project brings together a responsive interface, independently managed content, an interactive tattoo enquiry form, and hand-coded animations. From selecting tattoo placements on a body diagram to exploring the biography and YouTube sections, the interactions are tailored to the artist’s identity and the way visitors discover his work.

## Content Management and Customisation

Client autonomy was a central requirement. The administration interface allows Stan to manage his Tattoo, Flash, and Wallpaper galleries, update events, edit his biography in French and English, and maintain his contact details and social links.

The Wallpaper collection also feeds the homepage carousel. Updating these images allows him to refresh the website’s opening visual presentation through the administration interface.

This approach gives the artist control over the content that changes regularly, reducing the need for developer intervention for everyday updates.

## Interactive Contact Form

The contact form helps visitors describe their tattoo project through an interactive body diagram. They can select one or several body areas, with related selections combined into a larger placement where appropriate. Selecting both the upper and lower arm, for example, can be interpreted as a full sleeve.

The form’s wording updates automatically according to the selected body areas, price option, and reason for contacting the artist. This keeps the questions relevant to the enquiry and helps visitors communicate their project more clearly.

Implementing this behaviour required custom selection logic, rules for combining body areas, and coordinated updates between the diagram and the form text.

## Custom Animations and Interactions

I hand-coded the biography section’s unlocking interaction and scroll-driven animations, tailoring their behaviour to the content and the artist’s visual identity.

The YouTube section also features hand-coded animations. Alongside the biography interactions, this work adds a layer of custom front-end development beyond the site’s layouts and content management features.

## Technical Implementation

The website is built with React and TypeScript, with Vite providing the development and build tooling. Supabase provides back-end services, and i18next handles internationalisation.

The React interface connects public-facing pages with administrable content, allowing updates to appear in the relevant sections of the website. Responsive layouts and scroll-based animations support the presentation of the artist’s work across different screen sizes.

The project also includes image optimisation to support the delivery of visual content. The website is deployed on Vercel with a custom domain.

## In Development

A Three.js-based 3D playground is currently in development to extend the website’s interactive experience.

## Technology Stack

React · TypeScript · Vite · Supabase · i18next · Vercel
