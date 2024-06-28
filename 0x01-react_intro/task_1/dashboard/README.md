Embedding expressions, functions
mandatory

Using your code from the previous task, in task_1/dashboard/src/utils.js:

    Create a function named getFullYear that will return the current year
    Create a function named getFooterCopy:
        It accepts one argument isIndex(boolean). When true, the function should return Holberton School. When false, the function should return Holberton School main dashboard
    Modify the footer returned in task_1/dashboard/src/App.js to use these two functions

in task_1/dashboard/src/Notifications.js, create a Notifications element:

    It should import React
    It should export a function
    The function should return a div with the class Notifications
    The div should contain a paragraph with the text Here is the list of notifications
    import the file Notifications.css.

in task_1/dashboard/src/Notifications.css, style the Notifications class:

    Add a border and some padding around the div

Render the Notifications element:

    Modify task_1/dashboard/src/index.js to render the new element (Notifications) in a div named root-notifications
    Check that you can see the two elements on the browser, and using the React browser extension

Requirements:

    When running, there should not be any lint error in the console

