# Meditation User Stories

# User Story: Login/Registration Page

**Title:**  
## Login/Registration Page

_As a user, I want to log in or register, so that I can access my habit tracking data._

**Acceptance Criteria:**
1. The user can see the login form with email and password fields.
2. The user can register a new account with their email and a secure password.
3. The user can reset their password if forgotten.

**Priority:** High

**Story Points:** 5

**Notes:**
- Ensure that password fields are masked.
- Add a "Remember me" option for the login.
- Handle invalid login attempts with an error message.



## Account Registration

**Title:**
_As a user, I want to register with my name, username, age, and country so that I can create an account and access the habit tracking features._

**Acceptance Criteria:**
1. The user can enter their name, username, age, and country in the registration form.
2. The user can submit the form to create a new account.
3. The user receives a confirmation message once their account is successfully created.
4. The registration form must validate that the username is unique and the age is a valid number.

**Priority:** High

**Story Points:** 5

**Notes:**
- Make sure the username is checked for availability during registration.
- Validate that the user’s age is a valid number and is within an acceptable range (e.g., 18+).
- The country field should be a dropdown list of available countries.



## Account Login

**Title:**
_As a user, I want to log in using my username and password so that I can access my account and track my habits._

**Acceptance Criteria:**
1. The user can enter their username and password in the login form.
2. The login form is submitted to authenticate the user.
3. The user is redirected to the homepage upon successful login.
4. If the login is unsuccessful, an error message is shown with details on why login failed.

**Priority:** High

**Story Points:** 5

**Notes:**
- The login form should include a "forgot password" option.
- Password input should be masked for security.
- Provide a loading indicator when the login request is in progress.



## Error Feedback on Login

**Title:**
_As a user, I want to receive a message if I enter the wrong username or password so that I know my login attempt was unsuccessful._

**Acceptance Criteria:**
1. The user is informed if the entered username or password is incorrect.
2. The error message clearly states that either the username or password is invalid.
3. The user is given the option to try again with corrected details.

**Priority:** High

**Story Points:** 3

**Notes:**
- The error message should be prominent and easy to understand.
- The user should be allowed to reattempt logging in without refreshing the page.
- Ensure there is a timeout after a number of unsuccessful login attempts to prevent brute-force attacks.


# User Story: Home Page


## View Welcome Message
**Title:**
_As a user, I want to see a personalized welcome message with my name on the homepage, so that I feel recognized and can confirm I am logged into the correct account._

**Acceptance Criteria:**
1. The homepage displays a personalized welcome message with the user's name.
2. The message should greet the user based on the time of day (e.g., "Good Morning, [User]!").
3. The user can confirm that the account shown is the one they are logged into by checking the name displayed.
4. The welcome message is visible immediately upon loading the homepage.

**Priority:** High

**Story Points:** 3

**Notes:**
- Ensure the name is pulled from the user’s profile information.
- Make sure the message is responsive and looks good on all devices.
- Provide a fallback if the user's name is unavailable (e.g., "Welcome back!").




## Display Weekly Progress

**Title:**
_As a user, I want to see my daily progress for each habit on the homepage, so that I can easily monitor my progress._

**Acceptance Criteria:**
1. The user can see a list of habits with a progress bar or percentage indicating how much progress has been made during the week.
2. The progress should be updated in real time as the user logs their activities.
3. The homepage displays the number of days completed versus the total days of the week.
4. The progress section is clearly organized and easy to read.

**Priority:** High

**Story Points:** 5

**Notes:**
- Each habit's progress should be displayed in a visually appealing format (e.g., progress bars, color-coded).
- Include a "Reset Progress" button if the user wants to start over for the week.
- Ensure the progress is displayed in the correct time zone.



## View Completed Habits

**Title:**
_As a user, I want to see a section for completed habits on the homepage, so that I can track what I have already achieved._

**Acceptance Criteria:**
1. The homepage shows a section where completed habits are listed.
2. Each habit entry includes the habit name, date, and any relevant notes or achievements.
3. Completed habits are visually separated from ongoing or incomplete habits.
4. The section should be easy to access and navigate.

**Priority:** Medium

**Story Points:** 4

