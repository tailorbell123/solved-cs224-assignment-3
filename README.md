Download Link: https://assignmentchef.com/product/solved-cs224-assignment-3
<br>
For this assignment you will be creating a package delivery system. You need to think in terms of objects. The first object is the delivery truck that can store 50 liters of petrol. The cost per liter of petrol is 2.73$. You will be using the sample file, Drivers.txt for this assignment. Your code should however take into account that if an entry is increased or reduced (5 lines per entry) it reads all the entries in the file (You are going to assume that there are no errors in the file). For example, if there is just one entry, it should give the following lines as output:

Elton John

34

218

9

7

Based on this entry, the drivers name is Elton John, his truck has 34 liters already, his total funds are 218$. His truck covers 9 km per liter if empty and 7 km per liter when loaded.

The trucks can carry 12 to 20 packages/boxes (which is the second object) with random dimensions. The length, width and height of every package can range from 5 to 30 inches. This means that you will need to declare a dynamic array of boxes for each truck and every box will have a different dimension.

Calculate the total cost it will take the loaded truck to travel 60 km, drop the cargo and return empty based on the fuel consumption when the tank was full. This means that the drivers need to fill the tank first before making the journey. Based on the amount of money they have, calculate if everyone can do the journey. This means that you will need to declare a dynamic array of Trucks as well.

When unloading the boxes, show the volume of all the boxes and then deallocate the array of boxes. Once the trucks return, deallocate the array of all trucks after calculating the cost for the trip, how much money is left, how many litres of petrol are left.

The truck needs to have a <em>Load() </em>and an <em>Unload() </em>Function. When the trucks have been generated, the <em>Load() </em>function should be called that will generate the boxes and put them inside the truck (It should show the dimensions of all the boxes). Once the journey is over, it should call the <em>Unload() </em>function and unload all the boxes (It should show the dimensions of all the boxes). Once the journey is complete a new file Trip.txt should be generated that will show the current state of all the Drivers that made the journey.

Some important points:

<ul>

 <li>Sample code is there for your benefit. If you are going to use it, understand how it works.</li>

 <li>In the sample code we are using structs. You need to change it appropriately to use classes. A general rule of thumb is that all attributes in a class are private.</li>

 <li>Where necessary, declare your own functions inside classes. Make sure why you would keep a function as private or public.</li>

 <li>You do not need to follow the code given exactly. You can make changes where you see fit provided that it makes sense.</li>

 <li>You need to define separate *.h and *.cpp files for all the classes.</li>

</ul>