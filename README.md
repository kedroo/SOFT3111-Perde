# Perde — Event Discovery & Ticketing Platform

**SOFT3111.1 – Internet and Web Programming** · Instructor: Mustafa Taner Eskil · Group number: not assigned

Perde (Turkish for “curtain”) is a web application for discovering live events — concerts, theatre, stand-up comedy, cinema, sports and children’s shows — in Istanbul, Ankara and Izmir, and for buying tickets. Users pick seats on an interactive seat map with a 3D view from the seat, their seats are held for 10 minutes during checkout, and they receive e-tickets with QR codes. An AI assistant, *Suflör*, recommends events from the catalogue in natural language.

## Team

| Name | Student ID |
| --- | --- |
| Emre Yeşilördek | 21COMP1001 |
| Tuna Eren Çetin | 23SOFT1052 |

## Project #1 — Project proposal

📄 **[ProjectProposal.pdf](ProjectProposal.pdf)** — project overview and motivation, target users and roles, functional requirements (FR-01 – FR-16), non-functional requirements (NFR-01 – NFR-07) and user scenarios (S1 – S4).

## Screen sketches and prototype

| File | Contents |
| --- | --- |
| [screen-sketches/Perde_Screen_Sketches.pdf](screen-sketches/Perde_Screen_Sketches.pdf) | All 24 screens: wireframe sketch and final design side by side, with notes and where each action leads. |
| [screen-sketches/Perde_Screens.fig](screen-sketches/Perde_Screens.fig) | Figma file. Import it into Figma; the pages “Wireframes (sketches)” and “Final design” are wired as a clickable prototype (press **Present**). |
| [screen-sketches/wireframes_svg/](screen-sketches/wireframes_svg/) | Wireframes as vector SVG files (editable layers when dropped into Figma). |
| [screen-sketches/final_design/](screen-sketches/final_design/) | Images of the final user interface. |
| [prototype/index.html](prototype/index.html) | Navigable HTML prototype. Open it online at **https://kedroo.github.io/SOFT3111-Perde/prototype/** or download the folder and open `index.html`. |

The user interface is in Turkish for its target market; all documents, wireframes and annotations are in English.

## Planned technology

Next.js (React, TypeScript) · Tailwind CSS · Three.js for the 3D seat view · MariaDB with Drizzle ORM · Anthropic Claude API for the AI assistant.
