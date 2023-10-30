# Warehouse Assignment

JSON server has been installed and it's started using command json-server --watch db.json --port 5001.

1) A file named db.json is created, in that file data is given in object format {"warehouse":[{}]}. So in that object a property warehouse is given and a value of that property is an array, we can pass any number of objects in that array.
2) Install react-router-dom using command npm install react-router-dom
3) In index.js wrap <App/> Component in <BrowserRouter><App/><BrowserRouter/>
4) In App.js file import Routes, Route from react-router-dom.
5) In src, Create a folder named Components in that folder create another folder called WarehouseList.
6) In Warehouselist folder create a file called WarehousehouseList.
7) Use data from JSON server in that WarehouseList Component.
8) If we click on view details it should show details about that warehouse.
9) On click of edit button, we need to update details in form and click on save button
10) On Click of save button, data will be updated in UI and also in JSON server.
11) Finally on selecting options from drop down and entering no:of suare feets in search option, data will be filtered.

