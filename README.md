Thank you for your interest in CogoLabs.
---------------------------------------
This is a small problem we would like you to solve so that we may better understand your coding ability.

### Criteria
We will be looking at your problem-solving ability, code quality, cleanliness, and professionalism.

### Project
We would like you to create a web-based ranking system for a darts league. Minimally-outlined html, css, and javascript files have been provided for you.

### Rules
* After each player takes her/his turn, their name and score is entered into the text input in the format `name, score`.
* Clicking `Add to Rankings` parses the contents of the form field and adds the output to the rankings.
* The rankings should be appended to `ul#rankings` and formatted to meet the example output below.
* Players with the same score are 'tied', and should have the same rank.
* Players can take any number of turns. The results of multiple turns are added to the players score.

### Example
The following game should produce the specified output.

#### Game:
```
Apollo, 10
Number 6, 1
Cmdr. Adama, 27
Gaius Baltar, 7
John Cavil, 0
Apollo, 20
Gaius Baltar, 20
Starbuck, 42
```

#### Results:
```
1. Starbuck, 42 pts
2. Apollo, 30 pts
3. Cmdr. Adama, 27 pts
3. Gaius Baltar, 27 pts
5. Number 6, 1 pt
6. John Cavil, 0 pts
```

### Guidelines
* You may use any javascript libraries you wish, but none are required.
* Please do not use a large framwork like Angular, Ember, Knockout. We want to see how *you* write code.
* Use Backbone is allowed.
* Please do not include library source code in your application-instead use Bower or link to a CDN.
* jQuery and lodash have been included in the source for you to use if you wish to use them.
* Please don't use CoffeeScript, or the compiled coffee-javascript.
* If you are using a build tool (eg Yeoman, Grunt, etc), please submit the the code as-authored, as well as any compiled production files.

### Browser Support
We will test your application in Chrome. Please use code that would work in any modern browser. Don't stress about IE < 10.

### Bonus
* Writing automated tests for your code.
* Creating a pleasing UI.
* Toggle between multiple games.
* Adding the ability to add the results of multiple games at once.
* Submitting your project as a github repo.
* Surprise us!



