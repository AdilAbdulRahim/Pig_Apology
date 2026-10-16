# Firebase setup for Apology Piggy Bank

The site uses anonymous Firebase Authentication. Visitors can open the public link, choose a scoreboard name, and start using the shared scoreboard without a code.

1. In Firebase Authentication, enable Anonymous sign-in.
2. Create a Firestore database.
3. Publish the contents of `firestore.rules` as the Firestore security rules.
4. Keep the Firebase web app configuration in `index.html` pointed at this project.

Each anonymous visitor gets a player record owned by that browser's Firebase identity. The scoreboard is publicly readable; each visitor can create and update only their own record.
