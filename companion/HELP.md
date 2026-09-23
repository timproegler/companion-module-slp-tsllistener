##### SessionLinkPRO Solutions GmbH TSL Listener





This module will allow you to listen for incoming TSL UMD data and

* set tally states on your Companion Buttons
* forward the TSL UMD data as JSON string via a different protocol

## 

###### Configuration

* Enter the listening port that Companion should use to listen for the incoming data
* Select whether to listen via TCP or UDP
* Select the Protocol Version to use

## 

###### Actions

This module inherently has no actions. If you wish to perform an action based on a tally state change, use a Trigger.

## 

###### Variables

* Variable for each Address 'x' with UMD Label for value (tsl-listener:tally\_x\_label)
* Variable for each Address 'x' and Tally State (On/Off) (tsl-listener:tally\_x\_tally1 ... tsl-listener:tally\_x\_tally4)

## 

###### Feedbacks

* Set button to color if address 'x' Tally 1-4 is this state (On/Off)

