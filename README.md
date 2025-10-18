//PROGRAM DESCRIPTION:



//main branch is instantiated

//feature1 branches off from main and added 4 commits:

 	//Added ability to quit game with negative number input

 	//Added play again loop-functionality

 	//Improved user feedback messages for guesses

 	//Added version comment documenting quit feature

//dev branches off from main and added 1 commit:

 	//Added encouraging message for players

//feature2 branches off from dev and added 2 commits:

 	//Added maxAttempts constant and game over state

 	//Implemented max attempts logic and game over condition

//feature3 branches off from main and added 4 commits:

 	//Started hint functionality

 	//Got it done

 	//Had to fix

 	//Done

//hotfix branches off from main and added 1 commit:

 	//Fixed randomInt to properly include max value in range





//LEARNING SUMMARY:



//Merging creates a new commit from the combination of two files

//Rebase keeps your merge history linear by replacing previous commits, essentially "starting fresh"

//Squashing cleans up your commit history by merging them together

//Cherry-picking allows you to select only certain commits to add to your branch, rather than merging all previous commits



//feature1 added a lot of functionality: mainly user-friendly options, such as adding the ability to quit the game or play again, and 	//improved user feedback messages.

//feature2 added game logic functionality: like setting the number of max attempts allowed and implementing functionality for once this 	//number has been reached, and implementing the game over state and condition.

//feature3 was a little confusing looking at the commit messages: essentially, it added the functionality of giving the player a hint.



//In real projects, you would only use rebase when working on a project by yourself. You don't want to rebase a project that others are 	//working on since it essentially removes the past commits. You would, instead, use merge when working on group projects. You can 	//also use cherry-pick when you only want to add specific commits to a file, rather than merging all commits. This could be 	//beneficial if you want to test a certain combination of commits. Finally, squashing can be extremely beneficial in cleaning up 	//multiple unnecessary commits, especially if you're working in a group. This can ensure commits are easy to read and follow. 

