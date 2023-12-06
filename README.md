# Collections

 <br/>
 <br/>
 
 
 ## Part 1: Exploring the Course Services Project
 
 1. Download the src folder and import the project into IntelliJ Idea
 2. Run the main method and observe what happens
 3. Read the code on the Main class and try to understand why is not working
 4. Go to the Student, Course and CourseService class and read the code trying to undertand the functionality of each class(don't worry if you don't undertand 100% you will get there if you persist!)
 5. Open the Student class and implement the following methods:
 
 java
      public void enroll(Course course){
       //TODO implement
    }

    public void unEnroll(Course course){
        //TODO implement
    }

    public int totalEnrolledCourses(){
        //TODO implement
        return 0;
    }
 

 ## Part 2: Implementing the Course Services Project
 1. Find a classmate to work for this part (Pair programming time!)
 2. Discuss with your pair programming buddy what you both understood from the project.
 3. Implement the following methods of the CourseService class:
 
  java
     public void enrollStudent(String studentId, String courseId){
         //TODO implement so it adds the given course form the student
     }

     public void unEnrollStudent(String studentId, String courseId){
         //TODO implement so it removes the given course form the student
     }

     public void displayCourseInformation(String courseId){
         //TODO implement so it shows the course name, id and credits
     }

     public void displayStudentInformation(String studentId){
         //TODO implement so it shows the student name, id and list of enrolled courses
     }
  
4. Run the main method and verify that your implementation works.
