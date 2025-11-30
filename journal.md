# Project Journal

**Student Name:** Josh Bielas
**Project Title:** Habit Tracker
**Start Date:** 11/7/2025

---

## Entry: 11/2/2025 - 11/9/2025

### Time Spent
- **Total:** 5 hours and 20 minutes

### Tasks Attempted
1. Build a few Figma Diagrams for home page with different menus open.
2. Group meeting with task assignment decisions
3. Build UI prototype

### Problems Encountered
- **Problem 1:** I didn't really know how to use Figma, so I had to learn how
  - *Attempted solution:* I tried learning it by myself and searching for how to do things as needed.
  - *Outcome:* Resolved
- **Problem 2:** Organizing who would work on what for the week.
  - *Attempted solution:* We discussed and decided who would work on each part
  - *Outcome:* Resolved
- **Problem 3:** Still trying to learn how to write dart code
  - *Attempted solution:* Write code as much as I can, and get help from ai and youtube as needed. I still want to learn how to write dart code, so I carefully read all of the code and look at how it works. I then make changes to the ai's code to make it work exactly how I want it to.
  - *Outcome:* Resolved

### Tasks Completed
- [x] I completed the Figma diagrams for the home page
- [x] Group meeting and task assignments
- [x] Build UI Prototype

### Notes & Reflections
This week I was able to complete some UI diagrams with Figma. Then I was able to build the UI prototype by combining aspects of Jennessy and my Figma diagrams. 

### Next Steps
- [ ] Attend Monday's meeting and decide next steps for the project. I will likely start to connect backend functions to the UI to allow the basic functionality of the app to work.

---

## Entry: 11/9/2025 - 11/14/2025

### Time Spent
- **Total:** 5 hours

### Tasks Attempted
1. Integrate Habit class with UI
2. Minor refactoring and commenting of main.dart

### Problems Encountered
- **Problem 1:** Learning what is in the Habit and Log classes and how they work.
  - *Attempted solution:* Read the code and ask Josh Garbi and AI any other questions
  - *Outcome:* Resolved
- **Problem 2:** Flutter is still relatively new to me and I need to learn its syntax a bit more
  - *Attempted solution:* Continue coding and using Copilot as needed to provide understanding and aid development.
  - *Outcome:* Resolved

### Tasks Completed
- [x] Basic Habit class integration with UI
- [x] Minor refactoring and commenting of main.dart

### Notes & Reflections
This week I started integrating the front end and back end code. This is a big step in our project, and this was a good week to begin work on it. 

### Next Steps
- [ ] Attend Monday's meeting and decide next steps for the project. I will likely do a lot of refactoring of code in main.dart due to changes in the back end. I will also keep building new features into the UI.

---

## Entry: 11/16/2025 - 11/21/2025

### Time Spent
- **Total:** 6 hours and 15 minutes

### Tasks Attempted
1. Continue Habit class and UI integration
2. Move many UI methods from main.dart to main_helpers.dart
3. Attend team meeting

### Problems Encountered
- **Problem 1:** Continue implementing the rest of the fields from Habit such as start and end dates and isRecurring within the UI. Required adding new fields within the add Habit dialog.
  - *Attempted solution:* Determined how I wanted to set the fields up and add them as calendars, drop down menus, or switches
  - *Outcome:* Resolved
- **Problem 2:** Moving methods from main.dart to main_helpers.dart required determining which methods could be moved and deciding how to separate them.
  - *Attempted solution:* Read them and asked Copilot for help moving them and making changes while retaining the same functionality.
  - *Outcome:* Resolved

### Tasks Completed
- [x] Add the rest of the Habit fields to Habit creation from the UI
- [x] Moving methods from main.dart to main_helpers.dart
- [x] Attended team meeting and shared progress and learned where others are at

### Notes & Reflections
This week I made some major refactoring changes to main.dart. This makes it much more readable. Getting the methods from main.dart into another helper method file makes main much more clear and easy to understand. Having the other fields from Habit populated manually on instance creation allows for more functionality to be built in.

### Next Steps
- [ ] Attend Monday's meeting and decide next steps for the project. I will likely work on making habits only show in the UI when it is on or after their start date and on or before their end date.

---

## Entry: 11/30/2025 - 12/5/2025

### Time Spent
- **Total:** 5 hours

### Tasks Attempted
1. Add search bar
2. Implement searching
3. Create a temporary search method in main.dart until search.dart is fixed
4. Add a field for implementing times with habits in the create habit dialog
5. Attend team meeting

### Problems Encountered
- **Problem 1:** I found that the search.dart method wasn't workign as I expected it to
  - *Attempted solution:* I debugged it with Copilot and communicated what I found with the person who wrote the code. I then implemented a temporary fix in main.dart
  - *Outcome:* In Progress
- **Problem 2:** The code for setting times when a habit should be completed hasn't been merged yet
  - *Attempted solution:* Add a field for completion dates to the create habit dialog that will need to be hooked up later when the code is merged.
  - *Outcome:* In Progress

### Tasks Completed
- [x] Add search bar
- [ ] Implement searching
- [x] Create a temporary search method
- [x] Attended team meeting and shared progress and learned where others are at

### Notes & Reflections
This week I made good progress on implementing some new features. These features need some code changes on the backend that I am waiting to be fully implemented. When they are implemented I will finish implementing them within the UI portion of the app.

### Next Steps
- [ ] Attend Monday's meeting and decide next steps for the project. I will switch searching to using the searchHabits method from search.dart. I will also change the create habit dialog to work with completion times once it is implemented in the backend.

---