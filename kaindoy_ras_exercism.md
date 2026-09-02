**Name:** Rose Antonette S. Kaindoy\
**Section:** 1\
**Score:** your tallied point total across all entries below

**Template**\
**Exercise:** name of the exercise\
**Link:** link to your published solution for this exercise\
**Difficulty:** Easy, Medium, or Hard, with its corresponding point value in parentheses (e.g. "Medium (20 points)")\
**What problem does this exercise solve?**\
your answer here\
**What concepts or language features did you use?**\
your answer here\
**Where did you struggle and how did you resolve it?**\
your answer here

**Exercise:** Raindrops\
**Link:** https://exercism.org/tracks/go/exercises/raindrops/solutions/rskaindoy \
**Difficulty:** Easy (10 points)\
**What problem does this exercise solve?**\
The exercise solves the problem of identifying a number's divisibility by 3, 5, and 7 and producing the appropriate corresponding output.\
**What concepts or language features did you use?**\
I used Go's `strconv` package and its `Itoa()` function to convert an integer to a string. I also used an array to store the given sounds, `if` conditions with the `%` operator for divisibility checks, and string concatenation to combine the sounds.\
**Where did you struggle and how did you resolve it?**\
I struggled at first with how to convert an int to a string because I didn't know that  `Itoa()` function existed. I resolved this by looking up Go's built-in libraries and learning how to use `strconv.Itoa()`.

**Exercise:** Two Fer\
**Link:** https://exercism.org/tracks/go/exercises/two-fer/solutions/rskaindoy \
**Difficulty:** Easy (10 points)\
**What problem does this exercise solve?**\
The exercise solves the problem of generating the correct message when sharing a cookie with someone, depending on whether their name is known or unknown.\ 
**What concepts or language features did you use?**\
I used `len()` to check the input string's length to determine whether it was not empty, and string concatenation with the `+` operator.\
**Where did you struggle and how did you resolve it?**\
I did not struggle with this exercise, as I was able to understand and implement the required logic.

**Exercise:** Collatz Conjecture\
**Link:** https://exercism.org/tracks/go/exercises/collatz-conjecture/solutions/rskaindoy \
**Difficulty:** Easy (10 points)\
**What problem does this exercise solve?**\
The exercise solves the problem of determining how many steps are required for a given positive integer to reach 1 using the rules of the Collatz Conjecture.\
**What concepts or language features did you use?**\
I used the `errors` package for handling invalid inputs, a `for` loop structured like a `while` loop,  and the `%` operator to check divisibility.\
**Where did you struggle and how did you resolve it?**\
I initially didn't check the input limitations, specifically that the input must be a positive integer. I resolved this by adding a check for invalid inputs and returning an error when the input is less than or equal to 0.

**Exercise:** Word Count\
**Link:** https://exercism.org/tracks/go/exercises/word-count/solutions/rskaindoy \
**Difficulty:** Easy (10 points)\
**What problem does this exercise solve?**\
The exercise solves the problem of counting how many times each word appears in a given subtitle while accounting for capitalization, punctuation, whitespace, contractions, and numbers.\
**What concepts or language features did you use?**\
I used a `map[string]int` to store each word and its frequency, a `for` loop with `range` to go through each character, the `strings` package to convert the phrase to lowercase, and string concatenation to build each word.\
**Where did you struggle and how did you resolve it?**\
I initially struggled with handling apostrophes because apostrophes in contractions should be kept while apostrophes used as punctuation should not. I resolved this by checking whether an apostrophe had a word character on both sides before including it in a word.

**Exercise:** Reverse String\
**Link:** https://exercism.org/tracks/go/exercises/reverse-string/solutions/rskaindoy \
**Difficulty:** Easy (10 points)\
**What problem does this exercise solve?**\
The exercise solves the problem of reversing the characters in a given string. \
**What concepts or language features did you use?**\
I used the `rune` data type to work with individual characters in a string. \
**Where did you struggle and how did you resolve it?**\
I initially struggled with the `rune` data type because I was unfamiliar with how Go represents characters. I resolved this by learning how `rune` can be used to work with individual characters in a string.

**Exercise:** Leap \
**Link:** https://exercism.org/tracks/go/exercises/leap/solutions/rskaindoy \
**Difficulty:** Easy (10 points)\
**What problem does this exercise solve?**\
The exercise solves the problem of determining whether a given year is a leap year.\
**What concepts or language features did you use?**\
I used the `bool` data type for the first time, as well as `else if` statements and the `%` operator to check for divisibility and determine whether the year follows the rules for leap years. \
**Where did you struggle and how did you resolve it?**\
I struggled with Go's case sensitivity and resolved it by using lowercase `true` and `false`.

**Exercise:** Darts\
**Link:** https://exercism.org/tracks/go/exercises/darts/solutions/rskaindoy \
**Difficulty:** Easy (10 points)\
**What problem does this exercise solve?**\
The exercise solves the problem of calculating the correct score based on the dart's position on the target.\
**What concepts or language features did you use?**\
I used the Pythagorean theorem to calculate the dart's distance from the center of the target.\
**Where did you struggle and how did you resolve it?**\
I initially struggled with determining how to use the dart's `x` and `y` coordinates to calculate its distance from the center. I resolved this by using Pythagorean theorem and comparing the resulting distance with the target's scoring regions.

**Exercise:** Allergies\
**Link:** https://exercism.org/tracks/go/exercises/allergies/solutions/rskaindoy \
**Difficulty:** Medium (15 points)\
**What problem does this exercise solve?**\
The exercise solves the problem of determining a person's list of allergies depending on their allergy score.\
**What concepts or language features did you use?**\
I used the concept of bitwise AND `&` to add the bits of each item's allergy score to determine the allergy/ies of a person. I also used an array of string and learned the use of `struct`.\
**Where did you struggle and how did you resolve it?**\
I struggled with how to ...

