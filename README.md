
[![version](https://img.shields.io/badge/version-1.0.1-yellow.svg)](https://semver.org)

# Raspberry Pi / Ubuntu easy Python installer

An easy way to install a new Python version on a Raspberry Pi. Works also on Ubuntu!

## Installation

No real installation needed.

You can simply run this installer by

```bash
wget -qO - https://raw.githubusercontent.com/kitoborcom/python-installer/main/python.sh | sudo bash -s [python_verion]
```

fill in the Python version you want at `[python_verion]`

So, if you want to install version 3.8.8 do:

```bash
sudo wget -qO - https://raw.githubusercontent.com/kitoborcom/python-installer/main/python.sh | sudo bash -s 3.8.8
```
on your Raspberry Pi.

For 3.10 do
```bash
wget -qO - https://raw.githubusercontent.com/kitoborcom/python-installer/main/python.sh | sudo bash -s 3.10.0
```

For 3.11 **Alpha** do
```bash
wget -qO - https://raw.githubusercontent.com/kitoborcom/python-installer/main/python.sh | sudo bash -s 3.11.0a1
```


## Versions

* 1.0.1 / 21 Okt 2021 (Minor changes with Sudo)
* 1.0.0 / 26 sept 2021 (First Release)


---
**NOTE**

This script updates your Raspberry Pi OS !!! If you don't want to update the OS DO NOT USE THIS SCRIPT!

---

### MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Get your copy of the [MIT](https://choosealicense.com/licenses/mit/) License.
