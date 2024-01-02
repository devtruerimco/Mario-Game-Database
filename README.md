# Mario Game Database
A database of Mario character games 

This project is a relational database focused on the Mario franchise, organizing information about characters, additional details, sounds associated with characters, and specific actions each character can perform. Let's break down the components:

* More_info Table:

Stores detailed information about characters, such as birthday, height, weight, and a link to the character through the character_id.

* Characters Table:

Contains general details about each character, including their name, homeland, and favorite color.

* Sounds Table:

Lists sound files associated with specific characters, linking each sound to a character through the character_id.

* Actions Table:

Defines different actions that characters can perform, represented by unique action_id values.

* Character_actions Table:

Establishes a many-to-many relationship between characters and actions, indicating which actions each character can perform.
