# StockForest
Predicting Stock Price Movement with a Random Forest Classifier

This repo documents the (results of) a side project I started in 2021. Coming from a NLP background, I sought to expand my knowledge-domain and found the financial markets a very interesing topic. In this work I didn't wanted to create a model by myself, as doing so for this data would be a huge timesink, and I'm currently pursuing my masters degree.

Anyhow, as mentioned in the notebook, I decided to try a Random Forest model and designed a simple pipeline to extract and format data and feed it into the model. I also created a little backtesting framework to see how the trained model would do in the "real" world. To be clear: Predicting stock prices is obviously extremly reliant on really good data, and scraping yahoo finance probably doesnt give me that. Nonetheless it was fun to play around with different indicators, thinking of strategies and what could work.

## Overview

I'm working with day-to-day data (one-day candles). To predict is wether the price of a stock rises 15% during the next 2 weeks. The strategy focuses on Volume, which is represented in the indicator selection. My thinking is, a basic model with (probably) poor data can't realiably find an edge, but it could find patterns that other, bigger and better players are creating. Basically it's a trend-following strategy.

## Outlook

I focused more on getting everything to work and reading/researching about the financial markets in a more or less convoluted way, than to "beautify" the notebook and this shows. Same with my backtesting framework. So that would be something to improve. Readability, structure and additional comments as well as more information about tools used and my thinking behind the how and why will be added, when I again have the time. It probably will get out of hand once I start, so its better if I can really focus on it.
