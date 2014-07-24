# LEDBlink for Pinoccio

## Usage

Install Leo and Pinoccio board for leo

```
npm install -g leo leo-board-pinoccio
```

Clone Repository

```
git clone https://github.com/AdamMagaluk/pinoccio-LEDBlink.git
cd pinoccio-LEDBlink
```
Install Dependancies

```
npm install
```

Build

```
leo build -b pinoccio
```

Update Pinoccio

```
leo build -b pinoccio -p /dev/tty.usbmodemXXX
```
