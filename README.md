# Assignment-2

def remove_vowels(string):
    vowels = ['a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U']
    result = ""
    
    for char in string:
        if char not in vowels:
            result += char
    
    return result
    
