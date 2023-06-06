# Cars

## 3D-design
We have designed our cars using the software [Fusion 360](https://www.autodesk.fr/products/fusion-360/overview?term=1-YEAR&tab=subscription). The cars are composed of electronics, 3d printed parts and LEGO pieces. The first step was to import all the components into Fusion 360. For the electronic components, we have downloaded some existing models, listed below:

>- [ESP8266 board]()
>- [ESP32-CAM board]()
>- [L298N motor driver]()
>- [Motor]()
>- [Servo]()

We then imported the LEGO pieces. A good way of doing this is to use [BrinkLink Studio 2.0](https://www.bricklink.com/v3/studio/download.page). It's free, easy-to-use and it gives you access to a 3d model of all LEGO pieces. It also lets you assemble parts to build LEGOs directly within the application, but here we're only interested in the 3d model of the parts. Once we have selected the part we want in brinklink, we can't export it directly to Fusion 360. Here's how to do it:

>- In BrinkLing Studio 2.0, select File > Export As > "Collada" (.dae)
>- Use an online converter to convert your file from .dae to .stl. Here is a link to a converter: [Link](https://imagetostl.com/convert/file/dae/to/stl)
>- Import the file into Fusion 360
>- Rescale your lego part to a factor of exactly 0.04

Once all the parts have been imported. We were able to start designing the car. Design is a long and sometimes complicated process. The right solution doesn't come out on the first try, and sometimes you have to try again and again to get it right. There are a number of factors to take into account. In our case, we wanted the car to turn quickly. Which implies to have a small turning radius. One way of calculating it is to measure the Wheelbase (Wb), the Steer angle (Sa) and the Wheel width (Ww). 

Another gearbox ...

Taking these factors into account, we designed our car. Here's a timelapse of all the design process:
Mettre vidéo 2

Once the car has been designed, all that's left to do is print out the parts and build the car. 
