# Kube Homelab

## ChefConf 2019

- [Slides](https://speakerdeck.com/portertech/understanding-habitat-and-kube-a-home-lab-experiment)

## Hardware

### Hosts

Three hosts, each with the following components:

- [Intel NUC6i7KYK](https://www.amazon.com/Intel-NUC-mini-NUC6i7KYK-Core/dp/B01DJ9XS52/ref=sr_1_1?keywords=Intel+NUC6i7KYK&qid=1558666728&s=gateway&sr=8-1)

- [Crucial 16GB DDR4 2400 MT/s](https://www.amazon.com/Crucial-Single-PC4-19200-SODIMM-260-Pin/dp/B019FRBHZ0/ref=sr_1_3?keywords=Crucial+16GB+DDR4+2400&qid=1558666762&s=gateway&sr=8-3)

- [Crucial MX500 250GB SSD](https://www.amazon.com/Crucial-MX500-250GB-2280SS-Internal/dp/B077SL4FZG/ref=sr_1_6?keywords=Crucial+MX500+250GB+SSD&qid=1558666800&s=gateway&sr=8-6)

For a total of:

- 12 CPU cores (2.6GHz)
- 48GB RAM
- 750GB of SSD storage

### Flannel

```
etcdctl set /coreos.com/network/config < flannel.json
```
