# Alarm-Clock

### Jasmine Tan

*We want to develop software for an alarm clock.*

*The clock shows the time of day. Using buttons, the user can set the hours and minutes fields individually, and choose between 12 and 24-hour display.*

*It is possible to set one or two alarms. When an alarm fires, it will sound some noise. The user can turn it off, or choose to “snooze”. If the user does not respond at all, the alarm will turn off itself after 2 minutes. “Snoozing” means to turn off the sound, but the alarm will fire again after some minutes of delay. This “snoozing time” is pre-adjustable.*

### Use case Diagram
![alt text](https://github.com/jasminetan/alarm-clock/blob/master/diagram.png)

### Use case Description

#### Scenario
Set time and alarm

#### Triggering event
Start application

#### Actors
User

#### Pre-condition
Software installed

#### Post-condition
Time set, alarm set, and alarm shut off

#### Flow of events
Actor 

1 Start application

2 Choose time format

3 Set alarm(s)

4 Set snooze time

6 Snooze or turn off alarm


System

5 Trigger alarm

7 Time out alarm

#### Exception
**Step:** 7   
**Condition:** Snoozed or turned off alarm     
**Action description:** Time out alarm unecessary
