**User Stories**

1. “As a Dungeon Master, I want to press a single button to populate a city so that I can prepare for a Dungeons & Dragons session quickly.”

2. “As someone who doesn’t have their computer at a D&D session, I want to be able to easily print a copy of my city so that I can have a physical copy in front of me that I can write on.

**Use Cases**

1. Given three size options (small, medium, large) and three city types (village, town, city), when the user selects the specific parameters for their desired city, then the application will deliver a fully populated city filled with categories appropriate to those parameters.

2. Given that a city has already been generated, when a user selects the “export as Word doc” option, then a downloadable Word document will be generated containing the information displayed on the web page.

3. Given that a city has already been generated, when a user would like to customize the name or parameters of an element, then they will be able to do so by selecting the arrow at the end of the element.

4. Given a non-player character, when the NPC is of a certain fantasy race (e.g. Dwarf), then the randomly generated name will be appropriate for that race (e.g. Scottish-sounding for a Dwarf).

**Requirements List**

1. System shall be simple and easy to use

	1.1. System shall create a city from scratch with only take one click

	1.1.1. System shall accomplish the above by using a nested drop-down list

2. System shall be able to be printed easily

	2.1. System shall accomplish the above by having the ability to export as a Microsoft Word document
	
3.	System shall produce convincing random names appropriate for the fantasy race selected

	3.1.	System shall contain a bank of names to produce the above requirement
	
	3.1.1.	 System shall utilize Markov chains to produce further randomized names
	
4.	System shall be fully customizable

	4.1.	System shall allow user to customize the names of buildings and characters as well as the attributes of the characters
	
	4.1.1.	 System shall accomplish the above by providing a button by each field which, when clicked by the user, allows them to 			 enter the information they would like

