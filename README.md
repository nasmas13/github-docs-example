# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks ( ` )
- Not to be confused with quotation ( ' )
  
```
# Define a Person class
class Person
  # Constructor
  def initialize(name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

  # Instance method to return a greeting
  def greeting
    "Hello, my name is #{@name} and I am #{@age} years old."
  end
end
```

- When you can, you should attempt to apply syntax highlighting to your codeblocks

```ruby
# Define a Person class
class Person
  # Constructor
  def initialize(name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

  # Instance method to return a greeting
  def greeting
    "Hello, my name is #{@name} and I am #{@age} years old."
  end
end
```

- Make note of where the backtick keyboard key is located.
- It should appear above the tab key.
- But it may vary based on your keyboard layout.

<img width="200px" src="Assets/backtick-key.jpg" />

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.



```bash
Traceback (most recent call last):
        2: from /usr/bin/irb:23:in `<main>'
        1: from (irb):1
RuntimeError: This is a custom error message
```

> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Task Lists 

Github extends Markdown to have a list where you can check off items. [<sup>.[1].<sup>](#external-references) 

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 Use Emojis (Optional) 

Github Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode |Emoji|
| --- | --- |---|
| Cloud | `:cloud:` | :cloud: |
| Cloud With Lightning | `:cloud_with_lightning:` | :cloud_with_lightning: | 

# Step 5 - How to create a table


You can use the following markdown format to create tables:

```md
| Name | Shortcode |Emoji|
| --- | --- |---|
| Cloud | `:cloud:` | :cloud: |
| Cloud With Lightning | `:cloud_with_lightning:` | :cloud_with_lightning: | 
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>.[2].<sup>](#external-references)

- Make note of where the pipe keyboard key is located.
- It should appear above the return or enter key.
- But it may vary based on your keyboard layout.
![Photo of the pipe character on our keyboard](Assets/pipe-char.jpg)
 
## External References

- [Basic writing and formatting syntax (GitHub Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>.[1].<sup>
- [GFM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (With extensions)](https://github.github.com/gfm/#tables-extension-) <sup>.[2].<sup> 

  




