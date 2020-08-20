---
title: "Why you shouldn't go all in your dumb trading bot however perfect it is"
categories: [trading, trading-bots]
tags: [bitcoin]
header:
  teaser: /posts-images/crypto-currency-trading-bots.jpg
---

A few weeks back I thought I hit the golden ticket. I believed I found the perfect trading bot called virtubots developed by [fx4btc](https://github.com/fx4btc).
Perusing the bot's trade history, it had less than two trade losses. Incredible, right? His record has the lowest drawdown of only $11 during its successful weeks. 
The bot maker became the number one trader in the copy 
trading rankings in under two months since its beginnings. According to the description, he uses his own bots with some manual oversight. He also states he has 
ten years of trading experience. In which right now I don't believe it anymore since he made a spectacular rookie mistake.

![trading bot]({{ site.baseurl }}/posts-images/crypto-currency-trading-bots.jpg "trading bot")

I knew how his bot works. The bot does dollar-cost-averaging when micro-market trends go against the initial position. It then thus adjusts the open position into
to a higher or lower position and then it becomes possible to close into profit when the trade goes for its direction. I successfully did an experiment with 
this technique in Bitmex (see pic below).

[![trade history sample]({{ site.baseurl }}/posts-images/trade-history-sample.jpg "trade history sample")]({{ site.baseurl }}/posts-images/trade-history-sample.jpg)

It is indeed profitable but because profits come in small amounts, it is not possible to sustain trading the strategy manually. You have to automate it for 
sustained profits. 

Studying the bot's trade history, I knew it can handle a ranging market because its early history started in May 15, 2020 and from that day, there were consistent
daily profits but disaster struck when it tried to short a breakout bull run from a symmetrical triangle formation in July 22, 2020.

### What happen was truly a rookie mistake, a colossal mistake 

The said trader kept piling on the losing short position, never cutting losses "in order to preserve
his immaculate record of almost zero losses." But because it was a momentous breakout, the market continued trending against him longer than him remaining 
solvent and thus liquidating his whole capital from the beginning. He should have set limits to his losses, accept the wrong trade and never let it 
liquidate.

So basically, I think the bot is fine. It is the manual oversight that was the problem. The trader was bearish on the macro view so he was more confident
in fading or shorting.

He made three mistakes:
1. His technical analysis if it even existed is wrong. The Bitcoin market at that time is leaning bullish.
2. He doesn't set predetermined stop losses. This more akin to gambling. There is always a price level where you will always know that you're in the wrong.
3. Risking everything all for a perfect record.

If you want to see the whole trade history, you can download the screenshots [here](/posts-images/failedbot.zip).

FX4BTC said:
> Algorithmic trading has limitations. Since strategies are coded to identify a pattern and execute positions based on this pattern when the market dynamics
change, the pattern becomes less effective. The market dynamics were consistent for over 2 months which allowed the algo to profit on a daily basis. However, 
once the market dynamics changed, the algo doesn't adapt to the latest market conditions and losses are a result. In order to have consistent profits with 
automated trading, there has to be several filters and trading algos that which on/off based on the filters. This takes time and consistent optimization. 
In conclusion, we're back to development for the time being.

I know bullshit excuse, right? If you were a decent trader, you will know if your bot is wrong. Your own TA first before the bot's.

****

I'm glad that I only lost about $80 worth of BTC because I wasn't 100% confident about its trading strategies. In fact, I already noted in Twitter that the 
bot is already countertrading me several times.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Damm bot - its shorts underwater at 9,236.29. Probably it will DCA when price moves upward. I&#39;m bullish so this is scary watching what it does. <a href="https://t.co/cgS7ORhga4">https://t.co/cgS7ORhga4</a></p>&mdash; Bitcoin Master (@drei4u) <a href="https://twitter.com/drei4u/status/1280531871407857664?ref_src=twsrc%5Etfw">July 7, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">That&#39;s three times the bot&#39;s countertrading me.</p>&mdash; Bitcoin Master (@drei4u) <a href="https://twitter.com/drei4u/status/1286347846015504389?ref_src=twsrc%5Etfw">July 23, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">OMG <a href="https://twitter.com/hashtag/Bitcoin?src=hash&amp;ref_src=twsrc%5Etfw">#Bitcoin</a> might marubozu all the way to 10k. My poor shorting auto trading bot.</p>&mdash; Bitcoin Master (@drei4u) <a href="https://twitter.com/drei4u/status/1286346377732268032?ref_src=twsrc%5Etfw">July 23, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

I am sorry for those I led to believe that this bot is perfect, but you should never put all your eggs in one basket. 