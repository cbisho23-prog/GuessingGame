# Branch Structure Description 

## dev  
    -Aesthetic change: message to player in main class.

## feature1
    -Quit game functionality in GameEngine class. Makes changes/creates to makeGuess(), reset(), hasUserQuit();
    -Loop to play game again in main class. 
    -Aesthetic change: "try again" when player gets answer wrong in makeGuess().
    -Dev comment on version of feature quit.

## feature2
    -Aesthetic change: message to player in main class, same as dev branch change. 
    -Max attempt functionality. Additions to GameEngine constructor, makeGuess(), isGameOver(), getMaxAttempts().
    -Logic for max attempts added to makeGuess() in GameEngine class. Changes if/else statements.

## feature3
    -Hint functionality created. Methods added: isHintEnabled, setHitsEnabled, getHint. 
    -Implemented hint logic into if/else statement of makeGuess().
    -Changes return.

## hotfix
    -Corrects acquiring random int to within appropriate range. 


## Differences
    -Merge keeps commit history as messy as it is stands.
    -Rebase creates a clean history with a single base commit.
    -Cherry pick is like a surgeon's knife in a branch, removing a single commit and merging that into your code.
    -Squash allows you to cram several commits into one allowing you to house clean messy commit messages.

## Observation
    -The git log history starts with the initial commit at the bottom and works it way up through our merges, rebases, and hotfixes.
    -Commit message for merging feature1 into dev was flipped around (dev merged into feature1)
    -Since feature1 was deleted you have to follow the commit messages closely to see where it happened.
    
## Strategy Use
    -Merge is used when your commit messages follow standard practice (defined by self documentation or project team decision)
    -Rebase is good to use to clean up a messy commit history. E.g. maybe you commit to your local repo while you are working and do not fix the problem in one sitting. Code is large and frequent commits do not offer a working solution. 
    -Cherry picking is great for grabbing one slice of committed changes to add without having to go through many changes you already know are not compatible or acceptable.
    -Squash is great if you have many commits that you need to cram together, but you need more than one commit (like in rebase)




    
