# AI-Chatbot-in-Java
A simple rule-based AI chatbot built in Java that uses a knowledge base to answer questions, applies intent recognition for responses, and keeps a conversation log.


Features


Rule-based Intent Recognition: Matches user input with predefined intents (e.g., "hi", "how are you").

Knowledge Base: Stores common questions and responses using a HashMap.

Conversation Logging: Keeps a record of all user-bot interactions in memory and prints them at the end.

Exit Command: Type exit anytime to stop the chatbot.

Project Structure


How to Run


Save the file as AIChatbot.java.

Open the terminal or command prompt in the project folder.

Compile the code:

javac AIChatbot.java 4.Run the code java AIChatbot

Sample interaction


Hello! I am a simple AI Chatbot. Type 'exit' to quit.

You: hi

Bot: Hello! How can I help you?

You: how are you

Bot: I'm doing great, thanks for asking!


You: bye

Bot: Goodbye! Have a nice day.


Conversation Log:


User: hi

Bot: Hello! How can I help you?

User: how are you

Bot: I'm doing great, thanks for asking!

User: bye

Bot: Goodbye! Have a nice day.


Concepts Used


Java Collections (HashMap, ArrayList)

Rule-based NLP basics (keyword matching)

Console I/O (Scanner)

Logging mechanism (conversation history)

Future Enhancements


Add keyword detection, not just exact matches.

Save conversation logs to a text file.

Integrate with OpenAI API for smarter responses.

Add GUI support, either JavaFX or Swing.

Author


Developed as a simple Java project to demonstrate basic AI chatbot functionality.
