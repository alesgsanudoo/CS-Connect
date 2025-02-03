# CS-CONNECT 🚀

Welcome to **CS-CONNECT**, a simple bash script for managing and connecting to Purdue xinu backend servers! This script is to make your life easier when dealing with server, blacklists, and configurations. 

PD: I did this project for fun and because I was bored and didn't want to do my network homework :)

---

## Table of Contents 📑
1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Configuration](#configuration)
6. [Commands](#commands)
7. [Contributing](#contributing)

---

## Overview 🌟

The **CS-CONNECT** script is a tool that helps you:
- Connect to random or specific servers. (There is no need to use two commands now :D)
- Blacklist broken or unavailable servers.
- Automatically pull and update broken server lists from TA notes.
- Customize configurations.

---

## Features 🎨

- **Random Server Connection**: Don't waste time picking a server, let the script do it for you!
- **Blacklist Management**: Add or remove servers from your blacklist.
- **Auto-Refresh Broken Servers**: Stay updated with the latest list of broken servers from TA notes.

---

## Installation 🛠️

### Prerequisites:
- Access to Purdue's CS servers.

### Steps:
1. Cd into your ~ directory
   ```bash
   cd ~
   ```
3. Clone the script or copy the code into a file named `connect`
   ```bash
   wget https://raw.githubusercontent.com/alesgsanudoo/CS-Connect/7610098ca2ec71bc717d97cdec90486b88a7775a/connect
   ```
4. Make the script executable
   ```bash
   chmod +x connect
   ```
5. Run the script
   ```bash
   ./connect
   ```


## 🌟 Pro Tips

- **Alias the Script**: To save time, create an alias in your `.bashrc` or `.zshrc`:
  ```bash
  alias cc='~/connect'
  ```
- Then do:
  ```bash
  source .bashrc or .zshrc
  ``` 
  Now, you can simply type `connect` to run the script!
---


## Usage 🚀

Here are some examples on how to use it:

### Connect to a Random Server:
```bash
./connect
```

### Connect to a Specific Server:
```bash
./connect galileo10
OR
./connect 10
```

### Add a Server to Blacklist:
```bash
./connect  -a galileo5
```

### Remove a Server from Blacklist:
```bash
./connect  -r galileo5
```

### View All Servers:
```bash
./connect  -l
```

### View Blacklisted Servers:
```bash
./connect  -b
```

### Update Configuration:
```bash
./connect  -s REFRESH_BROKEN=FALSE
```

### To view more help:
```bash
./connect -h
```

---



## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### Happy Connecting! 🌈

Feel free to reach out if you have any questions or suggestions. Enjoy  **CS-CONNECT**! 🚀✨
