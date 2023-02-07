#Seminar in Computational Finance

Code for the Seminar in Computational Finance.

### Setup Instructions(only tested under Ubuntu and MacOS):

```
bash install.sh
```

The demo_ABIDES-Markets.ipynb file contains a simulation script, where one can set different parameters for the following parameters and look at the behaviour when simulated on an exchange:

* Number of Market Makers
* Number of Value Agents
* Number of Momentum Agents
* Number of Noise Agents

Interestingly different behavious can be seen when looking at the plots.

Visualisations for different amount of participants:

### Default setting: 
* 2 Market Makers
* 102 Value Agents
* 12 Momentum Agents
* 1000 Noise Agents

![Standard Setting](plots/basicL1.pdf)

![Standard Setting](plots/basicL2.pdf)

### More Market Makers: 
* 5 Market Makers
* 102 Value Agents
*  12 Momentum Agents
*   1000 Noise Agents
* Tighter Spreads in all cases

![Standard Setting](plots/5_market_makerL1.pdf)

![Standard Setting](plots/5_market_makerL2.pdf)

### More Noise Agents: 
* 2 Market Makers
* 102 Value Agents
* 12 Momentum Agents
* 10000 Noise Agents
* Spreads tend to stay smaller

![Standard Setting](plots/10000_noisyL1.pdf)

![Standard Setting](plots/10000_noisyL2.pdf)

### More Momentum Agents: 
* 2 Market Makers
* 102 Value Agents
* 102 Momentum Agents
* 1000 Noise Agents
* Order book has more momentum

![Standard Setting](plots/momentum_agentsL1.pdf)

![Standard Setting](plots/momentum_agentsL2.pdf)