# Getting-vowels
This example returns the found vowels "a e i o u" in the string. This can be useful when looking for or discovering vowels.
def get_vowels(String):
    return [each for each in String if each in "aeiou"]
get_vowels("animal") # [a, i, a]
get_vowels("sky") # []
get_vowels("football") # [o, o, a]
