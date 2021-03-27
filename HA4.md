## Homework Assignment 4 - Experiments - Due Tuesday April 6, 11:59 PM

Version History: 

- Released 2020/3/27

This assignment is due Tuesday April 6, 11:59 PM.

Create your homework repository in github classroom:
[https://classroom.github.com/a/fwYDiNIL](https://classroom.github.com/a/fwYDiNIL).
At the time of submission, it should contain a PDF, Markdown, or HTML file
with the bulk of your answers and a JS or Python file to accompany the last question.
Both files should be named `HA4` with the appropriate extension and have your
name at the top. You may include other files, e.g., a spreadsheet file, as
supplementary material.

In your PDF, MD, or HTML file, please complete the following problems below.
Each problem will specify what should be shown. If your solution requires
multiple calculations and you are using a spreadsheet or other program to
help, please clearly label what is going on in each step in a way that can be
seen without interacting with the program. 

Example 1: If you use a spreadsheet, each sub-result should have a label
next to it explaining what the sub-result is and how it was calculated,
visible in the PDF/MD/HTML, even if you include the spreadsheet file. I should not
have to open the spreadsheet file to see what it is. 

Example 2: If you use a script, each sub-result should have a comment above it
explaining what it is and what the code does to generate it.


### Section A: Experiment Design

For each of the scenarios A.1 and A.2, describe an experiment that tests the
idea in question. Describe:

- the independent variables and their conditions in the experiment and your
  justification/explanation for each (3 pts)
- dependent variables and your justification/explanation for each (3 pts)
- control variables, random variables, and confounding factors and your
  justification/explanation for each (5 pts)
- the population, how participants would be drawn from it, how many would
  participate, and how they would be assigned to trials (3 pts)
- the type of tasks the participants would perform, where the differences
  in trials would arise from (e.g., what changes in data?), and what order the
  trials would be given in (4 pts)
- your data analysis procedure including whether you would prune data points
  (and why) and what statistical tests you would use to analyze the collected
  data (and why) (3 pts)
- the limitations of your study, why may it not apply to someone else's
  similar problem? (4 pts)

If there are multiple possible criteria / interpretations to the scenario,
choose one that you think is among the most important, describe what it is,
explain why it is important, and design the rest of the experiment (e.g.,
tasks, variables) with that particular criteria / interpretation in mind.

In some cases, your answer may be dependent on information you do not know but
could discover in piloting. In those cases, note where you would pilot and
what you would determine from the pilot for your answer.

See lecture slides list statistical tests that can be used for greater than
two conditions.

#### A.1 Preview Text on a Tutorial Site

How much text should be shown to preview an article on a tutorial site?


#### A.2 "Sweets"

Suppose you're a product manager at a social media company. Your company has
just launched a new feature called "sweets" which are special posts designed
for sharing content about your meals. To encourage users to try this new
feature, you add a new icon too the default posting UI. One icon is shaped
like candy, the other shaped like a case slice. Which icon is better for
encouraging users to try the new feature?


#### A.3 Number of Participants (EXTRA CREDIT: 10 pts)

Suppose you are planning a within subjects experiment to determine if there's
a meaningful difference in speed between using a finger or a stylus on a touch
interface for a mobile game. You plan to give participants some tutorial-type
actions to do on screen. From piloting, you estimate that drawing with a
finger takes an average of 9 seconds to perform the task with a standard
deviation of 1.5 seconds. From this data you are also comfortable with assuming the
distribution is normal. You consider a difference in order time of 20%
meaningful. How many participants do you need for your experiment assuming the
commonly accepted level of significance and power? How many participants would
you need if a difference of 10% was meaningful?

You may calculate this yourself or use a tool (including online). If you
calculate this by hand, include any reference material you used and describe
each step in the calculation. If you use a tool, explain why you chose the
tool, what settings you used, and why. Include screenshots. Also, include the
URL if the tool is online. In either case, if you had guidance (e.g.,
StackOverflow post), cite that guidance.


### Section B: "By-Hand" Statistical Analysis

For Problems B.1 & B.2:

1. State what statistical test should be used. (3 pts)
2. Calculate the test statistic. Show your work (10 pts):
  - evidence/argument of meeting test assumptions
  - significance (alpha)
  - degrees of freedom where applicable
  - the test statistic to be compared again
  - major intermediary calculation where applicable, e.g., sample mean,
    sample standard deviationns, observed outcomese, expected outcomes.
3. State where there is a statistically significant difference. (2 pts)

You may use an existing tool to calculate the sample mean and sample standard
deviation (if required), as well as perform any basic arithmetic operation
(addition, subtraction, multiplication, division, square root, etc.) 

**You may not use a tool geared towards doing the entire statistical test for
you.** You may however verify your result using a program that performs the
test directly. If you choose to do this, you must still include the
sub-results as described above. Note that in class, we used the Student's t test
for both paired and independent unequal variance samples. The latter is often
replaced by the Welch's t test in practice, and thus stats programs may
perform the latter. You may choose to do the latter by hand when applicable
but if you do so, please make it clear.

The experiments and data described in this section are fictional and for
educational purposes only. 

#### B.1 


A manufacturer of third party gaming controls runs an experiment to compare
their new software-assisted button-press detection to the more traditional
standard button-press detection. In the experiment, 20 participants were asked
to play a simple test game. The controller switched between standard mode and
software-assisted mode between rounds of the game. The order of trials was
randomly set per participant. Through a series of tasks, a measure of time per
round in the game was recorded as follows: 


Standard: [27.9, 21.2, 21.4, 19.8, 25.6, 16.1, 28.2, 20.7, 24.0, 22.3, 27.4, 16.8, 22.0, 21.8, 26.4, 19.7, 22.5, 20.4, 23.1, 24.7]

Software-Assisted: [22.7, 29.4, 28.7, 27.5, 28.7, 23.9, 25.6, 23.2, 25.2, 27.6, 23.9, 24.8, 23.9, 23.5, 24.0, 26.0, 22.6, 26.7, 31.0, 28.2]

Is there a significant difference in how long participants took each round between the two modes? 

### B.2 Email Reading

An HR department is testing the use of emoji in subject lines.  The department
wants to know if adding an emoji to the subject line results in more
employees opening the email. They randomly select 800 employees for an
experiment, 400 of which receive the normal email with a smile emoji and 400
will receive without. In post-processing the data, a few users weer removed
because they left the company during the experiment period. The data kept
indicated that 141 people opened the email of the 395 who saw the emoji and
159 people opened the email of the 398 who did not see the emoji

Is there a significant difference how people who saw the emoji behaved versus
those who did not?


### B.3 Bootstrap Confidennce Intervals: Navigation

Designers ask participants to rate how much they like each of three styles
for browsing a photo app: Album, Bento-grid, and Carousel. The tasks were
completed by 20, 17, and 21 participants respectively. The following ratings
were recorded:

Album: [9.2, 7.1, 7.2, 6.7, 8.5, 5.6, 9.3, 7.0, 8.0, 7.5, 9.0, 5.8, 7.4, 7.4, 8.7, 6.7, 7.5, 6.9, 7.7, 8.2]

Bento: [5.1, 8.0, 7.7, 7.2, 7.7, 5.6, 6.3, 5.3, 6.2, 7.2, 5.6, 6.0, 5.6, 5.4, 5.6, 6.5, 5.0]

Carousel: [5.4, 7.5, 6.1, 4.7, 3.7, 3.9, 7.5, 5.1, 4.0, 5.3, 8.2, 5.2, 5.9, 5.5, 4.5, 3.3, 4.5, 4.7, 5.9, 6.3, 6.4]


a) Calculate 95% bootstrap confidence intervals as described in class. Use
5,000 resamples. You may use Javascript or Python, but you may not use a
library method that directly calculates them for you. (You may use libraries
for randomization, taking the mean, percentiles, etc.) Include your code in a
separate file.  This code does NOT have to follow any specific architecture
like MVC. (12 pts)

**Tip:** If you use Python, use a `seed` function (e.g., `numpy.random.seed`)
to set a seed value for the random number generator. This allows you to get
reproducible results even with random calls, making things easier to debug.
Unfortunately, no such functionality exists for Javascript's `Math.ranndom()` 

b) What are the confidence intervals of the conditions (in interval format)? (3 pts)

c) Plot the confidence intervals. (3 pts)

d) What can be inferred from these intervals? (2 pts)
