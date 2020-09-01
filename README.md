# NLP_NER

##### Goal

The goal is to find out companies and their symbols in a story text. Once you get the company information, you may want to map it to symbol 

For ex.

Apple Inc. -> AAPL <br>
Google Inc. -> GOOG

In Natural Language Processing (NLP) an Entity Recognition is one of the common problem. The entity is referred to as the part of the text that is interested in. In NLP, NER is a method of extracting the relevant information from a large corpus and classifying those entities into predefined categories such as location, organization, name and so on. Information about lables:

geo = Geographical Entity
org = Organization
per = Person
gpe = Geopolitical Entity
tim = Time indicator
art = Artifact
eve = Event
nat = Natural Phenomenon

After aextracting the company name by finding organization entity using NER, we map it to their symbol and then find the security and securties and dump the results into a json format.

Input:
Apple , Amazon and Microsoft are reporting earnings after market close on April 30th .

Output:
security: ['AAPL'] <br>
securities:  ['AAPL', 'AMZN', 'MSFT']
