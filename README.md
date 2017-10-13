# status-update-tone-analyzer

## Setup
- Add the agiliteStatusUpdateToneAnalyzer.json application to your Connections organisation
- Ensure the include-files property pulls the correct path referencing the agiliteCore.js and agiliteStatusUpdateToneAnalyzer.js files

## Description
The purpose of this Customizer application is to analyze the tone of a new status update message that's being posted either on the Homepage or in a Community. The Customizer app makes use of the IBM Watson Tone Analyzer service on IBM Bluemix.

The status update is analyzed in intervals of 2 seconds during the typing of the message. The message is sent to the Tone Analyzer service to determine the dominant tone(s) of the message.

To test this functionality, navigate to the activity feed either in the Homepage or in a Community. Start entering a status update. Beneath the input field you will see this Customizer application at work.

## Screenshots

![Screenshot 1](http://bleedingcode.com/wp-content/uploads/2017/10/agilite-customizer-tone-analyzer-1.jpg)

![Screenshot 2](http://bleedingcode.com/wp-content/uploads/2017/10/agilite-customizer-tone-analyzer-2.jpg)