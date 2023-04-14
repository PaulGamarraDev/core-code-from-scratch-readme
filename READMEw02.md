# core-code-from-scratch-readme

## WEEK 02

# Logic problem

*Description:*

The teacher asks his 5 students if they studied mathematics yesterday.
  - Alice: "Nobody studied math yesterday".
  - Bob: "1 person studied math yesterday".
  - Charlie: "2 people studied math yesterday".
  - Dan: "3 people studied mathematics yesterday".
  - Eva: "4 people studied mathematics yesterday".

The teacher knows that only those who studied would be telling the truth and those who didn't would be lying. Who is telling the truth?

*Analysis:*
  - First statement: those who studied would be telling the truth and those who didn't would be lying
  - Alice: if nobody studied she did not study and she will be lying accordingly to the first statment. Alice is lying
  - Eva: if she is telling the truth her comment will be in conflict with the other 3 students. Eva is lying
  - Dan: if he is telling the truth his comment will be in conflict with the other students. Dan is lying
  - Charlie: if he is telling the truth his comment will be in conflict with the other students. Charlie is lying
  - Bob: if he is telling the truth he studied.
 
*Conclusion:* Bob studied and he is telling the truth


# Cereal or Milk

1. Look for a bowl
2. Add your favourite cereal
3. Add milk
4. Enjoy!

![image](https://user-images.githubusercontent.com/106286065/231033713-95d0e4b6-3de8-4d05-a34b-1ef175f6fa58.png)

# Print my name

This was a guided challenge, learning how to use PSeInt.
![image](https://user-images.githubusercontent.com/106286065/231323372-2699ac10-47b6-4551-8624-02af29ca835f.png)

# Print my name & age

*Description:*

For this challenge, you will need to create an algorithm in Pseudocode using PSeInt that prints your name and your age in separate lines, remeber that your name should be a string and your age a number

![image](https://user-images.githubusercontent.com/106286065/231327134-3945e4c4-c9b0-48f6-a1b9-c86e60ac2c75.png)

# Mod in PSeInt Challenge

The challenge for you now is to create a PSeInt program that will receive a number from the user and add the mod operator using the even/odd case ( X % 2 ) where X is the user input

![image](https://user-images.githubusercontent.com/106286065/231624108-e6b2f416-d70d-4218-b046-70a800990e17.png)

# Register form

*Description:*

You are given the task to create a registration form for new users, this form should ask the user for the following information:
- First name
- Last name
- Age
- Email
- Address
At the end of the program, you should print all the information added from the user in a friendly way

![image](https://user-images.githubusercontent.com/106286065/231628023-32591a89-d209-4f35-a9fb-6717d0ecffff.png)

# Truth tables

*Description:* Answer ✅ or ❌ at the end of each operation

T & T = T ✅
T & F = F ✅
F & T = T ❌
F & F = F ✅
T | T = T ✅
T | F = F ❌
F | T = T ✅
F | F = F ✅
~T = T ❌
~F = T ✅
(T & F) | (~F) = T ✅
(T | F ) & (F | F) = T ❌
~((T | F ) & (F | F)) & F = T ❌
~((T | F ) & (F | F)) & T = F ❌