**Notes:**
- Display completed habits with a checkmark or similar indicator.
- Allow the user to click on a completed habit for more details (e.g., the number of days completed).
- Consider displaying achievements for completed habits (e.g., "You completed this habit for 7 consecutive days!").

# user stories for the menu

## Access Menu Options
**Title:**
_As a user, I want to access a menu with options for configuring my habits, viewing reports, editing my profile, and signing out, so that I can easily navigate to different parts of the app._

**Acceptance Criteria:**
1. The menu is easily accessible from any page in the app.
2. The menu includes clear options such as "Configure Habits", "View Reports", "Edit Profile", and "Sign Out".
3. The user can open the menu with a single click or tap.
4. The menu is responsive and works well on both desktop and mobile devices.

**Priority:** High

**Story Points:** 5

**Notes:**
- The menu should be collapsible for better user experience on smaller screens.
- Ensure that each option is clearly labeled and easy to understand.
- Highlight the active page or section in the menu (e.g., "Profile" should be highlighted when the user is on the Profile page).



## Navigate to Profile

**Title:**
_As a user, I want to access a menu with options to configure my habits, view reports, edit my profile, and sign out, so that I can easily navigate different parts of the app._

**Acceptance Criteria:**
1. The user can click or tap on the "Edit Profile" option from the menu to navigate to their profile page.
2. The profile page displays the user's personal information, such as name, username, age, and country.
3. The menu should clearly label the "Edit Profile" option and provide a visual cue when selected.
4. The user can return to the previous page from the profile page easily.

**Priority:** High

**Story Points:** 4

**Notes:**
- Ensure that the user's profile page is updated in real-time if any changes are made to their information.
- The "Edit Profile" button should be prominent and easy to locate in the menu.



## Navigate to Habits Page

**Title:**
_As a user, I want to access the habits page from the menu, so that I can configure and manage my habits._

**Acceptance Criteria:**
1. The user can click or tap on the "Habits" option in the menu to navigate to the habits page.
2. The habits page should list all the user’s habits, showing their current progress.
3. The user can easily add, remove, or edit habits from the habits page.
4. The habits page should be displayed clearly and organized for easy management.

**Priority:** High

**Story Points:** 4

**Notes:**
- Ensure that the "Habits" page is intuitive and easy to use, with clear buttons for adding or modifying habits.
- Provide a summary of the user's habits at the top of the page (e.g., “3 out of 5 habits completed this week”).



## Sign Out from Menu

**Title:**
_As a user, I want to sign out of my account using an option in the menu, so that I can securely log out when I'm finished using the app._

**Acceptance Criteria:**
1. The menu includes a clearly labeled "Sign Out" option.
2. When the user clicks or taps the "Sign Out" option, they are logged out and redirected to the login page.
3. The user receives a confirmation message that they have successfully signed out.
4. Any unsaved changes (if applicable) are either saved or discarded before sign-out.

**Priority:** High

**Story Points:** 3

**Notes:**
- Ensure that the user is logged out securely, with no residual data left in the session.
- After signing out, the user should be redirected to the login page or a public area of the app.
- Provide a "session timeout" feature for automatic logout if the user is inactive for too long.




# User Stories for profile page

## View Personal Information

**Title:**
_As a user, I want to view my saved name, username, age, and country on my profile page, so that I can see the details I provided during registration._

**Acceptance Criteria:**
1. The user can navigate to the profile page and view their saved personal information: name, username, age, and country.
2. The information is displayed clearly and in a readable format.
3. The user can easily distinguish between the different pieces of information (e.g., name, username, etc.).
4. The information is automatically fetched and displayed when the user accesses the profile page.

**Priority:** High

**Story Points:** 3

**Notes:**
- Ensure that the information shown is accurate and reflects what was saved during registration.
- Consider adding a section header or title to make it clear where the user’s personal details are located.


## Edit Personal Information

**Title:**
_As a user, I want to update my name, username, age, and country on my profile page, so that I can keep my information up to date._

**Acceptance Criteria:**
1. The user can edit their name, username, age, and country directly from the profile page.
2. Editable fields should be clearly indicated (e.g., text boxes, drop-downs for country).
3. The user can make changes to any or all of these fields.
4. The user can save changes to update their profile information.

