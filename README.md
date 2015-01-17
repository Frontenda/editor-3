Paperpointer
======
Simple way to do a 6DOF manipulator (aka 3D mouse) from your web-camera.

[More info and show case video](http://paperpointer.com).

##Server
Just supplies 3D data of pointer position over TCP (localhost:9353), so you can easily read this data in:
 * program that needs 6DOF input
 * plugin for editor (3D Max, Maya, etc), to add new dimensions of freedom

Start it via 'PaperServer.java. Example connection in 'PaperClient.java.

##Editor
Simple demo editor showing basic usages of 6DOF manipulator. Starts via DDDEditor.java

###Fast start
You need to have:
 * web-camera
 * java 8
 * [print and cut out pointer pdf](http://paperpointer.com/paperpointer.pdf)




