#Real FizzBuzz

###Step 1

Write some code that prints out the following for a contiguous range of numbers:

 - the number

 - `fizz` for numbers that are multiples of 3

 - `buzz` for numbers that are multiples of 5

 - `fizzbuzz` for numbers that are multiples of 15

 
e.g. If I run the program over a range from 1-20 I should get the following output

    1 2 fizz 4 buzz fizz 7 8 fizz buzz 11 fizz 13 14 fizzbuzz 16 17 fizz 19 buzz

###Step 2

Enhance your existing FizzBuzz solution to perform the following:

* If the number contains a three you must output the text 'lucky'. This overrides any existing behaviour.

e.g. If I run the program over a range from 1-20 I should get the following output

    1 2 lucky 4 buzz fizz 7 8 fizz buzz 11 fizz lucky 14 fizzbuzz 16 17 fizz 19 buzz

###Step 3

Enhance your existing solution to perform the following:

* Produce a report at the end of the programme showing how many times the following were output

** fizz

** buzz

** fizzbuzz

** lucky

** an integer

e.g. If I run the program over a range from 1-20 I should get the following output:

 1 2 lucky 4 buzz fizz 7 8 fizz buzz 11 fizz lucky 14 fizzbuzz 16 17 fizz 19 buzz
 
 fizz: 4
 buzz: 3
 fizzbuzz: 1
 lucky: 2
 integer: 10

 (Integer is 10 because there were 10 numbers that were not altered in any way).

###Step 4 (bonus step and not required)

Refactor you implementation to use `yield`.

###Notes

Avoid spending a large amount of time on this exercise. This is designed to a straightforward coding exercise.

Things we are looking for:

 - Test Coverage: The solution should be developed “test-first”, and should have excellent unit test coverage.

 - Simplicity: We value simplicity as an architectural virtue and a development practice. Solutions should reflect the difficulty of the assigned task, and should not be overly complex. Layers of abstraction, patterns, or architectural features that aren’t called for should not be included.

 - Self-explanatory code: The solution you produce must speak for itself. Multiple paragraphs explaining the solution are a sign that the it isn’t straightforward enough to understand purely by reading code, and are not appropriate.