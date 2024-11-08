---
layout: project
type: project
image: img/robott.png


title: "Workout Helper"
date: 2022
published: true
labels:
  - Python
  - Dictionaries
  - User interaction
    
summary: "A python script to help users find exercises for specific muscle groups."
---

<div class="text-center p-4">
</div>

I came up with this idea because I often find myself unsure about which exercises target specific muscles when I'm working out. I wanted a quick and easy way to identify exercises for particular muscle groups, so I decided to write a script that asks for a muscle group, then provides exercises tailored to that group. This seemed like a simple yet effective way to learn more about how to structure my workouts without constantly researching different exercises.

First, I created a dictionary where each major muscle group (like Chest, Legs, or Back) had a list of sub-muscles. I broke it down further into specific muscles, for example, the "Chest" group was split into "Upper Chest," "Middle Chest," and "Lower Chest," and similarly for other groups. This allowed me to quickly map exercises to particular muscles, making it easier to generate personalized workout suggestions.

Next, I built a function that prompts the user to select a muscle group from the available options. Once they make their choice, the script drills down further by asking which specific muscle they want to target within that group. Based on their input, the program then suggests an exercise associated with the specific muscle. For example, if the user selects "Upper Chest," the program suggests doing "Incline Dumbbell Press." This structure gives users a focused exercise suggestion without overwhelming them with too many choices.

The trickiest part was ensuring that the program responds gracefully to incorrect inputs. If a muscle group or specific muscle wasn't recognized, I had to implement a way to notify the user and prompt them to try again. Originally, the program would just exit if there was a typo, but I added input validation to handle misspelled entries, which made the script more user-friendly.

Overall, this project was a fun way to dive into Python dictionaries and user interaction. It gave me a better understanding of how to structure a program to handle input validation and offer a smooth user experience. Plus, it's nice to have a little tool that helps me organize my workouts more efficiently!

Link to Workout Helper repository: https://github.com/Adeilmo226/WorkoutHelper/tree/main
