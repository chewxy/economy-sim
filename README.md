# A Simple Simulation of The Economy

The basis of this repository is the talk I gave at Sydney Python September 2016. Here's the slides for [How to Make Money (In the Economy)](https://speakerdeck.com/chewxy/how-to-make-money-how-money-is-created-in-the-economy).

The purpose of the code in this repository is for an exploratory simulation of why debt fuels growth and why debt is needed to make money. I take a very Schumpeterian view on what money actually is (that is to say I believe money has been backed by debt all along and I personally find metalism a bit distatesful).

The economy is simulated with as much microeconomic grounding as I can make it without stuttering the computer. I also think that this simulation is quite instructive for people to understand what object-oriented-programming is. 

Because of the microeconomic grounding, the money creation process in this economy, while keeping to the spirit of the modern day money creation process, doesn't actually follow what your typical macroeconomics text book teaches you. For example, I eschew the notions of having multiple banks, and things like overnight rates and interbank loans. The world this simulation is in has no financial services, and investment is closer to education (which is an investment on its own) in the real world.

Despite all this, it's enough to demonstrate that money is indeed debt, and that debt fuels growth. 

#How To Run It#
It depends - if you just want to view the results, then clicking [here](https://github.com/chewxy/economy-sim/blob/master/How To Make Money.ipynb) should be enough. Otherwise, here are some steps:

1. Clone this repo into your local machine
2. Install [Jupyter](https://jupyter.org)
3. Run `jupyter notebook` at the directory where you stored this repo
4. Click on `How To Make Money.ipynb` 
5. Do your thing with Jupyter. The charts should be interactive

#Pull Requests#
This simulation was written about 3-4 hours before my presentation, and subsequently cleaned up. However, I am confident that there may be some mistakes. If you do find any, pull requests are welcome.