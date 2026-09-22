# Conflicts

Conflicts generally fall into two main categories: Developer–Developer and Developer–Manager.

## Developer–Developer Conflicts

Developer–developer conflicts typically stem from two distinct scenarios:

 ### High Technical Skills, Low Soft Skills (the "Dr. House" persona)

Lighthearted humor and constructive banter can help defuse tension in this situation. Once the underlying points are addressed without taking harsh delivery personally, this type of developer usually adjusts their communication style upon realizing unproductive friction is counterproductive.

 ### High Soft Skills, Low Technical Skills

This scenario is more challenging because evaluating technical arguments requires baseline domain expertise. First, simplify your arguments as clearly as possible. If simplifying does not resolve the disagreement, adopt a structured approach:

 - Document decisions and risks: Maintain clear written records of technical discussions and potential risks in chat logs, design docs, or recorded syncs.

 - Assign ownership: Ideally, allow the developer who proposed the approach to implement it.

 - Mitigate impact: If technical risks materialize, step in to help minimize consequences and resolve issues collaboratively.

Over time, navigating these real-world outcomes helps less technically experienced developers build a more objective view of their skills, dramatically reducing future conflicts.

## Developer-Manager conflict

Developer–manager conflicts are less frequent and usually stem from broken processes between feature scoping and execution. Once business requirements are finalized and approved, modifying them during active development becomes difficult and costly.

To prevent this, engineering team members (developers, QA, designers) must have the opportunity to provide feedback early during feature discussions.

### Example:
A web platform offers an in-app toggle to change the UI language dynamically. Business stakeholders request the same feature for the mobile app. By offering early feedback, developers can explain that mobile operating systems manage app localization natively. Implementing a control that redirects users to the OS settings achieves the business goal at a dramatically lower cost than building custom in-app localization logic.

If technical realities require changing business requirements after development has started, engineers should immediately initiate a discussion with project managers and business stakeholders to align on trade-offs.
