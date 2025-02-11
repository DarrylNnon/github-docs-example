# Writing Good Documentation

## Step 1 - Using Codeblocks.

codeblocks in markdown make very easy for tech people to copy, paste, share code. A good Cloud Engineer should uses codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research
```python
class Person:
    def __init__(self, name, age, gender):
        """Initialize a Person object with name, age, and gender."""
        self.name = name
        self.age = age
        self.gender = gender

    def introduce(self):
        """Introduce the person."""
        return f"Hello, my name is {self.name}. I am {self.age} years old and I identify as {self.gender}."

    def have_birthday(self):
        """Increase the person's age by 1 year."""
        self.age += 1
        return f"Happy Birthday! {self.name} is now {self.age} years old."

# Example Usage
person1 = Person("Alice", 30, "Female")
print(person1.introduce())
print(person1.have_birthday())

```

make note of where the bactick button is located
<img width="591" src="https://github.com/user-attachments/assets/800faa41-273c-4810-80b7-4d0036beef43" />

```bash
traceback (most recent call last):
      2: from /usr/bin/irb:23:in '<main>'
      1: from (irb):1
RuntimeError: This is a custom error message
```
Github flovored Mardown support emoji shortcodes.
Here are some examples:
| name | shortcode | Emoji |
| --- | --- |
| baz | bim | :cloud: |

:cloud:

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3
  
## Reference

- https://www.youtube.com/watch?v=O9z6OvL-AQQ&list=PLBfufR7vyJJ4q5YCPl4o2XAzGRZUjuD-A&index=16
