# 🔢 Java Prime Checker Free

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4,22,14&height=210&section=header&text=Java%20Prime%20Checker%20Free&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Fast%2C%20Accurate%20Primality%20Testing%20in%20Java&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.2.0-264653?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Java](https://img.shields.io/badge/Java-17%2B-2A9D8F?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.org)
[![License](https://img.shields.io/badge/license-MIT-E9C46A?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Speed](https://img.shields.io/badge/speed-%3C%201ms%20%2F%20test-F4A261?style=for-the-badge&logo=speedtest&logoColor=white)](https://github.com)

<br/>

### ⚡ A free, lightweight Java library & CLI for lightning-fast prime number checking

*🎯 Trial Division • 🧠 Miller-Rabin • 🔢 BigInteger Support • 📦 Zero Dependencies*

<br/>

<a href="https://share.google/clgJ3HRSmDKZD9zw8">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD-264653?style=for-the-badge&logo=download&logoColor=white&labelColor=19303A" alt="Download" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/clgJ3HRSmDKZD9zw8">
  <img src="https://img.shields.io/badge/🚀_TRY_ONLINE-2A9D8F?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=1E7A70" alt="Try Online" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/clgJ3HRSmDKZD9zw8">
  <img src="https://img.shields.io/badge/📚_DOCS-E9C46A?style=for-the-badge&logo=readthedocs&logoColor=black&labelColor=C2A255" alt="Docs" height="45"/>
</a>

</div>

<img width="1280" height="720" alt="maxresdefault - 2026-11-05T123814 908" src="https://github.com/user-attachments/assets/c04a0d9b-2ffe-445e-9ca4-e0e4bd209c89" />

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Java Prime Checker Free** is a small but powerful library and CLI tool for determining whether a number is prime — with **blazing speed** and **rock-solid accuracy**. It offers multiple algorithms (trial division, deterministic Miller-Rabin, and probabilistic testing) so you can pick the right tradeoff for your use case.

From simple educational demos to cryptographic-scale BigInteger checks — this tool handles it all.

> 💡 **Perfect for:** Students learning number theory, competitive programmers, cryptography projects, and anyone who needs reliable primality testing in Java.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🎯 **Trial Division** | 🧠 **Miller-Rabin** | 🔢 **BigInteger** |
|:---:|:---:|:---:|
| Simple & deterministic<br/>for small numbers | Deterministic for<br/>64-bit integers | Handles 1000-digit<br/>numbers with ease |

| ⚡ **Fast** | 📦 **Zero Deps** | 🖥️ **CLI + Library** |
|:---:|:---:|:---:|
| Sub-millisecond<br/>checks for most inputs | Pure Java — no<br/>external libraries | Use as a library<br/>or from the terminal |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Library

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ⚡ **Blazing Fast** | Checks most 64-bit numbers in under 1 millisecond |
| 🎯 **100% Accurate** | Deterministic Miller-Rabin guarantees no false positives for 64-bit |
| 🔢 **BigInteger Support** | Handles arbitrarily large numbers via probabilistic testing |
| 📦 **Zero Dependencies** | Pure Java, no external libraries — drop in and use |
| 🖥️ **CLI Included** | Batch-check lists of numbers from the terminal |
| ✅ **Fully Tested** | 10,000+ unit tests against known prime databases |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 CLI Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🔢  Java Prime Checker Free  v2.2.0             ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  >> check 97                                     ║
║  ✅ 97 is PRIME                                  ║
║  ⏱️ 0.02ms  🧠 Method: trial division            ║
║                                                  ║
║  >> check 561                                    ║
║  ❌ 561 is COMPOSITE (3 × 11 × 17)               ║
║  ⏱️ 0.05ms                                       ║
║                                                  ║
║  >> check 2^61-1                                 ║
║  ✅ 2305843009213693951 is PRIME                 ║
║  ⏱️ 0.42ms  🧠 Method: Miller-Rabin              ║
║                                                  ║
║  >> batch primes.txt                             ║
║  ✅ Processed 1,000 numbers in 0.38s             ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🔢 java-prime-checker-free/
├── 🎯 src/main/java/
│   └── com/example/prime/
│       ├── PrimeChecker.java      # Main API
│       ├── TrialDivision.java
│       ├── MillerRabin.java
│       └── cli/                   # Command-line interface
├── 🧪 src/test/java/              # JUnit tests
├── 📖 examples/                   # Library usage snippets
└── 📚 docs/                       # API reference & notes
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a number that gives wrong results? Want to add a new algorithm?

<div align="center">

<a href="https://share.google/clgJ3HRSmDKZD9zw8">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/clgJ3HRSmDKZD9zw8">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-264653?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/clgJ3HRSmDKZD9zw8">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-E9C46A?style=for-the-badge&logo=github&logoColor=black" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🔢 Made with ⚡ by the Prime Checker Team

*If this library saved you time — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4,22,14&height=120&section=footer" width="100%"/>

</div>
