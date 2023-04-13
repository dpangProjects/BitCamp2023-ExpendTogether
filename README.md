# Inspiration
Banking apps have a feature where you can only keep track of your income and spending. You can only see another person's income or spending if you have someone under your name for your account. If you wanted to see how your family or friends are doing financially it would be difficult to do so since chances are almost everyone will have different banks from each other. This is where our app comes in so that your group of close friends and families can keep track of how everyone is doing financially.

# What it does
User's are able to view, in realtime, income and expenditures of themselves and their close group of friends and/or families. See who is saving the most or spending the most with our app to keep track of your close ones' financial situations.

# How we built it
SwiftUI was used to build our IOS application. SwiftUI brings a pleasing to the eye view of their group's spending habits and income. Firebase was used to store a user's data including expenses and income to provide the user with a realtime view of their data. Plaid API was used to connect a user's bank account so that our app can securely retrieve their bank information to display to a user.

# Challenges we ran into
Plaid gave us a lot of trouble as we were not sure on how to fully connect a user's bank account to our app. It required us to have some kind of server to be a middle man in securely connecting our app to a user's bank. We got the initial connection working, but retrieving data was proven difficult.

SwiftUI with Firebase proved difficult to implement together for realtime data viewing. One thing that was very troubling was how to have our users be able to see live changes in their expenditures and incomes when there was a changed. Despite these challenges we were able to implement most of our realtime data viewing goals.

# Accomplishments that we're proud of
- having users be able to view their expenditures and income in realtime
- a clean UI for the user's experience
- a data base to keep all of the user's data
- some implementation of Plaid API that allows us to connect a user's bank to our app 
# What we learned
- Securely connecting to a user's bank account to get their information is tough but is doable with more time
- Building an IOS in SwiftUI that has a clean UI and has a good user experience
- Using Firebase to present users with realtime data viewing 
# What's next for Expend Together
- Fully implement realtime data viewing for all parts of our app
- Implementing more charts and graphs for our users
- Be able to join more groups and add group members
- Fully connect a user's bank account to our app for better data transactions
