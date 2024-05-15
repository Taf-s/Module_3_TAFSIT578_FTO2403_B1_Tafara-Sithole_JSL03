# [JSL03] Project Submission: Which one is which? Declarative or Imperative?!

This is the readme file for Declarative of Imperative

## Description

The purpose of the project was to decide which code snippet was Declarative and which was Imperative. Provide justification on why we chose a certain approach for the examples given.

## Technologies Used

\*Loom

## Loom Video Link

# Presentation Talking Points

Example #: [1]

## Imperative Approach [2 Minutes]

1. **Step-by-Step Explanation:**

   The function starts off by setting the grillTemperature to 204, followed by seasoning the steak with salt and pepper. It
   then enteres a while loop which checkes the desireDoneness by measuring the steakTemperature and adjusting the cooking time
   and grillTemperature based on the steakWeight and desiredDoneness. It then finishes off by serving the steak cooking it
   further based on the steakTemperature and desiredDoneness.

   Step 1: Preheat the grill by setting the grillTemperature to 204, Step 2: Season the steak by applying salt and pepper,
   Step 3: Cook the steak by grilling it, measuring its internal temperature and adjusting the grillTemperature based on
   the steakWeight and desiredDineness , Step 4: Serve the steak checking the steakTemperature for the desiredDoneness

   The code provides explicit instructions for each action by breaking it down into steps and using comments to describe each
   step

   The variables grillTemperature and steakTemperature are used to track the state and progress of the process.

2. **Emphasis on How:**

   The Imperative approach focuses on "how" the task should be accomplished, in this case through the use of loops and
   conditional statements. With the while loop handling the cooking steak process by looping through the process to achieve
   the desires doneness based on the temperature of the steak.

   The grillTemperature and steakTemperature are mutable variables that change their values throughout the execution based
   on the cooking process and conditions. With the grillTemperature being initially set to 0 changing to 204 when preheating
   the grill and the steakTemperature, initially set to 0 changing as the steak is grilled

Example #: [2]

## Declarative Approach [2 Minutes]

1. **High-Level Process Description:** Explain the code logic in the declarative approach.

   The cooking process is defined in a declarative manner using an array named cookingProcess. Each step in the cooking
   process
   is represented by an object within the array. Each object contains properties that describe the action to be taken. The
   cooking process is executed by iterating over each step in the cookingProcess array and a switch statement to determine
   the action to be executed.

   The cooking process is structured in steps Preheat grill, Season steak, Cook steak until desired doneness and Serve steak,
   which focus on what should happen rather than how it should happen.

2. **Use of Data Structures:**

   The use of data structures is evident in the way the cookingProcess array contains objects with properties that
   represent each step in the cooking process.

   The prcoess steps are organized in a structured format through the use of a switch statement which allows the code to
   check each step's action, executing it accordingly

   - Mention any abstraction layers or functions used to encapsulate actions.

# Learning Outcome [1 Minute]

I have learned how to identify the difference between Declarative and Imperative approaches based on certain features of the
code, how the same process, in this case cooking a steak can be written in two different ways. Furthermore how to explain
each of these different approaches which will be uselful when choosing what approach to take when working on projects.
