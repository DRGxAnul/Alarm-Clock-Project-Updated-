# ⏰ Alarm Clock GUI – Java Swing Desktop Application

A modern, interactive desktop alarm clock built with Java Swing that allows users to set multiple alarms with AM/PM support, real-time clock display, and audio notifications.

---

## 📌 Features

- **Live Clock Display** – Shows the current time in hh:mm:ss AM/PM format.
- **Multiple Alarms** – Add, view, and delete multiple alarms.
- **AM/PM Toggle** – Clearly labeled and color-coded toggle button for easy time selection.
- **Error Handling** – Prevents setting past alarms or duplicate entries, with user-friendly dialogs.
- **Alarm Alert** – Pops up a message and plays a real-time generated beep tone.
- **Dark-Themed UI** – Stylish and user-friendly interface using custom color schemes.
- **Optimized Event Handling** – Smooth interactions with real-time feedback.
- **Clean & Modular Code** – Easy to understand, maintain, and extend.

---

## 🛠️ Technologies Used

- **Language:** Java (JDK 8 or higher)
- **UI Framework:** Java Swing
- **Audio:** `javax.sound.sampled` for generating beep tones
- **Date/Time Handling:** `Calendar`, `Date`, `Timer`, `SimpleDateFormat`

---

## 🚀 Installation & Running

1. Clone the Repository
   ```bash
   git clone https://github.com/your-username/alarm-clock-gui.git
   cd alarm-clock-gui

2. Compile the Java File
   javac AlarmClockGUI.java

3. Run the program
   java AlarmClockGUI

## How to Use
1. Set an Alarm

Select a date, hour, and minute.

Toggle AM/PM.

Click "Add Alarm" to save.

2. Remove Alarm

Click on an alarm in the list.

Click "Remove Selected".

3. Alarm Triggers

Alarm will show a popup.

A beep tone will play using your system’s speaker.

## FOLDER STRUCTURE
alarm-clock-gui/
│
├── AlarmClockGUI.java        # Main Java class
├── README.md                 # Project documentation
