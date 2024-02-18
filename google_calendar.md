# Create Google Calendar Configuration
1. Login into [Google Console](https://console.cloud.google.com/)
2. Create a new service account by going hamburger button > IAM & Admin > Service Accounts > Create a new service account > Bring Owner rol > Create > select json ---> a new json file will be downloaded, this is very important 
3. Go to Hamgurger button > APIs & Services > Search for Google Calendar > Enable Google Calendar
4. Go to Google Calendar and create a new Calendar
5. Click on the 3 dots right to the created calendar (manage settings)
6. Share with people and copy the service account mail from the json key(client_email key), send invitation with make changes permission
7. Copy the calendar Id (from calendar settings), and paste it into glitch .env
8. Paste service account as a single line in glitch .env
