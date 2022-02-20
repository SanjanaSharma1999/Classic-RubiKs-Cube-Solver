# Classic-Rubics-Cube-Solver
<h3><strong style="color:blue;font-size:40px;font-family:serif;">Features</strong></h3>
<p style= "font-family:Georgia;color:#000000;font-size:110%;">
<h5>>🏻 User or program generated scrambles</h5>
<h5>>🏻 The ability to make custom moves</h5>
<h5>>🏻 The ability to hit either the solve button, or each step of the solve to see it solve step-by-step</h5>
<h5>>🏻 The ability to run simulations with a user defined amount of solves (be careful, too many could make the program freeze)</h5>
<h5>>🏻 Ability to copy scrambles or solutions to the clipboard, as well as view externally.</h5>
<h5>>🏻 Clicking on the 2D cube will allow you to see the other bottom tiles that are not normally visible.</h5>

<h3><strong style="color:blue;font-size:40px;font-family:serif;"><center>Various Commands</center></strong></h3>
If you don't want to use the GUI, you can also just type function commands in the interpreter. Here are some of the useful ones:
<h5>>🏿 print_cube() Prints the cube in text format</h5>
<h5>>🏿 scramble() You can either provide a number, a scramble in string format, or nothing for a 25 move default scramble</h5>
<h5>>🏿 get_scramble() Prints the previous scramble</h5>
<h5>>🏿 solve() Will solve the cube</h5>
<h5>>🏿 get_moves() Prints out the Solution that was generated upon using solve()</h5>
<h5>>🏿 simulation(num) The number provided is the amount of solves you want to simulate. Will return you the best solve with it's scramble, as well as the worst solve and it's scramble.</h5>

<h4>>The Solver itself is based upon a CFOP (Fridrich) method of solving. It solves the Cross, does the F2L step, does a 2-look OLL, and a 2-look PLL. As for notation, basic notation used in the cubing world is used, however, a counterclockwise move can be denoted with either an apostrophe (standard way), or using the letter i (denoting i for inverse).</br></h4>
