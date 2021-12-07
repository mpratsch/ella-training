```
def swap_case(s):
    new_word = ""
    for a in s:
        if a.isupper():
            new_word += a.lower()
        elif a.islower():
            new_word += a.upper()
        else:
            new_word += a
    return new_word

if __name__ == '__main__':
    s = input()
    result = swap_case(s)
    print(result)
```
