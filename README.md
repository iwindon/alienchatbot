
# Alien ChatBot

This is a chatbot project from Codecademy.  This is my solution to this project in the Rule-Based Chatbot section.  I had to make a few changes to the code from what they suggested as it would not work properly by following their instructions.  I made comments where appropriate on those changes.


## Features

- the regex and random libraries are imported
- a tuple of negative responses (you can add more!)
- a tuple of commands for a user to exit the program
- a tuple of random starter questions an alien might ask (feel free to add more)
- a tuple of dictionaries called alienbabble with the chatbot’s main intent-utterance matching pairs — you’ll add to this later!
- several methods for core chatbot functionality:
- .greet() will greet the user
- .make_exit() will check if a user has used an exit command
- .chat() will run the program allowing users to chat with the alien you created
- .match_reply() will match the response pairs in alienbabble for you several methods associated with user intents
- .describe_planet_intent() will include responses about the alien’s planet
- .answer_why_intent() will include responses for why the alien is visiting
- .cubed_intent() is a method that returns the cube of a number, because these aliens are very good at math
- .no_match_intent() will respond with something general when none of the other intents are matched

