## ttnctl downlink

Send downlink messages to the network

### Synopsis


ttnctl downlink sends a downlink message to the network

The DevEUI should be an 8-byte long hex-encoded string (16 chars), whereas the
TTL is expected to define a Time To Live in a handy format, for instance: "1h"
for one hour.

```
ttnctl downlink [DevEUI] [Payload] [TTL]
```

### Options inherited from parent commands

```
      --app-eui string              The app EUI to use
      --config string               config file (default is $HOME/.ttnctl.yaml)
      --mqtt-broker string          The address of the MQTT broker (default "staging.thethingsnetwork.org:1883")
      --ttn-account-server string   The address of the OAuth 2.0 server (default "https://account.thethingsnetwork.org")
      --ttn-handler string          The net address of the TTN Handler (default "staging.thethingsnetwork.org:1782")
      --ttn-router string           The net address of the TTN Router (default "staging.thethingsnetwork.org:1700")
```

### SEE ALSO
* [ttnctl](ttnctl)	 - Control The Things Network from the command line

###### Auto generated by spf13/cobra on 15-Apr-2016