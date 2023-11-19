# Systemd Containers

Some Podman Quadlets systemd units.

```
# clone the repo
git clone https://codeberg.org/imMaturana/systemd-containers ~/.config/containers/systemd

# reload systemd daemon
systemctl --user daemon-reload

# enable the services
systemctl --user enable --now {ipfs,i2pd,syncthing}.services
```

Don't forget to configure your browser proxy.

## Services

- [I2Pd](https://i2pd.website)
- [IPFS](https://ipfs.tech)
- [Syncthing](https://syncthing.net)


## Where is Tor?

I don't recommend you to use a Tor proxy, [Tor Browser](https://www.torproject.org/download/) exists for a reason.
