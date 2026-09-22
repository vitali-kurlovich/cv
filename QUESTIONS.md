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

This is a rare type of conflict, and сause of this type is often the wrong process on the road from formulating business requirements to implementation. When all business requirements are approved, it's too difficult to change it when development has started.
To avoid this, engineers (programmers, QA, designers) must have possability make feedback at the early stage of discussion about new features.

Example: The web service provides an opportunity to dynamically change the language. The business wants this feature in the mobile app. In the early stage, developers can explain that the app's language changing is operation system feature, so the solution can be implemented as a control that redirects the app to app settings, where the user can change the localization settings of the application. This solution can cost dramaticly lower then implementation similar to the web service.

Sometimes developers can change business requirements after the beginning of implementation. Developers must initialize discution process with the project manager and business representatives.
