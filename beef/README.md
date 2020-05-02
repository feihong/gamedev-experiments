# Beef quickstart

Beef is very new and it doesn't offer a binary for Mac. It's not trivial to get compile the binary right now.

## Prerequisites

```
brew install cmake
```

## Installation

```
git clone https://github.com/beefytech/Beef beef-src
cd beef-src/bin
./build.sh
```

The build results will be in `IDE/dist`.

### Build from latest release

When things are more stable, this might make sense

```
curl -L https://github.com/beefytech/Beef/archive/0.42.2.tar.gz -o beef.tar.gz
tar xvzf beef.tar.gz
cd Beef-0.42.2/bin
./build.sh
```

## Links

- [Beef releases](https://github.com/beefytech/Beef/releases)
- [Building on Linux and MacOS](https://www.beeflang.org/docs/getting-start/building/)
