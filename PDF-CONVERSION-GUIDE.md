# HOW TO CONVERT HTML TO PDF - DETAILED INSTRUCTIONS

## Method 1: Using Google Chrome (RECOMMENDED - Best Quality)

### Step-by-Step:

1. **Open the HTML file in Google Chrome**
   - Right-click on `bourbon-presentation.html`
   - Select "Open With" → "Google Chrome"
   - OR drag the file into Chrome browser window

2. **Open Print Dialog**
   - Press `Cmd + P` (Mac) or `Ctrl + P` (Windows)
   - OR go to File → Print

3. **Configure Print Settings** (IMPORTANT!)
   - **Destination:** Click "Change" and select "Save as PDF"
   - **Pages:** All
   - **Color:** Color
   - **Layout:** Landscape
   - **Paper size:** Select "Custom" or "Tabloid (11 x 17)"
     - If Custom: Set to 16 inches width × 9 inches height
   - **Margins:** None or Minimum
   - **Scale:** 100 (default)
   - **Options:** 
     - ✓ Check "Background graphics"
     - ✓ Check "Headers and footers" (optional)

4. **Save the PDF**
   - Click "Save"
   - Name it: `bourbon-tasting-presentation.pdf`
   - Save to your Desktop or event folder

### Pro Tip for Best Results:
Before printing, you can preview how it looks:
- Press F12 to open Developer Tools
- Press Cmd+Shift+P (Mac) or Ctrl+Shift+P (Windows)
- Type "Rendering" and select "Show Rendering"
- Under "Emulate CSS media type" select "print"
- This shows exactly how the PDF will look

---

## Method 2: Using Safari (Mac Only - Excellent Quality)

### Step-by-Step:

1. **Open the HTML file in Safari**
   - Right-click on `bourbon-presentation.html`
   - Select "Open With" → "Safari"

2. **Export as PDF**
   - Go to File → Export as PDF...
   - OR press Cmd + P, then click "PDF" dropdown → "Save as PDF"

3. **Save**
   - Name it: `bourbon-tasting-presentation.pdf`
   - Click "Save"

**Advantage:** Safari's PDF export often handles web fonts and styling very well.

---

## Method 3: Using Firefox

### Step-by-Step:

1. **Open the HTML file in Firefox**
   - Drag `bourbon-presentation.html` into Firefox

2. **Print**
   - Press Cmd + P (Mac) or Ctrl + P (Windows)
   - Select "Save to PDF" as destination
   - Choose Landscape orientation
   - Disable headers/footers
   - Enable background graphics
   - Click "Save"

---

## Method 4: Online Conversion (If browsers don't work)

### Option A: CloudConvert
1. Go to: https://cloudconvert.com/html-to-pdf
2. Upload `bourbon-presentation.html`
3. Click "Convert"
4. Download the PDF

### Option B: HTML2PDF
1. Go to: https://www.html2pdf.com/
2. Upload the HTML file
3. Download result

**Note:** Online converters may not preserve all styling perfectly, but they work in a pinch.

---

## Method 5: Command Line (For Technical Users)

If you have `wkhtmltopdf` installed:

```bash
wkhtmltopdf --page-width 16in --page-height 9in --enable-local-file-access bourbon-presentation.html bourbon-tasting-presentation.pdf
```

To install wkhtmltopdf:
- **Mac:** `brew install wkhtmltopdf`
- **Windows:** Download from https://wkhtmltopdf.org/downloads.html
- **Linux:** `sudo apt-get install wkhtmltopdf`

---

## Troubleshooting

### Problem: PDF pages are wrong size
**Solution:** Make sure to set paper size to 16×9 inches (widescreen) or Tabloid in landscape mode.

### Problem: Black background doesn't show
**Solution:** Enable "Background graphics" or "Print backgrounds" in print settings.

### Problem: Text is too small
**Solution:** 
- Check that Scale is set to 100%
- Try different paper size (Tabloid works well)
- The HTML is designed for 16:9 widescreen presentation

### Problem: Slides don't break properly
**Solution:** This is usually a print driver issue. Try:
1. Different browser (Chrome usually best)
2. Save as PDF instead of Print to PDF
3. Online converter as backup

### Problem: Fonts look different
**Solution:** The HTML uses web-safe fonts (Georgia, Arial). They should work everywhere, but if not:
- Try Chrome or Safari
- Ensure internet connection (for web font loading)
- Online converter may handle better

---

## Best Practice Workflow

1. **Preview First:** Open HTML in browser, scroll through all 35 slides
2. **Test Print:** Try printing just pages 1-3 as a test
3. **Full Export:** Once settings are right, print all pages
4. **Verify PDF:** Open the PDF and scroll through to ensure quality
5. **Backup:** Keep both HTML and PDF versions

---

## Alternative: Present Directly from HTML

You can also present directly from the HTML file in a browser:
- Open in browser
- Press F11 (or Fn+F11) for fullscreen
- Use Page Down / Page Up or Arrow keys to navigate
- Press Escape to exit fullscreen

**Advantages:**
- Perfect quality (no PDF conversion artifacts)
- Easy to edit last-minute if needed
- Animations work (if any)

**Disadvantages:**
- Need to be comfortable with browser navigation
- Requires laptop/device

---

## File Checklist

After conversion, you should have:

- ✓ `bourbon-presentation.html` (original, keep this!)
- ✓ `bourbon-tasting-presentation.pdf` (converted for presenting)
- ✓ `presenter-notes.md` (your speaking guide)
- ✓ `quick-reference.md` (one-page cheat sheet)
- ✓ `README.md` (overview and instructions)
- ✓ `PDF-CONVERSION-GUIDE.md` (this file)

---

## Need Help?

If you're having trouble:

1. **Simplest solution:** Just present from the HTML file in Chrome fullscreen
2. **Quick fix:** Use CloudConvert online converter
3. **Best quality:** Follow Chrome method above with exact settings
4. **Mac users:** Safari's "Export as PDF" is foolproof

The presentation is designed to work beautifully whether you use HTML or PDF!

---

*Good luck with your bourbon tasting event! You've got this! 🥃*

(That's the only emoji, I promise!)
