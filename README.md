# XCapt Lite | OSINT Reverse Search Tool 🔍

![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)
![OSINT](https://img.shields.io/badge/OSINT-Fact--Checking-10b981.svg)
![Processing: Local](https://img.shields.io/badge/Processing-100%25_Local-0f172a.svg)

**XCapt Lite** is a fast, client-side OSINT (Open-Source Intelligence) tool designed for rapid reverse image searching of embedded X (Twitter) videos and posts. 

It isolates frames, allows image mirroring to bypass basic anti-search filters, and automatically copies captures to the clipboard while simultaneously launching major visual search engines (Google Lens, Yandex, and TinEye). 

Built specifically for fact-checkers, researchers, and digital investigators.

## ✨ Key Features

* **Zero Data Retention (Privacy-First):** 100% of the processing happens locally within your browser's RAM. No data, images, or metadata are ever sent to or stored on external servers.
* **Clean Room Isolation:** Extracts the post or video frame from its native environment to avoid capturing UI artifacts, banners, or irrelevant screen data.
* **Image Mirroring:** Instantly flips the captured frame horizontally. This is a crucial feature to bypass basic manipulation techniques used by threat actors to hide original media from reverse search engines.
* **Auto-Launch Workflow:** Automatically copies the extracted evidence to the user's clipboard and opens tabs for Google Lens, Yandex Images, and TinEye for immediate `CTRL+V` searching.

## 🚀 How to Use

1. **Embed:** Paste the standard HTML embed code of any X (Twitter) post into the tool.
2. **Isolate:** Click "Isolate Window" to render the post in a clean, isolated popup.
3. **Capture:** Click "Capture Isolated Frame" and select the popup window. The tool will extract a high-fidelity image of the content.
4. **Search:** Click "Run Reverse Search". The image is copied to your clipboard, and the search engines will open automatically. Just paste the image to find the source.

## ⚖️ Disclaimer

This tool is provided "As-Is" for educational, fact-checking, and legitimate OSINT investigations. The owner and developers assume no responsibility for the accuracy of the reverse search results or any misuse of the tool. 

## ©️ Copyright & License

Created and maintained by **6sedici**.

This project is licensed under the **GNU Affero General Public License v3.0 (AGPLv3)**. 
You are free to use, modify, and distribute this software, but any modified versions or SaaS (Software-as-a-Service) implementations must also be made open-source under the same license. See the `LICENSE` file for more details.