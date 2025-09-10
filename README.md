# MyTube Mobile App

This is the React Native (Expo) mobile client for MyTube.

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- A physical phone with Expo Go app installed (recommended for network access)
- The MyTube server running on your local network

## Setup

1. **Clone the repository and install dependencies:**

   ```sh
   cd mobile
   npm install
   ```

2. **Configure backend URL:**

   - Open `App.js`.
   - Find the line with `fetch("http://YOUR_COMPUTER_IP:4000/videos")`.
   - Replace `YOUR_COMPUTER_IP` with your computer's local network IP address (e.g., `192.168.1.5`).
   - Find your computer's local IP address:
        - Open Command Prompt and run:
        ```sh
        ipconfig
        ```
        - Look for IPv4 Address (e.g., `192.168.1.5`).
   - Make sure your phone and computer are on the same Wi-Fi network.

3. **Start the Expo app:**

   ```sh
   cd mobile
   npm start
   ```

   - Scan the QR code with the Expo Go app on your phone.

## Troubleshooting

- If you see "Network request failed", double-check the backend URL and ensure your server is running and accessible from your phone.
- Make sure your firewall allows incoming connections on port 4000.

---
