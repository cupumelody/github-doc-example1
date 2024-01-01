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

![wJvjd](https://github.com/cupumelody/github-doc-example1/assets/145847069/85dcfdc7-16cc-45f8-863a-3825267c5e1b)
