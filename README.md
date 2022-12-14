# Server Side Application to fetch Crypto Transactions of a user

A Simple API for etherscan.io

### Dependencies

Create a .env in the root folder file and add: DB_URL="your_desired_url", API_KEY="your_api_key" , PORT=5000

Install all the dependencies and run with the following command, devStart uses nodemon to autorefresh.
```
    git clone https://github.com/pseudog0d/Ethereum-Wallet-API.git
    cd Assignment-API
    npm i && npm run devStart
```
### Executing program

- To run the script for updating the price of Eth every 10 minutes (I have configure it to show results every 10 seconds) just run:
```
    node saveEveryTenMins.js
```
![image_2022-08-19-23-34-37](img/image_2022-08-19-23-34-37.png)

The DB will get populated as the script is run, you can refer the timestamps in the screenshot to see that the results are being updated as the script is run every 10 seconds.


- To run the main API just execute:

```
    npm run devStart        
```

Hit the API through POSTMAN, or any tool of your choice, you can always use the route.rest file in VS code with the extension: REST Client and execute it here itself.

![image_2022-08-19-23-40-05](img/image_2022-08-19-23-40-05.png)

![image_2022-08-19-23-37-43](img/image_2022-08-19-23-37-43.png)

![image_2022-08-19-23-44-10](img/image_2022-08-19-23-44-10.png)



