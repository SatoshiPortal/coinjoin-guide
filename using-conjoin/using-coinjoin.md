# Using CoinJoin
To use Wasabi Wallet for private payments, follow these steps:

1. Download and install Wasabi Wallet and follow the detailed instructions provided in [<mark style="color:red;">**this guide**</mark>](https://app.gitbook.com/o/vkgJ5Qo6ByYsQmJoONIK/s/PdwveKS34LFQnTOWXGHS/)<mark style="color:red;">**.**</mark>
2. Open your wallet and make sure you have at least 5000 satoshis, as well as enough funds for mining + coordination fees. If you need to add bitcoin to your wallet, refer to the "Receiving Bitcoin" section of the Wasabi Wallet guide.
3. Wait for Wasabi to automatically coinjoin in the background. By default, the Auto-start coinjoin threshold is set at 0.01 BTC. If your non-private balance is below this amount, you will need to manually press the "Play" button.
4. Once completed, you can now make private payments. You will know when a coin has reached the desired level of privacy (reaches the Anonymity score target), as the corresponding amount will be labeled "PRIVATE" in the main view of your wallet.

{% hint style="danger" %}
### <mark style="color:red;">**WARNING**</mark>** **&#x20;

You must keep Wasabi running on your computer to ensure a successful CoinJoin. If you disconnect (close application, internet disconnects, Tor connection breaks) the CoinJoin round will be canceled.
{% endhint %}

With the release of Wasabi Wallet 2.0, coinjoin has become much simpler and user-friendly thanks to the introduction of the WabiSabi coinjoin protocol. This new protocol improves the efficiency of coinjoin rounds and enhances your privacy by allowing for coinjoins with hundreds of inputs and outputs. For example Wasabi Wallet coinjoin transactions, refer to [<mark style="color:red;">**https://docs.wasabiwallet.io/using-wasabi/CoinJoin.html#wasabi-coinjoin-examples**</mark>].

For more information on using Wasabi's coinjoin feature, check out the complete guide at [<mark style="color:red;">**https://docs.wasabiwallet.io/using-wasabi/CoinJoin.html**</mark>].



{% hint style="danger" %}
### <mark style="color:red;">**WARNING**</mark>

Send each coin in separate transactions. Sending them several at a time or all together will remove some of the privacy gains obtained through CoinJoin.
{% endhint %}

