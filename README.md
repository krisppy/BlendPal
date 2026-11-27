# BlendPal & BlendPal Pro (v2.0.0)

A lightweight, zero-dependency, multi-provider AI assistant and studio suite for **Blender 4.2 – 5.x** (4.2 LTS, 4.5 LTS, and 5.0–5.3+).  
Bring your own API key (Google AI Studio, OpenRouter, OpenAI, Anthropic, DeepSeek, or Custom endpoints), use your existing **Google Antigravity CLI (`agy`)**, **Claude Code**, or **OpenAI Codex** subscription at **$0 extra API cost**, or run 100% free offline with **Local Ollama**.

> **Download BlendPal (Standard — Free / $0+ Pay What You Want):**  
> **[Get BlendPal v2.0.0 on Gumroad](https://pkrisppy.gumroad.com/l/blendpal)**
>
> **Upgrade to BlendPal Pro (AI Studio Suite — One-Time Purchase):**  
> **[Get BlendPal Pro v2.0.0 on Gumroad](https://pkrisppy.gumroad.com/l/blendpal-pro)** *(Launch Early-Bird 25% Off with code `EARLYBIRD25` through Dec 25, 2026)*

---

## What's New in v2.0.0
- **Google Antigravity CLI (`agy`) + Live Quota Meter:** Connect your Google subscription at **$0 API cost** with dynamic model discovery, streaming, Vision, built-in image generation, and a live **5-Hour & Weekly Quota Meter** (Gemini & Claude/GPT pools with reset countdowns) right in Preferences and the Sidebar Header.
- **Native Vision Across All 3 Subscription CLIs:** Claude Code CLI now supports native Vision alongside Antigravity CLI and OpenAI Codex CLI.
- **Local `$0` PBR Normal & Height Map Baker:** Instantly bakes tileable Normal and Displacement maps locally inside Blender (powered by bundled `numpy`) for **AI Material Auto-PBR** and **Seamless Texture Generator**.
- **Backup Image Generator Routing:** Route image & texture generation to **Antigravity Built-in ($0)**, **OpenRouter**, **OpenAI**, or **Google AI Studio** while reusing your saved API keys.
- **Live-Refreshing Pop-up Chat & "Roll 3 Ideas":** Smooth live-streaming Quick Pop-up Chat (`Alt + ~`) and scene-aware 3-idea brainstorming cards across all AI prompt dialogs.
- **Cycles Rendered Viewport Capture + Auto Overlay Hiding:** Clean, overlay-free viewport snapshots in Cycles Rendered mode for Viewport Vision & Render Critique.
- **Illustrated v2.0 User's Manual (PDF):** Included with both editions (24 screenshots, synced 1:1 with v2.0.0).

---

## BlendPal vs. BlendPal Pro

### 1. Core AI Assistant & Everyday Tools (Included in Both)
| Capability | BlendPal | BlendPal Pro |
| :--- | :---: | :---: |
| Multi-Provider BYOK (Google AI Studio, OpenRouter, OpenAI, Anthropic, DeepSeek, Custom) + 1-Click Local Ollama | Yes | Yes |
| `$0` API-Cost Subscription CLIs (Google Antigravity + Quota Meter, Claude Code, OpenAI Codex) | Yes | Yes |
| Quick Pop-up Chat (`Alt + ~`), Live Shortcut Finder (`Ctrl + ;`) & "Roll 3 Ideas" Companion | Yes | Yes |
| Live 3D Viewport Vision, Render Critique & Live Node Tree Auto-Context (Shader & GeoNodes) | Yes | Yes |
| AI Material Suite (Procedural, Auto-PBR + Local Normal/Height Baker, In-Place Edit, Img → Mat) | Yes | Yes |
| AI World Builder, AI Geometry Nodes Builder (+ 5 Starter Foundations) & Python Script Studio | Yes | Yes |
| Instant Local Scene Health Audit (`$0`), Outliner Organizer, Batch Renamer & Right-Click Explain | Yes | Yes |
| Illustrated v2.0 User's Manual (PDF) + Ongoing Blender 4.2 – 5.x Updates | Yes | Yes |

### 2. Pro AI Workflows & 130+ Studio Presets (BlendPal Pro)
| Pro Studio Capability | BlendPal | BlendPal Pro |
| :--- | :---: | :---: |
| **AI Image-to-Lighting + Refine Lighting Match (Vision Feedback Loop)** | — | **Yes** |
| **Studio Lighting Library + Live Rig Controller** *(360° Orbit, EV, Kelvin, Hue Shift, Solo/Mute)* | 4 Starters | **50 Pro Rigs (5 Categories) + Live Controller** |
| **AI Image-to-Compositor Look-Dev + Refine Look + Live A/B Controller** | — | **Yes** |
| **Compositor Look-Dev Suite** *(Filmic, Analog Film, Cinema, Product, Stylized)* | — | **40 Pro Looks (5 Categories) + Live A/B** |
| **UV-Free Procedural Materials** *(Metals, Product, Archviz, Glass/Liquids, Stylized)* | — | **40 Pro Shaders (5 Categories)** |
| **AI Auto Character Posing (Text & Reference Photo)** *(Rigify IK, Mixamo, Humanoid, Quadruped, Bird + Mannequins, Blend, Mirror, Keyframe & Vision Refine)* | — | **Yes** |
| **AI Self-Verifying Geometry Nodes Agent + Live Controller** *(Depsgraph Audit, Multi-Pass Auto-Fix, Vision QA & Blender 5.3+ Sliders)* | — | **Yes** |

---

## Installation
1. Download `blendpal-v2.0.0.zip` ([Standard](https://pkrisppy.gumroad.com/l/blendpal)) or `blendpal-pro-v2.0.0.zip` ([Pro](https://pkrisppy.gumroad.com/l/blendpal-pro)) from Gumroad.
2. In Blender, go to **Edit → Preferences → Add-ons → Install from Disk...** and select the `.zip` file.
3. Enable **BlendPal** (or **BlendPal Pro**).
4. Choose your **AI Service** (BYOK API key, `$0` Subscription CLI, or Local Ollama) and click **Connect & Load Models**.
5. Open the sidebar (`N`) in the 3D Viewport, Image Editor, Node Editor, or Text Editor → **BlendPal** tab — or press **`Alt + ~`** (Grave Accent) for Quick Chat or **`Ctrl + ;`** for the Live Shortcut Finder.

## Feedback & Bug Reports
Found a bug or have a feature request? Open an issue in the **[Issues](https://github.com/krisppy/BlendPal/issues)** tab!
