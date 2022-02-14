# AlarmClock
    So the problem statement is, you're trying to automate your alarm clock by writing a function for it. You're given a day of the week encoded as 1 = Mon, 2 = Tue, ..., 6 = Sat, 7 = Sun, and whether you are on vacation as a boolean value (a boolean object is either True or False. Google "booleans Python" to get a better understanding).
    Based on the day and whether you're on vacation, write a function that returns a time in form of a string indicating when the alarm clock should ring.     When not on a vacation, on weekdays, the alarm should ring at "7:00" and on the weekends (Saturday and Sunday) it should ring at "10:00".
    While on a vacation, it should ring at "10:00" on weekdays. On vacation, it should not ring on weekends, i.e., it should return "off".
