# fs_wise2122_pet_project
1. - Created a new Repository "fs_wise2122_pet_project".
   - Downloaded all my projects and diagrams into "fs_wise2122_pet_project" folder present in my Desktop.
   - whenever I wanteed to add anything new to my git : Folder-"fs_wise2122_pet_project"-select "Git bash here".
   - A command type file will open. 
   - I entered codes - $ git add .
                    - $ git commit -m "small discription"
                    - $ git push
                    - ![Screenshot (210)](https://user-images.githubusercontent.com/87199756/153854559-fc51e416-7f85-44a7-b382-6b0497d823bb.png)

   - Sometimes I add files directly on git by dragging the file to upload then commiting it.
2. UML Diagram
   - Use the link for UML diagram https://github.com/Shreeja-Natesh/fs_wise2122_pet_project/tree/main/UML
3. DDD
4. Metrics
   Sonarcube -  Detect bugs, code smells, and security vulnerabilities
             -  https://sonarcloud.io/summary/overall?id=Shreeja-Natesh_fs_wise2122_pet_project
5. Clean Code Development
   - 1. Consistent naming convention
      ![CCC1](https://user-images.githubusercontent.com/87199756/153934780-c224197e-819a-4ca1-9d2d-0c4d8e9aca18.PNG)
         
         - All the names are easy to remember, searchable and clear.
   - 2. Comments
      ![CCC2](https://user-images.githubusercontent.com/87199756/153935112-ee5c2715-d9b5-4291-8722-df3bb86e4597.PNG)
         
         - Comments are added between the code.
   - 3. Clear use of functions
      ![CCC3](https://user-images.githubusercontent.com/87199756/153935289-3b5a0b8b-d667-4a1d-ad0d-d7800bd9c5cf.PNG)
         
         - Functions are kept short with limited or required number of arguments.
   - 4. Content Manger
         
         - Allows intraction with external data file.
   - 5. Function should do one thing
         
         - When called the function should return one value and be performed for only one kind of output.

   - Clean Code Cheat sheet for Android studio -  https://github.com/Shreeja-Natesh/fs_wise2122_pet_project/blob/main/Clean%20Code%20Cheat%20sheet%20for%20Android%20studio.pdf
7. Build Management
   - I wrote a seperate Mobile development code on Android studio.
    #Output - https://github.com/Shreeja-Natesh/fs_wise2122_pet_project/blob/main/proj1-1/Screenshot-output.png .
   - Android Studio uses Gradle, an advanced build toolkit, to automate and manage the build process, while allowing us to define flexible custom build configurations.
   - Code - https://github.com/Shreeja-Natesh/fs_wise2122_pet_project/tree/main/proj1-1
7. Unit Tests
   - I have used assert statement in my code "cancer.ipynb" which is used while debugging the code.
   - The assert statement is used to continue the execute if the given condition evaluates to True. If the assert condition evaluates to False, then it raises the AssertionError   exception with the specified error message.
8. Continuous Delivery 
   - In github action we can see in the workflows if any changes is made in the code or if anything additional is added.
   - Others can use your github link to download and make changes in the link.

9. IDE
   - I have used Android Studio which is the official integrated development environment for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development.
   - Setup :
         ![Screenshot (213)](https://user-images.githubusercontent.com/87199756/153851512-6dd73140-b613-4f48-89fb-0218aed1fd43.png)

   - Using Colab which is an interactive IDE with independant cells to run code.
         ![Screenshot (214)](https://user-images.githubusercontent.com/87199756/153851876-8322d91d-07ab-439f-9ea3-9e054ae181d4.png)

   - Favorite shortcuts
         
         - shift+shift - to search for anything for an example color
         - CTRL+O - override methods
         - CTRL+ALT+L - reformat the code
         -  CTRL+SHIFT+A - search for action
         - CTRL+E - recently opened files
         
10. Domain Specific Languages
   - what is it? It is languages created to support a particular set of tasks, as they are performed in a specific domain.
   - Below is the snippet of Domain Specific language written in Groovy.
   - This is used to run the Java application on Gradle.
   - ![DSL1](https://user-images.githubusercontent.com/87199756/153915669-f9acc82b-e5db-4aef-8e0d-b8f1924e44fa.PNG)
   - ![DSL2](https://user-images.githubusercontent.com/87199756/153915786-c73b9a44-b45c-4fca-8843-9f2c0ce12262.PNG)




11. Functional Programming
   - (mostly) side effect free functions
         ![Side_free](https://user-images.githubusercontent.com/87199756/153762589-cfed9866-514e-413f-aa7c-2d500ef66960.PNG)
           
           - Here the function does not make any changes in global variable but instead in local variable.
   
   - functions as parameters and return values
        a. ![image](https://user-images.githubusercontent.com/87199756/153765620-73204884-f22c-4e88-86f5-5d7c0b1b7209.png)

            - Created a function "create_model1" with x_train and y_train arguments. Then, when you call the function, you pass it's values for those parameters. Finally, my function returns a value.
        b. ![Return2](https://user-images.githubusercontent.com/87199756/153765831-f660c457-2a56-4643-97b3-69935771302f.PNG)
            
            - Created a function "k-fold" with model, num_folds, seed and scoring arguments. When called prints a message, here the message is the mean value.
        c. ![Return3](https://user-images.githubusercontent.com/87199756/153766047-bf8d20b8-3575-4689-8fdb-389e922ef624.PNG)
             
             - Created a function "create_model2" with x_train and y_train arguments. When the function is called we pass it's values for those parameters. Finally my function returns a value. 


         


         


    