**Priority:** High

**Story Points:** 5

**Notes:**
- Ensure that the fields for editing are easy to use and intuitive.
- Allow the user to edit each field individually without affecting the others.
- Consider adding validation checks (e.g., for the username format or age input).



## Save Updated Information

**Title:**
_As a user, I want the changes I make to my profile to be saved, so that my updated details are stored and reflected throughout the app._

**Acceptance Criteria:**
1. The user can save any changes they make to their personal information.
2. The updated information is stored and reflected immediately across the app (e.g., the name in the header should change).
3. A confirmation message is shown to indicate that the changes have been successfully saved.
4. If an error occurs (e.g., invalid input), the user is informed with a clear error message.

**Priority:** High

**Story Points:** 5

**Notes:**
- Ensure that the app updates the user’s details across all pages and sections where the information is used.
- Consider implementing automatic saving or offering a “Save Changes” button.
- Include error handling for invalid or missing inputs.


## Update Name in Header

**Title:**
_As a user, I want my updated name to be displayed in the app's header after I change it in the profile, so that my changes are immediately visible._

**Acceptance Criteria:**
1. The user’s updated name should immediately appear in the app’s header after they save the changes on the profile page.
2. The header is updated dynamically to reflect the change without needing to reload the page.
3. The name in the header is consistent with the updated information saved in the profile.

**Priority:** High

**Story Points:** 4

**Notes:**
- Ensure that the header is updated immediately after the user saves changes to their profile.
- This update should happen seamlessly without requiring a page refresh or additional user interaction.




# user stories for the Habits Page

## Add a New Habit
**Title:**
_As a user, I want to add new habits on the details configuration page so that I can manage and update my habits as needed._

**Acceptance Criteria:**
1. The user can navigate to the habits page and click an "Add Habit" button.
2. The user is directed to a form where they can input details about the habit, such as name, frequency (daily, weekly, etc.), and any other relevant information.
3. Upon submitting the form, the new habit is added to the list of habits on the habits page.
4. The new habit appears in the list with its assigned frequency and any other relevant details.

**Priority:** High

**Story Points:** 5

**Notes:**
- Ensure the form is simple to fill out and allows users to easily create a habit.
- Consider adding input validation to ensure that required fields (e.g., habit name) are filled out.
- Provide a success message when the habit is successfully added.



# Delete a Habit

**Title:**
_As a user, I want to delete existing habits so that I can keep my habits up to date._

**Acceptance Criteria:**
1. The user can click on a "Delete" button next to any habit in the habit list.
2. Upon clicking "Delete", the user is prompted with a confirmation message to ensure they want to delete the habit.
3. Once confirmed, the habit is removed from the list and is no longer tracked.
4. The user receives feedback that the habit has been successfully deleted.

**Priority:** High

**Story Points:** 4

**Notes:**
- Ensure that deleted habits are permanently removed and cannot be recovered unless the user recreates them.
- Consider providing an "Undo" option for a short time after deletion in case of accidental deletion.
- The "Delete" button should be easy to find, but not so prominent that users accidentally click it.



# Personalize a Habit with Color

**Title:**
_As a user, I want to assign a specific color to each habit to make it personal to me._

**Acceptance Criteria:**
1. The user can choose a color for each habit when creating or editing a habit.
2. A color picker is available to the user, allowing them to select a color from a palette or input a custom color code.
3. The chosen color is applied to the habit's display on the habits page and helps visually differentiate the habits.
4. The color choice persists even if the user refreshes the page or logs out and logs back in.

**Priority:** Medium

**Story Points:** 4

**Notes:**
- Ensure the color picker is user-friendly and accessible on both desktop and mobile devices.
- Provide a default color for users who do not wish to personalize their habits.
- The colors should be visually distinct enough to avoid confusion between different habits.

# User Story  for The Reports Page

## View Weekly Reports
**Title:**
_As a user, I want to see a report of my weekly habit progress so that I can understand how well I am maintaining my habits._

**Acceptance Criteria:**
1. The user can view a summary of their habit progress for the entire week.
2. The report includes details such as the number of days each habit was completed and the overall progress percentage.
3. The report is displayed in a clear, easy-to-read format (e.g., table or list format).
4. The user can filter the report by specific habits or days, if needed.

