# MODE Coding Exercise

Thank you for taking the time to work on this coding exercise.

To kick off the interview process, we'd like to evaluate your fundamental coding skills.
Our engineers will review your code for correctness, efficiency and readability.
This exercise should not take more than a few hours to finish.

After completing the exercise, please check your code into a repo under your personal
Github account. (Please keep this repo **private** to maintain the confidentiality of this process.)
Please also add the Github user [`tinkermode`](https://github.com/tinkermode) as a
collaborator of your private repo. This gives our team access to your code.

In our previous email to you, you should find a submission link at the end. Click the
link to open the submission form. Copy and paste your repo URL into the "Notes" section of
the form and submit. Our team will be notified to review your answers.

Normally, we expect candidates to submit their answers within 24 hours of receiving the exercise.
If you have questions about this exercise, or need additional time due to unforeseen circumstances,
feel free to contact us.

Thank you again for your time. Good luck!

*&mdash;The MODE team*

<hr>

## The Question

Write a function that draws a cube of a given height in the form of "ASCII art".
The function should take the height as an argument and print out the result. The height
must be an integer with value greater than zero. (The function should return
an error if an invalid height is passed to it.)

The following are some example outputs this function should produce.

```

> drawCube(1)
  +--+
 /  /|
+--+ +
|  |/
+--+

> drawCube(2)
  +----+
 /    /|
+----+ |
|    | +
|    |/
+----+

> drawCube(3)
   +------+
  /      /|
 /      / |
+------+  |
|      |  +
|      | /
|      |/
+------+

> drawCube(4)
   +--------+
  /        /|
 /        / |
+--------+  |
|        |  |
|        |  +
|        | /
|        |/
+--------+

> drawCube(5)
    +----------+
   /          /|
  /          / |
 /          /  |
+----------+   |
|          |   |
|          |   +
|          |  /
|          | /
|          |/
+----------+

```


While we prefer Go and JavaScript (Node.js), as we use them in most of the projects at MODE,
you may write your function in the language of your choice, as long as it is not too exotic.
