# Lab-8

## Name - Dhruv Parmar
## ID - 202001093

# Provided code
```
// represents a boa constrictor
 public class Boa {
  private String name;
  private int length; // the length of the boa, in feet
  private String favoriteFood;
 
 public Boa (String name, int length, String favoriteFood){
    this.name = name;
    this.length = length;
    this.favoriteFood = favoriteFood;
 }

// returns true if this boa constrictor is healthy
 public boolean isHealthy(){
  return this.favoriteFood.equals("granola bars");
 }

// returns true if the length of this boa constrictor is
// less than the given cage length
 public boolean fitsInCage(int cageLength){
  return this.length < cageLength;
 }
 }
 ```
 
 
# JUnit class file
![image](https://user-images.githubusercontent.com/78268483/233044804-0b66883d-2374-4412-86f5-741a09d91264.png)

# JUnit test file
![image](https://user-images.githubusercontent.com/78268483/233045159-083d1ddd-30e5-4f43-8bcc-ff138fa73769.png)

# JUnit output
![image](https://user-images.githubusercontent.com/78268483/233045307-d519ec5c-2e20-45d5-8399-485690534b61.png)

#JUnit class after adding new method 
![image](https://user-images.githubusercontent.com/78268483/233048909-573a05f8-809e-43a1-9ebf-750df7806de7.png)

#JUnit output after adding new method
![image](https://user-images.githubusercontent.com/78268483/233049060-ee941ae9-210b-4046-97a5-819b40064b26.png)
