## story 1.1 greet+search_flights+thanks 

* greet
    — utter_greet
* search_flights{'source':'bangalore','destination':'mumbai'} 
  — action_find_flights
* thanks
   — utter_welcome
   
## story 1.2 greet+search_flights+thanks 
* greet 
  — utter_greet
* search_flights{'source':'lucknow','destination':'delhi'}
  — action_find_flights
* thanks
  — utter_welcome
  
## story 2.1 greet+search_flights+bye
* greet
  — utter_greet
* search_flights{'source':'bangalore','destination':'mumbai'}
   — action_find_flights
* bye
   — utter_goodbye
   
## story 2.2 greet+search_flights+bye
* greet
  — utter_greet
* search_flights{'source.\':'lucknow','destination':'delhi'}
  — action_find_flights 
* bye
   — utter_goodbye

## story 3.1 greet+search_flights+thanks+bye 
* greet
  — utter_greet 
* search_flights{'source':'bangalore','destination':'mumbai'}
  — action_find_flights
* thanks
   — utter_welcome
* bye
  — utter_goodbye 
