# Reverse Engineering Projects

Professional portfolio showcasing reverse engineering skills using Python, C++, and specialized tools. Organized by challenge type with detailed writeups, code, and analysis.

## Featured Projects

| Project | Description | Tools Used | Difficulty | Status |
|---------|-------------|------------|------------|--------|
| [Coming Soon] | Python Crackme Analysis | Python, uncompyle6, dis | Beginner | 📝 In Progress |
| [Coming Soon] | Binary Exploitation CTF | Ghidra, pwntools, GDB | Intermediate | 📝 In Progress |
| [Coming Soon] | Malware Sample Analysis | YARA, Volatility, Radare2 | Advanced | 📝 Planned |
| [Coming Soon] | Firmware Reverse Engineering | Binwalk, Ghidra, UART | Expert | 📝 Planned |

## Table of Contents

### 🐍 Python Reverse Engineering
- [Python Crackme Challenges](#python-crackme-challenges)
- [Bytecode Analysis](#bytecode-analysis)
- [Pyc Decompilation](#pyc-decompilation)

### 🔧 Binary Analysis
- [ELF Analysis](#elf-analysis)
- [PE File Dissection](#pe-file-dissection)
- [Binary Exploitation](#binary-exploitation)

### 🛡️ Malware Analysis
- [HashMalwareDetector Analysis](malware-detection/Hash%20Malware%20Detector%20Analysis.md)
- [Dynamic Analysis](#dynamic-analysis)
- [Behavioral Analysis](#behavioral-analysis)

### ⚙️ Firmware & Embedded
- [Firmware Extraction](#firmware-extraction)
- [Embedded Protocol RE](#embedded-protocol-re)

## Project Structure Template
```
reverse-engineering/
├── projects/
│ ├── project-name/
│ │ ├── README.md # Detailed writeup
│ │ ├── src/ # Original binaries/samples
│ │ ├── analysis/ # Disassembly, scripts
│ │ ├── tools/ # Custom scripts/tools
│ │ ├── output/ # Results, flags, IOCs
│ │ └── screenshots/ # Visual documentation
│ └── ...
├── tools/ # Reusable utilities
├── docs/ # Methodology guides
└── README.md
```

## Quick Start

1. **Clone**: `git clone https://github.com/YOUR_USERNAME/reverse-engineering`
2. **Browse**: Navigate `/projects/` for individual challenges
3. **Tools**: See `/tools/` for reusable Python automation scripts
4. **Setup**: Python 3.10+, pip install -r requirements.txt per project

## Skills Demonstrated

Core Skills:
```
├── Python automation & scripting
├── Binary disassembly (Ghidra, IDA Free)
├── Debugger proficiency (GDB, x64dbg)
├── Malware analysis workflows
├── CTF problem solving
└── Documentation & reproducible research
```

## Tech Stack

| Category | Tools |
|----------|-------|
| **Disassemblers** | Ghidra, Radare2, Binary Ninja (Community) |
| **Debuggers** | GDB, WinDbg, x64dbg |
| **Python** | pwntools, uncompyle6, Capstone |
| **Malware** | YARA, PEiD, Volatility3 |
| **Firmware** | Binwalk, Jeff's tools |

## Contribution Guidelines

- Fork → Branch → PR with clear project writeup
- Follow project folder template exactly
- Include reproducible steps + original samples
- Screenshots must show your analysis process

## License

MIT License - Free for educational/portfolio use.

---

*Built for Computer Science skill demonstration. Updated Feb 2026.*
