# 🎨 Pixel Art & Block Converter

> A sleek, client-side web application designed to convert any standard image into pixel art, a block-based mosaic, or a manually planned block blueprint.

Perfect for creators, builders, and gamers (**Minecraft, Growtopia, Pixel Worlds**, or bead art) who want to blueprint their designs using custom textures and get an exact materials list.

---

## 🎥 Video Tutorial
Learn how to use the converter and its features in this quick walkthrough:

[![Watch the tutorial video](https://img.youtube.com/vi/X3oSTfbrhc0/0.jpg)](https://youtu.be/X3oSTfbrhc0)

---

## 🚀 Features

* 🌟 **Option 1: Automatic Pixel Art**  
  Instantly downscales your image into a classic pixelated grid. The layout stays centered and responsive while converting images.

* 🧱 **Option 2: Custom Block Converter**  
  Upload your own block textures or palettes. The algorithm analyzes the colors and maps your custom blocks to the closest matching pixels of the main image.

* 🛠️ **Option 3: Manual World Planner**  
  Create an empty grid and manually draw with uploaded block textures. Includes a dedicated tools sidebar with Eraser, Color Picker, Used Blocks palette, and optional background reference image support for tracing.

* 📚 **Stack Blocks Toggle**  
  In Manual World Planner mode, enable **Stack Blocks** to place multiple blocks on the same grid cell. When disabled, the current safety behavior remains active: a block must be erased before another block can be placed in the same cell.

* 💧 **Color Picker Tool**  
  Pick an existing block directly from the canvas. After picking, the tool automatically switches back to drawing with the selected block.

* 🔍 **Option 4: Project Inspector (.json)**  
  Save your generated block matrix as a `.json` file. Load it back anytime to inspect your project. Click any pixel on the canvas to see exactly which block was used via a smart tooltip.

* 🎒 **Dynamic Inventory Manager**  
  Manage your uploaded assets on the fly. Don't want a specific block to be used? Simply click the `×` (Remove) button on its preview tile to exclude it.

* 📊 **Real-Time Material Report**  
  Generates a clean, sorted inventory breakdown right beneath the canvas, showing the exact block quantities needed, ordered from most used to least used.

* 🖼️ **Custom Output Image Width**  
  Enter the output width in pixels like in Paint. The height is calculated automatically based on the selected grid ratio.

* 📐 **Accurate Grid Rendering**  
  Grid cells and block textures are rendered without leftover artifacts. Canvas scaling remains accurate when the browser zoom level changes.

* 📱 **Responsive Planner Sidebar**  
  The Manual World Planner tools sidebar stays vertical on the left side of the screen and scales down with the interface instead of covering the workspace.

* ⚡ **Lightweight & Fast**  
  Runs entirely in your browser using HTML5 Canvas—absolutely no backend or server uploads required.

---

## 🛠️ How to Use

1. **Select Operation Mode:** Choose between *Automatic Pixel Art*, *Custom Block Converter*, *Manual World Planner*, or *Inspect Saved Project*.
2. **Upload the Main Image:** Required for Option 1 and Option 2.
3. **Upload Block Images:** Required for Option 2 and Option 3. Select multiple block/palette textures at once.
4. **Manage Assets (Optional):** Hover over any block's preview tile and click the red `×` to remove it from the conversion engine.
5. **Set Grid Dimensions:** Define the grid size by adjusting Width and Height, measured in block counts.
6. **Set Output Width:** Enter only the final image width in pixels. The output height is calculated automatically.
7. **Generate or Create Grid:**
   * Use **Generate Pixel Art** for Option 1 or Option 2.
   * Use **Create Empty Grid** for Option 3.
8. **Use Planner Tools (Option 3):**
   * Select a block to draw.
   * Use **Eraser** to remove placed blocks.
   * Use **Color Picker** to select a block from the canvas.
   * Enable **Stack Blocks** if you want to place multiple blocks on the same cell.
   * Upload an optional background reference image for tracing.
9. **Export:** Save the final result as a `.png` image or export the exact block layout as a `.json` project file.
10. **Inspect Later:** Load a saved `.json` file in Option 4 and click cells to inspect used blocks.

---

## 🧩 Latest Improvements

* Fixed Option 1 layout centering so the interface no longer leaves unnecessary empty space on the right.
* Improved canvas sizing for `Output Image Width (px)` so grid cells stay aligned at normal zoom and browser zoom levels.
* Fixed block erase/repaint artifacts by redrawing the current canvas scene cleanly after planner edits.
* Improved Color Picker behavior so selecting a block from the canvas automatically switches back to draw mode.
* Kept the planner tools sidebar vertical on the left during zoom and responsive resizing.
* Added the **Stack Blocks** checkbox for optional same-cell block stacking in Manual World Planner mode.

---

## 🌐 Live Demo

Try it out directly in your browser without downloading anything:  
✨ [**Launch Pixel Art Converter**](https://burhanyslmn.github.io/Pixel-Art-converter/)

---

## 💖 Support & Sponsorship

If you find this tool helpful and want to support its ongoing development, or if you are interested in official project sponsorship, please reach out directly!

💬 **Discord:** `burhany`