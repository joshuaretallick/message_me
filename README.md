# MessageMe Chat app

For this app I wanted to expand on my knowledge of Rails but with a single page app and exploring new features.

I created this app following usual Rails protocol, opting for BCrypt for authentication and instead of Bootstrap, I decided to try a new CSS framework in Semantic UI.  I found there were a lot of similarities between the two, with Semantic giving me a cleaner look but I did feel Bootstrap was more intuitive. 
To make the chat app feature work in real-time without page refresh, I used an inbuilt Rails method called ActionCable which allows for full duplex communication.  I have used other similar ones before (ie PubNub) but this was much more straight forward, with the only tricky thing being adding some JavaScript and CoffeeScript so the user can operate this properly from their browser.

![Screen Recording 2021-03-10 at 17 16 08 2021-03-10 17_39_48](https://user-images.githubusercontent.com/71830424/110672642-c47e0400-81c7-11eb-852c-062ba998efb9.gif)

## View my app on Heroku
[CLICK HERE](https://shrouded-spire-09874.herokuapp.com/)
```sh
To operate, open on two different computers or use a second window in Incognito Mode
Example credentials:
Username: Franklin | Password: password
Username: Hannah | Password: password
```

## Installation Instructions
- Clone Repo to your local machine
- From Command Line enter directory and then run:
```sh
bundle install
yarn
bundle exec rails db:migrate
bundle exec rails server
```
- Then open `http://localhost:3000` in your browser

## Tech-Stack 
```
Ruby-on-Rails
CoffeeScript
JavaScript
Semantic UI
JQuery
Popper
BCrypt
ActionCable
```
