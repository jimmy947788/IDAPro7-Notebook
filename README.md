
<!-- ABOUT THE PROJECT -->
## IDA Pro 筆記

<!-- GETTING STARTED -->
### 官方文件
* [IDA Help: Environment variables](https://www.hex-rays.com/products/ida/support/idadoc/1375.shtml)
* [Python 3.9 support for IDA 7.5](https://hex-rays.com/blog/python-3-9-support-for-ida-7-5/)
* [IDA and common Python issues](https://hex-rays.com/blog/ida-and-common-python-issues/)
* [Intended audience](https://hex-rays.com/products/ida/support/ida74_idapython_no_bc695_porting_guide.shtml)
* [Installing PIP packages, and using them from IDA on a 64-bit machine](https://hex-rays.com/blog/installing-pip-packages-and-using-them-from-ida-on-a-64-bit-machine/)
* [Hex-Rays Microcode API vs. Obfuscating Compiler](https://hex-rays.com/blog/hex-rays-microcode-api-vs-obfuscating-compiler/)

### IDA Plugins
* [idaplugins-lis](https://github.com/onethawt/idaplugins-list) 列出常用的Plugin
* [d810](https://github.com/joydo/d810) 演算法反混淆
    - 要先安裝Python套件 [z3](https://github.com/Z3Prover/z3)
* [Lucid](https://github.com/gaasedelen/lucid) Hex-Rays Microcode Explorer
* [keypatch](https://github.com/keystone-engine/keypatch) 更容易編輯 opcode 打上patch
    - 要先安裝Python套件 [Keystone](https://www.keystone-engine.org/)
* [idenLib](plugins/idenLib/) 識別第三方函數庫的名稱
* [findcrypt-yara](https://github.com/polymorf/findcrypt-yara) 找加密方式的插件
  - 要先安裝Python套件 [yara-python](https://github.com/VirusTotal/yara-python)


###  其他
* [arybo](https://pythonhosted.org/arybo/) 布林代&Bit運算，d810優化flow後的log提示可以化簡則可以用它來計算
* [D810: 為 IDA Pro 建立一個可以反混淆的Plugin](https://eshard.com/posts/d810-deobfuscation-ida-pro) 
