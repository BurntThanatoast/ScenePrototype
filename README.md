Scene Flow Prototype Requirements


Scene types: Your prototype should demonstrate how at least four kinds of distinct types of scenes are used in your game. Every game needs to have a distinct main title screen and a separate credits screen that is easy to access without finishing the game first. The inclusion of other types of scenes can vary between teams. Kinds:

    Main title scene: Players should see this scene before any gameplay begins (some non-gameplay scenes, such as opening cinematics or logos may come before it, however).
    -Created a main tile scene where we have our made up studio logo fade in and out.

    Credits scene: This scene will be used by you are your teammates to show that you made this game (and that you aren't just demonstrating work done by others). For the prototype, the contents of this scene might just be placeholder text such as "[credits go here]".
    -Created a credits scene that you can reach by clicking on the credits button in the main menu.

    Gameplay scene: There might be multiple types of gameplay scenes, and, for this prototype, the contents of each one might just be text messages like "[overworld map]" or "[dialog puzzle 3]".
    -Created a gameplay scene that is reachable by clicking the start button in the main menu.

    Menu scene: Many games have a screen where you can adjust settings for the game. Even if you don't think your game needs a settings screen now, it is a good idea to make one so that there is an obvious place to add player customization features later.
    -Created a menu/settings/options screen that is reachable from the main menu by clicking on the options button.


Communication between scenes: The choices that players made on one scene must have some impact on the appearance of other screens. The inventory system used in D2 is an example of this. Your game might have an achievement system, a score system, or simply remember if someone has watched a mandatory cutscene so that the player can be allowed to skip it only after they have watched it once already. Your documentation should explain where we should look in your code to see how you implemented this communication. (For example, maybe you simply have a global variable that is updated by several separate scenes.)

-Created a variable in the options scene that will hold the sound setting for the entire game.  Will be used to scale sound effects.


Reachability: All important scenes must be reachable in the scene flow prototype. For example, if your game involves a good ending and a bad ending, there should be some way for us to practice reaching each ending. In the placeholder for scenes where players make interesting choices or need to play well to progress, you might have placeholder buttons that allow us to simulate high-skill gameplay with a single tap. (In many of your Roly Poly scene flow prototypes, many of you used instructions like "press 1 to win; press 2 to lose" in the placeholders for the core gameplay scenes.

-All scenes are reachable.  Has placeholder buttons for the different endings in the gameplay scene and brings you to them.


Transitions: The scene flow prototype must demonstrate the use of at least one kind of fancy transition that is appropriate to your game design. Kinds:
Coordinated fades to a common color: for example, one scene fades to black and the next scene fades from black.
Cross-fades: The two scenes are briefly active at the same time while some effect visually blends between them (e.g. a stinger video plays atop them).
Pause or Sleep: Rather than having the previous scene completely Stop, the scene is left in a paused or sleeping state so that it can be returned to without restarting it.
[Some other design proposed by your team]

-Has a transition from the main title to the main menu with a fade out to a fade in.