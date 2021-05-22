[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=4798843&assignment_repo_type=AssignmentRepo)
# Exercise 6.3 Messaging Service

The exercise template comes with a pre-defined `Message` class that can be used to create objects representing messages. Each message has a sender and some content.

Implement the `MessagingService` class. The class must have a parameterless constructor and contain a list of `Message` objects. After that, add the following two methods to the class:

- `def add(self, message)` - adds a message passed as a parameter to the messaging service as long as the message content is at most 280 characters long.

- `def get_messages()` - returns the messages added to the messaging service.

Tip! You can find out the length of the string using the `len()` method associated with the string.
