# idenLib.py

[`idenLib`](https://github.com/secrary/idenLib) (Library Function Identification ) plugin for `IDA Pro`

![ida_boost_2](https://user-images.githubusercontent.com/16405698/52437166-1bf3a680-2b0e-11e9-8212-7f017757133b.gif)

## Getting Started
When analyzing malware or 3rd party software, it's challenging to identify statically linked libraries and to understand what a function from the library is doing.

[`idenLib.exe`](https://github.com/secrary/idenLib) is a tool for generating library signatures from `.lib`/`.obj`/`.exe` files.

[`idenLib.dp32`/`idenLib.dp64`](https://github.com/secrary/idenLibX) is a [`x32dbg`/`x64dbg`](https://x64dbg.com) plugin to identify library functions.

[`idenLib.py`](https://github.com/secrary/IDA-scripts/tree/master/idenLib) is an [`IDA Pro`](https://www.hex-rays.com/products/ida/index.shtml) plugin to identify library functions.

### Prerequisites
下載 [`idenLib`](https://github.com/secrary/idenLib) 專案，用 `GitHub Desktop` 下載會一併下載[`zstd @ 197a573`](https://github.com/facebook/zstd/tree/197a5737c87730470213d8d3ee6a3fbbd712ba5b) 和 [`zydis @ f4431f2`](https://github.com/zyantific/zydis/tree/f4431f2d78fdd8f15e5fa0a55fa3ca800742476a)

### Build
需要用到`Windows SDK`用 
### Usage
- Copy the plugin under `plugins` folder
- Copy signatures under `SymEx` folder
- Install dependencies: [`zstd`](https://pypi.org/project/zstd/) and [`capstone`](https://pypi.org/project/capstone/) (`pip2 install zstd capstone`)

- You need to refresh signatures after adding new signature files
![refresh](https://user-images.githubusercontent.com/16405698/53285741-15933a80-375c-11e9-97cb-d38bb0b5c52e.png)


## Credits
- Disassembly powered by [Capstone](https://www.capstone-engine.org/)
- Decompressing powered by [zstd](https://github.com/facebook/zstd)
- Icon by [freepik](https://www.flaticon.com/authors/freepik)