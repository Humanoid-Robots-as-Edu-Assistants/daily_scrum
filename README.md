# "daily scrum - Nao as scrum assistant" for NAO robot [V.2.1]
*This project is available in German or English.*<br>

### About

In this application, the robot Nao takes on the role of a Scrum assistant. He explains to the students how a daily Scrum <br>
meeting works and what needs to be considered. Then a group of 1-8 participants can play through a meeting with Nao.

### How the program works

After the introduction, Nao asks for the number of participants. This determines how many loops the robot will make <br>
with the students. (A group size of max. 5 people is recommended.) After that, Nao starts with the first participant and <br>
asks the 3 questions that belong to the daily scrum.<br>
"What have you done in the last 24 hours to reach our sprint goal?"<br>
"What will you do in the next 24 hours to reach our sprint goal?"<br>
"What obstacles keep you or us from reaching the sprint goal?"<br>

In our test with students, the participants received a script, but students can also speak freely.<br>
Nao waits for sensor input before continuing.

### What do you need?

You will just need your NAO robot.

### Plans of further development:

We currently paused working on this project. There will be updates in the future.

### Choregraphe screenshot:

---

### Changelog
V 2.1  <br>
- notification fix <br>
- replaced time->LED notification with time->sound-signal notification <br>

V 2.0  <br>
- getting rid of the dialogs and replaced it with say-boxes and say-text-boxes <br>
- implemented new logic - to count participants <br>

V 1.1 <br>
- fixed spelling and added more breaks when speaking <br>
