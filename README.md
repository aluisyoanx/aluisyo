# Aluisyo Core (CLI)
Latest Release: v0.0.2
Maintained by Aluisyo.

## Warning: This is Highly Experimental for testing purposes, Use at own Risk!

## Information
### Aluisyo

The Future Of Blockchain Banking

Aluisyo is a decentralized cryptocurrency based on cryptonote with blockchain banking features and secure messaging.
Aluisyo is a fairly launched coin without any premine, ico or dev fee.

- Coin Name: Aluisyo
- Genesis Date: 25-02-19
- Ticker: ANX
- Address Prefix: aNX
- POW Algo: Cryptonight Original
- Max Supply: 200 million
- Block Time: 120 seconds
- Block Reward: smoothly increasing, starting from 5 all the way up-to 50
- Ports:
- P2P: 18001
- RPC: 19000


## Resources
- Web: [aluisyo.network](https://aluisyo.network/)
- GitHub: [https://github.com/aluisyonetwork/aluisyo-core](https://github.com/aluisyonetwork/aluisyo-core)
- Discord: [https://discord.gg/rbyNZRz](https://discord.gg/rbyNZRz)
- Our BitcoinTalk: https://bitcointalk.org/index.php?topic=5114934
- Our Telegram: https://t.me/joinchat/I5RElgnalLDhSHTQBjSluA

### [Block Explorers] 
- https://explorer.aluisyo.network/
- https://node.aluisyo.network/

### [Pools] 
- https://cnpool.cc/anx
- https://coinsforhash.com/aluisyo/


## Compiling Aluisyo from source

### Linux / Ubuntu

##### Prerequisites

- You will need the following dependencies to build the Aluisyo CLI: boost, cmake, git, gcc, g++, python, and make.
- On Ubuntu: `sudo apt-get install -y build-essential python-dev gcc g++ git cmake libboost-all-dev`

#### Building

- `git clone https://github.com/aluisyonetwork/aluisyo-core`
- `cd aluisyo-core`
- `mkdir build && cd $_`
- `cmake ..`
- `make`

If the build is successful the binaries will be in the src folder.

### Windows 10

##### Prerequisites

- Install [Visual Studio 2017 Community Edition](https://www.visualstudio.com/thank-you-downloading-visual-studio/?sku=Community&rel=15&page=inlineinstall)
- Install [CMake](https://cmake.org/download/)
- When installing Visual Studio, you need to install **Desktop development with C++** and the **VC++ v140 toolchain** components. The option to install the v140 toolchain can be found by expanding the "Desktop development with C++" node on the right. You will need this for the project to build correctly.
- Install [Boost 1.67.0](https://boost.teeks99.com/bin/1.67.0/), ensuring you download the installer for MSVC 14.1.

##### Building

- From the start menu, open 'x64 Native Tools Command Prompt for vs2017' or run "C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\Common7\Tools\VsMSBuildCmd.bat" from any command prompt.

- `https://github.com/aluisyonetwork/aluisyo-core`
- `cd aluisyo-core`
- `mkdir build`
- `cd build`
- `cmake -G "Visual Studio 15 2017 Win64" -DBOOST_LIBRARYDIR:PATH=c:/local/boost_1_67_0 ..` (Or your boost installed dir.)
- `msbuild aluisyo.sln /p:Configuration=Release /m`

If the build is successful the binaries will be in the src/Release folder.

#### Special Thanks
Special thanks goes out to the developers from The Circle Team (Conceal Network), Cryptonote, Bytecoin, Monero, Forknote, TurtleCoin, and Masari.
