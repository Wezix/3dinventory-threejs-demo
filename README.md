[Live Demo](https://fairygui.com/threejs-demo/3d/)

![](images/20200609-221718.png)

# How to run

## Development (with hot reload)
```bash
npm install
npm start
```

## Production build
```bash
npm install
npm run build
```
Then open `build/index.html` in your browser.

## WebXR / VR Support

This project includes WebXR support! A "ENTER VR" button will appear when:
- You're using a VR-capable device (Quest, Vive, etc.)
- Your browser supports WebXR (Chrome, Edge, Firefox Reality, etc.)
- The page is served over HTTPS (required for WebXR)

**Note:** WebXR requires HTTPS. When deployed to Vercel, HTTPS is automatic. For local testing with a VR headset, you may need to use a tool like [ngrok](https://ngrok.com/) to create an HTTPS tunnel.