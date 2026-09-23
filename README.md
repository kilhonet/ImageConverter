# ImageConverter

**A free Windows image converter: drag in your images and turn them into JPG · PNG · GIF · WEBP · TIFF with one click.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/imageconverter?lang=en)

![ImageConverter screen](images/imageconverter-en.webp)

## Overview

An iPhone HEIC photo that won't open on your PC, a batch of photos to shrink for your blog, a PDF you need as one picture per page — ImageConverter takes care of it.

Drag files or folders into the window and click the **Convert to** button. That's it. JPG is saved smaller with MozJPEG, and when you set a size the image is scaled to it with its proportions kept. You can also convert straight from File Explorer with a right-click.

Results are always saved as **new files**. ImageConverter never overwrites your originals or any existing file.

## Features

- **Many at once** — Add several files, or whole folders (subfolders included), and convert them in one go.
- **5 output formats** — JPG · PNG · GIF · WEBP · TIFF.
- **Wide input support** — JPG, PNG, GIF, BMP, WEBP, TIFF, HEIC, AVIF, PSD, PDF, SVG, TGA, ICO and more.
- **Smaller JPGs** — MozJPEG stores the same quality in fewer bytes.
- **Resize with proportions kept** — Set only the width or the height; the other follows the aspect ratio.
- **PDF → images** — Saves each page of a multi-page PDF as its own picture.
- **Recognized without an extension** — The format is read from the file's content, not its name.
- **Originals protected** — If the name is taken, it saves as `photo (1).jpg` instead.
- **Explorer right-click menu** — On Windows 10 and 11, including the Windows 11 default menu.
- **7 languages** — Korean · English · Japanese · Chinese · Russian · Italian · French. Follows your Windows display language.

## Download / Installation

| Type | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/imageconverter?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/imageconverter?lang=en&nosetup) |

The installer opens ImageConverter as soon as it finishes and registers the Start menu entry and the Explorer right-click menu. For the portable version, unzip it and run `ImageConverter.exe` — keep the `vendor` folder next to the executable. **The Explorer right-click menu comes with the installer.**

## Usage

### Basic flow

1. Start ImageConverter. **Home** shows an empty file list.
2. Drag the image files or folders you want to convert into the list. Only files whose format is recognized are added; the **Type** column shows the source format and **Status** shows `Ready`.
3. In the size box at the bottom left, choose **Original**, **Width** or **Height**. Choosing Width or Height shows a size (px) box next to it.
4. Check the output format. The button at the bottom right shows it, e.g. **Convert to JPG**. To change it, **right-click** the button and pick JPG · PNG · GIF · WEBP · TIFF.
5. Click the button. A progress bar appears and each file's status goes `Convert` → `Success`.
6. By default, converted files are saved in the **same folder as the original**, with the same name and the new extension.

### Screen layout

**Home**

| Element | What it does |
|---|---|
| File list | **FileName** · **Type** (detected source format) · **Status** (`Ready` / `Convert` / `Success` / `Fail`) |
| Right-click on the list | **Delete** · **Delete All** |
| Size choice | **Original** · **Width** · **Height** |
| Size box | Pick a common size from the list or type a number (shown only for Width or Height) |
| **Convert to JPG** button | Click to start. Right-click to choose the output format |

**Config**

