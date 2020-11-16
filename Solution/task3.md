**Task 3.1**
```java
public class Shirt {
  public int shirtID = 123; // стандартне значення номера моделі сорочки
  public String description = "Modno"; // стандартний опис сорочки
  // коди кольорів: Red=червоний, Blue=синій, Green=зелений, Unset=невідомо
  public String colorCode = "Red";
  public double price = 124241.344; // стандартна вартість сорочки
  public int quantityInStock = 2; // стандартна кількість на складі
  
  // цей метод просто виводить всю інформацію про сорочку на екран
  public void displayShirtInformation() {
    System.out.println("Shirt ID: " + shirtID);
    System.out.println("Shirt description:" + description);
    System.out.println("Color Code: " + colorCode);
    System.out.println("Shirt price: $" + price);
    System.out.println("Quantity in stock: " + quantityInStock);
  } // кінець методу displayShirtInformation
} // кінець опису класу
```

**Task 3.2**
```java
public class Quotation {
  String quote = "“If you cannot do great things, do small things in a great way.”";
  String name = "– Napoleon Hill";
  public void display() {
    System.out.println(quote);
    System.out.println(name);
  }
}
```
![task1]()
