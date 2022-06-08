# Firebase-for-Web Workout Fitness App
> An Angular 7 and Firebase application that monitors your health, schedule and meals. Learned and Inspired from Todd Motto



College Bus Tracking System

Problem Statement:

These days it is harder to track fitness since every one has been working  9-5. So this an application has been designed by the people at GDSC-CUIET to help people sustain a better heath index and help them live a longer and healther life.

Proposed Solution :

This project proposes a “Website for keepin gtrack of useer's meals, their workout routine and their health in general. The website is a one stop for all the neccessary things related to fitness" 

![workout-fitness](./src/assets/images/workout-fitness.gif)

Angular application File / Folder Architecture summary:

1. `package.json`: consists of Node/NPM library/package/module dependencies for application development
2. `node_modues` - folder consists of all installed packages
3. `src/main.ts` - entry point to angular application. src/index.html
4.  `src/app/auth` - folder for auth rules for the application
5.  `src/root` - root folder
6.  `src/health` - folder for the health related functionalities
7. `ng serve / npm start` -> main.ts (index.html) -> app.module.ts -> app.component.ts -> (app.component.html + css)


Functionality & Concepts used :

The Website has a very simple and interactive interface which helps the users select their route flight and find its prices. Following are few Web and Firebase concepts used to achieve the functionalities in website :
<br> 
<ul><li> Components : to add header, footer, search feature in the website. Header and footer components are reused in the website. </li>
<li> Directives : Define how the view components are placed. It also describes the overall structure of the website components. </li>
<li> Databinding : Show the synchronisation between model and view. It populates the websites after mapping the model and view of each website page.
</li>
<li> Firebase Auth : To authenticate users to the website.</li>
<li> Firebase Realtime database : To add most recent prices of the flights for different routes. </li>
<li> Firebase Hosting - To host the website. </li>
</ul>

Application Link & Future Scope :

The app is currently in the Alpha testing phase for only some users.

Once the website is fully tested and functional, we plan to take the app to beta testing stage where it will be available in all of the country to be tested by the users (one state at a time). We aim that by next year 100,000 users in India will use this fitness app for controlling their fitness and help them control their health. 

#### Made with ❤️ GDSC-CUIET team 
##### Developers
- Armaan jain Arman0432.cse19@chitkara.edu.in
- Devansh Walia Devansh0442.cse19@chitkara.edu.in
- Anshuman Singla Anshuman0425.cse19@chitkara.edu.in
- Yatin Singla  Yatin0433.cse19@chitkara.edu.in
- Rajat Sharma dunit99k@gmail.com
