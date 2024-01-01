# Writing Good Documentation

## Step 1 : Using Codeblock

Codeblock in markdown make it *very easy* for tech people to **copy, paste, share code**. A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (```)
- Not to be confuse with quotation (''')

```
# Simple Ruby program for greeting the user

# Prompt the user for their name
print "Enter your name: "
user_name = gets.chomp

# Greet the user
puts "Hello, #{user_name}! Welcome to Ruby programming."
# Simple Ruby program for greeting the user

# Prompt the user for their name
print "Enter your name: "
user_name = gets.chomp

# Greet the user
puts "Hello, #{user_name}! Welcome to Ruby programming."
```


- When you can you shoyld attempt to appply syntax highlightng to your codeblocks

```ruby
# Simple Ruby program for generating a multiplication table

# Prompt the user for a number
print "Enter a number: "
number = gets.chomp.to_i

# Generate and display the multiplication table
puts "Multiplication table for #{number}:"
(1..10).each do |i|
  result = number * i
  puts "#{number} x #{i} = #{result}"
end
```

- Make note of where the backtick button is located.
- It should appear above the tab key, but it may very based on your keyboard layout.

![wJvjd](https://github.com/cupumelody/github-doc-example1/assets/145847069/85dcfdc7-16cc-45f8-863a-3825267c5e1b)


Good Cloud Engineer use codeblock for both code and errorrs that appear in the console.

```bash
class CustomError < StandardError
end

def example_method
  # Some condition that triggers the error
  raise CustomError, "This is a custom error message."
end

# Example usage
begin
  example_method
rescue CustomError => e
  puts "Caught an error: #{e.message}"
end
```

> Here is an example of using a code for an appear in bash.

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Makdown to have a list where yoiu can check off items.

- [x] Finish Step 1
- [] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (optional)

Github flavored markdown supports emoji shortcodes. Here are some exapmles ;

| Name | Shortcode | Emoji |
| --- | --- | --- |
| cloud | `:cloud:` | :cloud: |
| cloud | `:cloud_with_snow:` | :cloud_with_snow: |
| cloud | `sun_behind_small_cloud` | :sun_behind_small_cloud: |

## Step -5 - How to make a table

You can use the following markodwn format to create a table.

```md
| foo | bar |
| --- | --- |
| baz | bim |
```

Github extends the functionality of MArkdown tables to provide more alignment and table cell formatting option. [<sup>(5)</sup>](external-references)


## Step 6 - 

## external Reference 
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github)<sup>(1)</sup>
- [Github flavored markdown](https://github.github.com/gfm/)<sup>(2)</sup>
- [GFM](https://github.github.com/gfm/#task-list-items-extension-)<sup>(3)</sup>
- [GFM - Emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)<sup>(4)</sup>
- [GFM - Tables](https://github.github.com/gfm/#tables-extension-)<sup>(5)</sup>





