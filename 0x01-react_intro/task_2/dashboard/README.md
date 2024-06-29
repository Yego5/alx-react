Modify the Notifications
in task_2/dashboard/src/utils.js:

    Create a function named getLatestNotification that returns the following string: <strong>Urgent requirement</strong> - complete by EOD

in task_2/dashboard/src/Notifications.js in the Notifications div:

    add a button element with inline styling (without using the CSS file):
        show button on right side of notifications box
        aria-label is Close
        when user clicks on the button it logs to the console Close button has been clicked
    in the button element add a children img element that will import the close-icon.png image
    after the paragraph add an unordered list
        the list has the following items:
            The first one has a default priority and says New course available
            The second one has a urgent priority and says New resume available
            Add the priority to the first and second items of the list using a data attribute
            The last item correctly displays the content of getLatestNotification using dangerouslySetInnerHTML

in task_2/dashboard/src/Notifications.css:

    style the notification priorities using their data attribute: set the color of default items to blue, and the color of urgent items to red.

Requirements:

    When running, there should not be any lint error in the console
    Your app should look like the following screenshot:
 
