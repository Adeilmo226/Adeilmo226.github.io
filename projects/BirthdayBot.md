---
layout: project
type: project
image: img/birthdaywide.webp


title: "Birthday Bot"
date: 2024
published: true
labels:
  - Python
  - Automation
summary: "A python script that emails my friends and family automatically on their birthdays with an customized birthday message."
---



I came up with this idea due to the fact I do not have the best memory and always forget the birthdays of my friends and family. So I decided to try to write a script that automatically sends a personalized email to a person on their birthday. Orginally I wanted to send a text message, but after doing some research, this proved to be too difficult and beyond my scope of knowledge. Additionaly, there already existed a module that I could import called smtplib that defines an SMTP client session object that can be used to send mail to any internet machine with an SMTP. 


First, I created a csv file that clearly listed the names, birthdates and emails of my friends and family members that I would like to send an email to. I used a csv file because it would be easy to parse through when making my script. I also had to create an app password for my gmail to be able to login to my account thorugh my program. Then I wrote a function that compared the current date to the date of each birthday on the csv file, if the dates matched, an email would be sent accordingly. I personalized the email by including their first and last name, as well as a funny Mr.Bean image. 

To automate this task, I used the cron schduler on my MacOS. It was my first time using a cron schdeler, so this proved to be the most difficult part of the project. I had been able to get my program to work manually by running the program on the terminal, but not automatically. My program was in my documents folder, which led to some security issues so I moved the program to my home directory. Instead of reading from my Birthdays.csv file directly (which has worked when running the program locally), I learned that I had to inculde the path of csv file instead when using cron, in order for the program to work, since cron does not know the location of any files that are being called or opened. 


Overall, this project proved to be pretty challenging but very rewarding in the end. I learned how to automate my program which was very cool and it was really fun being able to implement an idea I had into an actual program. 

Link to BirthdayBot repository: https://github.com/Adeilmo226/BirthdayBot/tree/main

