
# iControl Plugin (currently only for Xfinity Home)

Example config.json:

    {
      "accessories": [
        {
          "accessory": "iControl",
          "name": "Xfinity Home",
          "system": "XFINITY_HOME",
          "email": "your@email.com",
          "password": "<your password>",
          "pin": "<your 4-digit alarm pin code>"
        }
      ]
    }

This plugin works with Xfinity Home systems, but iControl also white-labels their product for other vendors like ADP, so it's possible it may work with other providers. If you have a non-Xfinity-Home system and want to do some hacking, submit a PR to [https://github.com/nfarina/icontrol]().