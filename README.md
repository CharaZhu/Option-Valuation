# Option Valuation

##### Price options using Monte Carlo Simulation and lattice approach.
</br>
 
#### TABLE OF CONTENTS 
- [Background](#background) 
- [Required Parameters](#Required-Parameters) 
- [Requirement](#requirement)
- [Technical Approach](#Technical-Approach)
- [Limitations and Future Improvements](#Limitations-and-Future-Improvements)
- [Reference](#Reference)  
<br/>

 
## Background
An options contract is a type of derivatives that applies to an underlying asset, like stocks, enables the contract 
holder to have the right but not the obligation to buy or sell an asset under specified terms. Therefore, options are 
asymmetric because they benefit one party over the other. An option has 3 configurations: the underlying asset, strike
price, and maturity. The strike price is the price at which the asset can be purchased when exercising the option. 
Maturity specifies the expiration date of the option. Furthermore, the two basic types of options are call option and put 
option. A call option gives the right to purchase something, whereas a put option gives the right to sell something. 
This project mainly emphasizes the pricing of Asian call and put options, lookback call and put options, floating lookback call and put options, and
American put options.

 

## Required Parameters
- risk-free rate: 2%, the underlying stock has the current price <img src="http://chart.googleapis.com/chart?cht=tx&chl= $">
100, 
- volatility: 25%
- no dividend payments 
- 
All the options have a strike price $105 and the maturity 2 months. The simulation has the unit time = 1 week. Noted the sample size at least 250.
 




 
1. Asian call
2. Asian put
3. Lookback call
4. Lookback put
5. Floating lookback call
6. Floating lookback put
7. American put option
 
 

 
