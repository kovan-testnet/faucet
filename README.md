# Kovan Faucet

The Kovan network is secured by preventing malicious actors from obtaining large amounts of Ether, but legitimate developers need to be able to receive Ether to deploy and test contracts.

There are current 2 methods of receiving Kovan Ether:

* Icarus Faucet (SMS Verified, Automated)
* Request Via Gitter (Manually Verified)

Additional, more convienient faucet services will be added in due course (e.g. [CAPTCHA / Github OAuth](https://github.com/kovan-testnet/KIPs/issues/2)).

## Icarus Faucet (Automated SMS Verification)

Pairty Technologies have set up a faucet service that requires your account to be registered via SMS using Parity. Any registered address can then receive 5 Kovan Ether every 24.

First you must verify an account on the mainnet using pairty's SMS verification service. A video walkthrough is available at: https://youtu.be/99UucFzYCRc.

Once you have registered your account, you can then simply visit http://icarus.parity.io/[your-verified-address] every 24 hours to receive your allowance (which will be sent to that account on the Kovan testnet). In future this service will be updated to allow for verified addresses to send Kovan Ether to other addresses.

## Gitter Channel (Manual Github Verification)

If you want to request to receive Kovan Ether manually (uptime is not guarunteed, and you may have to wait for a verifier to respond), please using the gitter channel:

https://gitter.im/kovan-testnet/faucet

### Manual Github Verification Rates

To reduce KETH getting into the hands of malicious parties, a restricted allowance of KETH is available.

Based on your github activity, various amounts of Kovan Ether will be sent based on your *ethereum-related* contributions:

* 1 - No Issues / Repos / Commits
* 5 - < 2 Issues / Repos / Commits 
* 10 - < 5 Issues / Repos / Commits
* 50 - < 20 Issues / Repos / Commits
* 500 - 100+ Issues / Repos / Commits (or Community-Trusted Developer / Team)
* 1000 - Major Community-Trusted Dapp Development Team

Special requests can be made if justified.

If you run out of KETH because of creating legit transactions, feel free to ask for more.

*Watch this space for updates on Kovan faucet services.*
