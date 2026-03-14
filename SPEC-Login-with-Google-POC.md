Project name: Login-with-Google-POC

- Create a web page. There are three pane on the scree, left, middle, right.
- Left pane is for account list, Mid pane is for toke display, right pane is for Google login icon.
- At the beginning, left pane is empty, mid pane is empty, right pane has a icon of standard "Login with Google".
- Flow: User click the "Login with Google" -> redirect to Google authentication -> when authenticated, redirect back the main page of this project. left pane show the google account and its aviator. Mid pane show the id token returned from Google.
- User can click "Login with Google" again to authenticate another Google account. After success, the left pane list appended with the second Google account. And so on.
