# **ConferenceManagement_with_AI**
## WID means What I Do
### *It's Project for graduate Project* 
### *This md file is for What I do and study every day*


## 2018_09_04
* Buy Mic for Raspberry Pi
* Review Android, Android Studio and basic step (page 126/829)
____
## 2018_09_05
* Install raspbian
* Review Android, Android Layout (page 179/829)
____
## 2018_09_06
* Install raspbian 
* Setup MIC and speaker
* have ISSUE that speaker and MIC are not worked together If Speaker work, then MIC doesn't work and Contrary
____
## 2018_09_08
* Solve ISSUE about Speaker and MIC. It's problem that Set device ID is diffrent each other.   
In my case, USB MIC is card 0,device 0 and Speaker(AUX) is card 1 and device 0  
so I solve it by making asoundrc
```javascript
pcm.!default{
	type asym
	playback.pcm{
		type hw
		card 0
	}
	capture.pcm{
		type hw
		card 1	
	}
}
ctl.!default{
	type hw
	card 0
}
```
*

____
## 2018_09_09
* Search STT and TTS
* get key for Google cloud API(STT)
* Make my Idea small for DeadLine
____
## 2018_09_11
### <em>Project topics is changed <em>
### basicaliy, It is AI on the Desktop 
### main function 
	* control External program by using voice AI
	* manage Conference with Cam,chatting,painter,voice
	* inform you with your plan
* find useful External library for AI that is ND4J
____
## 2018_09_13
* make basic UI

____
## 2018_09_14
* add code that run the program for the command you entered
____
## 2018_09_16
* adding conference solution code that I made for client
* make sever for conference(yet chatting part)
____
## 2018_09_17
* Perfectly added chatting code for client
* Perfectly added chatting code for sever
____
## 2018_09_18
* adding whiteboard code for client
* Perfectly added whiteboard code for sever
____
## 2018_09_19
* Perfectly added whiteboard code for client
* adding webcam code for client
* have ISSUE that when transport webcam data with ObjectInput/OutputStream, occur error, out of buffer
____
## 2018_09_21
* solve ISSUE by using "reset()" ObjectInput/OutputStream be unaffected by flush() and not be reset by gc 
Please check the link below for more information. 
<https://stackoverflow.com/questions/38005181/java-get-image-from-webcam-and-send-over-socket#>

____
## 2018_09_22
* completly added webcam code for client
* adding webcam code for server
____
## 2018_09_23
* Perfectly added webcam code for server
* combine component of conference with existing part that do order
* update UI
____
## 2018_09_24
* study about maven
* update UI
* combine component of conference with existing part that do order
____
## 2018_09_25
* study about google cloud speech
____
## 2018_09_28
* study about google cloud speech
____
## 2018_09_29
* adding google speech api
____
## 2018_09_30
* Perfectly added google speech api
____

## <em>The functions I've implemented are:</em>
### All of the features below work by voice
* Show time and date
* Runs an external program added by an individual
* Provides webcam, whiteboard, and text chat via Server NOT Local
____
## 2018_10_03
* study deeplearning
____
## 2018_10_06
* updata UI
* stabilize
____
## 2018_10_07
* updata UI
* stabilize
____
## 2018_10_09
* updata UI
* Combine text chat with WhiteBoard

____
## 2018_10_10
* updata UI
* Combine text chat with WhiteBoard
____
## 2018_10_11
* solve issue of STT that Check the end of Speech
* Webcam has Issue that More than one, than error occurs
* Voice has Issue that doesn't work
* add Search function
____
## 2018_10_14
* add TTS function
____
## 2018_10_29
* study deeplearning
____
## 2018_10_30
* Buy deeplearning book
____
## 2018_11
* study deepLearning and went conference of DeepLearning
____
## 2018_11_18
* Solve Webcam Issue by using UDP
____

