# NLP Test

Practical Test data understanding:
Chats will be shared in a single text document. Each chat will have its unique identification ‘_id’ it is also the ‘session id’ of chat, name of the file itself contain chat id. Key with value ‘Customer’ provide Customer chats and value ‘Agent’, ‘Agent-Freehand’ provide Agent chats in messages. Candidate need to create below mentioned output from those chat conversation text files.

Practical test:
1.	Sentiment Analysis:
Capture the sentiment for entire chat and display against each ‘session id’

2.	Entity Extraction:
Extract the entities in entire chat and display against each ‘session id’

3.	Word Cloud:
Create word cloud by excluding stop words, include 1 gram and 2 grams and ignore terms appear more that 50% time in entire bag of words. Display word cloud using matplotlib or any suitable visualization library.

4.	Build category using phrase:
    Basis on detection of below phrases need to display against each session id that whether category found in chat transcript.
Category: Acknowledgement 
(Key phrase to be detected)

    I know what you're saying; sorry about that; I understand; I do apologize for that; yeah I know I understand; I apologize for the wait;
    I am so sorry about that; I'm certainly sorry to hear that you; I'm sorry I'm talking myself for a second; I understand completely that;
    well I apologize for the inconvenience; that's alright I understand; you're quite welcome; I completely understand; 
    I understand your concern; I'm glad to pass that; I'm sorry you're disappointed and that you won't be needing that product;
    I'm sorry about the long hold;  this is something we definitely need to know; that's not the experience we want you to have;
    understandable how upsetting; it's frustrating when; thank you for bringing that to our attention; I understand where you're coming from;
    
Please use pctest branch while pushing your code and raise merge request.
