Loading & Running

```
sudo modprobe libcomposite
sudo gt load g_multi.scheme g_multi
```

Loading then Running

```
sudo modprobe libcomposite
sudo gt load g_multi.scheme g_multi --off
gt enable g_multi
```

Saving
```
gt save g_multi --stdout > g_multi.scheme
```

Example

```
BBBSERIALNUM 2516BBBK2626
MASS_STORAGE.IMG /var/cache/doc-beaglebone-getting-started/beaglebone-getting-started-2019-10-31.img
NCM_DEV_ADDR b0:d5:cc:fc:03:02
NCM_HOST_ADDR b0:d5:cc:fc:03:01
RNDIS_DEV_ADDR b0:d5:cc:fc:03:fe
RNDIS_HOST_ADDR b0:d5:cc:fc:03:ff
```