**Priority:** High

**Story Points:** 5

**Notes:**
- Ensure that the report covers all habits the user has tracked for the week.
- The report should update in real-time as the user logs their progress for each day.
- Consider adding the ability to export the report to CSV or PDF for further analysis.


## Visualize Completed Habits

**Title:**
_As a user, I want to see a chart of my completed habits for each day of the week so that I can quickly identify trends in my progress._

**Acceptance Criteria:**
1. The user can view a chart (e.g., bar chart, line graph) that shows how many habits were completed each day of the week.
2. The chart is interactive, allowing the user to hover over or click on individual data points for more detailed information.
3. The chart is clearly labeled with days of the week on the x-axis and the number of completed habits on the y-axis.
4. The user can switch between different types of visualizations (e.g., bar chart, pie chart) based on their preference.

**Priority:** Medium

**Story Points:** 4

**Notes:**
- The chart should be visually appealing and easy to understand, even for users with no data analysis experience.
- Consider offering color coding for different habits to differentiate them in the chart.



## View All Habits

**Title:**
_As a user, I want to see both completed and incomplete habits in my report so that I have a comprehensive view of my habit tracking performance._

**Acceptance Criteria:**
1. The report should display all habits, both completed and incomplete, for the week.
2. Incomplete habits are clearly marked or visually distinguished (e.g., in gray or with a “not completed” tag).
3. The user can easily identify which habits they have successfully completed and which ones they need to focus on.
4. The report includes additional details about incomplete habits, such as the specific days they were missed.

**Priority:** High

**Story Points:** 5

**Notes:**
- Ensure that incomplete habits are not hidden or difficult to find in the report.
- Consider adding a summary of the user’s habit completion rate to give them an overall performance view.

# User Story: For The Notifications Page

## Enable/Disable Notifications
**Title:**
_As a user, I want to be able to enable or disable notifications for the app, so that I can choose whether or not to receive reminders for my habits._

**Acceptance Criteria:**
1. The user can toggle a setting to enable or disable notifications for the app in the notifications settings page.
2. When notifications are disabled, the user will no longer receive any reminders for their habits.
3. When notifications are enabled, the user will start receiving notifications for the habits they have selected.
4. The user can easily toggle this setting on or off at any time.

**Priority:** High

**Story Points:** 3

**Notes:**
- Make sure that notifications are fully disabled when the user opts out, including push notifications and in-app reminders.
- Consider adding a clear visual indicator for when notifications are enabled or disabled.


## Add Habits for Notifications

**Title:**
_As a user, I want to select specific habits to receive notifications for, so that I only get reminders for the habits I am actively working on._

**Acceptance Criteria:**
1. The user can navigate to a list of their habits and choose which ones they want to receive notifications for.
2. The user can toggle notifications for each habit individually.
3. Once selected, the user will start receiving reminders only for the habits they’ve chosen.
4. The user can update the list of selected habits for notifications at any time.

**Priority:** High

**Story Points:** 4

**Notes:**
- Provide a clear list of habits with checkboxes to allow users to select the ones they want to receive notifications for.
- Allow users to deselect habits easily if they no longer wish to receive reminders for them.



## Set Notification Times

**Title:**
_As a user, I want to have the option to receive notifications three times a day (morning, afternoon, evening) for all selected habits, so that I get timely reminders throughout the day to complete my habits._

**Acceptance Criteria:**
1. The user can set up three distinct times for notifications: morning, afternoon, and evening.
2. For each habit that is selected for notifications, the user can assign specific times during the day for receiving reminders (e.g., 8 AM for morning, 2 PM for afternoon, and 6 PM for evening).
3. The notifications are sent automatically at the set times for each habit.
4. The user can modify the times for their notifications at any time.

**Priority:** Medium

**Story Points:** 5

**Notes:**
- Provide a simple time picker interface for users to easily set notification times.
- Ensure that the reminders are sent precisely at the set times.
- Consider offering default time slots (e.g., 8 AM, 2 PM, 6 PM) for users who want quick setup.


  

