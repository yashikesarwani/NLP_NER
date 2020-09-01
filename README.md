# NLP_NER

##### Goal

The goal is to find out companies and their symbols in a story text. Once you get the company information, you may want to map it to symbol<br> 
For ex.
Apple Inc. -> AAPL <br>
Google Inc. -> GOOG

<br>
<b>In Natural Language Processing (NLP), Named Entity Recognition (NER) is one of the common problems. The entity is referred to as the part of the text that one is interested in. In NLP, NER is a method of extracting the relevant information from a large corpus and classifying those entities into predefined categories such as location, organization, name and so on.</b><br> 
Information about labels:<br>

geo = Geographical Entity<br>
org = Organization<br>
per = Person<br>
gpe = Geopolitical Entity<br>
tim = Time indicator<br>
art = Artifact<br>
eve = Event<br>
nat = Natural Phenomenon<br>

<br>
After extracting the company name by finding organization entity using NER, we map it to their symbol and then find the security and securties and dump the results into a json format.<br>

Input:<br>
Apple , Amazon and Microsoft are reporting earnings after market close on April 30th .<br>

Output:<br>
security: ['AAPL'] <br>
securities:  ['AAPL', 'AMZN', 'MSFT']
