Team git repository link: github.com/Zariphron/Team-10

Members:
Phuc Le - PhucLe01,
Kevin Campbell - Zariphron,
Manh Dinh Vu - ManhDinhVu 

# Use Case Description

Date: 09/15/21

Product Name: Milestone 1

Problem Statement: To help students study

Non-functional Requirements: Readable Font, Simple Layout, 

# Use case 1: Generate flash cards
## Summary
 Input a markdown file and ouput flash cards.

## Actors
	1. User

## Preconditions
	*Is a markdown file
	
## Triggers
	Select convert to flash cards

## Primary Sequence
	1. Select option to convert to flash cards
	2. Select markdown file
	3. Confirm

## Primary Postconditions
	Recieve flash cards

# Use case 2: Share Flash Cards
## Summary
 	Share flash cards with other users, with the ability to download the cards.

## Actors
	1. Owner
	2. Recipiant

## Preconditions
	*Flash cards exist
	*Recipient exists

## Triggers
	Select option to shate flash card

## Primary Sequence
	1. Owner has flash cards
	2. Select 'share' on the flash cards
	3. Owner selects who to share the cards with
	4. Owner confirm share

## Primary postconditions
	Recipient has a copy of the shared flash cards

# Use case 3: Create time blocks
## Summary
	User can create a schedule for what to study and at what time

## Actors
	1. User

## Preconditions
	User has logged in

## Triggers
	User select make time block button

## Primary sequence
	1. User select "select a block of time"
	2. User write what that block of time is for
	3. User confirm and save that block of time

## Primary postconditions
	User will recieve a notice when time block is near

# Use case 4: Use pomodoro timer
## Summary
	A 25 minute timer

## Actors
	1. User

## Preconditions
	User is logged in

## Triggers
	User select start on the timer

## Primary sequence
	1. User select on the pomodoro timer
	2. User select start on the timer

## Primary postconditions
	User will be notified when the 25 minute timer ends

# Use case 5: Mind map of flash cards
## Summary
	User can select a flash card and connect it to another flash card

## Actors
	1. User

## Preconditions
	User has more than 1 flash card

## Triggers
	User select mind map

## Primary sequence
	1. User select mind map
	2. User select a flash card
	3. User select another flash card 
	4. User select which 2 flash card to connect
	5. User save mind map

## Primary postconditions
	User can go back to mind map to look or edit

# Use case 6: Convert markdown notes to pdf
## Summary
	User can convert a markdown file to a pdf file

## Actors
	1. User

## Preconditions
	User has a markdown file

## Triggers
	User select convert to pdf button

## Primary sequence
	1. User select a markdown note
	2. User select comvert to pdf button
	3. User select confirmation button

## Primary postconditions
	User has a pdf of the markdown note

# Use case 7: Share notes with other people
## Summary
	User can share their notes with other users

## Actors
	1. User
	2. Recipient

## Preconditions
	User has atleast 1 note
	There are other users

## Triggers
	User selects share note button

## Primary sequence
	1. User selects a note
	2. User selects share button
	3. User selects a recipient
	4. User confirms sharing of note

## Primary postconditions
	Recipient has a copy of the notes

# Use case 8: Create a pdf file of flash cards to print
## Summary
        Create a pdf file of flash cards to print

## Actors
	1. User
        2. The website 

## Preconditions
	* The user's account must have at least one flash card

## Trigger
	User presses on button "download flash cards" 

## Primary Sequence
	1. User presses on button "download flash cards"
        2. Web site creates a pdf file and upload there all flash cards with questions and answers
        3. Web site opens a new tab and allows the user to download the file
        4. User presses download, and receives the pdf file 

## Primary Postconditions
	* User receives a pdf file of all flash cards with questions and answers
	
## Alternate Sequences
        * The button to "download" should appear only when at least one flash cards were created

## Alternate Trigger
        * No alternate trigger


## Alternate Postconditions
        * No alternate postconditions

# Use case 9: Change order of flash cards based on how often user got answer correct 
## Summary
	Change order of flash cards based on how often user got answer correct

## Actors
      1. User
      2. The website

## Preconditions
      *The user needs to have at least 3 flash cards on his account
      *(optional) In settings user's account should have a checkbox "on" for this feature
      
## Triggers
      * User checks the answer of a flash card

