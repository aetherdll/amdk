# AMDK (Among Us Modding Development Kit)

A complete environment setup for developing C# mods for Among Us using BepInEx and IL2CPP.

> **Disclaimer:** This kit does NOT contain any copyrighted game files or executable binaries. Users must own a legitimate copy of Among Us.

---

## 📦 What's Included

* **BepInEx Bleeding Edge:** Pre-configured for Among Us IL2CPP modding.
* **Il2CppDumper Integration:** Tools to extract game assemblies and structure.
* **Template Project:** Ready-to-build solution configured with `.csproj` references.

---

## 🛠️ Setup Instructions

1. **Prerequisites:**
   * A clean installation of **Among Us** (Steam or Epic Games).
   * [.NET 6.0 SDK](https://dotnet.microsoft.com/download/dotnet/6.0) or higher.

2. **Installation:**
   * Download and extract `amongus.zip` into your Among Us main game directory.
   * Launch the game once to allow BepInEx to build necessary runtime assemblies.
   * Close the game.

3. **Building Mods:**
   * Open the project directory in **VS Code** or **Visual Studio**.
   * Run the build command in your terminal:
     ```bash
     dotnet build
     ```
   * Move the generated `.dll` file from `bin/Debug/net6.0/` into your `Among Us/BepInEx/plugins/` folder.

---

## 📜 License & Usage

This project is intended for educational and modding purposes only. BepInEx and Il2CppDumper belong to their respective open-source creators.
