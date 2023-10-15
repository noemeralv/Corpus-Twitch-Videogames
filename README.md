# Corpus-Twitch-Videogames

This dataset has 2216 samples (Twitch messages) and consists of three variables, Text, Polarity and Emotions, which are described as follows:

1. Text: is an independent variable, representing the input feature. These are the raw comments from Twitch users reacting to the stream. This variable will require additional processing in order to analyse it, and details on this processing will be provided later in this article.
2. Polarity: is one of the target variables that can take three values depending on the polarity of the message, Positive (P ), Negative (N ), Indeterminate(N EU ).
3. Emotion: is one of the target variables that can take six values depending on the emotion of the message, Approval/Empathy/Confidence, Disappointment/Sadness, Disapproval, Anger/Ira, Interest/Acceptance/ Hype, Undetermine

Our corpus includes chats from different Twitch streams, selected based on specific criteria:

1. Channels in Spanish. We ruled out bilingual streamers, whose chats could alternate between English and Spanish. Even so, we are aware of the high proportion of English terms registered in Twitch chats, both because it is a digital network used mainly by young people and because it contains a specialised lexicon in video games.
2. Channels whose main content is video games. All downloaded chats belong to Twitch broadcasts in which the streamer was playing a video game or commenting on a video game event. The reason is that one of the objectives of our project is to study the type of messages produced in a semi-specialised field of communication, such as the world of video games. This area also represents the most characteristic content of the Twitch platform, so studying it reveals, at the same time, defining features of this platform. We have gathered chats corresponding to very different types of video games: World of Warcraft, League of Legends, Fortnite, Apex Legends, Diablo, Red Dead Redemption, Dark Souls and Heroes of the Storm.
3. Channels with a viewer limit of no more than 1000 people. Recent literature has established that in chats with a higher number of participants, communication or interaction becomes almost impossible among those participating in the chat: the rate of incoming messages causes the so-called ‘scroll factor’ (Yus, 2020), and it tends to become what Hamilton, Garretson and Kerne (2014) have described as ‘an illegible waterfall of text’.
4. Channels in which the streamer has a webcam. Preference is given to these streams because engagement is usually higher on channels where the streamer shows their face via a webcam integrated into the live broadcast (Jodén & Strandell, 2021). 

To protect privacy, we anonymised all chat messages. We also filtered out messages from Twitch bots (Streamlabs and Nightbot), @ mentions, and URLs. 
Additionally, we removed messages that only consisted of emotes without any accompanying text. However, messages composed only of emotes were kept if those emotes were of general and frequent use on Twitch (https://www.twitchdatabase.com/global-emotes) and if they were univocal emotes in terms of polarity and emotion.

# Corpus-Twitch-Videogames

This development belongs to the project "Application of Artificial Intelligence in the analysis of Video game content on Twitch". As project leaders, the main contact of the team is Noemí Merayo and Rosalía Cotelo, whose e-mail address are as follows:

noemer@uva.es
rosalia.cotelo@uam.es


