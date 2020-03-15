## hangout1 
* greet
  - action_greeting
* inform
  - utter_inform
* proposition
  - utter_deny


## hangout2
* inform
  - utter_affirm


## hangout3
* inform
* proposition 
  - utter_deny 
* chedd_shih 
  - utter_affirm

## interactive_story_0
* greet
    - action_greeting
* proposition{"location": "9ahwa"}
    - utter_deny
* chedd_shih 
    - utter_affirm

## hangout4 
* greet 
    - action_greeting 
* proposition 
    - ask_form 
    - form{"name":"ask_form"}
    - slot{"interlocutor":"ahmed"}
    - utter_ask_location
    - slot{"location":"tunis"}
    - utter_ask_activity
    - slot{"activity":"basket"}
    - utter_ask_time
    - slot{"time":"15h"}
    - form{"name":"null"}
    - utter_submit
* goodbye
    - utter_goodbye
    - action_chat_restart

## hangout5
* greet 
    - action_greeting 
* proposition 
    - ask_form 
    - form{"name":"ask_form"}
    - utter_ask_location
    - slot{"location":"rades"}
    - utter_ask_activity
    - slot{"activity":"9ahwa"}
    - utter_ask_time
    - slot{"time":"20h"}
    - form{"name":"null"}
    - utter_submit
* chedd_shih
    - utter_affirm
* goodbye
    - utter_goodbye
    - action_chat_restart


## interactive_stor
* greet
    - action_greeting
* proposition{"location": "9ahwa"}
    - slot{"location": "9ahwa"}
    - utter_deny
* chedd_shih{"time": "19h"}
    - slot{"time": "19h"}
    - action_affirm
* inform
    - action_affirm
* ask_location

## interactive_stdory_2
* greet
    - action_greeting
* proposition{"location": "stade"}
    - slot{"location": "stade"}
    - utter_deny
* goodbye
    - utter_goodbye
    - action_chat_restart

## interactive_stfory_4
* greet
    - action_greeting
* proposition{"location": "stade"}
    - slot{"location": "stade"}
    - utter_ask_time
* affirm
    - utter_goodbye
* affirm

## interactive_story_3
* greet
    - action_greeting
* proposition 
    - utter_affirm

## interactive_story_1
* greet{"interlocutor": "amine"}
    - slot{"interlocutor": "amine"}
    - action_greeting
* proposition{"movie": "troy"}
    - ask_form
    - form{"name": "ask_form"}
    - slot{"interlocutor": "amine"}
    - slot{"requested_slot": "location"}
    - form{"name":"null"}
* form: affirm
    - utter_goodbye
    - action_chat_restart
    

## interactive_story_1_happy
* greet
    - action_greeting
* mood_great{"positive_word": "happy"}
    - slot{"positive_word": "happy"}
    - utter_happy
* goodbye
    - utter_goodbye
    - action_chat_restart

## interactive_story_1_sad
* greet
    - action_greeting
* mood_unhappy{"negative_word": "sad"}
    - slot{"negative_word": "sad"}
    - utter_why
* mood_unhappy{"negative_word": "fadit"}
    - slot{"negative_word": "fadit"}
    - action_consolation
* goodbye
    - utter_goodbye
    - action_chat_restart

## interactive_storysad2
* greet
    - action_greeting
* mood_unhappy{"negative_word": "sad"}
    - slot{"negative_word": "sad"}
    - utter_why
* mood_unhappy{"negative_word": "fadit"}
    - slot{"negative_word": "fadit"}
    - action_consolation
* proposition{"activity": "kahwa"}
    - slot{"activity": "kahwa"}
    - utter_deny
* chedd_shih
    - utter_affirm
* goodbye
    - utter_goodbye
    - action_chat_restart

## interactive_story_1
* greet
    - action_greeting
* mood_great{"positive_word": "happy"}
    - slot{"positive_word": "happy"}
    - utter_happy
* proposition{"location": "stade"}
    - slot{"location": "stade"}
    - utter_affirm
* goodbye
    - utter_goodbye
    - action_chat_restart

## interactive_story_1
* greet
    - action_greeting
* mood_great{"positive_word": "happy"}
    - slot{"positive_word": "happy"}
    - utter_happy
* proposition{"location": "stade"}
    - slot{"location": "stade"}
    - utter_ask_time
* goodbye
    - utter_goodbye
    - action_chat_restart


## interactive_story_1
* greet
    - action_greeting
* mood_great{"positive_word": "happy"}
    - slot{"positive_word": "happy"}
    - utter_happy
* proposition{"location": "stade"}
    - slot{"location": "stade"}
    - utter_ask_time
* goodbye
    - utter_goodbye
    - action_chat_restart

## interactive_story_1_sad
* greet
    - action_greeting
* mood_unhappy{"negative_word": "sad"}
    - slot{"negative_word": "sad"}
    - utter_why
* mood_unhappy{"negative_word": "fadit"}
    - slot{"negative_word": "fadit"}
    - action_consolation
* thank
    - utter_thank
* goodbye
    - utter_goodbye
    - action_chat_restart


