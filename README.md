# KIDS Safe Design Room

## One-sentence benefit
Helps online services coordinate age journeys, safe-design controls and evidence that protects children’s wellbeing.

## Live demo
Run the Java service and Angular application locally to use the complete experience.

## Screenshots
![child online-safety design workspace](docs/screenshot.png)

## Main features
Search safe-design reviews, create a regional rollout, progress readiness actions and monitor approval and high-priority gaps.

## Technology used
Angular, TypeScript, signals, computed state, server rendering, Spring Boot and Java.

## Installation instructions
Start the backend with `cd backend && mvn spring-boot:run`. In another terminal run `npm install && npm start`.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
Online platforms, games, AI-companion providers, regulators and child-safety teams need shared evidence for age assurance, time limits and safe-by-design decisions.

## Key workflows
Teams can find a safe-design review, add a validated review and advance corrective work to approval.

## Angular framework highlights
The interface uses standalone components, signals, computed values, OnPush change detection, built-in control flow and SSR-safe loading.

## Java backend highlights
The Spring Boot service provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
Angular HttpClient connects signal-based state to the Java API and updates the visible board after every write.

## Accessibility and responsive behaviour
Semantic structure, labelled controls, visible focus, high contrast and compact responsive tables support varied users and devices.

## Verification commands
Use `npm test -- --watch=false`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains the Angular experience, `backend` contains the Java service, and `docs` contains verified media.

## Tradeoffs
Records are held in memory for demonstration speed; operational use would add identity, durable storage, age-assurance signals and platform-risk integrations.

## Roadmap
Add age-journey maps, wellbeing indicators, parental-control evidence, risk assessments and audit-ready persistence.
