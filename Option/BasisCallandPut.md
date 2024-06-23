---
title: Basis: Call and Put
description: 
published: true
date: 2024-06-22T18:41:20.811Z
tags: 
editor: markdown
dateCreated: 2024-06-22T18:35:09.236Z
---

# Basis Call and Put
1. **Own Stock + Sell Call (Covered Call):**
   - Objective: Generate income from an existing stock position.
   - Action: Own the stock and sell call options against it.
   - Profit Potential: Limited to the premium received plus potential gains in the stock price up to the strike price.
   - Risk Management: Partially mitigated downside risk with the premium received, but potential for missed upside gains if the stock price rises above the strike price.

2. **Own Stock + Sell Put:**
   - Objective: Generate income or acquire more shares at a lower price if assigned.
   - Action: Own the stock and sell put options against it.
   - Profit Potential: Limited to the premium received. If the stock price remains above the strike price, the option expires worthless, and you keep the premium.
   - Risk Management: Potential obligation to buy more shares at the strike price if the stock price falls below the strike price.

3. **Own Stock + Buy Call:**
   - Objective: Hedge against potential losses or speculate on upward price movement.
   - Action: Own the stock and buy call options.
   - Profit Potential: Unlimited if the stock price rises above the strike price. Limited by the premium paid for the call option.
   - Risk Management: Limited to the premium paid. Protection against downside risk is not provided.

4. **Own Stock + Buy Put:**
   - Objective: Hedge against potential losses or speculate on downward price movement.
   - Action: Own the stock and buy put options.
   - Profit Potential: Unlimited if the stock price falls below the strike price. Limited by the premium paid for the put option.
   - Risk Management: Limited to the premium paid. Protection against downside risk is provided.

5. **Do Not Own Stock + Sell Call (Naked Call):**
   - Objective: Generate income from speculation on the stock price remaining below the strike price.
   - Action: Do not own the stock and sell call options.
   - Profit Potential: Limited to the premium received. Potential for unlimited losses if the stock price rises significantly above the strike price.
   - Risk Management: Unlimited risk due to potential obligation to sell shares at a higher market price.

6. **Do Not Own Stock + Sell Put (Naked Put):**
   - Objective: Generate income from speculation on the stock price remaining above the strike price.
   - Action: Do not own the stock and sell put options.
   - Profit Potential: Limited to the premium received. Potential for unlimited losses if the stock price falls significantly below the strike price.
   - Risk Management: Potential obligation to buy shares at the strike price if the stock price falls below the strike price.

7. **Do Not Own Stock + Buy Call:**
   - Objective: Speculate on upward price movement.
   - Action: Do not own the stock and buy call options.
   - Profit Potential: Unlimited if the stock price rises above the strike price. Limited by the premium paid for the call option.
   - Risk Management: Limited to the premium paid. Protection against downside risk is not provided.

8. **Do Not Own Stock + Buy Put:**
   - Objective: Speculate on downward price movement.
   - Action: Do not own the stock and buy put options.
   - Profit Potential: Unlimited if the stock price falls below the strike price. Limited by the premium paid for the put option.
   - Risk Management: Limited to the premium paid. Protection against downside risk is provided.
# Example
1. **Own Stock + Sell Call (Covered Call):**
   - Action: You own 100 shares of XYZ stock and sell one call option contract with a strike price of $55 for a premium of $2 per share, expiring in one month.
   - Scenario: If the stock price remains below $55 by expiration.
     - Outcome: You keep the premium of $200 and continue to hold your stock.
   - Scenario: If the stock price rises above $55 by expiration.
     - Outcome: Your shares may be called away at $55 per share, and you miss out on potential further upside gains.

2. **Own Stock + Sell Put:**
   - Action: You own 100 shares of XYZ stock and sell one put option contract with a strike price of $45 for a premium of $1.50 per share, expiring in one month.
   - Scenario: If the stock price remains above $45 by expiration.
     - Outcome: You keep the premium of $150 and continue to hold your stock.
   - Scenario: If the stock price falls below $45 by expiration.
     - Outcome: You may be assigned to buy more shares at $45 per share, effectively lowering your breakeven price.

3. **Own Stock + Buy Call:**
   - Action: You own 100 shares of XYZ stock and buy one call option contract with a strike price of $55 for a premium of $2.50 per share, expiring in one month.
   - Scenario: If the stock price rises above $57.50 (strike price + premium) by expiration.
     - Outcome: You profit from the increase in stock price beyond the breakeven point of $57.50.
   - Scenario: If the stock price remains below $55 by expiration.
     - Outcome: You lose the premium paid for the call option.

4. **Own Stock + Buy Put:**
   - Action: You own 100 shares of XYZ stock and buy one put option contract with a strike price of $45 for a premium of $1.50 per share, expiring in one month.
   - Scenario: If the stock price falls below $43.50 (strike price - premium) by expiration.
     - Outcome: You profit from the decrease in stock price beyond the breakeven point of $43.50.
   - Scenario: If the stock price remains above $45 by expiration.
     - Outcome: You lose the premium paid for the put option.

5. **Do Not Own Stock + Sell Call (Naked Call):**
   - Action: You don't own any shares of XYZ stock and sell one call option contract with a strike price of $55 for a premium of $2 per share, expiring in one month.
   - Scenario: If the stock price remains below $55 by expiration.
     - Outcome: You keep the premium of $200 as the option expires worthless.
   - Scenario: If the stock price rises above $55 by expiration.
     - Outcome: You face potentially unlimited losses as you may need to purchase shares at a higher market price to fulfill your obligation.

6. **Do Not Own Stock + Sell Put (Naked Put):**
   - Action: You don't own any shares of XYZ stock and sell one put option contract with a strike price of $45 for a premium of $1.50 per share, expiring in one month.
   - Scenario: If the stock price remains above $45 by expiration.
     - Outcome: You keep the premium of $150 as the option expires worthless.
   - Scenario: If the stock price falls below $45 by expiration.
     - Outcome: You may be assigned to buy shares at $45 per share, regardless of the current market price, potentially leading to significant losses.

7. **Do Not Own Stock + Buy Call:**
   - Action: You don't own any shares of XYZ stock and buy one call option contract with a strike price of $55 for a premium of $2.50 per share, expiring in one month.
   - Scenario: If the stock price rises above $57.50 (strike price + premium) by expiration.
     - Outcome: You profit from the increase in stock price beyond the breakeven point of $57.50.
   - Scenario: If the stock price remains below $55 by expiration.
     - Outcome: You lose the premium paid for the call option.

8. **Do Not Own Stock + Buy Put:**
   - Action: You don't own any shares of XYZ stock and buy one put option contract with a strike price of $45 for a premium of $1.50 per share, expiring in one month.
   - Scenario: If the stock price falls below $43.50 (strike price - premium) by expiration.
     - Outcome: You profit from the decrease in stock price beyond the breakeven point of $43.50.
   - Scenario: If the stock price remains above $45 by expiration.
     - Outcome: You lose the premium paid for the put option.
