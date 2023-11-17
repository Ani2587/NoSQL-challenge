# nosql-challenge

Follow the steps below to successfully run the code:

1. Clone the repository to your local machine.
2. In the command prompt, navigate to the /Resources folder where the establishments.json file is located.
3. Run foloowing command to import the data from Terminal:
    Import the dataset with mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
4. Run the server on the command prompt:
   
   For Mac: brew services stop mongodb-community@6.0
   For Windows: C:\Program Files\MongoDB\Server\6.0\bin\mongod.exe" --dbpath="c:\data\db
