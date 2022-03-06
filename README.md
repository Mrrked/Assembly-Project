
# Simple Arithmetic Quiz App
The scope of this project extends to a simple quiz application. It will only feature simple arithmetic problems. The purpose of this project is to test the knowledge of young students about basic math. The expected users of this application are Grade 3 students.

## Requirements
 - Ubuntu 18.04 LTS
 - NASM

## Commands

 - Assemble:  `nasm -f elf64 QuizApp.asm`
 - Link: `ld -s -o QuizApp QuizApp.o`
 - Execute:  `./QuizApp`
 
## Instruction Manual
1. Run the program 
2. The program shall display a welcome message.
3. The program shall display the first question and three choices.
4. The user shall select the letter of his answer and input the letter in the command line.
5. The program shall display the next questions and the user shall provide his answer for each one.
6. When the questions end, the program will display the user’s score.
