# User-Configurations-Manual


This code creates a **User Configuration Manager** using a Python dictionary to manage user settings.

**Main idea:**
It allows users to **add, update, delete, and view settings** such as theme, language, and notifications.

# Key Parts

* **`test_settings` dictionary** – stores user settings (key–value pairs).
* **`add_setting()`** – adds a new setting if it does not already exist.
* **`update_setting()`** – changes the value of an existing setting.
* **`delete_setting()`** – removes a setting from the dictionary.
* **`view_settings()`** – displays all current settings in a formatted way.

# Important Features

* Converts **keys and values to lowercase** to keep settings consistent.
* Prevents **duplicate settings**.
* Returns **messages** to tell the user what happened (added, updated, deleted, or error).

 **In short:**
The code is a simple program that **manages user preferences by adding, updating, deleting, and displaying settings stored in a dictionary.**
