# A Simple Simulation of The Economy

The basis of this repository is the talk I gave at Sydney Python September 2016. Here's the slides for [How to Make Money (In the Economy)](https://speakerdeck.com/chewxy/how-to-make-money-how-money-is-created-in-the-economy).

The purpose of the code in this repository is for an exploratory simulation of why debt fuels growth and why debt is needed to make money. I take a very [Schumpeterian view](https://en.wikipedia.org/wiki/Credit_theory_of_money) on what money actually is (that is to say I believe money has been backed by debt all along and I personally find [metallism](https://en.wikipedia.org/wiki/Metallism) a bit unintuitive).

The economy is simulated with as much microeconomic grounding as I can make it without stuttering the computer. As an aside, I also think that this simulation is quite instructive for people to understand what object-oriented-programming is. 

Because of the microeconomic grounding, the money creation process in this economy, while keeping to the spirit of the modern day money creation process, doesn't actually follow what your typical macroeconomics text book teaches you. For example, I eschew the notions of having multiple banks, and things like overnight rates and interbank loans. The world this simulation is in has no financial services, and investment is closer to education (which is an investment on its own) in the real world.

Despite all this, it's enough to demonstrate how money is created in our modern economy (and I'd even go so far to argue it was the same in ancient times as well, except we have it more codified now). 

#How To Run It#
It depends - if you just want to view the results, then clicking [here](https://github.com/chewxy/economy-sim/blob/master/How To Make Money.ipynb) should be enough. Otherwise, here are some steps:

1. Clone this repo into your local machine
2. Install [Jupyter](https://jupyter.org)
3. Run `jupyter notebook` at the directory where you stored this repo
4. Click on `How To Make Money.ipynb` 
5. Do your thing with Jupyter. The charts should be interactive

##A Note on the Simulation##
The simulation is not deterministic. Different runs of the simulation will yield different results, but all will end up with the same conclusion: without debt there can be no growth. Some simulations will yield multiple boom-bust periods, some will straightaway jump to a equilibrium phase. The main driver behind this is the `consumerism` variable of a `Person`, which is a random number drawn from a gaussian distribution.

#Pull Requests#
This simulation was written about 3-4 hours before my presentation, and subsequently cleaned up. However, I am confident that there may be some mistakes. If you do find any, pull requests are welcome.

If you have done anything cool with the simulation, also do make a pull request.