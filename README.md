# VDJ SKIN WYSIWYG PREVIEW EDITOR

<p align="center">
    <img src="https://github.com/LLPPR/VDJ_Skin_WebSimulator/blob/main/images/VISUALdj.png" alt="Visual DJ" width="250" height="250">
</p>

## Description
This project provides a browser-based visual simulator for designing Virtual DJ skins. In the spirit of old 'What You See Is What You Get' web editors, users are able to preview real time edits to the skin's XML file. The simulator leverages HTML, XSL and JavaScript to simulate the skin layout and styles defined in the XML file.

## Rationale
The purpose of this project is to provide an intuitive and visual way for users to design and customize Virtual DJ interfaces using an operational POV. Using a simple method to preview design changes, this tool aims to enhance the efficiency of customizing interfaces.

## Directory Structure
```
VDJ_Skin_WebSimulator/
├── skins/
│   ├── skin.xml
│   ├── skin.xsl
├── scripts/
│   ├── main.js
├── styles/
│   ├── style.css
├── images/
│   ├──VISUALdj.png
├── index.html
└── README.md
```

## Usage
1. **Open `index.html` in a Web Browser:** 
   - This file serves as the main entry point for the simulator. Opening it in a web browser will allow you to see the current state of the skin design.
2. **Edit the XML File in the `skins` Directory:**
   - Modify `skin.xml` to change the elements and their properties. This file defines the structure and components of the skin.
3. **Refresh the Browser to See Changes:**
   - After making changes to `skin.xml`, refresh the browser to see the updates in real-time.

## Customization
- **Modify `index.html`:**
  - Change the structure and elements of the skin directly in this file if needed.
- **Edit `styles/style.css`:**
  - Update the base styles and appearance of the simulator by editing this CSS file.
- **Add or Replace Images:**
  - Add or replace images in the `skins` directory as needed for your skin design.
- **Update `scripts/main.js`:**
  - Handle more complex parsing and styling logic based on the XML file by modifying this JavaScript file.

## Change Log
- **2025-02-24:** Initial setup and organization of the repository. Created `skin.xml`, `skin.xsl`, and updated `index.html` to integrate XSLT for real-time previews.
- **2025-02-24:** Structured the repository into `skins`, `scripts`, and `styles` directories for better organization and maintainability.
- **2025-02-24:** Updated README documentation to reflect the new structure and usage instructions.

## Additional Documentation
- **Commit History:** View detailed commit history [here](https://github.com/LLPPR/VDJ_Skin_WebSimulator/commits).

For any questions or further assistance, please feel free to open an issue on the repository.

---

## Disclaimer
This project is not affiliated with, sponsored by, or endorsed by Virtual DJ. It is a contribution to the open source community, created by an old school graphic designer, new school functional analyst and lifelong DJ. This project aims to capture the ease of use of the old WYSIWYG web design software to motivatte more users to contribute to the customization and usability of Virtual DJ.

---
