# NVMe Identify Viewer

[![Deploy static content to Pages](https://github.com/wipeseals/nvme-identify-viewer/actions/workflows/static.yml/badge.svg)](https://github.com/wipeseals/nvme-identify-viewer/actions/workflows/static.yml)

A web-based NVMe Identify data parser that helps you parse and understand NVMe controller and namespace information from hexdump data.

## 🔗 Live Application

**👉 [https://wipeseals.github.io/nvme-identify-viewer/](https://wipeseals.github.io/nvme-identify-viewer/)**

## ✨ Features

- **Multiple CNS Support**: Parse various NVMe Identify structures including:
  - Controller Identify (CNS 01h)
  - Namespace Identify (CNS 00h, 11h)
  - Active Namespace ID List (CNS 02h)
  - Controller Lists (CNS 12h, 13h)
  - Primary Controller Capabilities (CNS 14h)
- **Hexdump Input**: Paste hexdump output directly from `nvme-cli` or similar tools
- **Interactive Parsing**: Real-time parsing with structured field display
- **Sample Data**: Built-in sample data for testing and demonstration
- **Share Links**: Generate shareable URLs with parsed data
- **Responsive Design**: Works on desktop and mobile devices

## 📖 Usage

1. Visit the [live application](https://wipeseals.github.io/nvme-identify-viewer/)
2. Select the appropriate CNS (Controller or Namespace Structure) type
3. Paste your hexdump data into the input area
4. Click "Parse" to see the structured information
5. Use "Load Sample" to see example data
6. Use "Share Link" to create a shareable URL

## 🛠 Development

This is a static web application built with vanilla HTML, CSS, and JavaScript. It uses:
- Tailwind CSS for styling
- No build process required - can be served directly

## 📄 License

See [LICENSE](LICENSE) file for details.
