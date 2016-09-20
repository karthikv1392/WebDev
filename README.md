# A Acceleo tool to convert model to webpage using Acceleo

1) Import the Acceleo project onto the workspace by ensuring that the perspective of workspace is set to "Acceleo".
   ps : Please maintain the folder hierarchy

2) It will consist of different folders. Of that the folders of our interest will be "model" and "src".

3) The model folder will contain the DDA.ecore file which is  the metamodel, then a DDA.genmodel file and a web.xmi file and this 
   will be the model used for generating the code.

4) All the javascripts and css files are loaded from a public link in dropbox, hence no need to add an .js or .css file.
   Please make sure there is proper internet connection.

5) In the src file there is a package "org.eclipse.acceleo.sample", it will have generate.mtl. Please run the file

6) The output file will be generated in the model folder. Run the html file and verify

7) The html file will have all the four boxes generated automatically by acceleo namely 1) Courses 2) Instructor 3) Students 4) View all

8) The view details link below each of the above box will give a seperate view of each of the entities and there is also an option 
   view all which allows one to see all the tables together.

9) The tables are basically data tables with the table header generated using the attribute names from the entity class and the values 
   are populated using the values of the attribute from the dummy class and all these are generated using the acceleo code

10) One more good feature that has been implimented is that we used acceleo3's option to use a counter variable inside the for loop and the 
   size() function to print the number of instructors, courses and students in the system inside the boxes

11) That's it so it is a dynamic prototype with different views and allows the user to see everything in a quick snapshot.

For any further queries, email : karthikv1392@gmail.com
