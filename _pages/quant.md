---
layout: single
title: Quantitative-Crypto Trading and Data Science 
description: Guides, Articles, API, Literature, Libraries, Podcasts and other Resources to learn Algorithmic Trading.
image: "https://i.imgur.com/xOeOCnx.png"
permalink: /quant/
---

## Contents

* [Guides-Articles](#guides-articles)
* [CryptoQF](#cryptoqf)
* [Exchanges-API](#exchanges-api)
* [Books](#books)
* [Academic Literature](#academic-literature)
* [Software Libraries](#software-libraries)
* [Videos](#videos)
* [Podcasts](#podcasts)
* [Resources](#resources)
* [**Home**](/README.md) - Back to the main directory.

## Guides-Articles

* [A definitive guide to learning Python for Algorithmic Trading](https://www.womenwhocode.com/blog/a-definitive-guide-to-learning-python-for-algorithmic-trading)
  >Apart from just offering better profit opportunities for the trader, these algo-trading models also make the market more liquid and make the process a lot more systematic by ruling out any impact of human emotions on the trading activities."
* [Twitter sentiment analysis using Python and NLTK](http://www.laurentluce.com/posts/twitter-sentiment-analysis-using-python-and-nltk/)
  > This post describes the implementation of sentiment analysis of tweets using Python and the natural language toolkit NLTK. The post also describes the internals of NLTK related to this implementation.
* [reddit.com - Learning both financial modelling and python at the same time](https://www.reddit.com/r/investing/comments/90gzh6/learning_both_financial_modelling_and_python/)
  >So I've been trying to find the best way to learn financial modelling and python and I figured I could basically do both. Do you know any book/free course that would teach both python and financial modelling or should I learn financial modelling then Python?"
* [CodeAcademy - Learn Python 2](https://www.codecademy.com/learn/learn-python)
  > Learn the basics of the world's fastest growing and most popular programming language used by software engineers, analysts, data scientists, and machine learning engineers alike.
* [Algorithmic trading in less than 100 lines of Python code](https://www.oreilly.com/learning/algorithmic-trading-in-less-than-100-lines-of-python-code)"]
  >"Algorithmic trading refers to the computerized, automated trading of financial instruments (based on some algorithm or rule) with little or no human intervention during trading hours. Almost any kind of financial instrument — be it stocks, currencies, commodities, credit products or volatility — can be traded in such a fashion. \
  > The books The Quants by Scott Patterson and More Money Than God by Sebastian Mallaby paint a vivid picture of the beginnings of algorithmic trading and the personalities behind its rise."
* [Building a Python Fintech App in 200 Lines of Code — Introducing Betalyzer](https://medium.com/@ashishsingal1/introducing-betalyzer-a-fintech-tutorial-110ac9abda58)
  >Betalyzer is a fully function web app that uses some key Python libraries to create a financial technology application in 200 lines of code (ok, ok, it is more like 226 as of this writing). Betalyzer makes use of the modern financial data and web stack including pandas, Flask, Quandl, and Jupyter."
* [Here's how good you need to be at coding in Python to get a finance job](https://news.efinancialcareers.com/us-en/236550/python-coding-finance-job)
* [Python for Finance, Part 2: Intro to Quantitative Trading Strategies](https://www.learndatasci.com/tutorials/python-finance-part-2-intro-quantitative-trading-strategies/)
  >In Python for Finance, Part I, we focused on using Python and Pandas to retrieve financial time-series from free online sources (Yahoo), format the data by filling missing observations and aligning them, calculate some simple indicators such as rolling moving averages and visualise the final time-series.
* [Algorithmic Trading 101 — Lesson 4: Portfolio Management and Machine Learning in Python](https://medium.com/the-ocean-trade/algorithmic-trading-101-lesson-4-portfolio-management-and-machine-learning-in-python-bc50cd53abbd)
  >it’s important to talk about portfolio management strategy —an essential component of long-term trading success. "What types of strategies?" "How much of my net worth allocated to each?" "How often do I adjust?"
* [DataCamp - This Python for Finance tutorial introduces you to algorithmic trading, and much more](https://www.datacamp.com/community/tutorials/finance-python-trading)
  > besides the fact that technology brings about innovation the speeds and can help to gain a competitive advantage, the speed and frequency of financial transactions, together with the large data volumes, makes that financial institutions’ attention for technology has increased over the years and that technology has indeed become a main enabler in finance."
* [AI for algorithmic trading: 7 mistakes that could make me broke](https://medium.com/@alexrachnog/ai-for-algorithmic-trading-7-mistakes-that-could-make-me-broke-a41f94048b8c)
  >"my whole blog is concentrated on solving the following machine learning problem: having a window of past N observations predict N+t one, where N can be 30 days of bars (or other variables as news headlines) and t is forecasting horizon (can vary depending on your strategy). What we have done correctly here?"
* [Neural networks for algorithmic trading. Simple time series forecasting](https://medium.com/@alexrachnog/neural-networks-for-algorithmic-trading-part-one-simple-time-series-forecasting-f992daa1045a)
  > "This is first part of my experiments on application of deep learning to finance, in particular to algorithmic trading.  I want to implement trading system from scratch based only on deep learning approaches, so for any problem we have here (price prediction, trading strategy, risk management) we gonna use different variations of artificial neural networks (ANNs) and check how well they can handle this."
* [Correct 1D time series forecasting + backtesting](https://medium.com/@alexrachnog/neural-networks-for-algorithmic-trading-1-2-correct-time-series-forecasting-backtesting-9776bfd9e589)
  >"Let’s take historical time series of Apple stock prices starting from 2005 till today. You can easily download them from Yahoo Finance as .csv file. In this file data is in “reversed” order — from 2017 till 2005, so we need to reverse it back first and have a look:"
* [Multivariate time series forecasting](https://medium.com/@alexrachnog/neural-networks-for-algorithmic-trading-2-1-multivariate-time-series-ab016ce70f57)
  > "In this article we will see how to preprocess multivariate time series, in particular, what to do with every dimension, how to define and train a neural network on this kind of data and will compare results with what we had in last post."
* [Volatility forecasting and custom losses](https://codeburst.io/neural-networks-for-algorithmic-trading-volatility-forecasting-and-custom-loss-functions-c030e316ea7e) [ϟ](https://github.com/Rachnog/Deep-Trading/tree/master/volatility)
  > "In this tutorial we will reconsider returns forecasting problem, design and check a new loss function for it, transforms returns into some sort of volatility and check different metrics for this problems as well. If you want to see the code first, check it out here.\n\nFirst of all, let’s remember how we switch to returns (or percentage change) from original time series. I think, if we want to predict the return, we can switch all our dimensions (open, high, low, close, volume) to returns — they will be already normalized and this is more suitable option — having our input in form of returns if we plan to forecast return as well:"
* [Multitask and multimodal learning](https://becominghuman.ai/neural-networks-for-algorithmic-trading-multimodal-and-multitask-deep-learning-5498e0098caf) [ϟ](https://www.kaggle.com/aaron7sun/stocknews) [ϟ](https://github.com/Rachnog/Deep-Trading/tree/master/bayesian)
  > "In this tutorial we will use dataset, that contains not only multivariate time series, but also text data with daily news corresponding to trading days from Kaggle. You can check the details of the dataset on the link before, here is short summary what is inside:\n\nNews data: I crawled historical news headlines from Reddit WorldNews Channel (/r/worldnews). They are ranked by reddit users’ votes, and only the top 25 headlines are considered for a single date. (Range: 2008–06–08 to 2016–07–01)\n\nStock data: Dow Jones Industrial Average (DJIA) is used to \“prove the concept\”. (Range: 2008–08–08 to 2016–07–01)"
* [Hyperparameters optimization](https://medium.com/@alexrachnog/neural-networks-for-algorithmic-trading-hyperparameters-optimization-cb2b4a29b8ee) [ϟ](https://github.com/Rachnog/Deep-Trading/tree/master/bayesian)
  > "I think you have noticed that I usually take some architecture of the network as granted and don’t explain why I take this particular number of layers, this particular activation function, this loss function etc. This is really tricky question. Yes, it’s “normal” in deep learning community to take ReLU (or more modern in 2k17 alternative like ELU or SELU) as activation and be happy with this, but we usually don’t think if it’s correct. Talking about number of layers or learning rate for optimizer — we just take something standard. Today I want to talk about the way how to automatize the process of making a choice from these options."
* [Enhancing classical strategies with neural nets](https://medium.com/@alexrachnog/neural-networks-for-algorithmic-trading-enhancing-classic-strategies-a517f43109bf) [ϟ](https://github.com/Rachnog/Deep-Trading/tree/master/bayesian)
  > "Today I want to make a sort of conclusion of financial time series with a practical forecasting use case: we will enhance a classic moving average strategy with neural network and show that it really improves the final outcome and review new forecasting objectives you most probably would like to play with."
* [Probabilistic programming and Pyro forecasts](https://medium.com/@alexrachnog/financial-forecasting-with-probabilistic-programming-and-pyro-db68ab1a1dba) [ϟ](https://github.com/Rachnog/Deep-Trading/tree/master/bayesian)
  > "Today I want to introduce a slightly different approach to fitting the same algorithms. Treating them with probabilistic point of view allows us to learn regularization from data per se, estimate certainty in our forecasts, use much less data for training and inject additional probabilistic dependencies in our models. I will not dive so much into technical or mathematical details of bayesian models or variational inference, I will give some overview, but also concentrate more on application."
* [Backtesting with Pandas](https://medium.com/@alexrachnog/neural-networks-for-algorithmic-trading-backtesting-in-pandas-4940fec2175e)
  > "We were mostly concentrated on forecasting accuracy and experimenting around that before and we touched backtesting issue very briefly and using code from the Mike Halls-Moore’s book. Of course having a nice backtesting code allows to build really good strategies with risk management, money management and consider different scenarios, but if you’re researching just signals obtained from different data sources (even it’s just historical prices) with use of machine learning you need something simpler to understand if these signals to go long or short are really useful. Basically we just want to check the difference between prices and multiply it by signal sign — up or down and accumulate this info during test period."
* [The Best Open Source (And Free) Crypto Trading Bots](https://www.cryptotrader.tax/blog/the-best-open-source-and-free-crypto-trading-bots)
  > Crypto trading bots are tools used by traders to take the fear and emotion out of their trading. These bots allow you to run trading strategies 24/7 (assuming the exchange is working properly) and provide the customization needed to make the bot trade anyway you like. We’ve compiled a list of the best open source (and free) crypto trading bots currently available.All of these bots are available to download and require just a bit of command line experience to get up and running. Even though they are free, each offer many features to keep your automated trading profitable."
* [Mastering Python for Finance](https://www.packtpub.com/mapt/book/big_data_and_business_intelligence/9781784394516/1)
  >Chapter 1. Python for Financial Applications\n\nIn this introductory chapter, we will explore the aspects of Python in order to judge its suitability as a programming language in finance. Notably, Python is widely practiced in various financial sectors, such as banking, investment management, insurance, and even in real estate for building tools that help in financial modeling, risk management, and trading. To help you get the most from the multitude of features that Python has to offer, we will introduce the IPython Notebook as a beneficial tool to help you visualize data and to perform scientific computing for presentation to end users."
* [Quantum Astro Trading](http://www.timingsolution.com/TS/Articles/quantum_astro/index.htm)
  >In this article we discuss quantum trading strategies based on astro phenomena. I will try to do that as simple as possible. 
* [Developing Bitcoin algorithmic trading strategies](https://medium.com/swlh/developing-bitcoin-algorithmic-trading-strategies-bfdde5d5f6e0)
  >Developing algorithmic trading models and strategies is no simple task. To make matters worse the current state of crypto is highly volatile and rapidly changing. The market has become war zone due to regulations from the SEC and various governments targeting crypto exchanges. Despite all of the negative news, many traders are making it big in day-trading crypto assets."
* [RenkoTrading: an embarrassingly simple algorithm for cryptocurrency trading that will deprecate the old notion that “hodling is the best strategy” (part I)](https://cryptodigestnews.com/renkotrading-660d9f64c904)
  > Over the last months, I’ve explored ways not only to invest in crypto but also maximizing the profits from it. One of the first ideas that came to my mind was to develop an automatic trading bot to perform a type of trading known as arbitrage. Although there are different subtypes of arbitrage, in my case, essentially consisted in finding two cryptocurrency exchanges and profit from divergences in their exchange prices. 
* [Popular Python Trading Platforms For Algorithmic Trading](https://www.quantinsti.com/blog/python-trading-library/)
  >With this article on ‘Python Libraries and Platforms’, we would be covering the most popular and widely used Python Trading Platforms and Python Trading Libraries for quantitative trading.
* [Top Backtesting Platforms for Quantitative Trading](https://www.quantinsti.com/blog/top-backtesting-platforms-for-quants/)
  >When automating a strategy into systematic rules; the trader must be confident that its future performance will be reflective of its past performance. There are broadly two forms of backtesting system that are utilised to test this hypothesis; research back testers and event-driven back testers.
* [Using LSTMs For Stock Market Predictions (Tensorflow)](https://towardsdatascience.com/using-lstms-for-stock-market-predictions-tensorflow-9e83999d4653)
  > In this tutorial, you will see how you can use a time-series model known as Long Short-Term Memory. LSTM models are powerful, especially for retaining a long-term memory, by design, as you will see later. You’ll tackle the following topics in this tutorial
* [A first attempt at Bitcoin trading algorithms](https://dev.to/marbru/a-first-attempt-at-bitcoin-trading-algorithms)
  > Algorithmic trading is not a novel idea. In fact it seems to be quite a researched topic, and it's not difficult to find resources about it online. From strategies, to code libraries, to people sharing algorithms on github.\n\nIn or case, we wanted to use it to invest on bitcoin or other cryptocurrencies.
* [My Foray Into Algorithmic Crypto Trading](https://blog.madebywindmill.com/my-foray-into-algorithmic-crypto-trading-beac9113de36)
  > about a month ago I started playing around with algorithmic cryptocurrency trading. A month later I haven’t made a cent, but I did manage to have fun and learned quite a bit so thought it might be worth sharing. I also ended up writing a fairly flexible trading bot in Python which I wanted to share. (You can find it on GitHub.)
* [ANALYZING CRYPTOCURRENCY MARKETS USING PYTHON](https://blog.patricktriest.com/analyzing-cryptocurrencies-python/)
  > A DATA-DRIVEN APPROACH TO CRYPTOCURRENCY SPECULATION:
  >
  > We will walk through a simple Python script to retrieve, analyze, and visualize data on different cryptocurrencies. In the process, we will uncover an interesting trend in how these volatile markets behave, and how they are evolving.
* [@arbedout on Quant Trading Strategies](https://twitter.com/arbedout/status/1052361549560598528)
  >It is generally recognized that creating a profitable quantitative trading  strategy is difficult. Most putative strategies are likely not profitable even without considering trading costs.
* [Best Bitcoin Trading Bots in 2018 – Automated Trading Guide](https://captainaltcoin.com/best-bitcoin-trading-bots/)
  >Bitcoin trading bots can be utilized on many well-known cryptocurrency exchanges today. There are bots that are free of charge and can be downloaded online, and there are also trading bot services you have to pay for, offered by various trading engine and programming companies.\n\nWith so many people relying on trading bots, the question becomes which one should be avoided and which one can be trusted. Below is a list of top 6 best cryptocurrency trading bots. However, your mileage may vary when using them.
* [Algorithmic Cryptocurrency Swing Trading Strategy Part 1](https://www.linkedin.com/pulse/algorithmic-cryptocurrency-swing-trading-strategy-part-eremenko/)
  >Strategies that take advantage of modest short to medium term moves are known as swing trading strategies. In our algorithm, we use the Parabolic Time/Price System as our indicator which is an adaptive momentum indicator which adjusts to the speed of the trend. Its basic premise is that we want to enter into trades that must continue to be profitable or it will be liquidated (similar to any trend following system). Our exit signal generated from this is much tighter if the market is moving up quickly rather than if it was moving slowly helping us keep most of our profits from the latest 'swing'.
* [A tutorial on how to do algorithmic trading of cryptocurrency](https://steemit.com/ai/@dana-edwards/a-tutorial-on-how-to-do-algorithmic-trading-of-cryptocurrency)
  > If you can get this right your trade bot can make money by automatic trading. This bot can do it's own technical analysis and profit for you. Of course this also has implications for Steem and Steemit as bots are also on Steem. Expect these Steemit bots to get smarter if people choose to refine and test the algorithms are the algorithms are the secret sauce of profit bots.
* [Python for analysing financial markets](http://www.automatedtrader.net/articles/technology-strategy/157883/python-for-analysing-financial-markets)
  >This article is split into three parts. Firstly, we discuss the relative merits of various programming languages for analysing financial markets. 
  >
  Secondly, we go into detail about the libraries available in Python to analyse data.
  
  >Finally, we introduce Cuemacro's open-source financial market libraries written in Python: Chartpy (visualisation), Findatapy (market data) and Finmarketpy (backtesting trading strategies). We conclude by presenting some examples of market analysis written in Python using these libraries.
* [A Newbie Guide to Python](https://blog.appdynamics.com/engineering/a-newbie-guide-to-python/)
  >Python is a programming language that is useful for writing quick and simple scripts, but it is also a good language to use for creating large-scale full-blown applications. Even massive operations like YouTube use Python to deliver their content over the Web.\n\nreally basic high level information"
* [Forex trading with functional programming](http://lambda-the-ultimate.org/node/2852)
  >I'm looking for information about how to program a forex trading system with functional programming (I use scheme). Any idea or link you could give me?

## CryptoQF  

If you're on Crypto Twitter, you've probably seen Crypto Quantamental ([@CryptoQF](https://twitter.com/cryptoqf))and his [Coin Selection Model](https://twitter.com/CryptoQF/status/1042265797584797696) [[**D**](https://docs.google.com/spreadsheets/d/1gj15bVnukLGR14PrZ09us7ScRrhM8yg71_CalKX7gbU/edit?usp=sharing)]
  > "Important Disclaimer: This model is not designed to determine whether the crypto market will rise or fall. It is not designed to select coins that will have the most positive returns or identify coins with negative returns. It is designed to identify the coins that have the greatest chances of outperforming and the coins with the greatest chances of underperforming. Outperforming and underperforming is relative to the crypto universe. Therefore if the average crypto coin is up 1000% the dark green coins, in aggregate, would be attempting to beat that. If the average coin is down 50%, the dark green coins will be trying to beat that. This is not financial advice. This is merely my personal model, and I am sharing how I utilize it."

I made a [folder dedicated to his content](/CryptoQF), because I'm interested to learn what he has to say. It is an index of his content, including videos and blogs, in an attempt to present it in an organized fashion.

## Exchanges-API 

* [nomics.com](https://nomics.com/) - 100% of Nomics Was Created With Our Free Crypto API. Free Instant Access 
* [Coinigy.com - The All-In-One Cryptocurrency API](https://www.coinigy.com/bitcoin-api/)
  >The All-In-One Cryptocurrency API Live Data Powered by Coinigy CryptoFeed
* [High Frequency Trading on the Coinbase Exchange](https://www.coindesk.com/high-frequency-trading-on-the-coinbase-exchange/) 
  > After reading about high-frequency trading in the book Flash Boys by Michael Lewis, I decided I’d give it a shot myself, albeit in a clumsier, more amateurish way.
  >
  >The experience has been fascinating, both on a technical level, and in a strategic sense. Writing logic that controls money itself is a strange thing. Setting it loose for the first time, knowing that any bug could literally throw away cash, was terrifying.
  >
  >The exchanges have open API’s that allow anyone, literally anyone, to trade. There’s no premium access, no expensive trading floor credentials. It’s totally open – I love that."
* [Bitmex.com - Automated Trading Engines](https://www.bitmex.com/app/automatedTradingEngines)
  * [Bitmex perpetual swap](https://medium.com/@romanornr/bitmex-perpetual-swap-2d125a304dd)
    > "A lot of crypto traders trade on Bitmex. It’s one of the most advanced trading platforms I’ve ever seen. The most professional traders mostly trade on Bitmex. There are multiple reasons for a trader to trade on Bitmex."
* [Python-Binance.readthedocs.io](https://python-binance.readthedocs.io/en/latest/overview.html)


## Books 

* [Financial Modelling in Python — S. Fletcher & C. Gardner](https://uhs.es/Financial%20Modelling%20in%20Python.pdf)
* [Python for Finance - Yves Hilpisch (Oreily)](https://doc.lagout.org/programmation/python/Python%20for%20Finance_%20Analyze%20Big%20Financial%20Data%20%5BHilpisch%202014-12-27%5D.pdf)
* [Quant Reading List](https://www.quantstart.com/articles/Quant-Reading-List-Python-Programming)
  > This article will present a list of textbooks that are suitable for learning Python from the ground up to an intermediate level.
  >
  >Python, at least in the financial engineering world, originally began life as the "glue" between other codes written in compiled languages such as C++ and Java. However, with the advent of projects like NumPy, SciPy and PyPy, it is beginning to make in-roads into the realm of scientific computing, and hence derivatives pricing."
* [Algorithmic Trading - Winning Strategies and Their Rationale 2014](https://www.amazon.com/Algorithmic-Trading-Winning-Strategies-Rationale/dp/1118460146)
   > A comprehensive guide to professional grade algo strategies. \
   > "I recommend the book to both new traders and pros. New traders can use the book as a good starting point in their research. Pros can use the tools described in the book to enhance their existing strategies."


## Academic Literature 
* [The Market Cycles of ICOs, Bitcoin, and Ether](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3198694)
  > "We apply time series analysis to investigate the market cycles of Initial Coin Offerings (ICOs) as well as bitcoin and Ether. Our results show that shocks to ICO volumes are persistent and that shocks in bitcoin and Ether prices have a substantial and positive effect on these volumes – with the effect of bitcoin shocks being of shorter duration than that of Ether shocks. Moreover, higher ICO volumes cause lower bitcoin and Ether prices. Finally, bitcoin shocks positively influence Ether but not the other way round. Our study has implications for financial practice, in particular for cryptocurrency investors and entrepreneurial firms conducting ICOs. June 2018"
* [Are Weather-Based Trading Strategies Profitable?](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3111467)
  > "We estimate the profitability of global index-level trading strategies formed on daily weather across 49 countries. We use ex ante weather information combined with the statistical relationship between daily weather and country index returns to predict index returns on each day. We then form a long-short hedge strategy and a long-only strategy, and find that both strategies generate substantially out-of-sample gross profits. The long-only strategy produces more consistent annualized profits of up to 20.5%, as opposed to a mean world index return of 3.75% during 1993-2012. These findings help solidify the claim that weather exerts economically important impact on mood, and investors can trade profitably on daily weather."
* [Mitigating Spreadsheet Model Risk with Python Open Source Infrastructure](https://arxiv.org/pdf/1801.09771.pdf)
  >This paper lays ground work for spreadsheet modelling professionals to develop reproducible audit tools using freely available, open source packages built with the Python programming language, enabling stakeholders to develop clearly defined model “oracles” with which to test and audit spreadsheet calculations against."


...

## Software Libraries 

* [TA-Lib](http://ta-lib.org)
  > TA-Lib is widely used by trading software developers requiring to perform technical analysis of financial market data.
  > 
  > Includes 150+ indicators such as ADX, MACD, RSI, Stochastic, Bollinger Bands, etc.\
  > Candlestick pattern recognition\
  > Open-source API for C/C++, Java, Perl, Python and 100% Managed .NET
  * https://github.com/mrjbq7/ta-lib - Python wrapper for TA-Lib
* https://github.com/CryptoSignal/crypto-signal
* https://github.com/techietrader/Trading-indicators-and-Chart-patterns
* https://github.com/munrocket/ta-math
* https://github.com/Trendz/candlestick
* https://github.com/anandanand84/technicalindicators
* [Technical Analysis Library - Pandas \ Python](https://towardsdatascience.com/technical-analysis-library-to-financial-datasets-with-pandas-python-4b2b390d3543)
* [Catalyst -an algorithmic trading library crypto-assets written in Python](https://enigma.co/catalyst/) 
  * http://catalystcrypto.io
  * https://github.com/enigmampc/catalyst
    >Catalyst is an algorithmic trading library for crypto-assets written in Python. It allows trading strategies to be easily expressed and backtested against historical data (with daily and minute resolution), providing analytics and insights regarding a particular strategy’s performance. Catalyst also supports live-trading of crypto-assets starting with four exchanges (Binance, Bitfinex, Bittrex, and Poloniex) with more being added over time. Catalyst empowers users to share and curate data and build profitable, data-driven investment strategies.
* [/PierreRochard/coinbase-exchange-order-book](https://github.com/PierreRochard/coinbase-exchange-order-book)
  >Real-time Coinbase Exchange (GDAX) order book + basic market maker bot
* https://github.com/ccxt/ccxt -cryptocurrency trading library with support for more than 100 bitcoin/altcoin exchanges
  * https://pypi.org/project/ccxt/
  * https://ccxt.readthedocs.io/en/latest/README.html
    >A JavaScript / Python / PHP cryptocurrency trading library with support for more than 100 bitcoin/altcoin exchanges
  * [Design of Algorithmic Cryptocurrency Trading Bot](https://medium.com/@BlockchainEng/design-of-algorithmic-cryptocurrency-trading-bot-e6b30e30987f)
  > I have discussed the development of a cryptocurrency trading bot with python on my Medium.com blog previously, such as through the creation of a Binance Bot and creating an Advanced Cryptocurrency Trading Bot with CCXT to trade all coins on any and all exchanges.\n\nCreating the functionality within Python is one portion of a bot (the tactics), but the strategy behind the bot/software must now be discussed. 
* [MatPlotLib](https://matplotlib.org/index.html)
  >Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.
* [Best Python Libraries/Packages for Finance and Financial Data Scientists](https://www.linkedin.com/pulse/best-python-librariespackages-finance-financial-data-majid-aliakbar/)
* [9 Great Tools for Algo Trading](https://hackernoon.com/9-great-tools-for-algo-trading-e0938a6856cd)
  >In the last 5–10 years algorithmic trading, or algo trading, has gained popularity with the individual investor. The rise in popularity has been accompanied by a proliferation of tools and services, to both test and trade with algorithms. I’ve put together a list of 9 tools you should consider using for your algo trading process."
* [Python Algorithmic Trading Library](http://gbeced.github.io/pyalgotrade/)
  > PyAlgoTrade is a Python Algorithmic Trading Library with focus on backtesting and support for paper-trading and live-trading. Let’s say you have an idea for a trading strategy and you’d like to evaluate it with historical data and see how it behaves. PyAlgoTrade allows you to do so with minimal effort."
* https://plot.ly/products/dash/
  >Dash is a Python framework for building analytical web applications. No JavaScript required.
* [/pirate/crypto-trader](https://github.com/pirate/crypto-trader) - "moneybag Cryptocurrency trading bot library with a simple example strategy."
* [/rochars/trade](https://github.com/rochars/trade)
  >A paradigm for financial applications. Reference implementation in Python. #EleNão
* [/Haehnchen/crypto-trading-bot/](https://github.com/Haehnchen/crypto-trading-bot)


## Videos 

* [Algorithmic Trading with Python and Quantopian p. 1](https://www.youtube.com/watch?v=GlV_QO5B2eU)
> In this tutorial, we're going to begin talking about strategy back-testing. The field of back testing, and the requirements to do it right are pretty massive. Basically, what's required for us is to create a system that will take historical pricing data and simulate trading in that environment, and then gives us the results."
* [Getting started in Financial Modeling](https://www.youtube.com/watch?v=S1eSz_lfAao)
  >This Financial Modeling tutorial helps you to learn financial modeling with examples. This video is ideal for beginners to learn the basics of financial modeling."
* [Python Machine Learning Step-by-Step: Modeling Financial Time Series Data](https://vimeo.com/210865253)
  >During this talk, Reece Heineke will demonstrate in one hour how you can use Python to explore financial time series data, apply a number of machine learning models and find the best fitting one.\n\nStarting with a generated data set, we will evaluate ways to make the data quantity manageable, explore the data visually, do some basic cleaning and ultimately use supervised learning to determine which model is the most appropriate for the data."
* [Algo Trading with REST API and Python - The Basics](https://www.youtube.com/watch?v=dx5UvVKui9M)
  >Learn how to automate your trading strategy using FXCM's REST API and Python programming language. This video is a primer for our tutorial series to help you prepare your computer so you can follow along.  If you are an experienced programmer or have already prepped your computer, feel free to jump ahead to [Part 1: Connecting to the REST API](https://youtu.be/LJcrTscz0IA)
* [Detailed overview of building Python algo trading system with Bitcoin an crypto currency focus](https://www.youtube.com/watch?v=wn7sA3jZcyI) - [blog](https://quantlabs.net/blog/2018/03/new-course-building-python-algo-trading-system-with-bitcoin-an-crypto-currency-focus/)
  > OVERVIEW – As Bitcoin ruled the financial news cycle in recent times, many have had a peak interest in cyrpto currency along with systematic trading. There are many advanced trading research techniques including machine learning, AI, or quant. This course was created for the ‘newbie’ who has a basic understand in popular programming languages but easy to learn such as Python. A focus of technical analysis was chosen since it is popular among retail traders. It is also seems to offer more predictable results as opposed to harder to learn concepts such as quant or machine learning. In essence, a simpler with more effective techniques were purposely chosen to get someone with basic programming knowledge (eg. Python) to get ramped up faster! It is very hopeful any student will become more confident in their capabilities to complete this without the unnecessary complexities that usually hold back their success."
* [Bitcoin Trading Related Development Videos](https://www.youtube.com/watch?v=Kwlxngw1YBY&list=PLhWIQKZKupCYbPpIb2Oe-D1sljPeaTQAy) - includes pinescript tutorials and more 


## Podcasts

* [Chat With Traders · Conversations with talented traders—in stocks, futures, options, forex and crypto markets.](https://itunes.apple.com/us/podcast/chat-traders-conversations-talented-traders-in-stocks/id957265404?mt=2&i=1000420535357) 
  > Chat With Traders is your key to the minds of trading's elite performers. Start listening to learn how a diverse mix of traders went from zero to hero, how they successfully trade markets today, and get their best tips 'n pointers for profitable performance, plus much more. Note: You are responsible for your own trading decisions—this is not financial advice."
  * [166: The trader’s guide for learning to code—with data scientist, Hugo Bowne-Anderson](https://chatwithtraders.com/ep-166-hugo-bowne-anderson/)
    >The idea for asking Hugo to appear on this episode, was to chat about learning a programming language. Because for some traders, having the ability to write code can have great advantages—such as having the ability to collect stats on market behavior, perform research in a robust data-driven way, visualize large amounts of data, backtest and analyse trading ideas, implement algorithmic strategies, etc."
* [Nomics Podcast](https://p.nomics.com/podcast)

## Resources

* [Free Quantitative Finance Resources](https://www.quantstart.com/articles/Free-Quantitative-Finance-Resources)
  >Welcome to the big list of free quantitative finance resources!\n\nI've listed here all of the free ebooks, slides, courses, videos and data that I've found useful during my quant finance career.
* [Quant News](https://www.quantnews.com/)
  >Quantitative Trading, Algorithmic Trading, System Trading, Robot Trading and More.
* [/wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant) - A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance)
* [Build Crypto Bitcoin Trading Bot with Python Binance CCXT — How To Video Tutorials with Code](https://medium.com/@BlockchainEng/how-to-build-an-automated-cryptocurrency-trading-bot-on-binance-with-python-2cd9b5874e44)
  > This Medium post will serve as a centralized location for the Youtube Tutorials, Github Code, and links to further reading for this project, which has grown quite extensive with a large community, numerous tutorials, and code which is ready to be deployed on your own system in order to begin trading cryptocurrencies algorithmic with a bot."
* [Fintech open source repository](https://www.fintastico.com/coding/github-repos-list/)
* [Trading with Python](http://www.tradingwithpython.com/)
* [FreeCodeCamp.org](https://www.freecodecamp.org/)
* [Datacamp.com](https://datacamp.com)
* [PythonAndTrading.com](http://www.pythonandtrading.com/)
  >Getting started with algorithmic trading using Python and a bit of machine learning


