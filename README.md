# ShelfLyfe — Inventory Management App

**CS-360: Mobile Architecture and Programming | Project Three Portfolio Artifact**

## Project Overview

ShelfLyfe is an Android inventory management app I developed to make tracking everyday items a little easier. The idea was to give users one simple place to check what they have, update item quantities, and keep an eye on supplies that are running low. This repository showcases my Project Three app code and final UI design, along with what I learned from taking a mobile app from planning to implementation.

## 1. App Requirements and User Needs

My main goal was to build an app that made inventory tracking straightforward instead of turning a simple task into a complicated process. Users needed a way to access their inventory, view and manage items, and update quantities without digging through confusing menus. I also worked with an SMS alert feature intended to help users stay aware of low or empty stock. The focus throughout the project was convenience: users should be able to open the app, find the information they need, and make changes quickly.

## 2. Screens, Features, and User-Centered Design

To support those needs, I designed a login and registration experience, an inventory display, and controls for adding and updating inventory items. I also included an alert-related flow that required thinking about Android's SMS permission behavior. My Project Two UI designs gave me a starting point, but actually developing the app helped me see where the screens and interactions needed to be practical, not just visually appealing. I tried to keep the layout consistent, the actions easy to recognize, and the navigation simple. I consider that approach successful because each screen had a clear purpose tied to what a user would want to accomplish.

## 3. Coding Approach and Strategies

I learned pretty quickly that trying to tackle an entire mobile app at once is a great way to get overwhelmed. Instead, I worked through smaller pieces: building the screens, connecting user actions to functionality, incorporating SQLite for inventory data, and testing interactions in the Android emulator. When something didn't behave the way I expected, I went back to that specific feature instead of changing everything at once. In future projects, I want to keep using that incremental approach, along with more deliberate planning and testing before adding new features.

## 4. Testing, Functionality, and What I Learned

I used the Android emulator to launch ShelfLyfe and check how the app responded to navigation, inventory interactions, and its permission-related behavior. I also tested the alert flow, including the experience of responding to a permission request. Not every test went smoothly: I ran into emulator and app behavior that required troubleshooting and retesting. That was an important reminder that seeing an app launch successfully doesn't mean every feature is ready. Testing matters because it reveals problems a design mockup can't show, especially when permissions, data, and real user actions come together.

## 5. Development Process and Challenges

The biggest shift for me was going from thinking about an app as a collection of screens to understanding it as a complete user experience. My initial designs looked straightforward on paper, but implementation introduced challenges such as connecting the interface to stored inventory data and handling alert-related interactions. The way I worked through those challenges was by isolating one problem at a time, testing changes, and adjusting my approach when needed. That process pushed me to be more patient and think about how one part of the app affects everything else.

## 6. Where I Was Most Successful

I'm especially proud of bringing the inventory-management concept beyond a visual design and into an Android project that connects interface elements with actual app logic and data handling. Working with SQLite and the inventory workflow helped me demonstrate how I can take a user need, design an interface around it, and start implementing the functionality behind it. More importantly, ShelfLyfe taught me how to troubleshoot when the finished experience doesn't match the original plan. Those are skills I want to keep building on in future software projects.

---

**Portfolio note:** ShelfLyfe was developed as an educational project for CS-360. The accompanying Project Three ZIP contains the completed course artifact, including the app code and final UI design.
