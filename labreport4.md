# Lab Report: Vim (Week 7)
* screenshot using ```vim```

  [!Image](labreport4screenshot.jpg)

Steps taken to do this:

**Step 4: Login** 
 * Typed in username: logged in using the ```ssh``` command

**Step 5: Clone**
 * copied ```git@github.com:ucsd-cse15l-s24/lab7.git``` from lab steps
 *  Used ```git clone git@github.com:ucsd-cse15l-s24/lab7.git``` ```<enter>``` to clone lab7 repository

**Step 6: Run tests**
 * Typed in ```javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java``` ```<enter>``` to compile all files ending in ".java"
 * Typed in ```java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests``` ```<enter>``` to run the specified test file

**Step 7: Edit test**
* Opened test file using ```vim ListExamples.java``` ```<enter>```
* Entered: ```<down><down><down>...``` [40 times until I reached error line] ```<right><right><right><right><right>``` ```<e>``` ```<r>``` ```2``` ```:wq```

**Step 8: Run Tests**
* Entered: ```<up><up><up><up>``` ```enter``` to run ```javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java```
* Entered: ```<up><up><up><up>``` ```enter``` to run ```java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests```

**Step 9: Commit and Push** 


