# Veronika Kantina

## Contacts
- **Email**: nikakantina@gmail.com
- **Telegram**: @NikaKantina
- **GitHub**: NikaKantina

## Current goals
I've decided to change my career path, and right now I'm exploring which areas of self-development interest me the most. I consider taking this course as a great opportunity to learn about front-end development.

## Skills
- **Python** (basic)
- **HTML** (basic)
- **CSS** (basic)

## Code
```python
def open_file(filename):
    with open(filename, 'r') as f:
        read_flowers = f.readlines()
        flower_keys = []
        flower_values = []

        for line in read_flowers:
            flower_keys.append(line.split(':')[0]) 
            flower_values.append(line.split(':')[1].strip())
    
        flowers_dict = dict(zip(flower_keys, flower_values))
        return flowers_dict
full_dict = open_file('flowers.txt')
print(type(full_dict))
def main_func():
    input_name = input('Enter your First name only: ')
    first_letter = input_name[0][:1].capitalize() 
    
    flower_value = full_dict[first_letter]
    print("\nUnique flower name with the first letter: ", flower_value)
    
main_func()
```
## Professional experience
I worked as a project administration specialist for six years, where I was responsible for organizing and coordinating working group meetings and monitoring the implementation of decisions and instructions.

## Education
**Belarusian state university of informatics and radioelectronics**
- Digital Marketing

## Languages
- **Russian** (native)
- **English** (B2, Upper-Intermediate English)
