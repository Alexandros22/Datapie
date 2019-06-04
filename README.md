This is a Python program that has build for a course in my university.

To run this program will needed to install Python 3.x and Gevent with Greenlet.
You can install these through pip:

> pip install gevent  
> pip install greenlet    

gevent comes with greenlet, but if there is a error install greenlet too.

To execute navigate from terminal/PowerShell to the folder that example.py is and type:

> python example.py


We use gevent and greenlet to achieve multihreading and connection between our objects(threads). 
For this project i was in a team with Georgios Tzourbakis.
The idea was to build a program that allow us to take data from a source (Mine) and another program-instance 
is able to process that data and give them to another.

In the example.py was created for testing the Mine.py and Miner.py. In this example two Miner objects and one Mine 
are created. Miner2 connects to Miner1 and Miner1 connects to Mine. Mine sends 10 random characters(data) to Miner1
then Miner1 process the data make them all upper. Miner1 sends the processed data to Miner2 which mak them lower.

Please see the presentation to see the description of the full idea.


