
# Overview
The purpose of this project is to demonstrate a refactoring exercise and introducing unit tests to make the product more manageable and maintanable. 

### Background
This product is a walk-through of a legacy implementation of the popular "rock, paper, scissors" game, also known as [Roshambo](https://en.wikipedia.org/wiki/Rochambeau).

![alt text][logo]

### Exercise
The exercise is to add two additional options to the game: *lizard* and *spock*, as made popular by [The Big Bang Theory](http://bigbangtheory.wikia.com/wiki/Rock_Paper_Scissors_Lizard_Spock).

### Challenges
  - Large single class with large methods
  - No tests
  - Duplicated code
  - Nested `if/else` constructs
  - Mostly side effects

### Steps:
  - Add unit test scaffolding for application
  - Refactor application into isolated components
  - Add new features with tests

# Running Tests
To run any of the tests locally, from within the directory, run Gradle:
```
gradle <part>:clean <part>:test
```

# Run the Application
To run a given version of the application, build the jar and execute it:

```
gradle <part>:jar
java -jar <part>/build/lib/<part>.jar
```

[logo]: https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Pierre_ciseaux_feuille_l%C3%A9zard_spock.svg/768px-Pierre_ciseaux_feuille_l%C3%A9zard_spock.svg.png