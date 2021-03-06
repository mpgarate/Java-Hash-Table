BasicHashMap
===============

Hash map with linked lists to handle collisions, created as an exercise. 

Generic types are supported. 

Built using Java hashCode and java.util.LinkedList. 

### Usage

Instantiate

~~~java
BasicHashMap<String, Integer> map = new BasicHashMap<String, Integer>();
~~~

Store a key.

~~~java
String name = "Michael";
Integer age = 22;
map.add(name, age);
~~~

Get a key.
~~~java
Integer age = map.get("Michael"); // 20
~~~

Remove a key.
~~~java
map.remove("Michael");
~~~

Update a value. 
~~~java
map.add("Bill",22);
map.update("Bill", 45);
Integer value = hash.get("Bill") //45
~~~

Initialize a map with a custom array size.
~~~java
// This is a map of size 1, so all elements
// will be in the linked list at index 0.
HashMap miniMap = new HashMap(1);
~~~
