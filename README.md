

<div align="center">

# Avarwand Batch File Zipper 1.4.3

</div>

A **powerful, lightweight, and completely offline** tool for **batch compression of multiple files and folders** with optional individual password protection.

---

## Main Features

- **Batch compress unlimited files and folders** in one operation  
- **Two modes**: Select Files or Select Folders tab  
- **Drag and drop** support for importing files and folders  
- **Folder compression**: each folder becomes one archive with its full contents  
- **Individual archives**: one archive per file or folder  
- **Optional password protection**: unique random password for each item  
- **Customizable password length**: adjust to match your security needs  
- **AES-256 encryption** for password-protected archives  
- **ZIP and RAR format support**  
- **Built-in ZIP compression**: no external tools needed for basic ZIP  
- **Smart duplicate name handling**: files with same name but different formats get distinct archives  
- **Smart skip logic**: existing archives are not overwritten  
- **Flexible output**: set a path or leave empty to place archives next to source  
- **Real-time cancellation**: stop processing at any moment  
- **CSV password report**: all passwords and metadata saved automatically  
- **Optional deletion of originals** after successful compression  
- **Modern GUI** with responsive design  
- **Fully offline**: no internet connection required, no data leaves your machine  
- **Works with large batches**: hundreds or thousands of items  

---

## Use Cases

- Securing sensitive documents before cloud upload  
- Archiving project folders with individual encryption  
- Batch compression of media libraries  
- Preparing files for secure email transfer  
- Data backup with individual file or folder protection  
- Organizing and archiving large file collections  
- IT administration and batch archival tasks  

---

## System Requirements

- **OS**: Windows 10 / Windows 11  
- **Optional**: WinRAR and/or 7-Zip for full features  

No other dependencies required. Available as a standalone executable.

---

## Supported Formats

| Format                   | Tools Needed       |
|--------------------------|--------------------|
| ZIP without password     | None (built-in)    |
| ZIP with password        | WinRAR or 7-Zip    |
| RAR with/without password| WinRAR             |

---

## Tool Capabilities

### 🔧 No Tools Installed
- ✅ Create ZIP without password  
- ✅ Open ZIP without password  
- ❌ Create ZIP with password  
- ❌ Create/Open RAR files  

### 🔧 7-Zip Only
- ✅ Create ZIP with/without password  
- ✅ Open ZIP and RAR files  
- ❌ Create RAR files  

### 🔧 WinRAR (or Both)
- ✅ Full support for all formats  
- ✅ Create/Open ZIP with/without password  
- ✅ Create/Open RAR with/without password  

---

## How to Use

1. **Run ABFZ**  
2. **Choose mode**: Select Files tab or Select Folders tab  
3. **Add items**: use the buttons or drag and drop files/folders into the list  
4. **Set output path**: or leave it empty to place archives next to the source  
5. **Enable/disable password protection** and adjust password length if needed  
6. **Select archive format**: ZIP or RAR  
7. **Click "Start Compression"** and watch the progress  
8. **Done!**: Find compressed archives in the output path (or next to source items)  
9. **If password enabled**: Find all passwords in the generated CSV file  

---

## Select Files vs. Select Folders

| Feature | Select Files | Select Folders |
|---------|-------------|----------------|
| What gets compressed | Each file individually | Each folder as a whole (with all contents) |
| Drag and drop files | ✅ Added directly | Ignored |
| Drag and drop folders | Top-level files extracted | ✅ Folder added as one item |
| Import from folder | Imports direct child files only | N/A |
| Archive result | `document.zip` | `ProjectFolder.zip` |

---

## Privacy

ABFZ runs entirely offline on your device. It does **not** collect, store, or transmit any personal data, usage statistics, or telemetry. Your files never leave your machine.

---

## Safety Notes

- The tool only compresses files and folders: **no modification of originals** unless explicitly enabled  
- Existing archives are skipped: **no overwriting**  
- Password CSV saved securely alongside output archives  
- Cancel button works immediately and cleans up incomplete archives  
- Designed to minimize accidental data loss  

---

## Output Examples

### Without Password:
```
Input:  document.pdf
Output: document.zip (or document.rar)
```

### With Password Protection:
```
Input:  document.pdf
Output: document.zip (password-protected)
CSV:    passwords_2026-05-15_14-30-25.csv
```

### Duplicate File Names:
```
Input:  report.docx, report.pdf
Output: report docx.zip, report pdf.zip
```

### Folder Compression:
```
Input:  ProjectFolder/  (containing multiple files and subfolders)
Output: ProjectFolder.zip  (single archive with full folder contents)
```

---

## Password CSV File

The CSV file contains:
- Original file/folder name  
- Archive file name  
- Original size  
- Archived size  
- Generated password (customizable length, a-z and 0-9)  

Can be opened in Excel, Google Sheets, or any text editor.

---

## Performance

- ✅ No hardcoded file count limits  
- ✅ Processes files sequentially (one at a time)  
- ✅ Speed depends on file size and compression level  
- ✅ Depending on file size and type, between 1-10 seconds  
- ✅ UI remains responsive during compression  
- ✅ Cancel button works immediately  

---

## Known Limitations

- ZIP with password requires external tools (WinRAR or 7-Zip)  
- RAR format requires WinRAR (7-Zip cannot create RAR)  
- Sequential processing (not parallel)  
- About window disabled during compression  

---

## Contributing

This project is released as **freeware**.  
While primarily maintained by the author, suggestions, bug reports, and improvement ideas are welcome via email.  
Pull requests are currently not accepted.

---

## License

**ABFZ is freeware**, released under a custom End User License Agreement (EULA) by **Avarwand**.

In short, you are free to:

* **Use** ABFZ free of charge, for both personal and commercial purposes  
* **Share** ABFZ with anyone, redistributing, hosting, mirroring, and promoting it is welcome, as long as it is passed on **complete and unmodified**, **free of charge**, and with clear credit to **Avarwand**  

And you may not:

* Sell ABFZ, monetize access to it, or lock it behind paywalls, donations, surveys, registration walls, or paid bundles  
* Reverse engineer, decompile, or modify it (except to the limited extent permitted by applicable law)  
* Claim it as your own work, or remove its copyright and branding notices  

ABFZ is provided **"as is"**, without warranty of any kind.

*This summary is for convenience only. The legally binding terms are in the [LICENSE](LICENSE.md) file included with every release and in this repository.*

---

**Developed by Avarwand**  
**Latest Version: September 2026**
**Initial Release: December 2025**  

---

## Contact

**Avarwand Support**  
📧 [avarwand@yahoo.com](mailto:avarwand@yahoo.com)  
🌐 [github.com/avarwand](https://github.com/avarwand/)

© 2025–2026 Avarwand. All rights reserved.

---
