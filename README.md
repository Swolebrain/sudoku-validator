# sudoku-validator
<h1>Usage:</h1>

<code>
  var board = new Sudoku([
      [7,8,4,  1,5,9,  3,2,6],<br>
      [5,3,9,  6,7,2,  8,4,1],<br>
      [6,1,2,  4,3,8,  7,5,9],<br>
      [9,2,8,  7,1,5,  4,6,3],<br>
      [3,5,7,  8,4,6,  1,9,2],<br>
      [4,6,1,  9,2,3,  5,8,7],<br>
      [8,7,6,  3,9,4,  2,1,5],<br>
      [2,4,3,  5,6,1,  9,7,8],<br>
      [1,9,5,  2,8,7,  6,3,4]
  ]);
  
  
  var userWasRight = board.isValid();
</code>

<h1> Getting a random board:</h1>
<p> Either get it and parse it yourself from http://davidbau.com/generated/sudoku.txt,

or get the version that's already converted to an array by sending a get request to http://www.swolebrain.com:4004/sudoku</p>

<h1>Part 1</h1>
<ol>
  <li>Create a layout for your game with a 9x9 grid</li>
  <li>After the HTML is ready, load the empty sudoku game from the restful endpoint http://www.swolebrain.com:4004/sudoku</li>
  <li>Use the 2-D array returned by this endpoint in order to set your HTML board to its starting state</li>
</ol>


<h1>Part 2</h1>
<ol>
  <li>Create a validation button</li>
  <li>When the user clicks this button, use the code in this repo to validate their input</li>
  <li>You will have to create a 2-D array based on the content of the input boxes in your html</li>
</ol>