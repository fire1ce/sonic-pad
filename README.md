# sonic-pad

Creality Sonic Pad - Ender 3 s1 Pro Configurations

## Allow SHA1 for SSH Access

SSH Config:

```shell
Host sonic-pad
    HostName sonic-pad.3os.re
    User root
    # ForwardAgent yes
    HostkeyAlgorithms +ssh-rsa
    PubkeyAcceptedAlgorithms +ssh-rsa

```

## Printer's Configs Folder Location

```shell
/mnt/UDISK/printer_config
```
