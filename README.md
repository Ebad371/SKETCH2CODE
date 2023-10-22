# SKETCH2CODE

An early step in creating an application is to sketch a wireframe on paper explaining
the structure of the interface. Designers face a challenge when converting their
wireframes into code, this often involves passing the design to a developer and having
the developer implement the boilerplate graphical user interface (GUI) code. This work
is time-consuming for the developer and therefore costly. In this project, the authors
have solved this problem. They build an application that translates wireframe sketches
directly into code. This technique is called sketch2code. This project uses computer
vision techniques to sort out this problem and train the model in such a way that it
generates a code of the UI interface. For training, the dataset was collected manually,
and then the authors used data augmentation techniques on the dataset. This project
uses both the Tensorflow object detection algorithm and Yolo algorithm for the
detection of objects in a sketch such as buttons, text, etc, and converts it into a
programming language. This project also uses other computer vision techniques to
recognize colors and handwritten text on the sketch of the user interface. The user will
just have to take a picture of the sketch and upload it to the application. The algorithms
will work on the backend to produce a code for that sketch which will be downloadable
by the user. The goal of this project is to save the time of developers and make it userfriendly that everybody can sketch their applications and convert them into the code.
