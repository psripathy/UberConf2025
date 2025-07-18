* Make the data immutable
  - Defensive copy: Make the data immutable and if there is a neeed to change it and only at that point we make a copy - Proxy pattern
  - List.of(), List.copyOf()

* Avoid creating blank objects and set values later
* Validate data before creating the object
* Methods should accept the most generic (top level) type possible. For ex. if your methid iterates over a list of objects it generalize it by using Iterable as argument. 
