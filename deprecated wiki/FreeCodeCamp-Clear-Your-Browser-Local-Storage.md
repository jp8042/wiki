# Removing All Locally Stored Challenges

Removing all your locally stored challenges will solve many problems related to the browser crashing on FreeCodeCamp

In Chrome:

- On [freecodecamp](https://freecodecamp.com) open your console
  - Windows: `Ctrl` + `Shift` + `J`
  - Mac OS: `Cmd` + `Opt` + `J`
- Go to Application Tab(Chrome). 
  - There click on the "Local Storage" link in the nav bar on the right.
- Delete all the entries on the right side, or run this command in your browser's console to clear all entries from your localStorage: `localStorage.clear();`
- See if this solves your issue

![](https://preview.ibb.co/iOddxn/Capture.jpg)

Alternatively, if you are having issues with a specific challenge freezing your browser, [find the name of that challenge in local storage and delete just that one](FreeCodeCamp-Clear-Specific-Data-Local-Storage).
