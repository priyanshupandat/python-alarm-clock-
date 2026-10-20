# python-alarm-clock-

# Python Alarm Clock

## About the Project

I created this Python Alarm Clock as a small project to practice Python programming. It takes the alarm time from the user and checks the current time. When the entered time matches the system time, it prints a message and plays a beep sound.

## How It Works

- The user enters the hour and minute.
- The user selects AM or PM.
- The program converts the entered time into 24-hour format.
- It keeps checking the current time.
- When the time matches, the alarm rings and the program stops.

## Technologies Used

- Python
- `datetime` module
- `winsound` module

## How to Run the Project

1. Install Python on your computer.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Run the following command:

   `python alarm_clock.py`

5. Enter the hour, minute, and AM/PM when prompted.
6. Keep the program running until the alarm rings.

## Example

```text
Enter hour: 10
Enter minute: 30
Enter am/pm: am
Alarm set successfully!
```

When the system time reaches 10:30 AM, the program displays:

```text
Alarm is ON!
```

It also plays a beep sound for one second.

## What I Learned

While working on this project, I practiced taking user input, using conditional statements, converting AM/PM time, and working with Python's date and time module.

## Requirements

- Python 3
- Windows operating system (for the `winsound` module)


