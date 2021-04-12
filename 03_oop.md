### OOP

----
#### Materials

[OOP](https://docs.oracle.com/javase/tutorial/java/concepts/index.html)

[Lecture 3](https://coherentsolutions.sharepoint.com/sites/training-center/_layouts/15/WopiFrame.aspx?sourcedoc=%7b21357CB9-7D9D-4E18-AD42-22ADC9979308%7d&file=L3.pptx&action=default)

[Lecture 4](https://coherentsolutions.sharepoint.com/sites/training-center/_layouts/15/WopiFrame.aspx?sourcedoc=%7b87729213-AD13-40A5-876C-67E647EC725A%7d&file=L4.pptx&action=default)

[Reflection](https://docs.oracle.com/javase/tutorial/reflect/)

[Reflections Lib](https://github.com/ronmamo/reflections)

[Faker](https://github.com/DiUS/java-faker)

#### Task #3

Before start creating source code, read carefully all materials about OOP. It is not only 3 principles for interview;)

Store functionality should be based on above principles.

Classes to create:

- `Product` with such attributes as [name, rate, price]
- `Category` classes with the name attribute, for each store category [bike, phone, milk]
- `Store` - class that should handle category list and products that belong to each category
- `RandomStorePopulator` - utility class that will populate out store/category with fake data using `Faker` lib
- `StoreApp` - class with main method to execute our store scenario.

When invoke main method, application should init store with categories and products and `pretty` print this data.
Also, categories should be read dynamically (at runtime), from base category package using `reflections` lib.