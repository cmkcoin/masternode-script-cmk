## Installation script :

Installation script is build for Linux Ubuntu 16.04.

The script has been tested for the following VPS provider :

| Provider | Result |
| :---: | :---: |
| OVH  | OK |
| Scaleway  | OK |
| Digitalocean | Not tested |
| Vultr  | OK |

VPS provider are configuring Linux core in their own way that can cause error in script. Please reports if you test it on another provider listed above.

To launch the installation, connect to your VPS via SSH and run this command :

```bash
wget https://raw.githubusercontent.com/cmkcoin/masternode-script-cmk/master/install_mm.sh && chmod +x install_mm.sh && ./install_mm.sh
```

Follow the on-screen instructions.


---

---
## Error troubleshooting : 
If for some reason you dont have Git installed, you can install git with the following command:

```bash
sudo apt-get install git -y
```

If script doesn't start : 
- Check that you have write permission in the current folder
- Check that you can change permission on a file
