# Bio program that accepts input from the user and outputs a bio with that information

puts "Welcome to my Madlib program. Tell me about yourself!"
print "What's you name?"
name = gets.chomp 
print "How old are you?"
age = gets.chomp
print "What do you do for a living?" 
job = gets.chomp
print "Where to you live?" 
location = gets.chomp 
print "How long have you lived there?"
length = gets.chomp
puts "My name is "+ name 
puts "I am " + age +  "years old"
puts "I am a " + job + "and I have been living in " + location + "for" + length
