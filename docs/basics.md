# Basics

## Table of Content

* Git - Version Control
* Basic Terminal Usage
* Programming logic
* Data Structures
* Algorithms
* Design Patterns
* SOLID, KISS, YAGNI
* GitHub
* Licenses
* Semantic Versioning
* SSH
* HTTP/HTTPS/HTTP2 and APIs
* Character Encodings

System Design, Good architecture

Keep It Simple (KISS)

Don't Repeat Yourself (DRY) -> Every piece of knowledge must have a single, unambiguous, authoritative representation within a system

Write Everything Twice (WET) -> You can ask yourself "Haven't I written this before?" two times, but never three.

You must comment your abstractions

Avoid Hasty Abstractions (AHA) -> Prefer duplication over the wrong abstraction, Optimize for change first

Duplication is far cheaper than the wrong abstraction, prefer duplication over the wrong abstraction.

Keep Similar Items Nearby (Colocation)

* Repo
* Client Structure
  * Components (dumb)
  * Containers (smart)
  * Views / Screens
  * Routes
* Server Structure
 * │ app.js # App entry point
 * └───api # Express route controllers for all the endpoints of the app
 * └───config # Environment variables and configuration related stuff
 * └───jobs # Jobs definitions for agenda.js
 * └───loaders # Split the startup process into modules
 * └───models # Database models
 * └───services # All the business logic is here
 * └───subscribers # Event handlers for async task
 * └───types # Type declaration files (d.ts) for Typescript
* Don’t Rewrite Types
  * TypeORM/Typegoose
* Generate Code Wherever Possible
  * snippets
* Autoformat Code


https://mailchimp.com/

https://buttondown.email/
