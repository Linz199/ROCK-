# ROCK-
Futfkll
class Person
  attr_accessor :name, :age

  def initialize(name, age)
    @name = name
    @age = age
  end
end

# Creating an instance of Person
person = Person.new("Alice", 30)

# Using getter methods
puts person.name  # Output: Alice
puts person.age   # Output: 30

# Using setter methods
person.name = "Bob"
person.age = 25

puts person.name  # Output: Bob
puts person.age   # Output: 25
