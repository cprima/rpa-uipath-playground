# rpa-uipath-playground: param dev prod

The Main process has an input argument of type string with a default "dev".

On the main sequence's scope a variable of type array of strings holds "dev","prod".

Within a try/catch block an if conditions tests for the inpout argument being contained in that array.

It if does not consist then an alert of level FATAL is raised and a system exception thrown.


## Usage

Run job via orchestrator, set as parameter e.g. "foobar" and observe the process failing.

