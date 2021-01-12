## Base account
```
{
  "account": {
    "@type": "/cosmos.auth.v1beta1.BaseAccount",
    "address": "cro1whr4cwhker9mzszlr6d5mlvgatp6zpxr4uzsek",
    "pub_key": {
      "@type": "/cosmos.crypto.secp256k1.PubKey",
      "key": "AgURls3vju2/FH1Bm0cz4oB/3eIoej7TNYtShmFsUWHE"
    },
    "account_number": "3",
    "sequence": "4"
  }
}
```

## Module account
```
{
  "account": {
    "@type": "/cosmos.auth.v1beta1.ModuleAccount",
    "base_account": {
      "address": "cro1jv65s3grqf6v6jl3dp4t6c9t9rk99cd8lyv94w",
      "pub_key": null,
      "account_number": "9",
      "sequence": "0"
    },
    "name": "distribution",
    "permissions": []
  }
}
```

## Delayed vesting account
```
{
  "account": {
    "@type": "/cosmos.vesting.v1beta1.DelayedVestingAccount",
    "base_vesting_account": {
      "base_account": {
        "address": "cro17wvrdry29luuxd7hpaqwmz47v0a5ctylez8v5k",
        "pub_key": null,
        "account_number": "15",
        "sequence": "0"
      },
      "original_vesting": [
        {
          "denom": "basecro",
          "amount": "10"
        }
      ],
      "delegated_free": [],
      "delegated_vesting": [],
      "end_time": "1610446371"
    }
  }
}
```

## Continuous vesting account
```
{
  "account": {
    "@type": "/cosmos.vesting.v1beta1.ContinuousVestingAccount",
    "base_vesting_account": {
      "base_account": {
        "address": "cro17xrqjhtsylayn6rv4zaahv2yvtg82hjenf34yd",
        "pub_key": null,
        "account_number": "16",
        "sequence": "0"
      },
      "original_vesting": [
        {
          "denom": "basecro",
          "amount": "20"
        }
      ],
      "delegated_free": [],
      "delegated_vesting": [],
      "end_time": "1610446371"
    },
    "start_time": "1610443408"
  }
}
```

## Periodic vesting account
```
{
  "@type": "/cosmos.vesting.v1beta1.PeriodicVestingAccount",
  "base_vesting_account": {
    "base_account": {
      "account_number": "1",
      "address": "cosmos1s4ss9zquz7skvguechzlk3na635jdrecl0sgy2",
      "pub_key": {
        "@type": "/cosmos.crypto.secp256k1.PubKey",
        "key": "A2a4P4TQ1OKzpfu0eKnCoEtmTvoiclSx0G9higenUGws"
      },
      "sequence": "0"
    },
    "delegated_free": [],
    "delegated_vesting": [],
    "end_time": "3160620846",
    "original_vesting": [
      {
        "amount": "50",
        "denom": "stake"
      }
    ]
  },
  "start_time": "1580309975",
  "vesting_periods": [
    {
      "amount": [
        {
          "amount": "50",
          "denom": "stake"
        }
      ],
      "length": "32"
    }
  ]
}
```
