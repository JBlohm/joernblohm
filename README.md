```python
from dataclasses import dataclass, field
from typing import List

@dataclass
class Joern:
    location:   str       = "Hamburg, Germany"
    day_job:    str       = "Global IT Infrastructure Manager"
    night_job:  List[str] = field(default_factory=lambda: [
        "Options Trader",   # theta / premium selling
        "Vibe Coder",
    ])
    tech_stack: List[str] = field(default_factory=lambda: [
        "Python", "MicroPython", "SQL", "ESP32", "ESP8266", "Azure", "AWS"
    ])
    platforms:  List[str] = field(default_factory=lambda: ["macOS", "Linux"])
    ai_tools:   List[str] = field(default_factory=lambda: [
        "Claude Code", "Codex", "Gemini", "LM Studio"
    ])
    languages:  List[str] = field(default_factory=lambda: ["German", "English"])
```

---

## Day job — IT Infrastructure

| | |
|---|---|
| **Role** | Global IT Infrastructure Manager |
| **Focus** | Stakeholder management, cross-departmental collaboration, budget planning, coordination of external service providers, integration of AI tooling |

---

## Night job — Options Trading & Vibe Coding

| | |
|---|---|
| **Strategy** | Theta / premium selling — 27-symbol, 66-leg portfolio, delta-neutral bias, IVR-driven entries, Hedge Fund like methodology |
| **Tooling** | Custom MCP API (`theta-portfolio`) with 14 live endpoints: greeks, P&L, risk boundaries, option chain ladder |
| **Research** | Multi-LLM trading agents — autonomous futures trading system with collaborative agent architecture and persistent markdown-based learning |
| **Vibe Coding** | AI-assisted development with Claude Code, Codex, Gemini & LM Studio |

---

## Education

| | |
|---|---|
| **MBA** | Open University, Milton Keynes, UK |

---

## Side projects & interests

**DIY & hobbies**
Growing lemon trees from seed · Italian cooking · Drawing & Art

---

## Philosophy

> Validated claims over speculation. Precise framing over approximation.  
> Build the tooling first — then let it trade, automate, and monitor while you sleep.  
> Things work 100%, most of the time, until they don't. Risk management is key.

---

## How to reach me

- 📍 Hamburg, Germany
- 📧 joeblohm@proton.me
- 💼 [linkedin.com/in/joernblohm](https://www.linkedin.com/in/joernblohm/)
- 🌐 Languages: German · English
