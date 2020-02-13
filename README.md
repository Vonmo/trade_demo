# Vonmo Trade Demo
Experimental trading exchange demo consists of customer and admin zones.

Demo includes more than 20 active markets with market makers.

<details>
  <summary>Screenshots</summary>
  
  <a href="https://www.vonmo.com/pub/screens/exchange/markets.png" target="_blank">Markets list</a>
  
  <a href="https://www.vonmo.com/pub/screens/exchange/exchange.png" target="_blank">Exchange</a>
  
  <a href="https://www.vonmo.com/pub/screens/exchange/admin.png" target="_blank">Admin UI</a>
</details>

**Requirements**:
* RAM: 2Gb
* CPU: 2 Cores
* HDD: 2Gb free space
* Installed <a href="https://docs.docker.com/install/linux/docker-ce/ubuntu/" target="_blank">docker</a> and <a href="https://docs.docker.com/compose/install/" target="_blank">docker-compose</a>

**To start** demo please follow next steps:
1. Clone this repo on your machine:
   ```shell
   git clone https://github.com/Vonmo/trade_demo.git
   ```
1. Change working directory and run the demo:
   ```shell
   cd trade_demo && docker-compose up -d
   ```
1. <a href="http://trade-demo.vonmo.com/" target="_blank">Exchange Demo</a> and <a href="http://trade-admin-demo.vonmo.com/" target="_blank">Admin Demo</a> are ready!

**To stop** demo please run:
  ```shell
  docker-compose down
  ```
  
Resources:
* Articles about this experiment:
    * [Exchanges and modern technologies](https://www.vonmo.com/en/blog/vonmo-trade-experiment-exchanges-and-modern-technologies/)
    * [Orders. Types and processing features](https://www.vonmo.com/en/blog/vonmo-trade-experiment-orders-types-and-processing-features/)
    * [Order book. Processing and storing trade info](https://www.vonmo.com/en/blog/vonmo-trade-experiment-order-book-processing-and-storing-trade-info/)
    * [Stock charts](https://www.vonmo.com/en/blog/vonmo-trade-experiment-stock-charts/)
    * PUT HERE LINK
* [WebAPI Documentation](https://www.vonmo.com/docs/trade-front/v1.0/intro/)
