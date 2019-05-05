# COMP5703

AN ONLINE WEB-STREAMING SERVICE FOR BITCOIN EXCHANGES

This project is the outcome of COMP5703. Here is the [demo](http://5703.stonelyu.com)

---

## Introduction

Bitcoin, as a type of cryptocurrency, has become increasingly popular around the world with its market cap valued to be more than a hundred billion dollars. More and more people are interested in Bitcoin for investment. However, the risk of buying Bitcoin is also huge because of the volatile price and market.

In this project, an online web-streaming service for the Bitcoin-exchanges is implemented to provide a website showing related information about Bitcoin for people who are willing to know or plan to invest Bitcoin for the first time.  

This application provides graphical interface including Bitcoin transaction information in visualization, latest news and introduction about offered services that allow users to easily access to general information of the Bitcoin market, do real-time price tracking and previous trade history retrieving.

## How to use

1. `clone` this repo to your device

    ```bash
    git clone https://github.com/StoneLyu/COMP5703.git
    ```

2. Install all dependencies

    ```bash
    cd COMP5703
    npm install
    ```

3. start the project

    ```bash
    node app
    ```

Remember to modify the data access APIs at line `210`, `317`, `1019` and `1053` in the [index.html](public/index.html) if the webpage cannot show graphs and tables correctly.

You can find an example `.json` file [here](public/all_data.json) whose data is extracted from the database.