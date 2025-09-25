---
marp: true
theme: default
class: invert
---

# Brief History of Hybrid Development

"Write once, run anywhere"

![bg right fit](../assets/freeza.png)

---

# Hybrid Techniques over the years

![timeline](../assets/timeline-hybrid-techniques.png)

[Timeline](https://app.excalidraw.com/s/7WzUqRCDEgA/2LptH1giHHK)

---

# Performance Evolution

| Approach | Performance Level | Examples |
|----------|------------------|----------|
| **Webview-based** | Lowest | PhoneGap, Cordova, Ionic, Capacitor |
| **Bridge-based** | Improved | NativeScript |
| **Custom Engine** | Near-native | Flutter, React Native |
| **Compiled Native** | Native | Xamarin, KMM |
| **Compiler-optimized** | Excellent | Svelte Native |

---

# Code Sharing Approaches

| Framework Type | Code Sharing | Approach |
|----------------|--------------|----------|
| **Webview** | ~100% | Nearly complete sharing, compromised UX |
| **React Native/NativeScript** | ~70-90% | Shared code with platform-specific adjustments |
| **Flutter** | ~90-95% | Shared code with custom rendering |
| **KMM/Xamarin** | ~50-70% | Shared business logic, platform-specific UI |
| **PWA/Capacitor** | Variable | Web-first with optional native capabilities |

---

# It is all about balance

<style>
.three-column {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 20px;
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.column {
  flex: 1;
  text-align: center;
}

.column img {
  width: 100%;
  max-width: 200px;
  height: auto;
  border-radius: 4px;
  margin-bottom: 10px;
}

.caption {
  font-size: 14px;
  color: #666;
  font-style: italic;
  margin-top: 8px;
}
</style>

<div class="three-column">
  <div class="column">
    <img src="../assets/machine-lang.png" alt="Machine Language">
    <div class="caption">Xamarin / Flutter</div>
  </div>
  <div class="column">
    <img src="../assets/webview-only.png" alt="WebView Only">
    <div class="caption">PhoneGap / Cordova / Ionic</div>
  </div>
  <div class="column">
    <img src="../assets/react-native.png" alt="React Native">
    <div class="caption">React Native</div>
  </div>
</div>

---

![bg fit](../assets/js-frameworks.png)

---

![bg fit](../assets/mobile-frameworks.png)

---

![bg fit](../assets/mobile-frameworks-chart.png)

---

![bg fit](../assets/rn-is-the-best.png)

---

# Future of Hybrid Development

> "Write ~~once~~ less, run ~~any~~ somewhere"

- Aim for the best platform experience
- Share what makes sense
- One size doesn't fit all
- Line between web and app continues to blur
