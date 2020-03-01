# **API Assessment**

### **Description:**
Read in a CSV file and write two separate API calls:
1. User Update (POST /api/users/update)
- userUpdate.js
2. Bulk User Update (POST /api/users/bulkUpdate)
- bulkUserUpdate.js

### **Requirements**
*Developed with Node 13+*

Expects a CSV delimited by commas with the following headers and associated data-types: 

| firstName | lastName | email | favoriteTomato | totalTomatoOrders | daysSinceLastOrder | zip | phoneNumber | age | streetAddress | city | state |customMessageOne | gender |
| ------ | ------ | ------ | ------- | ------ | ------ | ------ | ------- | ------ | ------ | ------ | ------- | ------ | ------ | 
| string | string | string | string | int | int | int | string | int | string | string | string | string | string | 

### **Implementation**

1. Clone the Repo
2. Install the dependencies by executing `npm install`
3. Create a file named ".env" that contains the following text:
   
   `API_KEY={ENTER YOUR API KEY HERE}`
   
   `PATH_NAME='./tomato_users.csv'`
   
4. Profit
- For Bulk Update, run: `node bulkUserUpdate.js`
- For User Update, run: `node userUpdate.js`
