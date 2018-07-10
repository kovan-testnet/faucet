# Kovan Faucet

The Kovan network is secured by preventing malicious actors from obtaining large amounts of Ether, but legitimate developers need to be able to receive Ether to deploy and test contracts.

## Gitter Channel (Manual Github Verification)

If you want to request to receive Kovan Ether manually (uptime is not guaranteed, and you may have to wait for a verifier to respond), please using the Gitter channel:

https://gitter.im/kovan-testnet/faucet

### Manual Github Verification Rates

To reduce KETH getting into the hands of malicious parties, a restricted allowance of KETH is available.

For most people, you will be given 5 KETH. If you have a special request for more, you can get up to 100 KETH (and top-up for legitimate use-cases).

If even you run out of KETH because of creating legit transactions, feel free to ask for more.

## Requesting Large Amounts of KETH

There are few reasons for a dev to require a large amount of KETH. A small amount can be used to make many transactions. For a typical transaction requiring 100k gas at a price of 20 Gwei, you can make: `10e18 / (100000 * 20e9) = 5000` transactions with just 10 KETH. To request larger amounts, please post your rationale in the faucet channel; there should be a good reason for requesting more than the default.

Additional, more convenient faucet services will be added in due course (e.g. [CAPTCHA / Github OAuth](https://github.com/kovan-testnet/KIPs/issues/2)).
*Watch this space for updates on Kovan faucet services.*