| Element | What it does |
|---|---|
| **Output Path** | **Original File Folder** or a chosen folder (default `Desktop\ImageConverter`). Change it with the `…` button |
| **Format** | JPG · PNG · GIF · WEBP · TIFF (the same setting as the button's right-click menu) |
| **Quality** | 40–100, default 75. Applies to lossy formats (JPG · WEBP) |

### When you want to…

**Turn iPhone photos (HEIC) into JPG**
Drag the HEIC files, or the folder holding them, into the list, leave the format at **JPG** and click. Photos are saved **upright** according to the rotation recorded by the phone, so there's no need to turn sideways shots by hand.

**Size photos for a blog or online shop**
Choose **Width** in the size box and pick the width you want, such as `1280`. The height follows the aspect ratio, so nothing gets squashed. For a value not in the list, just type the number (1–30000). Photos narrower than that width are also brought to it.

**Make every image the same height, like thumbnails**
Choose **Height**: all results share the same height and each width follows its own proportions. Handy for lining up a mix of landscape and portrait shots in one row.

**Shrink files to send by email or messenger**
With **JPG**, MozJPEG stores the same quality in a smaller file. To go further, lower **Config → Quality** to around 60 and reduce the size with **Width** as well. Saving as **WEBP** usually comes out smaller than JPG.

**Keep a transparent background**
PNG, SVG and other images with transparency keep it when saved as **PNG** or **WEBP**. JPG can't hold transparency, so choose PNG or WEBP for logos and icons.

**Export an SVG logo as a PNG at the size you need**
Add the SVG, set **Width** to something like `512`, and convert to **PNG**. Rather than enlarging a small picture, it **draws the image fresh at that size**, so it stays sharp even when large.

**Turn a PDF into one image per page**
Add a PDF and convert: each page is saved as a numbered file — `document-001.jpg`, `document-002.jpg` … With **Original** pages come out at on-screen size; with **Width** they are drawn sharply at that width. The background is white. The status shows `Success` once every page is saved.

**Change an animated GIF into WEBP**
When the output format is **GIF** or **WEBP**, every frame of an animation is carried over. Converting an animated GIF to WEBP keeps the motion and cuts the size. Saving as JPG · PNG · TIFF stores the first frame.

**Save WEBP without any quality loss**
Raise **Quality** to **100** and WEBP is saved losslessly. Use it to keep an exact pixel-for-pixel copy that's smaller than PNG.

**Convert all the images in a folder**
Drag a whole folder in: it scans every subfolder and adds only the image files. Other files such as documents or videos are left out automatically, and the same file is never added twice.

**Handle files with no extension or the wrong one**
ImageConverter reads the format from the **file's content**, not its name. Files with no extension, or a `.jpg` that is really a PNG, are recognized correctly, and the result gets the proper extension.

**Collect the results in one folder**
In **Config → Output Path**, choose the lower folder option and every result goes there. The default is `Desktop\ImageConverter`, and it's created when you convert if it doesn't exist yet. Pick another folder with the `…` button. To keep results next to the originals, choose **Original File Folder**.

**A file with the same name already exists**
Nothing is overwritten. If `photo.jpg` exists, the result is saved as `photo (1).jpg`, `photo (2).jpg` and so on. Even shrinking a JPG into JPG leaves the original untouched.

**Convert straight from File Explorer**
Select one or more images in File Explorer, right-click → **ImageConverter** → **Convert to WebP**, **Convert to PNG** or **Convert to JPG**. A window opens with those files; pick a size and click the button.
- Results are saved in the **same folder as the originals**, and the window closes by itself when it's done.
- Right-click other files and convert again: each opens its own window, so they can run at the same time.
- The menu appears when you select JPG · PNG · GIF · BMP · WEBP · TIFF · HEIC · AVIF · PSD · PDF · SVG · TGA files.

**Make the same photos in several formats**
The list stays after converting. Right-click the button, switch the format and click again to produce the same files in another format.

**Tidy up the list**
Select the rows to remove (`Ctrl` · `Shift` for several), right-click the list and choose **Delete**. To clear everything, choose **Delete All**. Rows are only removed from the list; the actual files are not deleted.

**Stop in the middle of a conversion**
Close the window and it asks **Stop converting and quit?** Click **Yes** and it finishes the file in progress, then quits. Results already saved stay where they are.

## Configuration

Changes made in **Config**, and the size choice on Home, are remembered automatically for next time.

| Item | Default |
|---|---|
| Format | JPG |
| Size | Original (Width 640 / Height 540) |
| Quality | 75 |
| Output Path | Original File Folder (chosen-folder default: `Desktop\ImageConverter`) |
| Language | Windows display language (English if not supported) |

## Requirements

- Windows 10 · Windows 11 (64-bit)
- Everything needed for conversion is included — nothing else to install. No administrator rights are needed to run the program.
- The Internet connection is used only for new-version notices. All conversion happens on your PC.

## Updates

ImageConverter does **not** update itself. At startup it checks for a new version and shows a notice; clicking **Yes** opens the download page and closes the program. New versions are released manually after internal verification and announced on the [ImageConverter page](https://v2.kilho.net/imageconverter). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

**Version history**

| Version | Date | Changes |
|---|---|---|
| 2.0.0 | 2026-09-22 | Refreshed screen, sizes picked from a list or typed in, existing settings kept after updating, improved Explorer right-click conversion |
| 1.6.3 | 2026-09-03 | Faster conversion from the Windows 11 right-click menu, smoother update installs, sharper PDF conversion and more stable large documents, better HEIC · AVIF recognition, empty files filtered out of the list in advance |
| 1.6.2 | 2026-08-17 | Upgraded PDF conversion engine for better quality, safe quitting during conversion, stronger protection of existing files, better support for file names with special characters, faster file list |
| 1.6.1 | 2026-07-16 | More reliable JPG and multi-page PDF conversion, better recognition of HEIC and other formats, improved Explorer right-click menu and settings |

## License

ImageConverter is **freeware**. Use it free of charge and without restriction anywhere — at work, at home, in government offices, at school — and redistribute it freely.

## Links

- Website: <https://v2.kilho.net/imageconverter>
- Forum: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
