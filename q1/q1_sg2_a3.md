year=int(input("Enter your birth year: "))

if year<1900:
    print("\nInvalid Year. It should not be earlier than 1900")

elif (year-1900) % 12 == 0:
    print("\nYour Chinese Zodiac Sign is: Rat (鼠 / Shǔ)\nThe next Year of the Rat is 2032.")

elif (year-1900) % 12 == 1:
    print("\nYour Chinese Zodiac Sign is: Ox (牛 / Niú)\nThe next Year of the Ox is 2033.")

elif (year-1900) % 12 == 2:
    print("\nYour Chinese Zodiac Sign is: Tiger (虎 / Hǔ)\nThe next Year of the Tiger is 2034.")

elif (year-1900) % 12 == 3:
    print("\nYour Chinese Zodiac Sign is: Rabbit (兔 / Tù)\nThe next Year of the rabbit is 2035.")

elif (year-1900) % 12 == 4:
    print("\nYour Chinese Zodiac Sign is: Dragon (龙 / Lóng)\nThe next Year of the Dragon is 2036.")

elif (year-1900) % 12 == 5:
    print("\nYour Chinese Zodiac Sign is: Snake (蛇 / Shé)\nThe next Year of the Snake is 2037.")

elif (year-1900) % 12 == 6:
    print("\nYour Chinese Zodiac Sign is: Horse (马 / Mǎ)\nThe next Year of the Horse is 2038.")

elif (year-1900) % 12 == 7:
    print("\nYour Chinese Zodiac Sign is: Goat (羊 / Yáng)\nThe next Year of the Goat is 2027.")

elif (year-1900) % 12 == 8:
    print("\nYour Chinese Zodiac Sign is: Monkey (猴 / Hóu)\nThe next Year of the Monkey is 2028.")
    
elif (year-1900) % 12 == 9:
    print("\nYour Chinese Zodiac Sign is: Rooster (鸡 / Jī)\nThe next Year of the Rooster is 2029.")

elif (year-1900) % 12 == 10:
    print("\nYour Chinese Zodiac Sign is: Dog (狗 / Gǒu)\nThe next Year of the Dog is 2030.")

elif (year-1900) % 12 == 11:
    print("\nYour Chinese Zodiac Sign is: Pig (猪 / Zhu)\nThe next Year of the Pig is 2031.")

else:
    print("????")



