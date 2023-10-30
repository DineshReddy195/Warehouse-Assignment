# Warehouse Assignment

JSON server has been installed and it's started using command json-server --watch db.json --port 5001.

1) A file named db.json is created, in that file data is given in object format {"warehouse":[{}]}. So in that object a property warehouse is given and a value of that property is an array, we can pass any number of objects in that array.
2) Install react-router-dom using command npm install react-router-dom
3) In index.js wrap <App/> Component in <BrowserRouter><App/><BrowserRouter/>
4) In App.js file import Routes, Route from react-router-dom.
5) In src, Create a folder named Components in that folder create another folder called WarehouseList.
6) In Warehouselist folder create a file called WarehousehouseList.
7) Use data from JSON server in that WarehouseList Component.
![warehose-2](https://github.com/DineshReddy195/Warehouse-task/assets/87859772/389bd330-fa22-4e25-858d-b8b593db1c6e)
![Warehouse-1](https://github.com/DineshReddy195/Warehouse-task/assets/87859772/d4251c8b-8093-4cbe-9af5-4813832e9bab)
8) If we click on view details it should show details about that warehouse.
![Warehouse-details](https://github.com/DineshReddy195/Warehouse-task/assets/87859772/587b27d4-ec43-4fbe-b044-fcef38dbcc99)
9) On click of edit button, we need to update details in form and click on save button
   ![Warehouse-details-updating](https://github.com/DineshReddy195/Warehouse-task/assets/87859772/b969ecd4-2e05-4a31-b54d-557fbbb5cac7)
10) On Click of save button, data will be updated in UI and also in JSON server.
![Warehouse-details-updated](https://github.com/DineshReddy195/Warehouse-task/assets/87859772/0e400498-6767-4534-987f-77f2a3e3f76a)
11) Finally on selecting options from drop down and entering no:of suare feets in search option, data will be filtered.
    ![Warehouse-filter](https://github.com/DineshReddy195/Warehouse-task/assets/87859772/723a22f2-de6d-4d69-94ac-62836485c643)

