# How to Install WAGS using Eclipse

## Initial setup
 * Download Eclipse
 * Make sure your java install is up to date (1.7+)
    - If you need to update http://www.oracle.com/technetwork/java/javase/downloads/index.html
    - Linux users may need to use OpenJDK
 * Go to https://developers.google.com/eclipse/docs/getting_started and follow the guide using your version of Eclipse
 * Restart Eclipse
 * You should see a blue circle with a white 'g' on the top bar
 
![Alt text](/googleg.png?raw=true "Optional Title")

## Setting up project
 * In Eclipse click File > Import > Git > Projects from Git
 * Click Next
 * Click Clone URI
 * Click Next
 * Go to https://github.com/ASU-WAGS/Wags_Client
 * Click Clone or Download and copy the https link (green button)
 * Enter the link into the URI text field
 * Enter your Gitgub username and password at the bottom
 * Click next until you can click finish
 * Right click the project and click Google > gwt Compile
 * A popup will appear, click COmpile again
 * The Console should appear in Eclipse on the bottom if this finishes with no errors as shown below you've set up WAGS correctly
 
```
Compiling module wags.WE
   Compiling 5 permutations
      Compiling permutation 0...
      Compiling permutation 1...
      Compiling permutation 2...
      Compiling permutation 3...
      Compiling permutation 4...
   Compile of permutations succeeded
   Compilation succeeded -- 30.201s
Linking into /home/scott/git/Wags_Client/war/we
   Link succeeded
   Linking succeeded -- 0.443s
```
