# ELIZA+

ELIZA is a natural language conversation program described by Joseph Weizenbaum in the 1960s. ELIZA simulated conversation by using a 'Mad Libs'-style methodology of pattern matching and substitution. While Weizenbaum's intent was to show through ELIZA how 'the responses of a non-directional psychotherapist in an initial psychiatric interview demonstrate that the communication between man and machine was superficial,' users actually found ELIZA to be very convincing and therapeutic. 

While ELIZA's responses were originally limited to text, advancements in computation now allow us to easily integrate graphics. Similarly, recent advancements in natural language processing can enable sentiment detection of user-responses to create a more holistic chatbot experience.

Here, I build on [elizabot.js by Norbert Landsteiner](http://www.masswerk.at/elizabot/) and [Sentimood by Ethan Arterberry](https://github.com/soops/sentimood), a client-side version of [Sentimental by Roman K Yudin and Kevin M Roth](https://github.com/thinkroth/Sentimental) for AFINN sentiment analysis, to create ELIZA+. ELIZA+ converses with users using pattern matching like Eliza and in addition detects and responds to the sentiment of user-responses by updating an avatar.




