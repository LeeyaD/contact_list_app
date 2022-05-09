# Optional Project: Contact List App
App tracks contacts and their names, phone numbers, and email addresses. To add more complexity, assign contacts to categories (friends, family, work, etc).

Some things to think about while you work:
- Store data in a user's session or a file - user's session till I get to RB185: Networked Applications
- Add validations to validate values submitted via forms
- Keep shared content in a layout

## Notes
- Limit no. of contacts to 10 until you get to RB185
- Add sign-in functionality in RB185
- Add categories (friends, family, work, etc.) in RB185

## Building the Backlog
1. When user accesses the Contact List App, they see a page that allows gives them one choice; Add a contact.

[] Create a Ruby file for server-side code, `contact_list.rb` & add 1 route and 1 view, an index page with one button:
  - Add a contact

2. When user clicks `Add a Contact`, they see a form asking for a name, phone number, and if the user wants an email and notes.

[] Create a route and view for the button `Add a Contact` that directs user to a pg with a form for them to enter contact info and two buttons `Save` and `Cancel`
  - Decide DS for contact list and required/optional form fields
  - Add sessions to app, updating Gemfile as needed

3. When user clicks `Save`, they're taken to a page that shows the contact info they just entered. In addition to the `Add a Contact` button, there is now an `Edit` and `Delete` button for the individual contact.

4. When a user clicks `Cancel`, they go back to the main page.

5. When a user clicks `Edit`, they're taken to a page with a form that's displaying the current contact info. User can change info & click `Save` or `Cancel` and return to the main page.

6. When a user clicks `Delete` a popup window appears asking them if they're sure they want to delete the contact (contact name should be displayed). Options will be `Yes` or `No`

7. When user clicks `No`, nothing happens and they're returned to the main page.

8. When user clicks `Yes`, the contact is deleted and user is returned to the main page.