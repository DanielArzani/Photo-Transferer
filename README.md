﻿# 📸 PhotoTransferApp

A high-speed photo and video transfer tool built in C# with .NET 8 and WPF.

This app is designed to quickly move or copy large numbers of files (e.g., from a phone to a computer or external drive) with optional performance boosts using multithreading and native tools.

---

## ✨ Features

- 📁 Select source and destination folders  
- 🚀 Fast transfer using `Parallel.ForEach` or `robocopy`  
- 🧠 Skips duplicate files (coming soon)  
- 📊 Stats on total file size, average size, and count  
- 📦 Works with external drives and mounted devices  
- 🍎 (Bonus - future) iCloud integration via Python bridge  

---

## 🛠️ Built With

- [.NET 8](https://dotnet.microsoft.com/)
- [WPF (Windows Presentation Foundation)](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/)
- C#
- `System.IO`, `Parallel`, and optionally `Process.Start`

---

## 🚀 Getting Started

1. Clone the repo:

2. Open in Visual Studio 2022+

3. Make sure you have the .NET Desktop Development workload installed

4. Build and run

## 📂 Folder Structure

```bash
/PhotoTransferApp
├── /PhotoTransferApp     # WPF project files
│   ├── MainWindow.xaml
│   └── MainWindow.xaml.cs
├── /scripts              # (optional) iCloud Python script
├── README.md
```

## 📃 License
MIT License — use it freely, modify it, ship it, just give credit.

## 📌 To-Do
 - Async transfer with progress bar

 - Duplicate detection via hash

 - iCloud integration bridge

 - Drag & drop support

 - Language/localization support