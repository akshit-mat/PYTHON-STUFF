# ROCK PAPER SCISSORS GAME 🤜🧻✂
This game pretty much was just me messing around with the random module

## 🎮 I made two versions of this game:
### - Player vs Environment 🕹
this is a very basic python's random module based game

### - Player vs Environment (but with scoreboard) 🎯
this is one of the more refined games i've made where it records the score in MySQL using pymysql 

(this was kinda my 12th grade project... idk how they allowed me to do a game as a project lol)

## 🔧 Requirements and Libraries used
### - for PvE
- python>=3.10
- No external libraries are required for random module

### - for PvE with scoreboard
- python>=3.10
- MySQL>=8.0.31
- pip install pymysql
- No external library for random module

 NOTE: This is kind of an embarrassing incomplete part of this project... you need to pre-requisitely make a database in MySQL named "rps_scoreboard" with coloumns name (char), w (int), l (int), d (int) and total (int)
