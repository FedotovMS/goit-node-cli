To use this application use the following commands:

1. Display the contacts list:

node index.js -a list

2. Get a contact by ID (returns null if the contact does not exist):

node index.js -a get -i [id]

3. Add a contact and display the created contact object:

node index.js -a add -n [name] -e [email] -p [phone]

4. Remove the contact (displays the deleted contact object or null if the contact does not exist):

node index.js -a remove -i [id]

