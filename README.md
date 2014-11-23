# DIT - [Data Import Tool] :
### Utilised for: https://github.com/KshitijKarthick/DIT
## Program Features : [Implemented for the Reva University]
   * A Lightweight GUI for the Data Import Tool.
   * Invokes Individual Ruby Scripts to Perform Individual Relation Importing into the Database based on User Choice.
   * Each Ruby Script is Atomic and can be run Independently.
   * Output of each Ruby Script is Displayed on the Output Window in the GUI Tool.
  
## Program Details :
   * Program is written in Java
   * Invokes individual Ruby Scripts to perform the Selected Choice.
   * The generated Jar File should be placed in the same directory as all the Ruby Scripts present in /scripts in the DIT Repository.
   * The Console Output of Each Ruby Script is Displayed on the Output Window.

## Program Execution :
```
  # Windows and Posix OS Compliant.[Requirements: JRE, DIT Repository, Bundler, Ruby]
  > git clone https://github.com/KshitijKarthick/DIT
  > cd DIT
  > bundle install
  > [Copy the Generated Jar file to /scripts]
  > cd DIT/scripts
  > java -jar Data_Import_Tool.jar

```

## To Do :
  * Add Generic Features for the Data Import Tool.
  * Better Security incorporation in the Application.