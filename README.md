# BruteForce-Simulating
# Test File
 # BruteForce-Simulating
# Hello  Thaanks For Reading This, This is an Testing file Bugs may appear.

character_list = list("abcdefaxkfzfhkyjyipllm1235670890")
password = input(" Enter Your Password Or Word")
guess = ""
while (guess != password):
guess = random.choices("character_list",k=len(password))
print(guess)
guess = "".join(guess)
print(guess)
print(" Your Password is " + guess)
