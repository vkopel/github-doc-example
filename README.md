# Writing Good Documentation 

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __cloud engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')
```
def factorial(n)
  if n == 0 || n == 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```ruby
def factorial(n)
  if n == 0 || n == 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```
<img width="200px" alt="Screenshot 2023-08-24 at 11 52 57" src="https://github.com/vkopel/github-doc-example/assets/145416515/dd76c769-3ef8-4b43-84e6-856d9c0c5f42">

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.


```bash
Traceback (most recent call last):
        1: from (irb):1
NameError (undefined local variable or method `undefined_variable' for main:Object)
```

> Here is an example for using a codeblock for an error that appears in bash.

# Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. <sup>[1]</sup>

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

# Step 4 - Use Emojis (Optional) 

Github Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`  | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:`  | 🌩️ |

# Step 5 - How to create a table

You can use the following markdown format to create tables:
```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`  | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:`  | 🌩️ |
```
Github extends the functionality of markdown tables to provide more alignment and table cell formating options. [<sup>[2]</sup>](#references)


## References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax(Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images) 
- [GFM - Tasks Lists ](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>

