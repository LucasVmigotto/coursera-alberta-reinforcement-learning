Cleaning bot
    States: LIDAR to detect space environment.
    Actions: movements (in any four basic directions, rotate in own center or wait).
    Rewards: 1 for each clean room, decrease of -0.1 for every time step to encourage speed in cleaning, -1 for collisions with furniture, individuals or pets.

Music recommendation
    States: user time spend listening to the recommended song, like or dislike given by the user.
    Actions: start a new song or already listen song.
    Rewards: -1 if the user skips the song, 0 if the user wait until the first half, 0.1 if the user add it in some playlist, 1 if the user like it, -1 otherwise.

Facial recognition
    States: Image collected from a network camera system.
    Actions: Detect and identify the person as target or, based in probability of certainty, highlight the individual for human check.
    Rewards: 1 if correct identification, decrease of 0.5 if need human confirmation and -1000 for miss identification.
