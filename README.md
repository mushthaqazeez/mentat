# Mentat 👁️⚡

> *"It is by will alone I set my mind in motion. It is by the juice of Sapho that thoughts acquire speed, the lips acquire stains, the stains become a warning. It is by will alone I set my mind in motion."* — **Frank Herbert, Dune**

**Mentat** is a high-speed cognitive browser pilot (Manifest V3) that provides **sub-15ms voice and natural language motor control over any website**, powered by local System 1 ModernBERT decision inference.

[![Manifest V3](https://img.shields.io/badge/Chrome%20Extension-Manifest%20V3-blue.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg)](./LICENSE)
[![Engine](https://img.shields.io/badge/Engine-System%201%20ModernBERT-blueviolet)](#)
[![Voice-to-Action](https://img.shields.io/badge/Voice--to--Action-Zero--Latency-success)](#)
[![Cloud API Cost](https://img.shields.io/badge/Cloud%20Cost-%240.00-orange)](#)

---

## ⚡ Why Mentat?

Today's web automation agents (like OpenAI Operator or Anthropic Computer Use) send high-res screenshots over the internet to cloud LLMs, waiting **2,000ms–4,000ms** for every click and costing dollars per task.

**Mentat replaces this with a digital nervous system running directly in your browser tab:**
* **Instant Voice-to-Action:** Press `Alt + M`, speak your intent (*"Click on repositories"*, *"Search for mechanical keyboards"*, *"Open billing settings"*), and watch Mentat execute the action in milliseconds.
* **Sub-15ms Semantic Grounding:** Evaluates all visible interactive DOM candidates at 60 FPS using calibrated decision primitives (`resolveChoice`, $T=1.1692$).
* **Zero Cloud Latency & $0 Cost:** Runs 100% on local hardware using the browser's native engine. No external API keys or server backends required.
* **Complete Sovereign Privacy:** Your screen, passwords, and private data never leave your machine.

---

## 🏗️ How It Works

```text
[ User Voice or Keyboard Input ]  -->  "Click on billing settings"
                |
                v
      [ Mentat HUD (Alt+M) ]     -->  Built-in Web Speech API / Text
                |
                v
  [ DOM Interactive Harvester ]   -->  Scans all visible interactive nodes at 60 FPS
                |
                v
  [ Mentat Decision Engine ]      -->  resolveChoice() ranks candidates in ~14ms
                                       resolveNoul() verifies actionability
                |
                v
  [ Cybernetic Target Lock Ring ] -->  Draws glowing spice-amber HUD bracket
                |
                v
    [ Native Motor Dispatcher ]   -->  Smooth auto-scroll, focus, type, and click
```

---

## 🚀 Quick Install (Chrome / Edge / Brave / Opera)

1. Clone or download this repository:
   ```bash
   git clone https://github.com/mushthaqazeez/mentat.git
   ```
2. Open your Chromium browser and go to the extensions management page:
   * **Chrome:** `chrome://extensions`
   * **Edge:** `edge://extensions`
   * **Brave:** `brave://extensions`
3. Toggle on **"Developer mode"** in the top-right corner.
4. Click **"Load unpacked"** and select the cloned `mentat/` directory.
5. Pin the **Mentat** extension to your toolbar!

---

## ⌨️ Controls & Shortcuts

| Key / Action | Function |
| :--- | :--- |
| **`Alt + M`** (or `Option + M`) | Summon / Dismiss the floating Mentat HUD |
| **`Escape`** | Close HUD and clear target lock |
| **`Enter`** | Execute typed command |
| **Microphone Button** | Toggle live Voice-to-Action listening |

---

## 💡 Example Commands to Try

Navigate to any website (e.g. GitHub, Stripe, Amazon, or Reddit) and test:

* **Navigation:** *"Click on repositories"*, *"Go to settings"*, *"Open documentation"*
* **Search:** *"Search for mechanical keyboards"*, *"Search for rust async"*
* **Forms & Billing:** *"Open billing and subscription"*, *"Click Sign In"*, *"Click on pricing"*

---

## 🔬 Scientific Architecture & Primitives

Mentat is powered by the **System 1 Decision & Grounding Engine**:
* **Calibrated Temperature Scaling:** $T = 1.1692$ fitted during training for ModernBERT sequence classification heads.
* **Top-1 vs Top-2 Confidence Margins:** Computes relative certainty to reject ambiguous queries before executing motor actions.
* **Binary Noul Verification:** Calibrated $[0.0, 1.0]$ truth value determining if target elements are actionable, safe, and visible.

---

## 📄 License

Distributed under the [MIT License](./LICENSE). © 2026 Mushthaq azeez
