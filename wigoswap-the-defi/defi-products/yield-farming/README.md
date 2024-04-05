# 👨‍🌾 Yield Farming

<figure><img src="../../../.gitbook/assets/Yield Farming.png" alt=""><figcaption></figcaption></figure>

As users add liquidity to the platform, they earn LP Tokens. Staking the LP Tokens will lead to harvesting WIGO as the reward.

{% hint style="warning" %}
In terms of giving rewards, WigoFarm is better than Wigo Bank. However, there exists the risk of **Impermanent Loss**. While the term seems a little threatening initially, it’s not the case if you learn about the concept before attempting to use the farms.
{% endhint %}

## **Calculating the Rewards:**

The Annual Percentage Rate (APR) calculations related to the farms are twofold; Firstly, by providing liquidity, users benefit from the LP Rewards APR. Secondly, through staking their LP Tokens into WigoFarm, they profit from the Farm-related rewards APR.

\
`Farm Total APR = LP Rewards APR + Farm Related Rewards APR`

### **Calculating LP Rewards APR:**

As mentioned before, users who use the farms or the so-called farmers benefit from the LP Rewards by providing liquidity. An example is provided to calculate LP Rewards clear:&#x20;

For example, imagine In the FTM/DAI pair, we have these values:

**Liquidity:** $387.42M\
**Volume 24H:** $96.97M\
**Volume 7D:** 709.73M

Use the 24H volume to calculate the **fee share** of liquidity providers in the pool (based on the 0.18% trading fee structure):\
\
$96,970,000\*0.18/100 = **$174,546**

Next, use that **fee share** to estimate the projected **yearly fees** earned by the pool (based on the current 24h volume):\
\
$174,546\*365 = **$63,709,290**

We can now use the yearly fees to calculate the **LP Rewards APR**. That's **yearly fees** divided by **Liquidity:**\
\
($63,709,290/$387,420,000)\*100 = **16.44% LP Reward APR**

### **Calculating the APR of the Farm-related Rewards:**&#x20;

Calculating the APR related to the farm rewards is based on various factors. These include the farm multiplier and the entire amount of liquidity in the farm. This is the amount of WIGO distributed to the farm.
