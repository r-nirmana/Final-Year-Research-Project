# Final-Year-Research-Project
Worked on the final year research project which was detecting approaching vehicles towards users using Audio  Signal processing. Here in this project we have collected various audio samples of vehicles including engine sounds,  Horn sounds and then analysed the data samples in search of identifying different audio features which can be used  in classifying the audio signals. We have extracted different audio features from the audio samples including  amplitude envelope, spectrograms, MFCC, etc and proceeded with spectrograms in classifying the audio signals  using machine learning models.

ABSTRACT

Here in this project, we have designed a system which is basically capable of detecting approaching 
vehicles towards the users and with such information available, the information could be used in 
alerting the distracted users about approaching vehicles when they are about to enter an intersection 
or wander into roads. The main objective of this project is to detect the presence of a vehicle and 
identifying whether a vehicle is approaching the user or leaving the user. In this study we have 
taken the approach with audio signal processing. We have analysed the sounds of the vehicles 
which were both collected and already existing data samples and obtained the results using 
Machine learning techniques. Processing of the audio signals was done in three steps, identifying 
audio features, extracting the audio features and detecting the presence of a vehicle and identifying 
whether the vehicles are approaching users or leaving. We have identified different audio features
and out of them we have proceeded with the spectrograms of the audio signals since those 
spectrograms can be used in classifying the audio signals. Classification of the audio signals was 
done using Python and the results were obtained successfully.

INTRODUCTION

With the newest technologies around, lives have become much more comfortable. Applications of 
the technological areas has been doing a significant role in making the lives easier as well as 
helping the mankind to sustain a more well organized life. In recent years, the use of smartphones 
to sense users' surroundings and learn about their contextual information has gotten a lot of 
attention. A considerable number of such studies have been carried out for users who are driving, 
but far less work has been put in for users who are walking. Here in this study we will be focusing 
on sensing and learning important information for pedestrian users using their smartphones. This 
research carries out a methodology to identify whether a vehicle is approaching a user or leaving 
a user. All these identifications are done on the basis of audio signal processing. Vehicles generate 
a lot of sounds. Engine sounds, Horn sounds and the tyre friction sounds are some of them. We 
have analysed these audio samples and obtained effective results. An audio signal is a 
representation of sound that is often made up of a series of binary digits or a changing level of 
electrical voltage for analogue signals. Audio samples consists of unique features. Those features 
define the samples and extracting these features and identifying which features can be used in 
classifying the signals was done. Different audio features, how they were extracted and how the 
classification was done will be discussed further in the methodology section. The process of 
listening to, analysing, and classifying audio recordings is known as audio classification. It has a 
wide range of applications, including speech to text translation, sound recognition, music or song 
identification, automatic speech recognition, and virtual assistants. And in this study we have used 
audio signal processing in detecting whether a vehicle is approaching a user.

METHODOLOGY

The system can be discussed in three main parts. They are inputs 
to the system, the process and the outputs of the system. 

a)Data Collection.
We have taken input audio samples in three main ways. We have used already existing data 
collection , Vehicle sounds collected in the university premises and the sounds collected in the 
Laboratory.

• Existing audio sound Data collection : 
This data collection was consisted of engine sounds and horn sounds of different vehicles. 
This data set was named as Urbansounds8k and was used in identifying different audio 
features.

• Audio Data collection done in the university premises
Sounds of vehicles were collected in campus premises. This sound collection includes 
sounds of cars, three wheelers and motor bikes. These samples were collected near the 
Jagda gate in NITR between 6.00pm and 9.00 pm. All these samples were collected by the 
microphones embedded in smartphones. Recordings were done in between a spot where 
we could capture both approaching and leaving sounds of the vehicles. Recordings were 
started when we observe a vehicle in a distance of about 100 meters and the recordings 
were ended when the vehicles were passed and reached 100 meters from the spot. So each 
samples were about one to two minutes and consisted of both approaching and leaving 
sounds. Then we have trimmed down the audio and obtained the approaching and leaving 
samples separately so that we can use them in extracting features separately and classifying 
them.

• Audio data collection done in the laboratory
Data samples were collected in the laboratory on the basis of approaching and leaving 
classes according to different frequencies. We have created a lab setup with microphones, 
speakers and recorded the audio samples with focusrite scarlett 2i2. First we have arranged 
the microphone setup. The microphones were fixed as shown in the figure(Fig ) so that the 
microphones avoid unnecessary sounds as the microphones were highly sensitive. The 
package was covered from a sponged layer. Then the fixed microphones were connected 
to the focusrite scarlett 2i2 and the audio samples were recorded in the following procedure.

o Sound Samples of frequencies 100Hz, 500 Hz , 1KHz , 1200 Hz and 1500 Hz were 
played using the speaker.

o Then the recording was started and the Microphones were moved back and forth 
between the starting point and the speaker.

o From starting point to the speaker the approaching audio was recorded for all the 
above mentioned frequencies and then starting from the speaker moved back to 
record the leaving sample of the different frequencies.

o All these audio samples were captured and stored for further feature extraction and 
classification purposes.






