Dators nejauši ģenerē vienu skaitli no 1 līdz 100. Tālāk, piedāvā spēlētājam uzminēt to skaitli.
Spēles loģika ir labi aprakstīta kodā.

import random

repeat= True

while repeat:
  number = random.randint(1, 100)
  guess = 0
  tries = 0
  print(number)

  while guess != number:
    guess = int(input("guess: "))
    tries +=1
    if number < guess:
      print("lower")
    elif number > guess:
      print("higher")
    else:
      print("gg")
      print(f"you guessed in {tries} tries")
  response = input("again y/n: ")
  if response == "y":
    repeat = True
  elif respone == "n":
    respone = False
  else:
    repeat = False
