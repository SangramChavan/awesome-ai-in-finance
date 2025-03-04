<div align="center">
	<img width="500" height="350" src="media/logo.svg" alt="Awesome">
	<br>
  <p>
    <a href="https://github.com/georgezouq/awesome-deep-reinforcement-learning-in-finance">DL/RL/SL Strategies Research & Tools in Quantitative Finance</a>
  </p>
</div>

# Awesome DL/RL/SL in Quantitative Finance

The main goal is collect those AI (RL / DL / SL / Evoluation / Genetic Algorithm) used in financial market. otherwise, we add Technology Analysis / Alpha Research / Arbitrage and other useful strategies tools & docs in quantitative finance market.

We collect all market include traditional market like `stock/futures/currencies` and crypto currency markets.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

- [Implementation](#Implementation)
- [Papers](#papers)
- [Courses & Book](#courses--book)
- [Strategies](#strategies--research)
- [Trading System](#trading-system-back-test--live-trading)
- [Research tools](#research-tools)
- [Data Sources](#data-sources)
- [Tutorials & Docs](#tutorials)
- [Exchange API & Docs](#ai-framework)
- [Other Tools](#others)

## Implementation

- [Personae](https://github.com/Ceruleanacg/Personae): 📈 Personae is a repo of implements and environment of Deep Reinforcement Learning & Supervised Learning for Quantitative Trading.
- [AutomatedStockTrading-DeepQ-Learning](https://github.com/sachink2010/AutomatedStockTrading-DeepQ-Learning): Every day, millions of traders around the world are trying to make money by trading stocks. These days, physical traders are also being replaced by automated trading robots. Algorithmic trading market has experienced significant growth rate and large number of firms are using it. I have tried to build a Deep Q-learning reinforcement agent model …
- [Deep-Reinforcement-Stock-Trading](https://github.com/Albert-Z-Guo/Deep-Reinforcement-Stock-Trading): A light-weight deep reinforcement learning framework for portfolio management. This project explores the possibility of applying deep reinforcement learning algorithms to stock trading in a highly modular and scalable framework.
- [tf_deep_rl_trader](https://github.com/miroblog/tf_deep_rl_trader): Trading Environment(OpenAI Gym) + PPO(TensorForce)
- [trading-gym](https://github.com/6-Billionaires/trading-gym): This trading-gym is the first trading for agent to train with episode of short term trading itself.
- [trading-rl](https://github.com/Kostis-S-Z/trading-rl): Deep Reinforcement Learning for Financial Trading using Price Trailing @ ICASSP 2019
- [deep_rl_trader](https://github.com/miroblog/deep_rl_trader): Trading Environment(OpenAI Gym) + DDQN (Keras-RL)

## Papers

- [THE THEORY OF SPECULATION L. BACHELIER 1900](http://www.radio.goldseek.com/bachelier-thesis-theory-of-speculation-en.pdf): The influences which determine the movements of the Stock Exchange are
- [Brownian Motion in the Stock Market Osborne,1959](http://m.e-m-h.org/Osbo59.pdf)                                                                                                                              innumerable. Events past, present or even anticipated, often showing no apparent
- [A Deep Reinforcement Learning Framework for the
Financial Portfolio Management Problem](https://arxiv.org/pdf/1706.10059.pdf)
- [Reinforcement Learning for Trading 1994](http://papers.nips.cc/paper/1551-reinforcement-learning-for-trading.pdf)
- [Dragon-Kings, Black Swans and the Prediction of Crises Didier Sornette](https://arxiv.org/pdf/0907.4290.pdf): We develop the concept of “dragon-kings” corresponding to meaningful outliers, which are found to coexist with power laws in the
distributions of event sizes under a broad range of conditions in a large variety of systems. 
- [Financial Trading as a Game: A Deep Reinforcement Learning Approach](https://arxiv.org/pdf/1807.02787.pdf): An automatic program that generates constant profit from the financial market is lucrative
                                                                                                               for every market practitioner. Recent advance in deep reinforcement learning provides a
                                                                                                               framework toward end-to-end training of such trading agent...
- [MACHINE LEARNING FOR TRADING](https://cims.nyu.edu/~ritter/ritter2017machine.pdf): Abstract. In multi-period trading with realistic market impact, determining the dynamic trading strategy that optimizes expected utility
                                                                                      of final wealth is a hard problem. Gordon Ritter shows that, with an
                                                                                      appropriate choice of the reward function, reinforcement learning techniques (specifically, Q-learning) can successfully handle the risk-averse
                                                                                      case
## Courses & Book

- [Overview of Advanced Methods of Reinforcement Learning in Finance](https://www.coursera.org/learn/advanced-methods-reinforcement-learning-finance/home/welcome)
- [Advanced-Deep-Trading](https://github.com/Rachnog/Advanced-Deep-Trading): Mostly experiments based on "Advances in financial machine learning" book

## Strategies & Research

#### Traditional Markets

- [trump2cash](https://github.com/maxbbraun/trump2cash): A stock trading bot powered by Trump tweets http://trump2cash.biz
- [Quantitative-Trading](https://github.com/Ceruleanacg/Quantitative-Trading): 💸 Papers and Code Implements for Quantitative-Trading
- [gym-trading](https://github.com/hackthemarket/gym-trading): Environment for reinforcement-learning algorithmic trading models
- [zenbrain](https://github.com/carlos8f/zenbrain): A framework for machine-learning bots
- [DeepLearningNotes](https://github.com/AlphaSmartDog/DeepLearningNotes): Machine Learning in Quant analysis

#### Portfolio Management

- [qtrader](https://github.com/filangel/qtrader): Reinforcement Learning for Portfolio Management
- [PGPortfolio](https://github.com/ZhengyaoJiang/PGPortfolio): PGPortfolio: Policy Gradient Portfolio, the source code of "A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem

### High Frequency Trading (HFT)

- [SGX-Full-OrderBook-Tick-Data-Trading-Strategy](https://github.com/rorysroes/SGX-Full-OrderBook-Tick-Data-Trading-Strategy): Providing the solutions for high-frequency trading (HFT) strategies using data science approaches (Machine Learning) on Full Orderbook Tick Data.
- [HFT_Bitcoin](https://github.com/ghgr/HFT_Bitcoin): Analysis of High Frequency Trading on Bitcoin exchanges

#### Crypto Currencies

- [LSTM-Crypto-Price-Prediction](https://github.com/SC4RECOIN/LSTM-Crypto-Price-Prediction): Predicting price trends in cryptomarkets using an lstm-RNN for the use of a trading bot
- [tforce_btc_trader](https://github.com/lefnire/tforce_btc_trader): TensorForce Bitcoin Trading Bot
- [Tensorflow-NeuroEvolution-Trading-Bot](https://github.com/SC4RECOIN/Tensorflow-NeuroEvolution-Trading-Bot): Using tensorflow to build a population of models that trade cyrpto and breed and mutate iteratively
- [gekkoga](https://github.com/gekkowarez/gekkoga): Genetic Algorithm for solving optimization of trading strategies using Gekko
- [Gekko_ANN_Strategies](https://github.com/markchen8717/Gekko_ANN_Strategies): ANN trading strategies for the Gekko trading bot
- [gekko-neuralnet](https://github.com/zschro/gekko-neuralnet): Neural network strategy for Gekko
- [bitcoin_prediction](https://github.com/llSourcell/bitcoin_prediction): This is the code for "Bitcoin Prediction" by Siraj Raval on Youtube

### TA

- [Gekko-Bot-Resources](https://github.com/cloggy45/Gekko-Bot-Resources): Gekko bot resources.
- [gekko_tools](https://github.com/tommiehansen/gekko_tools): Gekko strategies, tools etc.
- [gekko RSI_WR](https://github.com/zzmike76/gekko): Gekko RSI_WR strategies
- [gekko HL](https://github.com/mounirlabaied/gekko-strat-hl): calculate down peak and trade on
- [EthTradingAlgorithm](https://github.com/Philipid3s/EthTradingAlgorithm): Ethereum trading algorithm using Python 3.5 and the library ZipLine
- [gekko_trading_stuff](https://github.com/thegamecat/gekko-trading-stuff): A dumping ground for my files I use with this awesome crypto currency trading platform
- [forex.analytics](https://github.com/mkmarek/forex.analytics): Node.js native library performing technical analysis over an OHLC dataset with use of genetic algorithm
- [Bitcoin_MACD_Strategy](https://github.com/VermeirJellen/Bitcoin_MACD_Strategy): Bitcoin - MACD Crossover Trading Strategy Backtest
- [crypto-signal](https://github.com/CryptoSignal/crypto-signal): Automated Crypto Trading & Technical Analysis (TA) Bot for Bittrex, Binance, GDAX, and more! (250+ coins)
- [Gekko-Strategies](https://github.com/xFFFFF/Gekko-Strategies): Strategies to Gekko trading bot with backtests results and some useful tools.
- [gekko-gannswing](https://github.com/johndoe75/gekko-gannswing): Gann's Swing trade strategy for Gekko trade bot

### Lottery & Gamble

- [LotteryPredict](https://github.com/chengstone/LotteryPredict): Use LSTM to predict lottery

### Arbitrage

- [ArbitrageBot](https://github.com/BatuhanUsluel/ArbitrageBot): Arbitrage bot that currently works on bittrex & poloniex
- [r2](https://github.com/bitrinjani/r2): R2 Bitcoin Arbitrager is an automatic arbitrage trading system powered by Node.js + TypeScript.
- [cryptocurrency-arbitrage](https://github.com/manu354/cryptocurrency-arbitrage): A cryptocurrency arbitrage opportunity calculator. Over 800 currencies and 50 markets. https://cryptoworks.co
- [bitcoin-arbitrage](https://github.com/maxme/bitcoin-arbitrage): Bitcoin arbitrage - opportunity detector
- [blackbird](https://github.com/butor/blackbird): Blackbird Bitcoin Arbitrage: a long/short market-neutral strategy


## Data Sources

#### Traditional Markets

- [Tushare](): 

#### Crypto Currencies

- [CryptoInscriber](https://github.com/Optixal/CryptoInscriber): 📈 A live cryptocurrency historical trade data blotter. Download live historical trade data from any cryptoexchange, be it for machine learning, backtesting/visualizing trading strategies or for Quantopian/Zipline.
- [Gekko-Datasets](https://github.com/xFFFFF/Gekko-Datasets): Gekko Trading Bot dataset dumps. Ready to use and download history files in SQLite format.

## Research Tools

- [JAQS](https://github.com/quantOS-org/JAQS): An open source quant strategies research  platform.
- [pyfolio](https://github.com/quantopian/pyfolio): Portfolio and risk analytics in Python https://quantopian.github.io/pyfolio
- [alphalens](https://github.com/quantopian/alphalens): Performance analysis of predictive (alpha) stock factors http://quantopian.github.io/alphalens
- [empyrical](https://github.com/quantopian/empyrical): Common financial risk and performance metrics. Used by zipline and pyfolio. http://quantopian.github.io/empyrical
- !!![deprecated]!!![fooltrader](https://github.com/foolcage/fooltrader): Trade as a fool 
- [zvt](https://github.com/zvtvz/zvt): zero vector trader(which base on fooltrader)

## Trading System (Back Test & Live trading)

### Traditional Market

[System]

- [zipline](https://github.com/quantopian/zipline): Zipline, a Pythonic Algorithmic Trading Library http://www.zipline.io/
- [rqalpha](https://github.com/ricequant/rqalpha): A extendable, replaceable Python algorithmic backtest && trading framework supporting multiple securities http://rqalpha.io
- [backtrader](https://github.com/backtrader/backtrader): Python Backtesting library for trading strategies https://www.backtrader.com
- [kungfu](https://github.com/taurusai/kungfu): Kungfu Master Trading System

[Combine & Rebuild]

- [pylivetrader](https://github.com/alpacahq/pylivetrader): Python live trade execution library with zipline interface.
- [CoinMarketCapBacktesting](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting): This project tests bt(http://pmorissette.github.io/bt) and Quantopian Zipline(https://github.com/quantopian/zipline) as backtesting frameworks for coin trading strategy.

### Crypto Currencies

- [gekko](https://github.com/askmike/gekko): A bitcoin trading bot written in node - https://gekko.wizb.it/
- [zenbot](https://github.com/DeviaVir/zenbot): Zenbot is a command-line cryptocurrency trading bot using Node.js and MongoDB.
- [bot18](https://github.com/carlos8f/bot18): Bot18 is a high-frequency cryptocurrency trading bot developed by Zenbot creator @carlos8f https://bot18.net/
- [magic8bot](https://github.com/magic8bot/magic8bot): Magic8bot is a cryptocurrency trading bot using Node.js and MongoDB.
- [catalyst](https://github.com/enigmampc/catalyst): An Algorithmic Trading Library for Crypto-Assets in Python http://enigma.co
- [QuantResearchDev](https://github.com/mounirlabaied/QuantResearchDev): Quant Research dev & Traders open source project **[BUILDING]**
- [MACD](https://github.com/sudoscripter/MACD): Zenbot Macd Auto-Trader
- [abu](https://github.com/bbfamily/abu): A quant trading system base on python.http://www.abuquant.com/

#### Plugins

- [easytrader](https://github.com/shidenggui/easytrader): 提供银河/国金/华泰客户端/同花顺客户端/雪球的基金、股票自动程序化交易以及自动打新，支持跟踪 joinquant /ricequant 模拟交易 和 实盘雪球组合, 量化交易组件
- [CoinMarketCapBacktesting](https://github.com/JimmyWuMadchester/CoinMarketCapBacktesting): This project tests bt(http://pmorissette.github.io/bt) and Quantopian Zipline(https://github.com/quantopian/zipline) as backtesting frameworks for coin trading strategy.
- [Gekko-BacktestTool](https://github.com/xFFFFF/Gekko-BacktestTool): Batch backtest, import and strategy params optimalization for Gekko Trading Bot. With one command you will run any number of backtests.

### TA (Technical Analysis) Lib

- [pandas_talib](https://github.com/femtotrader/pandas_talib): A Python Pandas implementation of technical analysis indicators
- [finta](https://github.com/peerchemist/finta): Common financial technical indicators implemented in Python-Pandas (70+ indicators).
- [tulipnode](https://github.com/TulipCharts/tulipnode): Tulip Node is the official node.js wrapper for Tulip Indicators. It provides over 100 technical analysis overlay and indicator functions. https://tulipindicators.org
- [techan.js](https://github.com/andredumas/techan.js): A visual, technical analysis and charting (Candlestick, OHLC, indicators) library built on D3. http://techanjs.org/


### Exchange API

- [HuobiFeeder](https://github.com/mmmaaaggg/HuobiFeeder): Connect HUOBIPRO exchange, get market/historical data for ABAT trading platform backtest/analysis and live trading
- [ctpwrapper](https://github.com/nooperpudd/ctpwrapper): Shanghai future exchange CTP api

## Tutorials

### ML

- [Reinforcement-learning-with-tensorflow](https://github.com/MorvanZhou/Reinforcement-learning-with-tensorflow): Simple Reinforcement learning tutorials
- [Algorithm_Interview_Notes-Chinese](https://github.com/imhuay/Algorithm_Interview_Notes-Chinese): Algorithm Interview Notes Chinese
- [Learning-Notes](https://github.com/Ceruleanacg/Learning-Notes): 💡 Repo of learning notes in DRL and DL, theory, codes, models and notes maybe.
- [Deep-Learning-World](https://github.com/astorfi/Deep-Learning-World): 📡 Organized Resources for Deep Learning Researchers and Developers
- [100-Days-Of-ML-Code](https://github.com/Avik-Jain/100-Days-Of-ML-Code): 100 Days of ML Coding

### Quant

## AI Framework

- [convnetjs](https://github.com/karpathy/convnetjs): Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
- [TensorForce](https://github.com/reinforceio/tensorforce): TensorForce: A TensorFlow library for applied reinforcement learning
- [gym](https://github.com/openai/gym): A toolkit for developing and comparing reinforcement learning algorithms. https://gym.openai.com/
- [Pavlov.js](https://github.com/NathanEpstein/Pavlov.js): Reinforcement learning using Markov Decision Processes. For JS, written in C++.
- [baselines](https://github.com/openai/baselines): OpenAI Baselines: high-quality implementations of reinforcement learning algorithms
- [prophet](https://github.com/facebook/prophet): Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth.

### Visualizing

- [playground](https://github.com/tensorflow/playground): Play with neural networks! http://playground.tensorflow.org
- [netron](https://github.com/lutzroeder/netron): Visualizer for deep learning and machine learning models https://www.lutzroeder.com/ai


## Articles

- [The-Economist](https://github.com/nailperry-zd/The-Economist): The Economist 经济学人，持续更新
- [nyu-mlif-notes](https://github.com/wizardforcel/nyu-mlif-notes): NYU machine learning in finance notes
- [Using LSTMs to Turn Feelings Into Trades](https://www.quantopian.com/posts/watch-our-webinar-buying-happiness-using-lstms-to-turn-feelings-into-trades-now?utm_source=forum&utm_medium=twitter&utm_campaign=sentiment-analysis)

#### Chinese

- [Maury Osborne和三文鱼的故事](https://zhuanlan.zhihu.com/p/20586843)
- [布朗运动、伊藤引理——细说Black-Scholes公式的前世今生（上篇）](https://zhuanlan.zhihu.com/p/32664487) 
- [布朗运动、伊藤引理——细说Black-Scholes公式的前世今生（下篇）](https://zhuanlan.zhihu.com/p/32746192)
- [趋势策略小试牛刀，海龟交易体系的构建](https://www.ricequant.com/community/topic/62/%E8%B6%8B%E5%8A%BF%E7%AD%96%E7%95%A5%E5%B0%8F%E8%AF%95%E7%89%9B%E5%88%80-%E6%B5%B7%E9%BE%9F%E4%BA%A4%E6%98%93%E4%BD%93%E7%B3%BB%E7%9A%84%E6%9E%84%E5%BB%BA)

## Others

- [zipline-tensorboard](https://github.com/jimgoo/zipline-tensorboard): TensorBoard as a Zipline dashboard http://jimgoo.com/tensorboard-and-zip…
- [gekko-quasar-ui](https://github.com/H256/gekko-quasar-ui): An UI port for gekko trading bot using Quasar framework.

#### Other Resource

- [awesome-quant](https://github.com/wilsonfreitas/awesome-quant): A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance)          
- [awesome-quant-china](https://github.com/thuquant/awesome-quant): Quant resource in china
- [awesome-rl](https://github.com/aikorea/awesome-rl)
