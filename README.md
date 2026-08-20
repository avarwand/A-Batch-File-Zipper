# Avarwand Batch File Zipper (ABFZ)

A **powerful, modern PowerShell-based GUI tool** for **batch compression of multiple files** with optional individual password protection.  
No command line. No risk. Full control.

---

## Main Features

- **Batch compress unlimited files** in one operation  
- **Individual archives** – one archive per file  
- **Optional password protection** – unique random password for each file  
- **AES-256 encryption** for password-protected archives  
- **ZIP and RAR format support**  
- **Built-in ZIP compression** – no external tools needed for basic ZIP  
- **Smart skip logic** – existing archives are not overwritten  
- **Real-time cancellation** – stop processing at any moment  
- **CSV password file** – all passwords saved with metadata  
- **Modern GUI** with responsive design  
- **Fully GUI-based** – no PowerShell knowledge required  
- **Works with large batches** – hundreds or thousands of files  

---

## Use Cases

- Securing sensitive documents before cloud upload  
- Archiving project files with encryption  
- Batch compression of media libraries  
- Preparing files for secure email transfer  
- Data backup with individual file protection  
- Organizing large file collections  
- IT administration and automation tasks  

---

## System Requirements

- **OS**: Windows 10 / Windows 11  
- **PowerShell**: 5.1 or later (included in Windows)  
- **Optional**: WinRAR and/or 7-Zip for full features  

No other dependencies required.

---

## Known Limitations

- ZIP with password requires external tools (WinRAR or 7-Zip)  
- RAR format requires WinRAR (7-Zip cannot create RAR)  
- Sequential processing (not parallel)  
- About window disabled during compression  

---

## Supported Formats

- **ZIP without password** – Built-in PowerShell (no tools needed)  
- **ZIP with password** – Requires WinRAR or 7-Zip  
- **RAR format** – Requires WinRAR  

---

## Tool Capabilities

### 🔧 No Tools Installed
- ✅ Create ZIP without password  
- ✅ Open ZIP without password  
- ❌ Create ZIP with password  
- ❌ Create/Open RAR files  

### 🔧 7-Zip Only
- ✅ Create ZIP with/without password  
- ✅ Open ZIP files  
- ✅ Open RAR files  
- ❌ Create RAR files  

### 🔧 WinRAR Only (or Both)
- ✅ Full support for all formats  
- ✅ Create/Open ZIP with/without password  
- ✅ Create/Open RAR with/without password  

---

## How to Use

1. **Run the script** (double-click or right-click → Run with PowerShell)  
2. **Select files** (Select Files button or Select Folder button)  
3. **Choose output folder** for compressed files  
4. **Enable/disable password protection**  
5. **Select archive format** (ZIP or RAR)  
6. **Click "Start Compression"**  
7. **Watch the progress** → Done!  
8. **Find compressed files** in output folder  
9. **If password enabled** → Find passwords in CSV file  

---

## Safety Notes

- The tool only compresses files — **no deletion or modification**  
- Original file contents are never changed  
- Existing archives are skipped — **no overwriting**  
- Password CSV saved securely in output folder  
- Designed to minimize accidental data loss  

---

## Output Files

### Without Password:
```
Input:  document.pdf
Output: document.zip (or document.rar)
```

### With Password Protection:
```
Input:  document.pdf
Output: document.zip (or document.rar)
CSV:    Passwords_20251229_143025.csv (contains password)
```

---

## Password CSV File

The CSV file contains:
- Original filename  
- Archive filename  
- Original file size  
- Compressed file size  
- Generated password (16 characters: a-z, 0-9)  

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
**Latest Version: May 2026**
**Initial Release: December 2025**  

---

## Contact

**Avarwand Support**  
📧 [avarwand@yahoo.com](mailto:avarwand@yahoo.com)  
🌐 [github.com/avarwand](https://github.com/avarwand/)

© 2025–2026 Avarwand. All rights reserved.

---
