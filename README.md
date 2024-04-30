# ELAN Transcription Workshop
## Workshop Plan
1. [Background to documentary linguistics](#background-to-documentary-linguistics)
   1. [Goals](#Goals)
   2. [Methodological overview](#methodological-overview)
2. [Overview of practical section](#overview-of-practical-session)
3. [Recording](#recording)
4. [ELAN Setup](#elan)
   1. [Installing ELAN](#installing-elan)
   2. [Importing, creating a project](#importing-creating-a-project)
   3. [Synchronisation](#synchronisation)
   4. [Segmentation](#synchronisation)
5. [Finally, transcription](#finally-transcription)
   1. [Goals of transcription](#synchronisation)
   2. [How to transcribe language in ELAN](#how-to-transcribe-language-in-elan)
6. [Where to from here](#where-to-from-here)
   

## Background to documentary linguistics
### Goals
What is the purpose of documentary linguistics? Why do we want to document language at all, and why do we care so much about indigenous or minority languages throughout the world? There are many answers to these questions. A better understanding of how language works, and how specific languages work, allows us to create technologies to support them, such as predictive text in our phones or automated translators such as Google Translate. Perhaps more importantly, language documentation can help support the preservation of endangered languages. We can create records of languages, teaching materials, story books, dictionaries, and many more things that can help a community keep their own language alive.


### Methodological overview
The core methodology of documentary or descriptive linguistics involves recording a language in use, and then making it accessible for analysis. These recordings also act as a record or archive of the language for the future, which is especially important when a language is endangered and at risk of dying out. A main way of preparing recordings for archival and analysis is transcription. In most cases, transcribing a single sentence or two is not a challenge. However, in order to properly document a language, linguists need hours of recordings, with or without video, and they need to be able to easily refer back to specific pieces of audio and transcription.

To do this, we often use a piece of software called [ELAN](https://archive.mpi.nl/tla/elan), developed and maintained by the Max Planck Institute for Psycholinguistics in Nijmegen, Netherlands. It allows us to attach annotations, transcriptions, and translations to synchronised audio and video, and gives us a more straightforward way of sharing these data with archives or other linguists.

## Overview of practical session
The practical component of this workshop will be divided into two parts:
- Recording
- ELAN

The recording part will cover the practise of recording linguistic data in the field, including the technical aspects of digital audio, as well as best practises in sorting and maintaining useable and useful data.
The second part will introduce the software [ELAN](https://archive.mpi.nl/tla/elan), used for annotating and transcribing recorded data. It will cover the installation and setup of ELAN, the initial processing of data in ELAN, and ultimately the practical transcription of recorded data for analysis.

> Throughout this workshop, we will be recording, preparing, and transcribing our own short linguistic activity. This activity will be described in boxes such as this one.
## Recording
### Recording practise
The greatest challenge in recording linguistic data is the fact that you only get one chance. Particularly when recording natural conversation, a bad or failed recording cannot readily be recovered or remade without expecting more time of speakers than is necessary. Given this, it is important to go into recording with intention, and with an awareness of how, where, and why these recordings will be used. This can then inform how you go about recording speakers.

For instance, if you are particularly interested in understanding how a language uses concepts like "up" and "down", you might want to record video in addition to audio so you can see where people are pointing. 

What and where you are recording also needs to inform how you record speakers. If you are recording somewhere with a lot of background noise, you might want to place microphones closer to speakers, or use "lav" mics. If you are recording a larger group of people, you will need to make sure you can clearly determine who is talking, whether through video or individual microphones for each speaker.

Lastly, but perhaps most importantly, is consent. It is important to make sure people are comfortable being recorded or filmed. Perhaps you had planned on recording someone in audio and video, but they do not want to be on video. Here, you should find an alternative method to make sure that you are still able to capture anything you need, or find something else to record instead.

> For the purposes of this workshop, we are going to undertake a linguistic elicitation activity used to document how speakers of a language describes the locations of objects in relation to each other. The [Man and Tree](https://archive.mpi.nl/islandora/object/lat%3A1839_da98dab1_75df_452a_8575_6b44137801e6) picture sets are run here as a guessing game between two people. In this activity, one person picks up a picture card at random and describes it. They are the describer. The other person, the guesser, looks at every card and guesses which card the describer is looking at from their description. They can ask follow up questions, but they cannot look at the describer's card. The specific pictures used in the workshop can also be found in the [Man and Tree pictures](/Man%20and%20Tree%20Pictures/) folder above.

> Given what was discussed above, how do we want to go about recording this activity? We will have two speakers, so we will need a way of differentiating them later on. Also, we want to document how people describe specific images, so we need to know which image they are talking about. For these reasons, it would be ideal to record it with audio *and* video.

If we are recording with both audio and video, we need a way of synchronising the two recording later. Sometimes, this can be done automatically if the camera and microphone are attached. Often, we need to do it manually. How to do this will be explained below, but in order to make it as easy as possible for ourselves, we can make a visual and audio reference point by clapping in front of the camera. This achieves the same result as clappers seen in film production.

### Audio quality

Another consideration depending on what we are recording and what we want to use it for is the quality of the audio. If we are trying to closely study the sounds of a language (phonetics), we will generally need higher quality audio recordings than if we are studying a language's grammar, where we only need to be able to tell what people are saying. That being said, we can maximise our efficiency with recording if we can produce a recording that can be used for both of these. As such, we always want to strive for optimal audio quality as much as possible.

Some factors in audio quality are largely beyond our control in the moment. A separate microphone will produce a better recording than a mobile phone, and a better (more expensive) microphone will often produce a better recording again. Often though, a mobile phone is all that's available, so we would need to make do. There are some factors, however, which we can change. For instance, if we are trying to make high quality recordings of the sounds of a language, we can improve the audio quality by recording indoors in a quiet place, away from other people and background noise which might bleed through into the recording. If recording outside, make sure that there is minimal wind hitting the microphone, or use a wind filter to minimise its effect on the audio. If other background noise is unavoidable, placing the microphone closer to the person being recorded can help.

Any microphone will have a maximum volume level it can record before the audio begins to distort. This is called "clipping" or "peaking". When this happens, the microphone is no longer accurately recording the sound as it was produced. While this recordings with clipping might still be useable for some areas, the close study of phonetics mentioned above requires a true representation of the sound. Many audio recorders will have a measurement of the volume of the sound they are recording visible, and will give a warning when clipping. It is worth double checking audio to make sure it is not too loud. If it is, the volume can be reduced in future recordings by a) putting the microphone further away, b) speaking more quietly, c) many more specialised recorders will have a "gain" knob that can increase or reduce the volume of the audio being recorded. Audio with clipping cannot be fixed after it has been recorded.

### File management

When working with a lot of recordings, it is important to have a system of file management so that you can find things quickly and easily. 

## ELAN Setup

### Installing ELAN
ELAN can be downloaded and installed from the [MPI website](https://archive.mpi.nl/tla/elan).

### Importing, creating a project
The [ELAN Templates](/ELAN%20Templates/) folder above contains a series of templates for use when creating ELAN projects. These templates are already set up for various types of recording, and will save us some work. They vary in two ways: the number of speakers, and the number of things being transcribed. Most important are the "text" and "free translation" tiers. "Text" refers to the actual content of the recording in the language, while "free translation" refers to a translation of the recording into the language in which the research is being conducted. These will be discussed in more detail later.

When we open ELAN and select File > New... we are able to attach the files we will need in two groups, media and template. Media is everything we have recorded, including audio and video. Template is the template file discussed above.

> Select File > New... and use the file navigator on the left side to find your recordings. Make sure you have the Media button selected, and then add them to your project by clicking them on the left and clicking the >> button. Next, select Template, and do the same thing for your template. Navigate to the ELAN Templates folder and select Template 2, as we will have two speakers and only need Text and Free Translation tiers. Finally, press OK.

### Synchronisation

When we made our recordings, we recorded our audio and video separately, but with a clap to enable us to easily synchronise them later. We can do this synchronisation easily inside ELAN's Media Synchronisation Mode. Here, each media file attached to the project will be given a separate player which can be aligned to the reference point (clap) we made in our recording earlier.

> Select Options > Media Synchronisation Mode. Select each piece of media one by one in the Player box and align each one to the clap using the media controls and scrubbing bar. You can test the synchronisation by selecting All in the player box and playing the recording. It should be possible to perfectly align the recordings. Once all recordings are aligned, press the Apply Current Offsets button in the Offset box.

### Segmentation
In order to make the transcription of anything longer than a sentence manageable, we first need to break it up into smaller segments. We can do this in ELAN's Segmentation Mode. In segmentation mode, we can see our audio and video and a track for each speaker at the bottom, as well as options regarding the segmentation and some media control options at the top. In Segmentation Mode, we can create segments for each phrase or utterance by each speaker, which we will later transcribe and translate individually. We do this by playing through the recording and using the `Enter` key to mark the start and end of each utterance. We can easily start and pause the recording using `Ctrl+Space`. It is also important here to separate speakers into separate tracks. The template we used already has two speakers, visible in two tracks at the bottom of the screen. We can quickly switch between these with the Up and Down arrows, though these only work if the audio track is selected first. Segmentation is the longest and most boring part of transcription, but it is unfortunately both important and useful.

> Select Options > Segmentation Mode. Go through your recording and divide it into segments using the Enter key to mark the start and end of each utterance by each speaker. You can start and pause the recording using `Ctrl+Space` and change between speakers using the Up and Down arrows. Make sure that under Segmentation at the top you have "Two keystrokes per annotation" selected. This allows us to easily mark the start and end of each utterance, and skip any silence between or while the other person is speaking.


## Finally, transcription

### Goals of transcription
In the process of transcription we are trying to capture what was said, exactly as it was said. This allows us to preserve the data of the recording exactly as it was spoken originally to make sure we don't miss anything later. Additionally, sometimes we want to quote people exactly in their original language rather than in English or a translation. In any case, the word-for-word exact transcription of recordings in their original language is the most important part of transcription, and is why we go through the whole process of importing, synchronising, and segmenting our recordings - to make them much easier to transcribe. The process of transcription, whether for linguistics or for anthropology, is the same.

One challenge that we can face in transcription of languages that are not often written is that there is no standard or official way of spelling them. We want to be as consistent as possible in transcription, so that later on we know exactly what was said. If there is any standard system for spelling the language, official or developed by researchers, it is best to use that as best as you can. Otherwise, try to be consistent in how you spell different sounds so that someone else reading your transcriptions can know exactly what was said.

### How to transcribe language in ELAN
ELAN makes transcription fairly straightforward once we have gone through the processes of segmenting the recordings. It will lay out each segment according to speaker in two columns, one for the text and one for the free translation. As mentioned above, the text column is for exact word-for-word transcription of the segment. You are able to play the audio snippet at various volumes, as well able to slow it down to better hear exactly what is said in the segment. The free translation column is for a natural translation into English (or whichever language you are translating into). This should be a translation that sounds good and correct in English, and not necessarily an exact literal translation. For instance, in the languages of Bhutan, the verb comes last in the sentence, but in English it comes in the middle. The free translation in this case should have the verb in the middle as in English, and not in the order it is in the original language.

> Select Options > Transcription Mode. If this is the first time you have opened transcription mode (and sometimes after) you a box will come up asking you to set up the transcription window. Specifically, it asks for your preferred font size, the number of columns, and their labels. In our case, we have **2** columns, one `text` and one `translation`. If there is an empty third column that appears when you select `translation` for the second column, do not worry.

> Depending on your preference (set in the Settings box on the left side of the transcription window), the audio for a segment will either play when you click on its row, or when you press the `Tab` key. In any case, you play the audio again with the `Tab` key. There is an occasional glitch where the audio will keep playing beyond just the segment you have selected. Do not worry if this happens, just press `Tab` again to stop the audio. 

> Now, slowly work your way through all of the segments, transcribing the recording exactly as you hear it, and then also giving an English translation. If the segment is too fast for you to be able to hear easily what is said, you can slow it down by changing the Rate on the left side of the window to below 100. If you want to bring the playback back to full speed, return the Rate slider to 100.

## Where to from here
A challenge often faced by linguists in transcription is that you need to speak the language. By the end of a major project, a linguist might be able to do this, but early on this will probably not be the case. In these situations, we need the help of people who speak the language.

This workshop stops short of explaining what "analysis" linguists actually do to document languages. This is, for many reasons, too complicated to be covered in a single workshop. That being said, there is a lot of linguistics work that can be done without needing a full university degree, especially if you are working with a language you speak. For instance, one of the first parts of language documentation is working out all the sounds of a language, something that is much easier to do if you speak the language.

As linguists, we are always looking for people who are interested in their languages to help us with transcription and analysis, especially in terms of less studied or more endangered languages such as Lhokpu or Black Mountain Mönpa. This is especially the case at the moment with Gwen and Mareike's ongoing research projects here in Bhutan.

## Other Notes
### Adding a comments column

### Typing in the Tibetan Script
The default font in ELAN is not able to properly render the Tibetan script. If we want to write with it, we need to assign a new font to the speaker column. First, we need check which fonts we have installed that will display Tibetan, and then we can assign them to the text tiers.

> Select View > Font Browser... and type some text in Tibetan in the box at the bottom "Paste UNICODE Text". It might appears a squares, or display incorrectly. Next, press the "Check" button at the bottom, and a list of fonts that can render Tibetan will appear in the box titled "Fonts that will Render text". Close the font browser window and select Tier > Change Tier Attributes. Select the first tier (Text-Speaker 1) then select "More Options..." and next to "Tier Font" select "Browse...". Select any of the Tibetan fonts which appears earlier in the font browser window, then press Apply, Apply, check the box "all tiers with the same type" to ensure that you can type Tibetan for all speakers, then Apply again. You can now close the Tier Attribute window and the Tibetan script should be working.