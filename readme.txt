This is a tutorial to learn the scrapy. 
The tutorial is here http://python.jobbole.com/81320/

Note:
1. install pymongo:  pip install pymongo
2. install MongoDB and start it

   2.1 http://docs.mongodb.org/manual/tutorial/install-mongodb-on-windows/
   2.2 download and install http://www.mongodb.org/downloads?_ga=1.12428855.246612167.1430320276
   2.3 execute mongod and specify the folder where data will dump into, e.g.
       C:\mongodb\bin\mongod.exe --dbpath d:\test\mongodb\data

3. connect to MongoDb through shell (Not being used by this tutorial, the scrapy will do the work)

    go to the folder where MongoDB installed, and go to the bin folder, execute:
    mongo