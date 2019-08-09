# liri-node-app


LIRI is a Language Interpretation and Recognition Interface. 
LIRI is a command line node app that takes in parameters and gives back data. 
The user has the option of using four commands (listed below) in conjuntion with specific parameters associated with the commands. The Commands are:

* `concert-this`

* `spotify-this-song`

* `movie-this`

* `do-what-it-says`

---

## HOW TO USE
**Instance 1**: Run the `concert-this` command
    
    node liri.js concert-this <name of artist or band>
    
Output: The system will display a list of all events and locations where the artist or band will perform. It can result in multiple records. The system will also log all the results in the log.txt file.


---

**Instance 2**: Run the `spotify-this-song` command
    
    node liri.js spotify-this-song <name of song>
    
Output: The system will display a list of information associated with the song. It can result in multiple records. The system will also log all the results in the log.txt file.


**Instance 3**: Run the `movie-this` command
    
    node liri.js movie-this <name of movie>
    
Output: The system will display information associated with the movie. The system will also log all the results in the log.txt file.


**Instance 4**: Run the `do-what-it-says` command
        
    node liri.js do-what-it-says
        
Output: The system will read the text in the random.txt file, and perform the comman listed in the random.txt file. 

---

## TECHNOLOGIES ARE:
* Javascript
* Nodejs

## Node packages:
    * Node-Spotify-API
    * Request
    * Moment
    * DotEnv
* APIs used:
    * Bands in Town
    * OMDB


