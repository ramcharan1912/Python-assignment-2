# Python-assignment-2
def remove_vowels(string):
    vowels = ['a', 'e', 'i', 'o', 'u']
    result = ""
    for char in string:
        if char.lower() not in vowels:
            result += char
    return result
