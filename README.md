## 👋 Welcome to headscale 🚀

Headscale - Tailscale control server

## 📋 Description

Tailscale control server

## 🚀 Services

- **app**: Headscale (`headscale/headscale:latest`)

## 📦 Installation

```shell
composemgr install headscale
```

## 🔧 Configuration

```shell
TZ=America/New_York
BASE_HOST_NAME=headscale.example.com
```

## 🌐 Access

- **Headscale**: http://localhost:8080

## 📂 Volumes

- `./rootfs/data/headscale` - Application data

## 🔐 Security

- Change default passwords
- Configure HTTPS with reverse proxy
- Regular backups

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
