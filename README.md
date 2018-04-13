# HouseholdHarmonizer
Application listens to your family and alerts household members to potential misunderstandings (hopefully before they result in fights). Works with a Smart Speaker &amp; iOS or Android device.

Note - it is possible that this concept will be too creepy for people not wanting Alexa interjecting (it?)self into their personal lives.  However this same principle could be used for:

- Mediators to get feedback on their use of open-ended questions and other mediator tools
- Lawyers to get feedback on their success avoiding surprises when questioning witnesses
- Anyone interested in analyzing conversation for misunderstandings / missed meaning

Right now I'm envisioning this as a Swift project since I've started tinkering with iPhone app creation.  I also know that CoreML framework should be helpful for implementing some of the models.  I believe that models probably already exist for:

- speech detection
- speech recognition
- speaker identification
- idiom / slang dictionary

I think that the biggest parts of this project will be:

- statement / question correlation model
- bringing all the pieces together in a good user experience
