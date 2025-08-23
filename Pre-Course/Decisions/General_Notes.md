# Decisions
In most algorithms, there is a natural point where you need to make a decision on what to do next based on some criteria. When you find yourself using words like "if," "when," or "unless," it's an indication that you've reached a decision point.

*Examples:*
- If the forecast predicts rain, then you want to take an umbrella
- You buy cookies and ice crean unless grandma is in town, then you buy cherry ice instead
- You're buying pizza for dinner and usually choose supreme. However, if Rylie and Ash are coming to dinner, they prefer veggie deluxe. If Jo is coming, they only eat cheese pizza.

## Yes or No:
When you add a decision to a process, frame it as a yes or no question - this forces the response to be one of only two options. This is an example of a *binary choice.* 

> **_Note:_** By limiting the possible responses, you make it easier to outline the process flow.

*Examples:*
- Is the forecast predicting rain? Yes, then take an umbrella. No, do nothing.
- Is Grandma in town? Yes, buy cherry ice. No, buy cookies and ice cream.
- is Joe coming to dinner? Yes, buy cheese pizza. No, then is Rylie or Ash coming to dinner? Yes, buy veggie deluxe. No, buy a supreme pizza

> **_Note:_** Notice the last example has two "if" statements that become two questions.

## Adding a yes or no decision (Process):
The symbol that indicates a decision in a process is a diamond shaped block. This block has two arrows pointing outward: One labeled "Yes" and one labeled "No"

Here are three different types of decisions that you might encounter in a process:
- If yes (or no) do a thing, otherwise, do nothing and continue the process.
- if yes, do a thing, otherwise do another
- if yes, do a thing, otherwise ask another question to decide what to do.

## Something or Nothing:
This lesson will focus on one type of decision: a something-or-nothing choice.

---
**Example:**

Start > Pick Up Keys > Pick up Wallet > Leave the House > End

This process might work well for a while, but after beign soaked in the rain, you decide you need to start checking the weather.

When two points join together, you use a connector pieve (a small gray circle) to combine them into a single path!

---

## One Thing or the Other:

This lesson focuses on one-thing-ot-the-other decisions in which you chose between two alternate paths.

---
**Example:**

Similar to before, but adds stepts irregardless of if you say yes or no!

Using this type of process **ALWAYS** skips one or more steps in a process.

---

## Decisions with Muiltiple Criteria:

When you compbine criteria in a decision, you use either the word "and" or "or" depending on the situation.

When you use the word "and," you need to meet **both** (or all if there are more than two) of the criteria for the decision.

When you use the word "or," you need to meet **any** criteria.

## Multiple Decisions:

The order of decisions can be very important **so be careful**!

## Loops:
A loop allows you to repeat steps multiple times in a process without requiring you to duplicate the same process steps multiple times in a process diagram. There are three distinct patterns for loops. You may need to repeat steps:
- While or until some condition is true, such as while two cards have the same rank
- A fixed number of times, for example doing 10 reps of an exercise.
- For each item in a group, like doing something for each person in a class.

There is no designated symbol in a process diagram for loops.

*Using a Loop in a Process Diagram:*
- The decision **must** ask a yes or no question
- You must use a connector **before** the decision

## Repeat While:
While or Until:

These two words are both indicators that you want to use the **repeat while** pattern. With some slight wording adjustments, you can switch between using "while" and "until," but retain the same overall meaning.

*Example:*
Imagine you're teaching someone to drive. You might tell them:
- While the light is red, wait.
- Until the light is green, wait.
- While the light is red, wait until it turns green

*Note:* It is preferred in processes to use "while"

"**Divide and Conquer**" approach is called a **binary search**

*Example:*
- Guess a number between 1-100
- You guess 50
- They say "Higher"
- You guess 75
- They say "Lower"

etc. until you get the correct number

## Repeat *n* Times:

The repeat while loop is still the foundation here.

For repeat *n* loops, you set a goal in your algorithm and add 1 to a counter. You set your loop to end once the counter is equal or (or greater than, depending on circumstance) your goal. 

*Note:* Something must change in the path that loops up to the decision and eventually causes a loop to end. If the thing causing the loop to end is forgotten, you'll end up in an **infitite loop**. This is a common bug in programming.

## Repeat for Each:
The repeat while loop is still the foundation.

For repeat for each processes, you use a marker variable to track which item you are holding. This marker variable is often referred to as an **Index** (you can rename the variable to whatever you want)

Wiuthin your loop, you need to adjust the marker so that it refers to the next item, and the decision checks to see if there are any items left in the group to reference.

## Bubble Sort:
Bubble sort is another type of sorting algorithm like binary sorting. It's called a bubble sort because it appears to bubble values towards the top, or the end, of the list.

---
**Example:**
Sort the following alphabetically:
- Girlhood
- Dear Ex
- Wadja
- Solaris
- A Silent Voice

For bubble sorting, you compare the first two items (i.e. "Girlhood" and "Dear Ex") and determine if they are in the correct order. They are not, so you switch them You then compare the next two items (i.e. "Girlhood" and "Wadja") and switch if necessary. Then, you compare the next two (i.e. "Wadja" and "Solaris") and switch them again if applicable. and so on and so fourth until you reach the end. After one round of bubble sorting this example, you end up with:

- Dear Ex
- Girlhood
- Solaris
- A Silent Voice
- Wadja

*Note:* The highest "value" sank to the bottom, and the lowest "value" rose closer to the top. Your highest value with **always** be the very last one after 1 pass, so each pass allows you to check one less item. Pass 2 would be:
- Dear Ex
- Girlhood
- A Silent Voice
- Solaris
- ~~Wadjda~~

*Note:* Notice that Wadjda is sticken through - there is no need to check it again after the first pass, as you know the highest value has always moved to the bottom after pass one. After pass 2, the second highest value is now in the correct place, so pass three would be:
- Dear Ex
- A Silent Voice
- Girlhood
- ~~Solaris~~
- ~~Wadjda~~

The total number of passes is always one less than the total number of items in the list, so a repeat *n* times loop is best for the **outer loop**.

The fourth and final pass returns this result:
- A Silent Voice
- Dear Ex
- Girlhood
- Solaris
- Wadjda