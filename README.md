## Setup
```sh
snap install ./scapy_2.4.5_amd64.snap --dangerous
snap connect scapy:network-control
sudo scapy
```

## Hello World
```python
>>> send(IP() / TCP() / "Hello, world!")
```

## Going Further
Refer to the original [project](https://github.com/secdev/scapy) and [documentation](https://scapy.readthedocs.io/en/latest/).
