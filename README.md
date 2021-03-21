# djangoapi
This project was built using Django (squlite), HTML, and Bootstrap

# Stock Portfolio
This is a a Stock Portfolio app that allows user to add and delete stock symbols.  Current stock information is pulled into the Portfolio table with the iexcloud.io API website. 

# Stock Portfolio Home Page
This is the landing page for the app.  Users are able to search for stock tickers and pull in current Stock data.

# Add Stock Page
Users are able to add stocks to their portflio table for tracking current stock data and trends. 

# Delete Stock Page
Users are able to delete stocks from their portfolio if they wish. 

# Logout Page
Once the user logs out there is a message thanking them for using the app and in the menu there is a link to return them to the Login Page.

Task App System Tech Stack Selection:
Version Control Sys: Github

Frontend: HTML/Bootstrap,  IDE VS Code
Business Logic: Typescript
WebServer Imp: Django
Data Layer: Sqlite
Web Server Cloud Dep: TBD (I have used Heroku)
Web App Cloud D: TBD (I have used Netlify)

# Important info for running project
Project runs in your python venv.  Here are steps (windows):
1. cd into stock directory of project
2. run python -m venv venv
3. run source venv/Scripts/activate
4. run python manage.py runserver to run project on localhost:8000, Command C to turn off
5. run deactivate to turn off.

