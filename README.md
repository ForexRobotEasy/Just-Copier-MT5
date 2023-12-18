# Just Copier MT5 - ReadMe

This ReadMe file provides an overview of the code for Just Copier MT5, a simple and efficient forex software developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing sample code that can work as described in this product.

For detailed reviews and trading results of Just Copier MT5, please visit [this link](https://forexroboteasy.com/forex-robot-review/review-of-just-copier-mt5-a-simple-and-efficient-forex-software/).

## Copy Trades Functions

### Copy Trades from Provider

```mql5
void CopyTradesFromProvider(int providerID, double lot)
```

This function copies trades from the specified provider with the given lot size.

### Copy Trades to Receiver

```mql5
void CopyTradesToReceiver(int receiverID, double lot)
```

This function copies trades to the specified receiver with the given lot size.

### Copy Trades from Multiple Providers

```mql5
void CopyTradesFromMultipleProviders(int[] providerIDs, double lot)
```

This function copies trades from multiple providers with the given lot size.

### Set Receiver Lot to Match Multiple Providers

```mql5
void SetReceiverLotToMatchProviders(int[] providerIDs)
```

This function sets the receiver lot size to match the lots of multiple providers.

## Main Program

```mql5
void OnStart()
```

The main program demonstrates the usage of the copy trade functions. It showcases the following examples:

1. Copy trades from a specific provider (ID: 123456) with a lot size of 0.01.
2. Copy trades to a specific receiver (ID: 654321) with a lot size of 0.02.
3. Copy trades from multiple providers (IDs: 123456, 789012, 345678) with a lot size of 0.03.
4. Set receiver lot size to match the lots of multiple providers.

Please refer to the code comments for specific implementation details.

## Product Description

Just Copier MT5 is a simple and efficient forex software developed by the Forex Robot Easy Team. This software provides a range of functions for copying trades from providers to receivers. It offers the flexibility to copy trades from a specific provider, multiple providers, or set the receiver lot size to match the lots of multiple providers.

With Just Copier MT5, traders can easily replicate successful trading strategies by copying trades from experienced providers. This software simplifies the process of trade replication, allowing users to focus on their trading strategies and improve their overall trading performance.

For detailed reviews and trading results of Just Copier MT5, please visit [this link](https://forexroboteasy.com/forex-robot-review/review-of-just-copier-mt5-a-simple-and-efficient-forex-software/). Please note that ForexRobotEasy is not the official developer of this product. To find the official developer of Just Copier MT5, please visit the MQL5 website.
