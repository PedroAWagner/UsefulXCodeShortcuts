# UsefulXCodeShortcuts
These are some useful XCode shortcuts that'll surely make it easier to work, only using your keyboard :)

(These are in no particular order, just wrote them as I found them)

### Quickly open assistant editor:
- _**option click**_ the file you'd like to have on your assistant editor and _voilà_
- to get rid of it, just press _**cmd + enter**_

### Get rid of navigation panes
- _**cmd + 0**_ gets rid ~~and puts back~~ the left navigation pane
- _**cmd + opt + 0**_ gets rid ~~and puts back~~ the right navigation pane

### Quickly indent your code
- Just select the part of code you'd like to indent, and press _**ctrl + I**_

### Quickly refactor a variable name
- Higlight the variable you'd like to refactor, right click on it, and press refactor. A cool UI will appear, and you'll change the name of the variable everywhere you have written it. 

### Quickly refactor a method
- Sticking with the refactoring theme, swift now can refactor methods. Just highlight the part of the method you want refactored, right click on it, go to refactor, and press **extract method**. XCode will create a fileprivate method, with a default name, that you just need to change.

### Easy Markdowns for view navigation
- This isn't really a shortcut, but it's just something I use to make navigation easier. Whenever your write a markdown in your code, do it like this:
    ````
    //MARK: - Something
    ````
  Now when you go to navigate your class, there'll be a line to separate each markdown
  
### Quickly open a file
- Press _**cmd + shift + O**_ to create a popup, where you can type the class you want to open

### Quickly navigate to opened file
- Press _**cmd + shift + J**_ to jump the file highlight to the file you're currently editing

### Edit all in scope
- To change a variable name but just inside the scope of a function, highlight the name you want to change and press _**cmd + ctrl + E**_

### Quickly refactor storyboard
- Inside your storyboard you want refactored, select the views you want, go to _**Editor > Refactor**_ to Storyboard. A neat little popup will appear where you just type the name of the new storyboard file, and XCode automagically creates a new storyboard file, and links it in your "old" storyboard.

### Track how long your build takes
Just type the following line in your terminal, and each time you build your projects, XCode will show how long your build takes
    ```
    defaults write com.apple.dt.Xcode ShowBuildOperationDuration -bool YES
    ```



