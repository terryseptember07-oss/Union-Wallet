# Union-Wallet
Payment App
name": "Union Wallet",
  "short_name": "UnionWallet",
  "description": "The all-in-one subscription payment platform for South Africa",
  "start_url": "./index.html",
  "display": "standalone",
  "orientation": "portrait",
  "background_color": "#F7F7F5",
  "theme_color": "#F4651A",
  "categories": ["finance", "utilities"],
  "icons": [
    {
      "src": "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Crect width='512' height='512' rx='112' fill='%23F4651A'/%3E%3Cpath d='M256 96L96 176l160 80 160-80L256 96zM96 336l160 80 160-80M96 256l160 80 160-80' stroke='white' stroke-width='32' stroke-linecap='round' stroke-linejoin='round' fill='none'/%3E%3C/svg%3E",
      "sizes": "512x512",
      "type": "image/svg+xml",
      "purpose": "any maskable"
    },
    {
      "src": "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 192 192'%3E%3Crect width='192' height='192' rx='42' fill='%23F4651A'/%3E%3Cpath d='M96 36L36 66l60 30 60-30L96 36zM36 126l60 30 60-30M36 96l60 30 60-30' stroke='white' stroke-width='12' stroke-linecap='round' stroke-linejoin='round' fill='none'/%3E%3C/svg%3E",
      "sizes": "192x192",
      "type": "image/svg+xml",
      "purpose": "any maskable"
    }
  ],
  "shortcuts": [
    {
      "name": "Send Money",
      "short_name": "Send",
      "description": "Send money to anyone",
      "url": "./index.html?screen=send",
      "icons": [{ "src": "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 96 96'%3E%3Crect width='96' height='96' rx='20' fill='%23F4651A'/%3E%3Cpath d='M76 20L31 65M76 20L62 76 48 54 26 42z' stroke='white' stroke-width='6' stroke-linecap='round' stroke-linejoin='round' fill='none'/%3E%3C/svg%3E", "sizes": "96x96" }]
    },
    {
      "name": "QR Wallet",
      "short_name": "QR Pay",
      "description": "Show or scan QR code",
      "url": "./index.html?screen=qr",
      "icons": [{ "src": "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 96 96'%3E%3Crect width='96' height='96' rx='20' fill='%23F4651A'/%3E%3Crect x='18' y='18' width='24' height='24' rx='3' stroke='white' stroke-width='5' fill='none'/%3E%3Crect x='54' y='18' width='24' height='24' rx='3' stroke='white' stroke-width='5' fill='none'/%3E%3Crect x='18' y='54' width='24' height='24' rx='3' stroke='white' stroke-width='5' fill='none'/%3E%3Cpath d='M54 54h10v10M64 74h10M74 54v10' stroke='white' stroke-width='5' stroke-linecap='round' fill='none'/%3E%3C/svg%3E", "sizes": "96x96" }]
    }
  ]
}