... this is just a visual comment (does not run) ...

# 📥 Input
name = ask=str="What is your name?"
age  = ask=num="Enter your age"

# 🎲 Random values
x     = random[1 to 10]
fruit = random["apple,banana,grape"]

# 🖨️ Output
show "Hello" @name
show "You are" @age "years old"
show "Your random number is" @x
show "Your random fruit is" @fruit

# ⚖️ Conditional logic
if @x is @age
  show "Your guess equals your age!"

or @x not @age
  show "Your guess does not equal your age."

or
  show "Fallback if none of the above ran."

# 🔄 Other comparisons
if @age is above [60]
  show "Elder!"

if @age is below [13]
  show "Kid!"

if @age between[13 to 19]
  show "Teen!"

# 🧠 Accessing variables
show "Name:" @name
show "Age:" @age

# 🚫 `...` blocks are used as comments only
... 
this is a fake block comment
...



#completely free do whatever you want with it
