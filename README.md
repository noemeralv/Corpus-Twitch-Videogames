# Corpus-Twitch-Videogames

The Excel of this repository corresponds to a corpus of chats extracted from video game content streamed on Twitch. This dataset has 2,216 samples (Twitch chat messages) and consists of three variables: Text, Polarity and Emotions, which are described as follows:

1. Text: Text: a variable that represents the input feature. These are the raw comments from Twitch users reacting to the stream. This variable will require additional processing to analyse it.
2. Polarity: is one of the target variables that can take three values depending on the polarity of the message, Positive (P), Negative (N), Indeterminate (NEU).
3. Emotion: : is one of the target variables that can take six values depending on the emotion of the message: Approval (Approval/Empathy/Confidence), Sadness (Disappointment/Sadness), Disapproval, Anger,  Hype (Interest/Acceptance/Hype), Undetermined.

Our corpus includes chats from different Twitch streams, selected based on specific criteria:

1. Channels in Spanish. We ruled out bilingual streamers, whose chats could alternate between English and Spanish. Even so, we are aware of the high proportion of English terms registered in Twitch chats, both because it is a digital network used mainly by young people and because it contains a specialised lexicon in video games.
2. Channels whose main content is video games. All downloaded chats belong to Twitch broadcasts in which the streamer was playing a video game or commenting on a video game event. The reason is that one of the objectives of our project is to study the type of messages produced in a semi-specialised field of communication, such as the world of video games. This area also represents the most characteristic content of the Twitch platform, so studying it reveals, at the same time, defining features of this platform. We have gathered chats corresponding to very different types of video games: World of Warcraft, League of Legends, Fortnite, Apex Legends, Diablo 4, Red Dead Redemption 2, Dark Souls and Heroes of the Storm.
3. Channels with a viewer limit of no more than 1,000 people. Recent literature has established that in chats with a higher number of participants, communication or interaction becomes almost impossible among those participating in the chat: the rate of incoming messages causes the so-called ‘scroll factor’ (Yus, 2020), and it tends to become what Hamilton, Garretson and Kerne (2014) have described as ‘an illegible waterfall of text’.
4. Channels in which the streamer has a webcam. Preference is given to these streams because engagement is usually higher on channels where the streamer shows their face via a webcam integrated into the live broadcast (Jodén & Strandell, 2021). 

TAs per the Twitch Terms of Service (Twitch, 2020), users need to verify their age before accessing the platform. Individuals below the age of 13 are not allowed to use Twitch. However, it is virtually impossible to confirm the age, gender, origin or profile of each user, as registration on the platform is free and does not require any personal data. Following the guidelines provided by the Association of Internet Researchers (2019), we can consider that the streams and messages from the viewers in the chat should be treated as public places. However, to maintain the highest level of anonymity and comply with those guidelines, we have anonymized the usernames of all participants in the chats included in our corpus. We also filtered out messages from Twitch bots (Streamlabs and Nightbot), @ mentions, and URLs (This process will be explained in detail in the section on data processing). These previous considerations enable us to incorporate ethical and privacy principles into the process of creating our corpus. This will permit us to guarantee that the collection and use of data is done in a fair manner, respecting privacy, avoiding bias and discrimination, and ensuring transparency in the process.

# Corpus-Twitch-Videogames

This development belongs to the project "Application of Artificial Intelligence in the analysis of Video game content on Twitch". As project leaders, the main contact of the team is Noemí Merayo and Rosalía Cotelo, whose e-mail address are as follows:

noemer@uva.es
rosalia.cotelo@uam.es


