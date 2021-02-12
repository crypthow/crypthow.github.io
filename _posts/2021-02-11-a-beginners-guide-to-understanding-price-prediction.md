---
layout: post
title:  A Beginner's Guide to Understanding Price Prediction
date:   2021-02-11 20:41:35 +0000
image:  posts/2021-02-11-understanding-price-prediction/hero.png
tags:   ethereum investment
---

What does it take for a cryptocurrency to go from its current price to the price that will finally allow you to retire early?

Prices are going up, and you are being sold the moon. If you are holding ETH, you have likely come across people talking about **ETH reaching $2,000 - $5,000 - $10,000!**

**But what does it mean for ETH to reach these prices?** Surely, it shouldn't be that hard for ETH to go from $1,800 to $10,000.

# The Path to $10k

## Blissful Ignorance

You've just bought some crypto, great! You've invested into the future of finance, but you naturally want to get rich as soon as possible, life is short!

You are scrolling through the subreddits matching your investment, and everyone is so excited and positive. The community is talking of the price of your new favourite coin: it could increase by 10%, 60%, 200%, 450%. Some people are even saying that 450% is conservative and the price could increase by as much as 1,000%, by the end of the year! Everything is possible in the world of crypto, nobody really knows, but everyone has an opinion, a bullish one when they happen to be _hodling_ that cryptocurrency.

And so you naturally get excited. You take the predicted price you have read, open your calculator app, and multiply the predicted price with the number of coins you are holding. Dopamine is flowing through your veins, you are feeling good, the future is looking bright.

But do you understand what needs to happen for these movement in price to occur? Wouldn't it be great if you had a **minimum of knowledge** so you could make your own opinion on the topic? **This is your investment, you should make the effort to understand where your money is predicted to go**, so you can make your own decisions based on your own research, not because someone is throwing their wishful thinking out there so they can feel better about their own investment.

Let's see what it would take for ETH to reach the famous $10k price prediction.

## It's All About The Market Cap

You are reading a lot about prices, but not as much about the market capitalization of a cryptocurrency. Price is something you can easily relate to, market cap, not so much!

**Market cap** is the total market value of a cryptocurrency's circulating supply. If you have a crypto with only 10 coins in circulation, valued at $2 each, its market cap will be $20:

```
Current Price ($2) x Circulating Supply (10) = Market Cap ($20)
```

That would be a pretty lame cryptocurrency!

Why does it matter? The market cap allows you to quantify how much value a market needs to gain in order for a coin to reach a certain price. You can then compare the predicted market cap and its expected gain with other cryptocurrencies, or even companies. Comparing the price of 1 ETH with the price of 1 BTC is meaningless, comparing their market caps is insightful. This is why cryptocurrencies are ranked by market cap, not by price.

The bigger its market cap is, the more successful the crypto is.

## ETH Predicted Market Cap

![]({{ site.baseurl }}/images/posts/2021-02-11-understanding-price-prediction/eth-price-market-cap.png)
*ETH price and market cap from [coinmarketcap.com](https://coinmarketcap.com/currencies/ethereum/)*

ETH's circulating supply is 114,632,202 ETH and has a price of ~$1,801:

```
Current Price (~$1,801) x Circulating Supply (114,632,202) = Market Cap (~$206B)
```

As I am writting this, **ETH has a market cap of $206 Billions**, that information is easily accessible, most apps trading crypro will make it available to you, and you can find historical data on websites such as [CoinGecko](https://www.coingecko.com/), or [CoinMarketCap](https://coinmarketcap.com).

Swap the current price with the speculating price, and you will be able to get its predicted market cap, and the gains it needs to make in order to reach that goal.


```
Predicted Price ($10,000) x Circulating Supply (114,632,202) = Predicted Market Cap ($1,146,322,020,000)
```

**ETH's market cap would be $1.146 Trillion**, that's a **gain of $940B** in order for ETH to reach a price of $10,000.

## Put It Into Perspective

Now we can compare our dream market cap with existing ones, compare the amount of gain with well established companies. This will allow you to finally draw a picture in your mind of what it actually mean for the price of 1 ETH, to go from $1,800 to $10,000. Remember though, nothing is impossible in crypto, things are crazy and very irrational.

### What is this gain worth?

Let's compare the gains ETH needs in order to reach a price of $10k, with different companies' market caps:

<canvas id="gains.v.others" width="400" height="250"></canvas>
<script type="text/javascript">
	docReady(function () {
		var ctx = document.getElementById('gains.v.others');
		new Chart(ctx, {
			type: 'bar',
			data: {
				labels: ['ETH (Current)', 'Facebook', 'Tesla', 'BTC', 'Expected gains', 'Microsoft'],
				datasets: [{
					label: "Market cap (in billions)",
					data: [205, 769, 779, 893, 940, 1840],
					backgroundColor: [
						'#333',
						'#4867aa',
						'#e82127',
						'#ef8e1a',
						'#e0e0e0',
						'#009fe8',
					]
				}]
			},
			options: {
				legend: {
					display: false,
				},
				scales: {
					yAxes: [{
						ticks: {
							beginAtZero: true
						}
					}]
				}
			}
		});
	});
</script>

That's right, in order to reach $10k, ETH's market cap needs to gain the entire market cap of companies like **Tesla** or **Facebook**, and more, but _only_ half of the market cap of **Microsoft**.

It would also be the equivalent of gaining **the entire current market cap of Bitcoin**, plus some.

Now we are starting get some idea of what such speculations mean. Not impossible, but it's quite something!

Looking at historical data, the gains BTC and ETH had combined in market cap since March 2020, would align with what ETH needs in order to reach a price of $10k.

<canvas id="previous.gains" width="400" height="100"></canvas>
<script type="text/javascript">
	docReady(function () {
		var ctx = document.getElementById('previous.gains');
		new Chart(ctx, {
			type: 'horizontalBar',
			data: {
				labels: ['Gains to reach $10k'],
				datasets: [{
					label: "Previous BTC gains",
					data: [802],
					backgroundColor: '#ef8e1a',
				}, {
					label: "Previous ETH gains",
					data: [194],
					backgroundColor: '#333',
				}]
			},
			options: {
				scales: {
				  yAxes: [{
				    stacked: true,
				  }],
					xAxes: [{
					  stacked: true,
						ticks: {
							beginAtZero: true
						}
					}]
				}
			}
		});
	});
</script>

## The Conscious Invester

The goal of this post isn't to trash the prediction of ETH reaching the price of $10k or beyond, but to provide a visualisation of what such prediction looks like.

Next time you come across someone's comment telling you ETH will reach $_x_, hopefully you will be more aware of what their price prediction mean.
