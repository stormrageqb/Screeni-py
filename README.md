# Screeni-py

![GitHub release (latest by date)](https://img.shields.io/github/v/release/pranjal-joshi/Screeni-py) ![GitHub all releases](https://img.shields.io/github/downloads/pranjal-joshi/Screeni-py/total?color=Green&label=Downloads) ![GitHub](https://img.shields.io/github/license/pranjal-joshi/Screeni-py)

[![Screenipy Test - New Features](https://github.com/pranjal-joshi/Screeni-py/actions/workflows/workflow-test.yml/badge.svg?branch=new-features)](https://github.com/pranjal-joshi/Screeni-py/actions/workflows/workflow-test.yml) [![Screenipy Build - New Release](https://github.com/pranjal-joshi/Screeni-py/actions/workflows/workflow-build-matrix.yml/badge.svg)](https://github.com/pranjal-joshi/Screeni-py/actions/workflows/workflow-build-matrix.yml) [![CodeFactor](https://www.codefactor.io/repository/github/pranjal-joshi/screeni-py/badge)](https://www.codefactor.io/repository/github/pranjal-joshi/screeni-py) 


## [**Click to Download Now**](https://github.com/pranjal-joshi/Screeni-py/releases/latest)
---

## What is Screeni-py?

### A Python-based stock screener for NSE, India.

**Screenipy** is an advanced stock screener to find potential breakout stocks from NSE and tell it's possible breakout values. It also helps to find the stocks which are consolidating and may breakout.
Screenipy is totally customizable and it can screen stocks with the settings that you have provided.

## How to use?
* Download the `screenipy.exe (For Windows)` or `screenipy.bin (For Linux)`.
* Linux users should make sure that the `screenipy.bin` is having `execute` permission.
* **Run** the file. Following window will appear after a brief delay.

![home](https://user-images.githubusercontent.com/6128978/114149274-5c424f80-9938-11eb-9eda-4f300c0248ee.png)

* **Configure** the parameters as per your requirement using `Option > 5`.

![config](https://user-images.githubusercontent.com/6128978/114150376-9c560200-9939-11eb-9d46-e7bbd32d6cb1.png)

* Following are the screenshots of screening and output results.

![screening](https://user-images.githubusercontent.com/6128978/114150728-ff479900-9939-11eb-9f76-7b98830b0ba4.png)
![results](https://user-images.githubusercontent.com/6128978/114150744-040c4d00-993a-11eb-8a69-a39e831761e7.png)
![done](https://user-images.githubusercontent.com/6128978/114150766-09699780-993a-11eb-82b1-43ec77cba2fb.png)

* Once done, you can also save the results in an excel file.

## Hack it your way:
Feel free to Edit the parameters in the `screenipy.ini` file which will be generated by the application.
```
[config]
period = 365d
daystolookback = 20
duration = 1d
minprice = 20.0
maxprice = 50000
volumeratio = 2
consolidationpercentage = 10
shuffle = y
onlystagetwostocks = y
useEMA = y
```
Try to tweak this parameters as per your trading styles. For example, If you're comfortable with weekly charts, make `duration=5d` and so on.

## Contributing:
* Please feel free to Suggest improvements bugs by creating an issue.
* Please follow the [Guidelines for Contributing](https://github.com/pranjal-joshi/Screeni-py/blob/new-features/CONTRIBUTING.md) while making a Pull Request.

## Disclaimer:
* DO NOT use the result provided by the software 'solely' to make your trading decisions.
* Always backtest and analyze the stocks manually before you trade.
* The Author and the software will not be held liable for your losses.
