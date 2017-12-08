# Kovan Faucet

The Kovan network is secured by preventing malicious actors from obtaining large amounts of Ether, but legitimate developers need to be able to receive Ether to deploy and test contracts.

There are currently a few different methods of receiving Kovan Ether:

* Icarus Faucet (SMS Verified, Automated)
* ~~Github Gist Faucet ( Automated )~~ (Disallowed)
* Request Via Gitter (Manually Verified)
* Use PoW via [SmartPool](https://medium.com/smartpool/smartpool-alpha-release-472d60f1ef7b#.5tryckqwb)

Additional, more convienient faucet services will be added in due course (e.g. [CAPTCHA / Github OAuth](https://github.com/kovan-testnet/KIPs/issues/2)).

## Reqeusting Large Amounts of KETH

There are few reasons for a dev to require a large amount of KETH. A small amount can be used to make many transactions. For a typical transaction requiring 100k gas at a price of 20 gwei, you can make: `10e18 / (100000 * 20e9) = 5000` transactions with just 10 KETH. To request larger amounts, please post your rationale in the faucet channel; there should be a good reason for requesting more than the default.

## Icarus Faucet (Automated SMS Verification)

Pairty Technologies have set up a faucet service that requires your account to be registered via SMS using Parity. Any registered address can then receive 5 Kovan Ether every 24 hours.

First you must verify an account on the mainnet using pairty's SMS verification service. A video walkthrough is available at: https://youtu.be/99UucFzYCRc.

Once you have registered your account, you can then simply visit http://faucet.kovan.network/[your-mainnet-verified-address] every 24 hours to receive your allowance (which will be sent to that account on the Kovan testnet). In future this service will be updated to allow for verified addresses to send Kovan Ether to other addresses.

## Gitter Channel (Manual Github Verification)

If you want to request to receive Kovan Ether manually (uptime is not guarunteed, and you may have to wait for a verifier to respond), please using the gitter channel:

https://gitter.im/kovan-testnet/faucet

### Manual Github Verification Rates

To reduce KETH getting into the hands of malicious parties, a restricted allowance of KETH is available.

For most people, you will be given 5 KETH. If you have a special request for more, you can get up to 100 KETH (and top-up for legitimate use-cases).

If even you run out of KETH because of creating legit transactions, feel free to ask for more.

*Watch this space for updates on Kovan faucet services.*
