# Homework 02

## NOC List

Congratulations agent. Your work on the Mission Briefing application was exemplary and has already proven invaluable to getting field agents up to speed on their new missions. The Director has noticed your hard work and has seen fit to increase both your security clearance and your field of responsibility. Your next mission is a top priority for the agency and if completed successfully, could provide you with a valuable shortcut to a supervisor position. Please read below for further info.

Our undercover agents in Eastern Europe are in trouble. The NOC list (Non-official cover) has been leaked and we need our directors to have quick access to the information so we can try to mitigate the damage. Some of the agents on the list have an access level that makes them privy to very sensitive information. We need an application that will present the NOC list's information in a quickly digestable format. Our top agents have been working on it, but we need this done ASAP and you've proven yourself to be quite capable of a quick turnaround.

See the agency's Github repository for the project resources. Also contained within will be additional instructions for completing this mission.

The Director herself has given you access to all the agency's resources to complete this mission. We're counting on you agent.

This message will self destruct in 5 seconds.

### Steps to Success

#### Storyboard Tasks

* [x] The master view should be embedded in a navigation controller
* [x] The table view cell prototype should display two labels. One on the left of the cell and one on the right.
* [x] The table view cell prototype should have a disclosure indicator
* [x] The table view cell prototype should have its reuse indentifier set (hint: this should match the identifier set in "cellForRowAtIndexPath")
* [x] The table view prototype cell should segue to the detail view. This should "show" the detail view.

* [x] The detail view should have a custom class name of "DetailViewController". See the identity inspector in Interface Builder.
* [x] The detail view should have 3 labels
	* [x] A label in the upper left corner that displays the agent's cover name
	* [x] A label 10 pts below the cover name label that displays the agent's real name
	* [x] A label centered horizontally and vertically in the view that displays the agent's access level. It should say "Level #".
	* [x] These labels should be connected to their appropriate properties in the DetailViewController class.

#### Code Tasks

* [x] 1 and 2. Extract the appropriate values from the agent dictionary and set the associated Agent object values
* [x] 3. Set the title of the master view
* [x] 4. Initialize the agents NSMutableArray
* [x] 5. Call loadNocList method
* [x] 6. Create a for-in loop to iterate over the agent dictionaries and create Agent objects out of them
* [x] 7. Call a method to reload the data for the tableview
* [x] 8. Set the segue identifier to match the value used in the storyboard 
* [x] 9. Get the index path value for the selected cell
* [x] 10. Replace the "0" in the brackets with the row value of the index path object
* [x] 11. Use the provided call to the segue object for the destinationViewController to send the Agent object to the detail view controller
* [x] 12. Set the number of rows per section for our tableview (we only have 1 section)
* [x] 13. Add the appropriate cell identifier in the dequeue method call
* [x] 14. Get a handle to the appropriate Agent object from the agents array
* [x] 15. Set the two cell labels to their appropriate values from the Agent object (the cover name and the real name)
* [x] 16. Send something to the object calling this method. What is this method supposed to return?
* [x] 17. Connect this property to its associated storyboard object
* [x] 18. Create two additional properties for the other storyboard objects and connect them as well
* [x] 19. Extract the agent's last name from the cover name property
* [x] 20. Set the title of this view to "Agent #", where # is the agent's last name
* [x] 21. Set the three labels to their appropriate values from the Agent object
* [x] 22. Call the configureView method
