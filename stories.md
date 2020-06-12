## story 1.1 greet+search_flights+thanks
* greet
  - utter_greet
* search_flights{"source":"bangalore","destination":"mumbai"}
  - action_find_flights
* thanks
  - utter_welcome
## story 1.2 greet+search_flights+thanks
* greet
  - utter_greet
* search_flights{"source":"lucknow","destination":"delhi"}
  - action_find_flights
* thanks
  - utter_welcome
## story 2.1 greet+search_flights+bye
* greet
  - utter_greet
* search_flights{"source":"bangalore","destination":"mumbai"}
  - action_find_flights
* bye
  - utter_goodbye
## story 2.2 greet+search_flights+bye
* greet
  - utter_greet
* search_flights{"source":"lucknow","destination":"delhi"}
  - action_find_flights
* bye
  - utter_goodbye
## story 3.1 greet+search_flights+thanks+bye
* greet
  - utter_greet
* search_flights{"source":"bangalore","destination":"mumbai"}
  - action_find_flights
* thanks
  - utter_welcome
* bye
  - utter_goodbye
## story 3.2 greet+search_flights+thanks+bye
* greet
  - utter_greet
* search_flights{"source":"lucknow","destination":"delhi"}
  - action_find_flights
* thanks
  - utter_welcome
* bye
  - utter_goodbye
## story 4.1 greet+search_trains+thanks
* greet
  - utter_greet
* search_trains{"source":"bangalore","destination":"mumbai"}
  - action_find_trains
* thanks
  - utter_welcome
## story 4.2 greet+search_trains+thanks
* greet
  - utter_greet
* search_trains{"source":"lucknow","destination":"delhi"}
  - action_find_trains
* thanks
  - utter_welcome
## story 5.1 greet+search_trains+bye
* greet
  - utter_greet
* search_trains{"source":"bangalore","destination":"mumbai"}
  - action_find_trains
* bye
  - utter_goodbye
## story 5.2 greet+search_trains+bye
* greet
  - utter_greet
* search_trains{"source":"lucknow","destination":"delhi"}
  - action_find_trains
* bye
  - utter_goodbye
## story 6.1 greet+search_trains+thanks+bye
* greet
  - utter_greet
* search_trains{"source":"bangalore","destination":"mumbai"}
  - action_find_trains
* thanks
  - utter_welcome
* bye
  - utter_goodbye
## story 6.2 greet+search_trains+thanks+bye
* greet
  - utter_greet
* search_trains{"source":"lucknow","destination":"delhi"}
  - action_find_trains
* thanks
  - utter_welcome
* bye
  - utter_goodbye
## story 7 greet+find_itineraries+thanks
* greet
  - utter_greet
* find_itineraries
  - action_find_itineraries
* thanks
  - utter_welcome
## story 8 greet+find_itineraries+bye
* greet
  - utter_greet
* find_itineraries
  - action_find_itineraries
* bye
  - utter_goodbye
## story 9 greet+find_itineraries+thanks+bye
* greet
  - utter_greet
* find_itineraries
  - action_find_itineraries
* thanks
  - utter_welcome
* bye
  - utter_goodbye
## story 10 greet
* greet
  - utter_greet
## story 11 bye
* bye
  - utter_goodbye
## story 12 thanks
* thanks
  - utter_welcome
## fallback
- utter_unclear
