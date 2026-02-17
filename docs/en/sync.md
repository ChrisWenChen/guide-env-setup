# Cloud Storage and File Synchronization

## Why Synchronization Matters

In scientific research, cloud storage and file synchronization play an indispensable role:

- **Backup**: Protect your valuable research data (papers, code, notes) from hardware failures or accidental loss.
- **Cross-Device Sync**: Seamlessly access your files across lab desktops, personal laptops, tablets, and even HPC clusters.
- **Collaboration**: Share folders with colleagues, co-author papers, and keep everyone up-to-date with automatic updates.

Choosing the right cloud storage service ensures that your work is always available, consistent, and secure.

## Popular Cloud Storage Services

Below are commonly used cloud storage platforms in academia, along with their key features:

| Service | Free Tier | Paid Plans (Annual) | Additional Features |
|---------|-----------|----------------------|----------------------|
| **Microsoft OneDrive** | 5 GB | 100 GB ($19.99), 1 TB ($69.99, with Microsoft 365) | Deep integration with Office 365, real-time collaboration |
| **Google Drive** | 15 GB | 100 GB ($19.99), 2 TB ($99.99), 5 TB ($249.99) | Seamless integration with Google Workspace (Docs, Sheets, Gmail) |
| **Dropbox** | 2 GB | 2 TB ($119.88), 3 TB ($199) | Excellent cross-platform clients, file versioning |
| **Nutstore** | 1 GB (monthly upload limit) | 30 GB ($16.86), 60 GB ($33.72) | Fast in mainland China, WebDAV support, no individual file size limit |

*Note: Prices are approximate and may vary by region or promotion.*

---

## Regional Recommendations

Due to differences in network environments, the optimal choice may depend on your location:

### Mainland China
- **Microsoft OneDrive**: The desktop app works normally; web access may occasionally be restricted.
- **Nutstore**: Fully accessible, fast, and stable – ideal for daily research file synchronization.
- **Dropbox** and **Google Drive**: Cannot be used directly without additional tools.

### United States and Other Overseas Regions
- **Dropbox**: Industry standard, stable and fast.
- **Microsoft OneDrive**: A great choice if you already use Microsoft 365 for writing and collaboration.
- **Google Drive**: Convenient if you rely on Gmail, Google Photos, or Google Workspace.

---

## Cross-Platform Support and WSL

All major cloud storage services provide native clients for **Windows**, **macOS**, **Linux**, and mobile platforms, making it easy to sync your research files across different operating systems.

If you use **WSL (Windows Subsystem for Linux)**, you can directly access Windows-synced folders via the `/mnt/c/` path. For example, if your OneDrive folder is located at `C:\Users\<YourUsername>\OneDrive`, you can access it in WSL with:

```bash
cd /mnt/c/Users/<YourUsername>/OneDrive
```

You can also set up an alias in your configuration file for quick access (see [Basic Terminal Commands] for details).