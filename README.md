# SmartAlert
McHacks Hackathon Fire Alarm Project 2021

Inspiration:
The problem this app addresses initially seems like an obvious one: fire alarms are pretty ineffective
when it comes to those with hearing loss. This is why we were surprised when we found out that this
problem had never been fully addressed. Apart from those with hearing impairment, studies show that
nearly 50% of fatal residential fires occur between 10 pm and 6 am, usually when people are in deep
sleep. So not only is fire alarm notification a problem for those who are hearing impaired, 
but even for people who are just sleeping.

What it does:
The purpose of the app is to alert people with hearing loss that their fire alarm has been activated. There are several features of the app that can be turned on/off by the user: a buzzer, a flashlight strobe, and sending a text to emergency contacts when the app is triggered.

How we built it:
We built this app within Android Studio, using Java as the primary language. We used the Android MediaRecorder library to continuously capture audio input. We implemented a Fast Fourier Transform to convert this data into frequencies. We intended to compare the frequencies obtained from the audio input to those of a standard residential fire alarm.

Challenges we ran into:
None of us had any experience with Android app dev, or the Android Studio. It was very challenging for us to learn to use new tools while trying to implement some very conceptually difficult methods. It took a lot more time than we expected to get used to programming in Android Studio. For frequency analysis, it was difficult to interpret the results of the FFT and use them to create audio profiles of the inputs.

Accomplishments we’re proud of:
We’re proud of how far we got in the development of this app in such a short amount of time with no previous experience in Android development. Along the way, we managed to implement some pretty difficult methods. Collaborating remotely with other team members, dealing with time zone differences, and making the best out of our work from home situations.

What we learned:
Mobile app development with Android Studio.
Fourier transform
How to keep listening for frequencies.

Built with:
Android Studio
