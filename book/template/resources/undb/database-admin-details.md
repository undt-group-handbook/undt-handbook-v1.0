# Admin details

By default, new users who are added to the database will be able to view all entries, however they will only be able to edit entries for which they are listed as the "Researcher" or an "Authorised User".

These may only be edited by other users who have access to the backend Access database. This is password protected: in general, this should not be used for field editing. If you have a genuine need to access the backend and cannot use the client, please get in contact with the person currently responsible for maintaining the database.



## Adding new users

The user resposible for maintaining the database has the responsibility for adding new user accounts when needed. Accounts are largely used in the event of bugs and errors, to track what may have raised issues a specific user is facing.

New users may not be added via the client, and may be added in the database stored on the RDSF. Load the database and enter the password, and load the "Users" table. Add a new entry for the new user, and provide them with the username and password.



## Bypass key

If you need to edit the client GUI, you can bypass the startup options if you are an elevated user. Load the backend database stored on the RDSF, and open the "Users" table. Find the entry corresponding to the relevant user, and set the "UserType_ID" field to "1".

This user now has access to edit the client. Open the client, and enter your login details. When prompted, select to enable the bypass key. Close the client again, and open it up while holding the `Shift` key. You will now have access to edit the client.

While performing edits, make sure that you are doing this on a copy of the client which has been saved to your local space, to prevent causing any breaking errors.