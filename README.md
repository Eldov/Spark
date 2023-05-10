# Spark
Putting all the basics together for the exam

## Spark Arquitecture

Let's imagine that a teacher hand out candy bags to her students:  
![Candy Bag](https://images.handyimprints.com.au/product/100g-m-ms-cello-bag.jpg)
  
and ask them to filter out the brown candies.  
  
Let's also imagine that each table in that classroom has space for 2 students:  
![Example Class](pics/Spark%20Classroom.PNG)
  
- **The Class**: Including the teacher and students, represents the **Cluster**.
- **The Teacher**: Giving instructions and collecing results, represents the **Driver**.
- **The Tables**: Having one or more students, represents the **Executers**.
- **The Students**: Each receiving individual tasks and sharing the materials on the table, represent the **Cores**.
- **Pile of Candy Bags**: Represents the **Dataset**.
- **Candy Bag**: Represents the **Partition**.
- **Candy Piece**: Represents a **Record**.

