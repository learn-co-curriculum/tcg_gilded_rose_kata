# Gilded Rose Kata

## Learning Goals

- Write tests to validate some behavior
- Use tests to refactor a ruby class

## Introduction

Clone the [Gilded Rose Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata). Follow the instructions in the Readme, using the ruby folder.

1. Run the text tests with `ruby texttest_fixture.rb` to get a sense for how the class works. You can pass a number to run for more days, like `ruby texttest_fixture.rb 4`. Save a version of the text tests `ruby texttest_fixture.rb 10 > correct_version.txt`.
2. Write passing unit test cases to capture the behavior of the `GildedRose` class. Each test case should capture just one behavior. Try to write enough test cases that you've covered all of the requirements listed in the GildedRoseRequirements.
3. Refactor the class in `gilded_rose.rb`. Use your tests to make sure the code still works at each step. After your refactoring, test that running the text test still produces the same output. For example, `ruby texttest_fixture.rb 10 > refactored_version.txt` to generate the new version of the text, and `diff correct_version.txt refactored_version.txt` to compare the versions for any differences.
4. Read the blog post [Writing Good Tests for the Gilded Rose Kata](http://coding-is-like-cooking.info/2013/03/writing-good-tests-for-the-gilded-rose-kata/) and reflect on your own test cases. Were there any cases you missed? Did you use your tests effectively while you were refactoring?

## Bonus

Try the same refactoring exercise in Javascript (or another language!)
