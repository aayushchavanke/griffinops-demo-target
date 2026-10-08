# 🌐 GriffinOps Live Demo Web Target

This repository contains the standalone, live web target application monitored by **GriffinOps (Autonomous AI SRE Copilot Platform)**.

---

## 🚀 1-Click Hosting

Because this application is a pure, zero-dependency static web app (index.html), it can be hosted in seconds on:
- **Vercel** (ercel deploy)
- **Netlify** (Drag-and-drop or GitHub integration)
- **GitHub Pages** (Settings -> Pages -> Deploy from Branch: main / oot)
- **Cloudflare Pages**

---

## 📡 Connecting to Your GriffinOps Backend

1. Open your deployed demo web target.
2. In the **"1. GriffinOps Backend Server URL"** input field, paste your hosted GriffinOps backend URL:
   https://your-griffinops-deployment.onrender.com
   *(Or keep http://localhost:8000 for local testing)*
3. Click **Connect**. The status indicator will turn green: **CONNECTED (Online)**.
4. Select an API key generated in your GriffinOps dashboard.
5. Use the action buttons to stream live telemetry:
   - **⚡ Send Normal Telemetry Ping** (35 ms, HTTP 200)
   - **🐢 Simulate High Latency** (680 ms slow database query anomaly)
   - **💥 Simulate Server Error** (1250 ms, HTTP 500 outage spike)

You will see immediate pre-mortem alert cards and live streaming logs in your GriffinOps Executive Overview!
