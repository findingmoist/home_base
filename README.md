Connects to the network specified in the config whenever it is within range by pausing the Bettercap recon. Once out of range of the specified home network, Bettercap recon is restarted.

## config.toml
```
main.plugins.home_base.enabled = false
main.plugins.home_base.ssid = 'your_home_network'
main.plugins.home_base.password = 'your_home_network_password'
main.plugins.home_base.minimum_signal_strength= -75
```

## Updates
* Testing to make work with jayofelenys 64bit.
* Does not seem to work at this time. 

