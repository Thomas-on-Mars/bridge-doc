# Buy BNB as Gas

{% hint style="info" %}
This feature is available after v2.1.0
{% endhint %}

## Why do we need this feature?

When users swap their tokens to the BEP20 equivalents on Binance Smart Chain, they also need to get some BNB to pay for gas. 

## Requirements

* The destination network has to be **Binance Smart Chain**
* The ****token is a popular BToken, such as BTC, ETH, USDT, BUSD   ****
* The total of your swap order has to be greater than **2BNB**

### How many BNB you can get?

There are 3 options: 0.5 BNB, 1BNB and 2 BNB

## User Guide

### 1. Input your order information

![](../.gitbook/assets/image%20%281%29.png)



### 2. Check the box "I want to swap some BNB gas in this order"

### 3. Choose BNB amount

### 4. Confirm the order information

![](../.gitbook/assets/image%20%285%29.png)

The network fee should be the sum of the fee for swapping assets and the fee for purchasing BNB on your behalf. 

{% hint style="info" %}
The network fees are floating, you might get a different rate than you expected when your order is completed.
{% endhint %}

The actual amount of network fee you have to pay is ****_**network fee\*\(1-discount\)**_**.** When the discount is 100%, the network fee is free. 

### 5. Complete the deposit transaction by sending the exact amount of token to the address shown

![](../.gitbook/assets/image%20%283%29.png)



### 6. You can also verify the order process from the “History” board. 

![img](https://lh4.googleusercontent.com/74FfAjGt-NItSTjwNkBXFLTpLkkOGf7LGZ_ZyIpYusreWvvHilqFlgiL8Npl_gDAZfXOCcb60KfK_E3eZa4kE9V_AbiRTHN-L7MUmpEdhyg8K4jdrdJmyP-qn-iQ-8OliCXm_g-2)



{% hint style="info" %}
The actual amount of token you receive can be different from the confirmation page
{% endhint %}

Calculation formula: 

Received token  = Input amount  - network fee - cost to buy BNB

