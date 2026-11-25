# BlendPal (v1.4.8)

A lightweight, zero-dependency, multi-provider AI assistant for **Blender 4.2 – 5.x** (4.2 LTS, 4.5 LTS, and 5.0–5.3+).
Bring your own API key (OpenRouter, OpenAI, Anthropic, Google Gemini, DeepSeek, or Custom endpoints) or run completely free with **Local Ollama**.

## Key Features
- **Native Quick Pop-up Chat (`Alt + ~` / Grave Accent) & Live Shortcut Finder (`Ctrl + ;`):** Press **`Alt + Grave Accent`** anywhere for Quick Chat, or **`Ctrl + ;`** to search your **actual Blender Preferences keymap** live ($0 instant search across operators, menus, pie menus, and context toggles, with optional AI fallback).
- **Any AI Provider + Searchable Model Dropdowns + Recommended Models Popup + Live Cost Tracker:** Fetch live model lists directly from your provider, assign different models per task, pick from tiered per-task **Recommended Models** with live pricing in 1 click, track per-call & session tokens/`$` cost (or `FREE`), and check your live OpenRouter credit balance right inside Add-on Preferences.
- **3-Layer Official Docs Grounding:** Version-locked `docs.blender.org` system prompt, live local Blender scene/RNA inspection, and optional OpenRouter Web Search verification.
- **Live 3D Viewport Vision & Render Critique:** Attach a live 3D Viewport screenshot or active Image Editor Render Result with one click.
- **1-Click Run Code in Chat:** Execute Python blocks right from chat responses with Undo support and automatic Fix Script on error.
- **AI Material Suite (Procedural, Multi-Map Auto-PBR, In-Place Edit & Image-to-Material):** Generate procedural shader nodes (with Linear RGB guardrails), Auto-PBR textures with Triplanar Blend, AO Cavity Darkening, and optional Cycles Displacement, edit existing materials in place, or convert any reference photo/viewport snapshot into a procedural material via Vision -> Shader AI.
- **AI World / Environment Builder:** Apply instant `$0` World presets (Nishita Golden Hour, Overcast Studio Dome, Dark Product Studio, Twilight Volumetric Mist) or describe any custom World Shader for AI to build.
- **One-Click Studio Lighting Rig:** Auto-scaled 3-Point Studio, Product Rim, Overhead Softbox, and Studio World + Fill rigs aimed at your selection, with optional cyclorama backdrop.
- **Instant Local Scene Health Audit ($0 API cost):** Scan for unapplied/negative scale, missing or unpacked textures, heavy modifiers, orphan datablocks, and render/AgX settings with 1-click local fixes and optional AI advice.
- **Right-Click Explain + Full Node Tree Explainer:** Right-click any property, operator, modifier, or node — or explain an entire Shader / Geometry Node graph in one click.
- **Outliner Organizer & Batch Object Renamer:** Auto-sort objects into collections or standardize messy object names with full Undo.
- **Python Script Studio & Presets:** Generate, Edit, Fix, Test, and save reusable Script Presets.
- **Reference Image & Seamless Texture Generator:** Generate references or flat tileable PBR albedo textures straight into Blender's Image Editor.

## Installation
1. Go to **Edit -> Preferences -> Add-ons -> Install from Disk...** and select `blendpal-v1.4.8.zip`.
2. Enable **3D View: BlendPal**.
3. Choose your Provider, paste your API key (not needed for Local Ollama), and click **Test Connection & Fetch Models**.
4. Open the sidebar (`N`) in the 3D Viewport, Image Editor, Node Editor, or Text Editor -> **BlendPal** tab, or press **`Alt + Grave Accent`** (`Alt + ~` / Grave Accent) anywhere to open the Quick Pop-up Chat.
