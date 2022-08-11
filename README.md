# Registry for Marinade's non-Quarry partners

This registry can be used to replace or add additional information to Marinade's liquidity gauges frontend in Tribeca.

Please add the following entry for each gauge to the appropriate file:

```json
{
  "{quarry-key}": {
    "stakeLink": "{externat-link-to-staking-pool}",
    "imgSource": "https://raw.githubusercontent.com/marinade-finance/tribeca-non-quarry-config/main/icons/{name-of-image}",
    "name": "{name-of-quarry}"
  }
}
```

Also add the according image to the /icons folder.
