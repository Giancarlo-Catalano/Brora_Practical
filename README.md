# Brora_Practical
Initial practical for the CSCU9P6 group project



## Team members and their emails
* Ewan Dunn
    * ewd00010@students.stir.ac.uk
* Giancarlo Catalano:
    * gac00056@students.stir.ac.uk
* Josh Gould
    * jog00105@students.stir.ac.uk
* Patrick Cosgrove
    * pac00093@students.stir.ac.uk
* Samuel Barret
    * sjb00025@students.stir.ac.uk
    
    
## Things to do
* Create a public repository
  * Add a .gitignore
* Add other team members using emails
* Add the given [zip file](MVCExample-starter-files.zip "zip files")
  * Each member will
    * Create a new issue for their assigned modifications
    * Create and checkout a new branch
    * Do modifications on own pc
      * see [Tasks](##-Tasks)
    * Commit and push changes to the remote repository
    * Push to the new branch not the master
    * Create a pull request
    * Tag the issue you created or link the pull request
    * Assign the pull request to 1 of your team members and choose the same person as a reviewer
* When assigned as a reviewer, each member will
    * Inspect the proposed merge
    * Make comments on the merge
    * Either accept the merge or reject and propose request changes
    * Check to see if the linked issue has been closed
    * Take appropriate actions (close, comment …)

## Tasks
1. (2 tasks, 1.a, 1.b) Modify View3, View4 to use the Subscriber-Notify protocol with View 1
    * View3, View4 need to 
    * implement the Observer interface
    * Subscribe to the model
    * The update methods should have method headers compatible with the Observer Interface
  * You can comment out from Controller2 things related to the refresh views button
2. Instantiate Controller2 several times in Main
    * Their views all subscribe to the model and they all get notified when the model is modified by the “increment A” button in controller1
    * (you can have multiple instances of controller1)
    * Note: the constructor in controller2 specifies the location of all windows to be the same, so they are overlapping!
3. Add an extra parameter to the constructors of Controller1 and controller2
  * A string that will be used to set the frame title
  * Remember to change the constructor call in main
  * Also add more parameters to specify the position of the frame
4. Add a button to controller2, which calls a methods that increases the second counter (databaseB) 
   * Make sure that all observing views get updated
   
   
   
## Distribution of tasks
(by alphabetical order)
(this is a proposition, just in case)

* Task 1.a: Ewan
    * modifies View 3, comments out from Controller2
    * assigns pull request to Giancarlo
* Task 1.b: Giancarlo
    * makes repository
    * modifies View4
    * assigns pull request to Josh
* Task 2: Josh
    * change main
    * assigns pull request to Patrick
* Task 3: Patrick
    * change constructors in controller1, controller2
    * assigns pull request to Samuel
* Task 4: Samuel
    * add button to controleer2
    * assigns pull request to Ewan





