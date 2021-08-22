# AMI

The AMI Meeting Corpus is a multi-modal data set consisting of **100 hours** of **meeting** recordings. For a gentle introduction to the corpus, see the [corpus overview](https://groups.inf.ed.ac.uk/ami/corpus/overview.shtml). To access the data, follow the directions given [there](https://groups.inf.ed.ac.uk/ami/download). Around two-thirds of the data has been elicited using a scenario in which the participants play different roles in a design team, taking a design project from kick-off to completion over the course of a day. The rest consists of naturally occurring meetings in a range of domains. Detailed information can be found in the documentation section.

### Directory Architecture

```
Data Directory 
   |——————annotations
   |        └—————— words
   |                  └—————— ES2005a.A.words.xml (the word annotion for the first speaker in sessition 		       															 ES2005a, the annotation includes each word's start and end time)
   |                  └—————— ES2005a.A.words.xml 
   |                  └—————— ...
   |——————beamformed
   |        └—————— EN2002a (speech after beemforming?? more clear multi-talker speech)
   |        └—————— EN2002b
   |        └—————— ...
   |——————EN2002a
   |        └—————— audio
   |                  └—————— EN2001a.Array1-01.wav (the first microphone of microphone array, far-field)
   |                  └—————— EN2001a.Array1-02.wav 
   |                  └—————— .... 
   |                  └—————— EN2001a.Headset-0.wav (the headset for the first person, close-talking)
   |                  └—————— EN2001a.Headset-1.wav 
   |                  └—————— .... 
   |——————EN2002b
   |        └—————— ...
   |——————EN2002c
   |        └—————— ...
   └——————EN2002d
   |        └—————— ...
   └——————.....
            └—————— ...
            
```

### Notes

- There are two recording scenarios in AMI:
  - Scenario Meetings
    - For scenario meetings, 1 day-recording session is divided into four [a, b, c, d] 1-hour meetings
    - Selecting **ES2001** meeting session together with **'a'** below allows you to get signals for **ES2001a** meeting.
  - Non Scenario Meetings
- The overlap ratio in AMI is very low
  - Most overlap are responses from  people, like "yeah", "ok", etc...
- There are average **4 speakers** in each recording.