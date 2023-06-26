# Dima Malkov

### My contact information:

* Email: d.mamalkov@gmail.com
* Phone number: +380992294145
* Instagram: Dim_rico
* Telegraf: @Mdimadimadima

### About me:
Here some new information about me. I wanna be Front end developer. I want to learn, develop and grow.
### Skils:
* HTML, CSS
* JavaScript Basic
* Git Basic
### Code example:

    var location1 = 3;
    var location2 = 4;
    var location3 = 5;
    var guess
    var hits = 0;
    var guesses = 0;
    var isSunk = false;
    while (isSunk === false) {
        guess = prompt("Ready, aim, fire! (enter a number 0-6):");
        if (guess < 0 || guess > 6 ) {
            alert("Please enter a valid cell number!");
            }   else {
            guesses = guesses + 1;

            if (guesses === location1 || guesses === location2 || guesses === location3){
                alert("HIT!")
                hits = hits + 1;

                if(hits == 3){
                    isSunk = true;

                    alert("You sunk my battleship!");
                }
            } else {
                alert("MISS!")
            }
        }
    }
    var stats = "You took" + guesses + "guesses to sink the battleship" +
        "which means your shooting accuracy was" + (3/guesses);
    alert(stats);

### English
**B1**
