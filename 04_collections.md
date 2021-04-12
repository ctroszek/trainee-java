### Collections

----
#### Materials

[Collections](https://docs.oracle.com/javase/tutorial/collections/index.html)

[Lecture 9](https://coherentsolutions.sharepoint.com/sites/training-center/_layouts/15/WopiFrame.aspx?sourcedoc=%7bEF21525C-52B3-45A0-8E14-71BFC9BAB74E%7d&file=L9.pptx&action=default)

[XML](https://en.wikipedia.org/wiki/XML)

[XML processing](https://docs.oracle.com/javase/tutorial/jaxp/)


#### Task #4

Starting extend our store. Please append ability user to interact with our store, while sending commands thru read stream.

Add support of such commands: 

- `sort` - products from store according config. In resources folder create xml config file like
```xml
<sort>
    <name>asc</name>
    <price>asc</name>
    <rate>desc</name>
</sort>
```
Config file can contains from 1 to N fields. Sort should be done using `Comparator`. Sort and print should not modify
 default store product lists and their order.
  
- `top` - print top 5 products sorted via price desc
- `quit` - exit app
