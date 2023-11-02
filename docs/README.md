# ImageLab

ImageLab is a framework and application that allows students to develop image modification processors (filters)
and to experience the results visually and aurally.

The ImageLab application is provided in an **imagelab.jar** file.

An associated **filters** package is provided as a folder with source (.java) and compiled (.class) files.
The source versions serve as examples for students to write their own filters.

A sample set of images are provided in an **images** directory.

## Usage

### To run ImageLab from the command line:

* Make sure a **filters** directory is _in the same directory_ as the **imagelab.jar** file and contains compiled filters (`.class` files).  For example, this could be accomplished using the command  
```javac -cp .:imagelab.jar filters/*.java```

* Then issue the command  
```java -cp ".:imagelab.jar" Run``` 
  
 Note that on Windows platforms, the ":" character in the classpath must be changed to the ";" character.)

 ### To run ImageLab using BlueJ
[Install BlueJ for your operating system](https://www.bluej.org/)
* Clone the ImageLab repository to your local machine.
* Run BlueJ.
* Select Open Project... from the Project menu.
* Select the root folder of the cloned ImageLab repository.
* Right-click on the "Run" icon which pops up a menu. Select the "void main(String[] args)" method.
* Select "OK" in the "Method Call" popup window.

At this point, ImageLab should open in a seperate GUI window.
 

## Downloads

ImageLab: [imagelab.zip](https://github.com/MetroCS/imagelab/releases/download/v1.8.3/imagelab.zip)

ImageLab application only:  [imagelab.jar](https://github.com/MetroCS/imagelab/releases/download/v1.8.3/imagelab.jar)

## License

ImageLab is a framework for student exploration of image processing.  
Copyright (C) 2016,2019 by Aaron Gordon & Jody Paul  
The software comes with ABSOLUTELY NO WARRANTY.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <a href="https://www.gnu.org/licenses/">www.gnu.org/licenses</a>
