<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=22&duration=3500&pause=600&color=6C47FF&center=true&vCenter=true&width=500&lines=mcp7x;pentest+%26+programming" alt="mcp7x"/>
</p>

```python
class mcp7x:
    discord   = "mcp7x"
    langs     = ["Python", "Rust", "C", "TypeScript", "Go"]
    domains   = ["binary analysis", "tool development", "network security", "cryptography"]
    projects  = ["SpectreC2", "Shroud", "pentest-toolkit"]

    def __str__(self):
        return "security engineer — offensive tooling & low-level research"
```

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
</p>

---

### projects

**[/SpectreC2](https://github.com/pythernel/SpectreC2)** — Encrypted C2 framework. AES-256-GCM beaconing over HTTP/JSON with REST API task management. Multi-platform implants with modular command routing (shell, file ops, process injection). SQLite-backed listener and agent persistence.

**[/Shroud](https://github.com/pythernel/Shroud)** — Windows PE crypter. Iterates COFF section table, applies XOR encryption to `.text` and `.rdata` sections, then appends a polymorphic loader stub. The stub resolves `kernel32.dll` at runtime, decrypts sections in place, and jumps to the original entry point.

**[/pentest-toolkit](https://github.com/pythernel/pentest-toolkit)** — Six offensive security modules:
- Async TCP port scanner with banner grabbing and 104 service signatures
- PE structure analyzer (DOS/NT headers, sections, import/export directories)
- Raw socket packet sniffer — Ethernet, IP, TCP, UDP, ICMP parsing
- Shellcode injector — local thread, callback (`EnumWindows`), remote process
- Exploit dev utilities — cyclic pattern, ROP gadget search, bad char analysis, XOR/ADD encoders, buffer builder
- Crypto toolkit — hash identifier (15 types), wordlist cracker, XOR bruteforce with crib dragging, base64/32/16 detection

---

### focus

| area | |
|------|---|
| **binary** | PE/ELF internals, x86/x64 asm, Windows API, process injection, memory dumping and analysis |
| **network** | raw sockets, protocol parsing, packet capture/analysis, C2 infrastructure design and deployment |
| **crypto** | AES-256-GCM, XOR analysis and bruteforce, hash identification and cracking, crib dragging |
| **stack** | Python, Rust, C, TypeScript, Go — FastAPI, Docker, PostgreSQL, async/await patterns |

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pythernel&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&icon_color=6C47FF&text_color=FFFFFF&title_color=6C47FF&hide=contribs" height="140"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=pythernel&theme=dark&hide_border=true&background=0D1117&stroke=6C47FF&ring=6C47FF&fire=6C47FF&currStreakLabel=6C47FF" height="140"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pythernel&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&text_color=FFFFFF&title_color=6C47FF&langs_count=6" height="140"/>
</p>

<p align="center">
  <a href="https://discord.com/users/mcp7x"><img src="https://img.shields.io/badge/Discord-mcp7x-5865F2?style=flat-square&logo=discord&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=pythernel&color=6C47FF&style=flat-square&label=profile+views"/>
</p>
