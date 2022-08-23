# Fighting-game
Game simulates fight between two samurais. All main logic was written on Java Script.

<ol>
  <li> Img folder contains sprites of background, environment, character moves.</li>
  <li> index.html include UI elements: health bars, timer and canvas.</li>
  <li> In js folder you can find 2 files:</li>
  
    3.1 utils.js keeps some helper-functions using for clean code.
    
    3.2 classes.js keeps two main classes: parent class Sprite and child class Fighter. The first one is used for positioning and animation. The second has methods for character control.
  <li> index.js is main file where objects of background, shop and two characters are declared, is used render function and is coded some additional logic.</li>
</ol>

<h3>Game rules:
</h3>
<ol>
  <li>You can play this game with one partner only on one keyboard.
  <li>One person plays for samurai Mack (on the left side) and second plays for samurai Kenji (on the right side). The firts character hits slowlier than the second but has more attack range.
  <li>Goal off the game is to kill your opponent or to have more health than enemy when timer goes to 0.
</ol>
<h3>
Controller keys:
</h3>

For samurai Mack:

    a - left movement

    d - right movement

    w - jump

    f - katana attack

For samurai Kenji:

    leftArrow - left movement

    rightArrow - right movement

    upArrow - jump

    downArrow - katana attack
