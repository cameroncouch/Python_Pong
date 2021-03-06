<h1>Pong</h1>

<h2>Bug list</h2>
<ul>
<li>Ball/Paddle collision conditional is inaccurate, causing collision to
detect only at the middle of the paddle. The entire vertical surface of the 
paddle should register as a valid collision point</li>
</ul>

<h2>Features to add</h2>
<ul>
    <li>Serve. To begin the game the ball should start at 0, 0 and the player will press space
    bar to initiate play</li>
    <li>Play to score. Prior to beginning the game, the players should be able to
    choose a score that will end the game once either player reaches it</li>
    <li>Player adjustable ball speed</li>
    <li>Player adjustable paddle speed</li>
    <li>Menu screen</li>
    <li>Play vs Computer</li>
</ul>
<h2>How to play</h2>

<p>Players move their paddles up and down on the screen to block the incoming
ball from entering their goal zone. It's a retro battle of reflexes!</p>

<table>
    <th>Controls
        <tr>
            <td>Player 1 (Left)</td>
            <td>Player 2 (Right)</td>
        </tr>
        <tr>
        <td>W : Up</td>
        <td>&#8593; : Up</td>
        </tr>
        <tr>
            <td>A : Left</td>
            <td>&#8592; : Left</td>
        </tr>
        <tr>
            <td>S : Down</td>
            <td>&#8595; : Down</td>
        </tr>
        <tr>
            <td>D : Right</td>
            <td>&#8594; : Right</td>
        </tr>
    </th>
</table>

<h2>Notes</h2>
<p>This was built by following the Free Code Camp tutorial</p>
<p>Written with Python3 and the Turtle Module</p>
<p>Sound effects were created by myself, using <a href="https://www.pulseboy.com">Pulseboy</a></p>