#Project Title -> Fake News Headline Generator

#1 - import the random module
import random


#2 - create subjects
subjects = [
    "sharukh khan",
    "virat kohli",
    "allu arjun",
    "rashmika",
    "Prime Minister Modi",
    "bus driver of cumbum",
    "a group of parrots"
]

#3 - create actions
actions = [
    "drinking a soya souce",
    "cancels",
    "skipping with a village dog",
    "eating a biryani",
    "playing hide and seek",
    "sleeping",
    "celebrate"
]

#4 - create a place_or_thing
places_or_things = [
    "at a mumbai highway",
    "in mumbai local trains",
    "during IPL match",
    "at India Gate",
    "a plate of samosa",
    "in cumbum cheruvu",
    "in inside a writing pen",
]

#start the headline generation loop
while True :
    subject = random.choice(subjects)
    action = random.choice(actions)
    place_or_thing = random.choice(places_or_things)

    headline = f" Breaking News : {subject} {action} {place_or_thing}!"
    print("\n" + headline)

    user_input = input("\n Do ypu want another headline (yes/ no) : ").strip().lower()
    if user_input == "no":
        break

#print goodbye meassage
print("\n Thanks for using the Fake News Headlie Generator, Have a fun day")
