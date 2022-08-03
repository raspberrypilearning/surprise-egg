
--- question ---

---
legend: Question 2 of 3
---

A Code Club creator has created a colour palette for their animation. The code for the colour palette looks like this:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 1
line_highlights: 
---
# Colour palette

w = (255, 255, 255) # White
y = (255, 255, 0) # Yellow
g = (30, 30, 30) # Dark grey
b = (0, 0, 255) # Blue
b = (139, 69, 19) # Brown
--- /code ---

When they run their code it does not display any blue, it only uses brown. Why is this?

--- choices ---

- ( ) The code on line 6 is incorrect. It will not produce a blue colour on the LED matrix.

  --- feedback ---

Try again. Line 6 is written correctly but there is something else wrong with the code. 

  --- /feedback ---

- (x) The code on line 6 is correct. However, when Python goes to line 7 it creates a new variable called `b` and stores the brown colour values within it. This is the variable that is access when the `b` variable is called to display the colour.

  --- feedback ---

Correct! Always use different variable names for your colours. 

  --- /feedback ---

--- /choices ---

--- /question ---
