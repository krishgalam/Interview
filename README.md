# Interview
This repository contains consolidated interview questions I have come across and its explanations in read me file

# Transient, Scoped and Singleton Services Differences
Transient objects are always different; a new instance is provided to every controller and every service.

Scoped objects are the same within a request, but different across different requests.

Singleton objects are the same for every object and every request.

# Singleton Design pattern
Singleton is a creational design pattern, which ensures that only one object of its kind exists and provides a single point of access to it for any other code.

EN : The Singleton should always be a 'sealed' class to prevent class inheritance through external classes and also through nested classes.
The Singleton's constructor should always be private to prevent direct construction calls with the `new` operator.
The Singleton's instance is stored in a static field.
