**1. Install below software in Ubuntu machine**

sudo apt-get install qt5-default

sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils


**2. Clone wallet sources**

```
git clone https://github.com/kredX/kredit.git
```

**3. Set symbolic link to coin sources at the same level as `src`. For example:**

```
git submodule add https://github.com/kredX/kredit.git cryptonote
```

Replace URL with git remote repository of your coin.

**4. Build**

```
mkdir build && cd build && cmake .. && make
```
