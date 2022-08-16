## Loop the animation

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step, you will use a `for` loop to repeat the animation three times to create a 15 second animation. 
</div>
<div>
![An animation of what will be achieved by the end of this step.](images/step-four-output.gif){:width="300px"}
</div>
</div>

### Loop the animation

A `for` loop can be used to repeat a block of code for a set number of times. This animation needs to be 15 seconds long. If you count the values in the brackets of the `sleep()` function calls then you can see that the total is **5**. 

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 62
line_highlights: 64, 66, 68, 70
---
# Display Animation
sense.set_pixels(frame_1) # Set pixels using the frame_1 list
sleep(1)
sense.set_pixels(frame_2)
sleep(1)
sense.set_pixels(frame_3)
sleep(1)
sense.set_pixels(frame_4)
sleep(2)
--- /code ---

To make your animation last **15 seconds** in total, you need to repeat it **3 times**. This is because **3 x 5 = 15**.

--- task ---

Find the the comment that says `# Display animation`.

Create a new line by pressing the enter key. 

Add code to setup your `for` loop. 

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 72
line_highlights: 73-74
---
# Display Animation
for x in range(3): # Repeat the animation 
egg_animation()
--- /code ---

**Tip**: Your code will not work at the moment so don't try and run it.

--- /task ---

You need to tell Python which lines of code should be repeated three times. You can do this by indenting the code so that it sits **inside** the loop.

--- task ---

**Indent** your `egg_animation()` function call so that it sits inside the loop. 

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 72
line_highlights: 73-74
---
# Display Animation
for x in range(3): # Repeat the animation 
  egg_animation()
--- /code ---

--- /task ---

--- task ---

**Test**: Click Run to test your code. The animation should now repeat three times and play for a total of 15 seconds. 

![An animation of what will be achieved by the end of this step.](images/step-four-output.gif){:width="300px"}

--- /task ---

--- task ---

**Debug**:

I get a syntax error when I run my code!
+ Check that you code matches the code in the examples above
+ Check that you have added indents where they are needed
+ Make sure that `for x in range(3):` has a colon `:` at the end

Only some of my frames are shown multiple times:
+ Check that all the lines of code are indented.
 
--- /task ---

--- save ---