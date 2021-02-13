# setwlanflt

I am a script to activate/deactivate MAC filtering for WLAN in the
TP-LINK "54M Wireless ADSL2+ Modem Router" (firmware version: "3.0.1
Build 100901 Rel.23594").

Call me as follows, where 1 turns on filtering, 0 turns it off:

```
$ ./onoff 1
Activated
$ ./onoff 0
Deactivated
```

Call me as follows to deactivate filtering for a period of time:

```
$ ./pause 30m
Deactivated
Waiting...
Activated
```

Router login and password are assumed to be in `.netrc`.
