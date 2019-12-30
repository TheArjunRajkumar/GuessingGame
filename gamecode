import random
import math

ceil = 100
floor = 0
answer = random.randint(floor, ceil)
guess = (ceil - floor) / 2
steps = 1

while guess != answer:
    guess = math.ceil(guess)
    if guess < answer:
        print(f'{steps}. Higher! g:{guess}, a:{answer}')
        floor = guess
        guess += ((ceil - guess) / 2)
    elif guess > answer:
        print(f'{steps}. Lower! g:{guess}, a:{answer}')
        ceil = guess
        guess -= ((guess - floor) / 2)
    steps += 1

print(f'This is your guess: {guess}')
print(f'This is the answer: {answer}')
