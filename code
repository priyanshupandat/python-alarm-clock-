import datetime
import winsound

hour = int(input("Enter hour: "))
minute = int(input("Enter minute: "))
am_pm = input("Enter am/pm: ").lower()

if am_pm == "pm" and hour != 12:
    hour += 12
elif am_pm == "am" and hour == 12:
    hour = 0

print("Alarm set successfully!")

while True:
    current_time = datetime.datetime.now()

    if current_time.hour == hour and current_time.minute == minute:
        print("Alarm is ON!")
        winsound.Beep(1000, 1000)
        break
