# Aakash_M__bankbot
Introduction  
The Bank Bot AI project is a banking assistant chatbot 
developed using Python and the Streamlit framework. 
The purpose of this project is to create a simple banking 
support system where users can register, log in, and ask 
banking-related questions. The chatbot provides 
responses related to banking topics such as savings 
accounts, loans, ATM services, and digital banking.  
The project also stores user information and chat history 
using JSON-based storage, which acts as a lightweight 
database. The main goal of the project was to 
understand how artificial intelligence chat systems can 
be integrated with web applications.  
Problems Faced During Development  
The model not responding properly.  
• Slow response time when generating answers.  
• Connection errors when the Ollama server was not 
running.  
• Incorrect responses for unrelated queries.  
Solution  
To solve this problem, a banking FAQ JSON system was 
implemented. Instead of relying completely on the AI model, 
the chatbot now checks predefined banking questions and 
answers stored inside the code.  
If the question is related to banking, the chatbot provides the 
stored answer.  
If the question is unrelated, the system returns:  
"Only banking related questions are supported."  
This improved the reliability and accuracy of the chatbot.  
User Authentication Problems  
1. User accounts disappearing after      refreshing  the age.  
2. No permanent storage for registered users.  
3. Multiple login errors when the session   
JSON Data Structure Errors  
Key Error: 'users'  
This happened because the JSON file structure did not contain 
the correct keys when loading data.  
 
 
Through this project, several important concepts were 
learned:  
1. Web Application Development  
Using Streamlit helped in understanding how to create 
interactive web applications using Python.  
2. JSON Data Storage  
The project demonstrated how JSON files can be used as a 
simple database for small applications.  
3. Authentication Systems  
Implementing login and registration systems helped in 
understanding user authentication.  
4. Cybersecurity Basics  
Password hashing introduced the importance of securing 
sensitive data. 5. Chatbot Logic  
The project showed how rule-based chatbot systems work 
and how they can be integrated with web applications.  
Conclusion  
The BankBot AI project successfully demonstrates the 
development of a simple banking chatbot with user 
authentication and JSON-based storage. Despite several 
challenges during development, solutions were implemented 
to improve the functionality and reliability of the system.  
The project helped in gaining practical experience in Python 
programming, chatbot design, authentication systems, and 
data management. In the future, this project can be 
improved by integrating more advanced AI models, adding 
database systems such as SQLite or MySQL, and expanding 
the chatbot’s banking knowledge base.  
If you want, I can also give you a much better 3-page report 
with these sections (teachers love this format):  
• Abstract  
• Introduction  
• System Architecture  
• Problems Faced  
• Solutions Implemented  
• Future Improvements  
• Conclusion  
That version looks more like a real engineering project 
report. 
