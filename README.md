<div align="center">
  <h1>Samael - Local DDoS Toolkit (Educational)</h1>
  <i>a simple local DDoS toolkit for testing & educational purposes.</i>
</div>

---

## Features

- HTTP Flood (mass HTTP requests)
- TCP Flood (raw TCP packets)
- Minecraft Bots (spam bots)

---

## How it Works

- Next.js frontend connects to Fastify backend via WebSocket.  
- Frontend provides a UI to configure & launch attacks.  
- Backend executes attacks using your local resources.

---

## Usage

```bash
git clone https://github.com/pablemus616/samael-mini-ddos-stresser-tool.git
cd samael-mini-ddos-stresser-tool
npm i
npm run dev
Open the frontend UI at http://localhost:3000
Configure your attack (target, method, packet size, etc.) and launch.
```

---

## Notes

- Runs locally and depends on your machine’s bandwidth & CPU.
- Intended for stress-testing your own servers/services.
- Not for illegal or malicious use.
