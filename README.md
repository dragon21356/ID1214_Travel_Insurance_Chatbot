# ID1214_Travel_Insurance_Chatbot

Hello there and welcome to the Travel Insurance Chatbot! This AI-powered tool helps users compare between travel insurance policies quickly and easily. Follow this guide to set up and use the chatbot on your local system!

Some key things to note:

1. System Requirements

Python: Version 3.8 or higher

Required Libraries:
pandas
numpy
faiss
sentence-transformers
transformers
torch

Hardware:
Minimum: 4GB RAM
Recommended: GPU for faster performance (optional)

Now to get started with installation:

2. Setup Instructions

Install Python:
Ensure Python 3.8 or higher is installed on your system. Download it from python.org.

Install Required Libraries:
Open a terminal or command prompt in the folder containing the chatbot file.
Run the following command to install the required libraries:
pip install pandas numpy faiss sentence-transformers transformers torch

Prepare the Data File:
Ensure you have a .csv file containing travel insurance data. We have included a sample file that we populated using real-data
that was gathered from existing insurance plans.

The file must include these columns:
Insurance Provider
Plan Name
Premium Price (S$)
Overseas Medical Expenses (S$)
Trip Cancellation (S$)

Now to run the chatbot:

3. Running the Chatbot

Start the Chatbot:
Place the .csv file and the Python script in the same folder.
Open a terminal or command prompt in that folder.
Run the chatbot using the command "python chatbot.py" or simply run from within your respective IDE

Upload the Data File:
When prompted, upload the .csv file containing the travel insurance data that we have provided or your own one that has been formatted
specifically.

Ask Questions:
Type your query into the console. 

Examples of queries include:
a. Tell me about FWD travel insurance plans  
b. Compare trip cancellation coverage across providers
c. What are the best plans to take for a family trip 
d. Compare AXA and AIA travel insurance plans
e. What are the cheapest travel insurance options

Try it out for yourself!

View Results:
The chatbot will analyze your query and provide a detailed response.

In case you stumble into some errors, here are a couple troubleshooting steps:

4. Troubleshooting

a. The chatbot doesn't start.
Ensure Python and the required libraries are installed.
Check for syntax errors if the script was modified.

b. Response is inaccurate.
Verify that the .csv file contains complete and correctly formatted data.

c. Slow response times.
If available, use a machine with a GPU to improve performance or run it on a cloud interface.

Some answers to questions that you may have

5. FAQ

Can I update the data?
Yes! Simply add your updated values and replace the .csv file. Then restart the chatbot and follow the steps from earlier.

What happens if my query isn’t understood?
This may occur due to T5's limited usability but if it does, the chatbot will prompt you to clarify your question.

Is my data secure?
The chatbot does not permanently store any user data or queries and is run completely locally with an option to share a secure link
to any of your trusted friends, therefore guaranteeing security

6. Additional Notes

a. Ensure the column names in the .csv file match the expected format exactly.

b. The chatbot is designed for single-user sessions. Restart the script to reset the chatbot.


Thank you for joining us on this adventure! Take care and we hope this helps you make better decisions :)
