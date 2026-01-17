# Space Shooters (Web + PWA)

Space Shooters is a top-down space survival game with smooth drift movement, upgrade rarities, rare drops, and boss arena fights every 10 levels. Built as a **web game** that can also be installed as a **PWA** on iOS/Android.

---

## Play / Run Locally (recommended)

> PWAs (service workers + offline) do **not** work from `file://` (double-clicking the HTML).  
> You must run it from a web server.

### Option A: VS Code (easiest)
1. Install **Visual Studio Code**
2. Install the **Live Server** extension
3. Open the project folder in VS Code
4. Right-click `index.html` → **Open with Live Server**

### Option B: Python simple server
From the project folder:
```bash
python3 -m http.server 8000