## Primary sequence
      1. When the user checks the answer, there should be two buttons: "Got it right!" or "Got it wrong"
      2. User pressed on one of the buttons
      3. If the user pressed the "Got it right" button => count adds +1 to correct answers and shuffle the card at the end of the deck
      4. If the user pressed the "Got it wrong" button => this card shuffles in the middle (between this card and the end) of the deck.

## Primary postconditions
      * User's deck of flash cards shuffled according to on which button he/she pressed
      
## Alternate Sequences
      * If the user didn't press any of the buttons and flips the card back => do nothing

## Alternate Trigger
      * No alternate sequences

## Alternate Postconditions
      * No alternate postconditions

# Use case 10: Find text 
## Summary
      * A user who has logged in and entered a file can search text in that file.

## Actors
      * User

## Preconditions
      * The user has logged and entered a file.

## Triggers
      * User selects “search” option.

## Primary sequence
      1. System prompts the user to enter text.
      2. System searches for the text in the file.
      3. System shows matching results.

## Primary postconditions
      The system displays a message that searching is completed.
      
## Alternate Sequences
      * The user-entered text does not exist.
      1. The system displays a message that no matches were found.
      2. The system prompts the user to enter a text that exists.

# Use case 11: Rename files 
## Summary
      * A user who has logged in and can rename any file. 

## Actors
      1. Users
      2. Preconditions

## Preconditions
      * The user has logged in

## Triggers
      * User selects “rename” option.

## Primary sequence
      1. System shows files.
      2. User selects a file and rename it.
      3. System renames the file.

## Primary postconditions
      * The system displays a message that the file was renamed.
      
## Alternate Sequences
      * The user entered an invalid name.
      1. The system displays an error message to the user.
      2. The system prompts the user to enter a valid name.

# Use case 12: Track hours worked every day 
## Summary
      Users are able to document how long they worked in a day.

## Actors
      1. Professors
      2. Students

## Preconditions
      1. Users have an account
      2. Users have logged in to the application

## Triggers
      * Users selected in Time Management option, then users select in the Track hours function

## Primary sequence
      1. System prompts users to click the start button.
      2. Users click the start button to count time.
      3. System gets the date of the calendar.
      4. System begins to count time.
      5. Custom stop counting time when they want.
      6. System shows a record of users.

## Alternate Postconditions
      * Users see their records everyday

# Use case 13: Visualize hours worked and projects
## Summary
      A user wants to see their activities in a day, one month, or one year.

## Actors
      1. Professors
      2. Students

## Preconditions
      1. Users have an account
      2. Users have logged in the application

## Triggers
      * Users selected in Time Management option, then users selected in Visualize hours function.

## Primary sequence
      1. System prompts user click on which activities they want to see.
      2. User clicks on the activities they want.
      3. System prompts users to select the date that they want to see.
      4. User chooses the date that they want.
      5. System shows their record of that date.
      6. User backs out to the previous screen, and select a different record if they want.
      7. User returns to the main screen.

## Primary Postconditions
      *  Users see their records

# Use case 14: Visualize timeblocks (similar to day view on google calendar)
## Summary
      * A user wants to see their activities in our calendar that they create by themselves.

## Actors
      1. Professors
      2. Students

## Preconditions
      1. User has an account
      2. Users have logged in the application
      3. User created a calendar

## Triggers
      * Users selected in Time Management option Then users selected in Visualize timeblocks function

## Primary sequence
      1. System prompts user to click on which calendar user want to see.
      2. Users clicks calendar
      3. System shows the user a list of events in the calendar that the user created before.
      4. User clicks an option of events which they want to see or click all event option.
      5. System shows the user’s events to review.
      6. User clicks on an event.
      7. User backs out to the screen to choose a previously made event or quit Visualize timeblocks function.

## Alternate Postconditions
      * Users see their notes on flash card

# Use case 15: Create time blocks (using markdown)
## Summary
      * A user wants to create some notes, aware and strategic of how they want to spend their time.

## Actors
      1. Professors
      2. Students

## Preconditions
      1. Users have an account
      2. Users have logged in to the application

## Triggers
      * Users select Time Management option then user selects the “create calendar” symbol on the top right.

## Primary sequence
      1. System prompts user for input of the title for the event.
      2. User types title.
      3. System prompts user for more specific information to input for the event.
      4. User writes notes down in the editor.
      5. System prompts user input date time they want to save, also reminder every day or every week
      6. User selects the date-time.
      7. User saves it.
      8. System converts the file text under markdown editor (see use case “input a markdown file and output flash cards")
      9. System attaches this event on the calendar.
