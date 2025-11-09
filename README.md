Chat package
Files:
- index.html (login)
- register.html
- chat.html
- profile.html
- dm.html
- admin.html
- _redirects

Instructions:
1. Upload these files to your Netlify site root (or zip and drag to Deploys).
2. In Firebase Realtime Database Rules ensure usernames, messages and status have read/write configured as needed.
3. Create /admins/{yourUid}: true in the DB to enable admin panel.
4. Test register -> login -> chat.
5. For production, harden rules: require auth for writes, and use Cloud Functions for privileged actions.
