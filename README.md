# Blackjack

Welcome to this simplified version of BlackJack! It's a universally known card game in which you will be using a deck of 52 cards to compete the dealer. You and dealer(robot) will each get an initial hand of two cards to start. The J Q K will each acount for 10 points and A will be regarded as 11 (not 1 for this simplified version). You can choose either to hit one card (get one from the deck) or stand with what you have in hands. Winner is the one with higher total points but not exceeding 21, which it will bust and lose. You will need to have an account to enjoy this game. 

## Our team member(Github username)

YaochenS 

Burushuijiaoba

RichardChiqui 

MichaelEJT

ricop14

## Planing

[see here](/docs/Planning.pdf)

## Login

You will be prompted to index page (also our login page). If you already have registered before you can sign in or change the username/password or even delete your account(Please no), otherwise you can have your account(Exciting!) using the signup button. After logging in, you will be prompted to the gameplay page. 

## Database

The name of our database is users.db and due to the nature of our game, we only have one table "accountInfo" recording all the required user informations.

It has five attributes except for the auto-increasing primary key. They are username, password, emailAddress, lastLogin, numOfGames. Most of them pretty self explain their meanings. lastLogin stands for the last time this player enter the game and numOfGames simply stands for the number of games he or she has played in total.

## How to run

[See User Instrcutions](https://github.com/MichaelEJT/blackjack_simulator/blob/main/user_instructions.pdf)

## Video Clips

[Youtube link](https://youtu.be/oIggSdOKtkc)


## Dependency List
* better-sqlite3
* browser-sync
* concurrently
* express

## API Endpoints
[See here](/docs/endpoints.md)
We have used a lot of endpoints to do logic work such as storing or changing user informations. We have also used endpoints to realize functions such as sendFile or redirect.
* Login
* Signup
* Personal Information
* User Entered Wrong Login
* User Info Already Exists
* Game
