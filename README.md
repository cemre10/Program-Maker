# Program Maker

## Concepts

Welcome to the Concepts section, where we delve into the foundational ideas that power the Program Maker.

### 1. [Dynamic Scheduling](#🚀-features)

Program Maker provides dynamic scheduling for lessons and groups, allowing flexibility in creating diverse schedules without conflicts.

### 2. [Support for Multiple Lessons and Groups](#concept-2)

The program supports multiple lessons and additional groups, accommodating complex schedules while maintaining clarity and coherence.

### 3. [Time-Saving Usage](#concept-3)

Utilizing Program Maker can save a significant amount of time in creating schedules, especially in scenarios involving numerous lessons and diverse groups.

### 4. [Clash Prevention](#concept-4)

One of the core features is the prevention of clashes in your time schedule. The program intelligently generates schedules that avoid conflicts, ensuring a smooth and organized timetable.

## Concept Details

### Concept 1

Dynamic Scheduling in Program Maker allows for the efficient allocation of lessons and groups, adapting to various scenarios and preferences. The program intelligently handles scheduling changes without compromising on coherence.

### Concept 2

Support for Multiple Lessons and Groups ensures that the program caters to diverse educational settings. Whether it's handling multiple lessons or accommodating different groups within a lesson, Program Maker is designed to be versatile.

### Concept 3

Time-Saving Usage is a key benefit of Program Maker. By automating the scheduling process, the program eliminates the need for manual intervention, saving valuable time for users.

### Concept 4

Clash Prevention is a critical aspect of Program Maker. The program analyzes the provided data to generate schedules that avoid clashes, ensuring a well-organized and conflict-free timetable.


Welcome to Program Maker, this is a Python program designed to help you create schedules for lessons and groups. This program reads input from a text file, processes the information, and generates all possible schedules that are not CLASHING based on the provided data.

## 🚀 Features

- Dynamic scheduling for lessons and groups.
- Support for multiple lessons and additional groups.
- Usage of this program can save a lot of time.
- Prevents clash in your time schedule.

## 🌟 Input File Format

The text file should start with the number of lessons (an integer). 
Following that, list the lesson names (strings).
For each lesson, specify how many times it occurs in a week and provide the corresponding schedule.
Repeat this process for all lessons.
If a lesson has multiple groups, indicate 'yes' and specify the schedule for each group; otherwise, mark 'no.' Continue this pattern for all other lessons."

Example Input/Output File:

- [Program.txt](program.txt)
- [Output.txt](output.txt)

## 🎩 Is it complex?

Don't worry; it's designed to simplify your scheduling woes. Let's unravel the magic behind the scenes and analyze what our program actually does with using our [Program.txt](program.txt) input. 🚀

## 🎯 How to Use

1. Run the program:
   ```bash
   python program_maker.py
   ```
   The output will be:
   ```
   Welcome to Program Maker
   Enter your txt file:
   ```
   - Enter your .txt file here. Now lets analyze the format of .txt file from the initial example [Program.txt](program.txt).
2. Understanding the input file format.
   ```
   3                      # Number of Lessons
   LESSON1                - Lesson Name
   LESSON2                - Lesson Name
   LESSON3                - lesson Name
   2                      # how many times 1. lesson occurs in a week and provide the corresponding schedule.
   Wednesday 10:30
   Friday 12:30
   1                      # how many times 2. lesson occurs in a week and provide the corresponding schedule.
   Thursday 14:30
   1                      # how many times 3. lesson occurs in a week and provide the corresponding schedule.
   Tuesday 8:30
   yes                    - Does 1. lesson has 2. group? if yes type 'yes' and provide the corresponding schedule.
   Monday 10:30
   Tuesday 12:30
   no                     - Does 1. lesson has 3. group? if no type 'no'
   yes                    - Does 2. lesson has 2. group? if yes type 'yes' and provide the corresponding schedule.
   Wednesday 8:30
   no                     - Does 2. lesson has 3. group? if no type 'no'
   no                     - Does 2. lesson has 2. group? if no type 'no'
   ```


![](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExN3E1Y3RmMDBwNXdibG4zaWhiNG9zdncwMjltaTJvbGRtazYwdjJsZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/KAq5w47R9rmTuvWOWa/giphy.gif)

![GPA Calculator](https://img.shields.io/badge/GPA_Calculator-Interactive-brightgreen)
![CGPA Calculator](https://img.shields.io/badge/CGPA_Calculator-Advanced-blue)



