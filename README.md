# Spark
Putting all the basics together for the exam

## Spark Arquitecture

Let's imagine that a teacher hands out candy bags to her students:  
![Candy Bag](https://images.handyimprints.com.au/product/100g-m-ms-cello-bag.jpg)
  
and asks them to filter out the brown candies.  
  
Let's also imagine that each table in that classroom has space for 2 students:  
![Example Class](pics/Spark%20Classroom.PNG)
  
- **The Class**: Including the teacher and students, represents the **Cluster**.
- **The Teacher**: Giving instructions and collecing results, represents the **Driver**.
- **The Tables**: Having one or more students, represents the **Executers**.
- **The Students**: Each receiving individual tasks and sharing the materials on the table, represent the **Cores**.
- **Pile of Candy Bags**: Represents the **Dataset**.
- **Candy Bag**: Represents a **Partition**.
- **Candy Piece**: Represents a **Record**.
  
Each student gets a candy bag to filter out the brown candies. Some of the students finish their work before the others and they will receive the remaining candy bags until all the bags are done.

One of the students, though, gets stuck and cannot finish its work. So the teacher tells another student to help them.