# Using Conjoin

1. Download Wasabi Wallet. Follow the detailed instructions <mark style="color:red;">**here**</mark>
2. Make sure that you have at least a balance of 0.11 bitcoin in your Wasabi wallet.
   * To add bitcoin to your wallet, <mark style="color:red;">**check “Receiving Bitcoin” from the Wasabi wallet guide**</mark>** ** (link).
   * You cannot CoinJoin directly from your hardware wallet, you need to have funds in the wallet you create using Wasabi.
3. Open your Wasabi Bitcoin wallet from the right-hand menu, under “Wallet Explorer”.
4. Select “CoinJoin” from the dropdown menu.
5. Select the coins you want to make private by adding a checkmark beside each one.
   * You can select up to 7 coins.
   * The bitcoin balance needs to have enough to meet the minimum balance requirements to participate in the CoinJoin round.
   * The round will begin once the timer elapses.

{% hint style="danger" %}
### <mark style="color:red;">**WARNING**</mark>

Only select coins that have the same anonymity set. Else, this will reduce the privacy of your coins. Make sure you only select coins that have either a red, yellow or green shield. The green shield with the check mark in it means that those coins are successfully private.&#x20;
{% endhint %}

5\. Make sure the anonymity set is set to 50 (Green shield with check mark) by clicking on the large shield icon under “Target” at the bottom of the page.

6\. Type in your password.&#x20;

7\. Click enqueue.&#x20;

* You will only need to enter your password once. The coinjoin process will restart itself automatically until the target anonymity set is reached.

8\. You will only need to enter your password once.&#x20;

* The coinjoin process will restart itself automatically until the target anonymity set is reached.&#x20;

9\. The coinjoin process begins either once the time elapses (1 hour) or 100 peers have registered themselves.

{% hint style="danger" %}
### <mark style="color:red;">**WARNING**</mark>** **&#x20;

You must keep Wasabi running on your computer to ensure a successful coinjoin. If you disconnect (close application, internet disconnects, Tor connection breaks) the coinjoin round will be canceled.
{% endhint %}

10\. Wait until the coinjoin process is complete.

11\. You will now have at least one coin with the targeted anonymity set and possibly change from that CoinJoin transaction that is not anonymous (red shield).

12\.  Send the coins to your desired wallet or leave them in the current one**.**

{% hint style="danger" %}
### <mark style="color:red;">**WARNING**</mark>

Send each coin in separate transactions. Sending them several at a time or all together will remove some of the privacy gains obtained through CoinJoin.
{% endhint %}

![](<../.gitbook/assets/CoinJOIN wasabi.gif>)
