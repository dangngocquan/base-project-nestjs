# BASE PROJECT NESTJS

### About environment variables

***1. SERVER CONFIG***

PORT=3000

***2. POSTGRES DATABASE CONFIG***

DB_HOST=localhost

DB_PORT=5432

DB_USERNAME=postgres

DB_PASSWORD=12345678

DB_NAME=postgres

***3. GOOGLE OAUTH2 CONFIG***

GOOGLE_CLIEND_ID='your-google-client-id'

GOOGLE_CLIEND_SECRET='your-google-client-secret'

***Steps to get this environment variables:***

***+ Step 1: Go to Google Cloud by link `https://console.cloud.google.com/`***

***+ Step 2: `Select a project` > `New project` > Create and access your project***

***+ Step 3: Go to `APIs & Services`***

***+ Step 4: Go to `OAuth consent screen` > Select UserType is `External` and then Create > Write your app information***

***+ Step 5: Go to `OAuth consent screen` > `Publish App`***

***+ Step 6: Go to `Credentials` > `Create Credentials` > `OAuth client ID` > Choose your Apllication Type you want and remember to add `Authorized JavaScript origins` and `Authorized redirect URI` (or update later) > Create and save your `CLient ID` and `Client secret`***

***4. MAIL SERVICE***

GOOGLE_APP_PASSWORD='nbcz umma surb vehn'

GOOGLE_MAIL_HOST='smtp.gmail.com'

GOOGLE_MAIL_USER='example@gmail.com'

GOOGLE_MAIL_FROM='noreply@example.com'

***Steps to get this environment variables:***

***+ Step 1: Go to your google account by link `https://myaccount.google.com/`***

***+ Step 2: Turn on 2-Step Verification: Go to option `Security` > `How you sign in to Google` > `2-Step Verification` > Turn on it***

***+ Step 3: Create a app password by link `https://myaccount.google.com/u/4/apppasswords` > Write you app name > Copy and save your app password***
