# My POP_OS config

## Obtain Config File:

``` bash
dconf dump / >mysettings.conf 
```

## Apply Config:

``` bash
dconf reset -f /
dconf load  / < mysetting.conf
```
