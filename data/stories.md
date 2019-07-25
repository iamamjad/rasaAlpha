## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## createEnvironmentDialog
* createEnvironment
  - utter_createEnvironment
  
## changeColorDialog
*  changeColor
  - utter_changeColor
  
## changeTimeDialog
*  changeTime
  - utter_changeTime
  
## changeWeatherDialog
*  changeWeather
  - utter_changeWeather
  
## gameOperationDialog
*  gameOperation
  - utter_gameOperation
  

## New Story

* greet
    - utter_greet
