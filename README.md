#Branch Structure Description 

##dev  
    -Aesthetic change: message to player in main class.

##feature1
    -Quit game functionality in GameEngine class. Makes changes/creates to makeGuess(), reset(), hasUserQuit();
    -Loop to play game again in main class. 
    -Aesthetic change: "try again" when player gets answer wrong in makeGuess().
    -Dev comment on version of feature quit.

##feature2
    -Aesthetic change: message to player in main class, same as dev branch change. 
    -Max attempt functionality. Additions to GameEngine constructor, makeGuess(), isGameOver(), getMaxAttempts().
    -Logic for max attempts added to makeGuess() in GameEngine class. Changes if/else statements.

##feature3
    -Hint functionality created. Methods added: isHintEnabled, setHitsEnabled, getHint. 
    -Implemented hint logic into if/else statement of makeGuess().
    -Changes return.

##hotfix
    -Corrects acquiring random int to within appropriate range. 