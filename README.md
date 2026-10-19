# 📄 Upgrade to GIMP 3.0 AI Assistant!

**GIMP AI ASSISTANT**  
Official Download & Guide (Global)  
▶ https://d-dchannel.github.io/GIMP-AI-Assistant/

---

## ✨ Features & Highlights

* **AI Auto Background Removal**: State-of-the-art AI automatically isolates subjects (people or products) in a fraction of a second with incredible precision.
* **Manual Fine-Tuning (Masking)**: Need minor adjustments? Add a tweaking layer mask with a single click to instantly restore any over-erased details.
* **Seamless Object Removal**: Erase unwanted objects effortlessly. Select the area, click the button, and the tool generates an "Adjustment Layer" that seamlessly blends with surrounding textures for easy fine-tuning.
* **Landscape Sharpness Enhancement**: Crisp and vibrant enhancement tailored specifically for scenery and landscape photos.
* **Portrait Sharpness Enhancement**: Enhances clarity and skin detail for portraits.
* **Auto White Balance**: Automatically eliminates color casts to restore original, true-to-life colors and clean whites.
* **Final Touch**: Adds an adjustment layer mask right and allows you to erase remaining edges naturally.
* **Invert Mask**: Quick toggle to invert layer masks between black and white.
* **Black & White**: Instantly convert any image into a high-quality monochrome photo.
* **E-Commerce & ID Photo AI Auto-Crop**: Simply set your desired image size and margins. The AI detects the subject and crops it perfectly—ideal for online marketplace listings and official ID photos!
* **Automated Batch Processing**: Combine features like *Crop + Resize + Enhancement* for bulk workflows. Put your images in the `AI_Input` folder, and let the AI process hundreds of photos automatically without stopping.

---

## ⚡ Quick Start in 2 Easy Steps

1. Click **[Start Server]** in GIMP.
2. Launch the AI by double-clicking **`main.exe`**.

That's it! Enjoy your powered-up editing workflow in GIMP.

---

## ⚠️ Important Notices (Please Read First)

* **First-Time AI Initialization**: The first time you click "AI Background Removal," the bundled AI models will automatically configure themselves on your PC. This initial process may take 1–2 minutes depending on your PC specifications. Subsequent operations will run at full speed.
* **Security Software Warnings**: When launching `main.exe`, Windows Defender or your antivirus software may display a warning. Click **"More info"** and select **"Run anyway"**.
* **GIMP Connection Setup (Required every session)**: To allow GIMP to communicate with the AI assistant, perform the following step each time you open GIMP:
  * Go to the top menu: **Filters** → **Development** → **Script-Fu** → Click **[Start Server]**.
  * Ensure the port number is set to **`10008`**, then click **OK**.

---

## 🛠️ Installation & Setup

### 1️⃣ Preparation: Place the GIMP Plugin (First time only)
You need to manually copy the remote communication file into GIMP's plugin folder.

* **Folder to copy**: `remote_listener`
* **Target Directory (Windows)**:  
  `C:\Users\<Your-Username>\AppData\Roaming\GIMP\3.0\plug-ins\remote_listener\remote_listener`  
  *(Place the `remote_listener` directory inside the `plug-ins` folder)*
* **Next Step**: Close GIMP completely and restart it.

### 2️⃣ Directory Structure
> ⚠️ **Do not move or rename files** within the distributed folder structure.

```text
GIMP AI ASSISTANT1.2/
├─ AI_Input/
├─ AI_Output/
├─ main.exe
├─ models/
└─ remote_listener/
   └─ remote_listener.py
```

### 3️⃣ How to Use

1. Launch GIMP and perform **Filters** → **Development** → **Script-Fu** → **[Start Server]**.
2. Launch **`main.exe`**.
3. Place your target images into the `AI_Input` folder.
4. **Operate via Web Interface** (Click *"Display GIMP AI Assistant Screen"* at the top).  
   Clicking the buttons on the web interface starts the AI background removal and processing. Once complete, the images will automatically appear in GIMP and be saved to the `AI_Output` folder.

---

### 4️⃣ Troubleshooting & Important Notes

* **Error: "AI_Input is empty"**: Make sure you have placed valid image files (`.jpg` or `.png`) inside the `AI_Input` folder.
* **No response when clicking buttons**: Verify that `main.exe` is running and that you didn't forget to start the server in GIMP (**Filters → Development → Script-Fu → Start Server**).
* **System Load**: Heavy AI computation may temporarily spike CPU/GPU usage, but performance will return to normal as soon as processing finishes.

---

## ⚖️ Disclaimer & License

Please use, download, and install this software at your own risk. The developer assumes no responsibility for any damages, losses, or issues arising from the use of this tool.  
Redistribution of downloaded files, as well as modification, transfer, re-licensing, or sale of the source code (including secondary use), is strictly prohibited.

**Copyright © D&D Channel. All Rights Reserved.**
