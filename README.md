# 📚 VertexHub - English Dictionary

A lightweight Roblox GUI tool that helps you search English words from multiple dictionary sources and copy them to your clipboard with one click. Perfect for word games, typing practice, or any situation where you need quick word access.

## ✨ Features

- 🔍 **Prefix & Suffix Search** – Find words that start with or end with your query
- 📋 **One-Click Copy** – Click any word to instantly copy it to your clipboard
- ✅ **Used Word Tracking** – Mark words as used to avoid repetition (visual indicator)
- 🔄 **Reset Used Words** – Clear the used words list anytime
- 🗂️ **Large Dictionary** – Combines 9 English word lists (A–Z) for comprehensive coverage
- 🖱️ **Draggable & Minimizable** – Move the window anywhere, collapse when not needed
- 🎨 **Clean Modern UI** – Dark theme with smooth visuals

## 🚀 Installation

1. **Download the script** – Copy the entire Lua script from [vertexhub.lua](link-to-your-script)
2. **Execute in Roblox** – Use any Roblox executor (e.g., Synapse X, Krnl, ScriptWare) to run the script
3. **The GUI will appear** – You can now search and copy words

## 🎮 How to Use

| Action | Description |
|--------|-------------|
| **Search** | Type in the search box – results update automatically |
| **Prefix / Suffix** | Toggle between prefix (starts with) or suffix (ends with) mode |
| **Copy Word** | Click any word from the list – it's copied to clipboard |
| **Mark Used** | Copied words turn gray and show `[USED]` – prevents accidental re-use |
| **Reset Used** | Click the "Reset Used" button to clear the used markers |
| **Minimize** | Click the `-` button in the header to collapse the window |

## ⚙️ Dictionary Sources

The script loads words from these 9 text files (hosted on GitHub):

- `A-Z.txt`
- `A-C.txt`
- `D-F.txt`
- `G-I.txt`
- `J-L.txt`
- `M-O.txt`
- `P-R.txt`
- `S-U.txt`
- `V-Z.txt`

All files are combined, deduplicated, and sorted alphabetically.  
Words must be 2–20 letters long and contain only A-Z characters.

## 🛠️ Requirements

- Roblox executor with `HttpGet` and `setclipboard` support
- Internet connection (to download dictionary files)
- Roblox game that allows GUI injection (most games work)

## 📝 Notes

- No auto-typing – this tool only **copies** words to clipboard
- You can paste the copied word anywhere (chat, game input, etc.)
- The dictionary is loaded once at startup – may take a few seconds depending on your connection
- If a source fails to load, the script continues with the successfully loaded ones

## 🖼️ Screenshot

![VertexHub GUI](https://via.placeholder.com/280x370?text=VertexHub+GUI)  
*(Replace with actual screenshot URL)*

## 📜 License

This project is for educational purposes only. Use at your own risk.

## 👨‍💻 Author

VertexHub – Improve your word game!

---

**Enjoy seamless word copying!** 🚀
