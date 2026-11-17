# Campus Club Membership
A simple student club membership webpage built with HTML and internal
CSS.
Features
- Navigation bar with Home, Events, and Join links
- Programming Club information card
- NEW badge on the club card
- Membership form with:
  - Full Name
  - Email
  - Student ID
  - Age
  - Membership Type (General or Executive)
  - Preferred Club
  - Reason for joining
  - Agreement checkbox
- Basic HTML form validation
- Purple and white user interface
Technologies Used
- HTML5
- CSS3 (Internal CSS)
How to Run
1. Download or clone this repository.
2. Open the project folder.
3. Open index.html in a web browser.
Form Validation
The form uses built-in HTML validation:
- required prevents empty fields.
- type="email" checks the email format.
- minlength="3" requires at least 3 characters in the name.
- pattern checks the Student ID format (XX-XXXXX-X).
- min="17" and max="40" set the allowed age range.
- maxlength="200" limits the reason text to 200 characters.
Note
This is a front-end practice project. The form demonstrates HTML
validation, but it does not store or submit membership information to a
database.
