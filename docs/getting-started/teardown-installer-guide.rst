=====================================================
Teardown Installer: Setup Guide and Troubleshooting
=====================================================

.. meta::
   :description: Comprehensive guide for the Teardown installer. Learn how to set up the game, resolve installation errors, and configure game files for PC.
   :keywords: Teardown installer, install Teardown, Teardown setup.exe, Teardown installation error, Teardown PC setup guide

.. contents:: On this page
   :depth: 2
   :local:

Overview
========

The **Teardown installer** is designed to deploy a complex voxel-based environment and a custom physics engine to your PC. Whether you are using the automated Steam setup or a standalone installer, ensuring a clean installation is key to maintaining stable performance and mod compatibility.

Prerequisites for Installation
==============================

Before running the **Teardown setup**, ensure your system has the following components updated to avoid common "missing DLL" errors:

* **DirectX:** Version 12 is required for advanced rendering.
* **Visual C++ Redistributables:** Ensure the latest x64 versions are installed.
* **Storage:** At least 4GB of free space. An **SSD** is highly recommended due to the way Teardown streams voxel data.

Installation Methods
====================

Official Steam Installation
---------------------------

The most common way to **install Teardown** is via Steam. This method is preferred as it automatically manages dependencies and updates.

1. Open the Steam Client.
2. Navigate to your Library and select **Teardown**.
3. Click the blue **Install** button.
4. Choose the installation path (e.g., ``C:\Games\SteamApps\common\Teardown``).
5. The **Teardown installer** will download approximately 2-4GB of data and verify it automatically.

Manual or Backup Setup
----------------------

If you are using a backup or a standalone **Teardown setup.exe**:

1. **Run as Administrator:** Right-click the ``setup.exe`` file and select "Run as administrator" to ensure the installer has permission to write to the Program Files directory.
2. **Path Selection:** Avoid using special characters in the folder names, as this can sometimes cause issues with the game's physics engine.
3. **Component Selection:** Ensure "Create Desktop Shortcut" and "Install DirectX" (if prompted) are checked.

Troubleshooting Teardown Installation Errors
============================================

If you encounter issues during the process, refer to the table below for quick fixes:

.. list-table:: Common Setup Errors
   :widths: 30 70
   :header-rows: 1

   * - Error Type
     - Recommended Solution
   * - **Disk Write Error**
     - Ensure the target drive isn't full and that you have write permissions. Try running the installer as admin.
   * - **ISDone.dll / Unarc.dll**
     - Often caused by faulty RAM or antivirus interference. Disable your antivirus temporarily and retry.
   * - **Missing .dll Files**
     - Reinstall the *Microsoft Visual C++ Redistributable* packages and update your GPU drivers.
   * - **Corrupted Files**
     - Right-click Teardown in Steam > Properties > Installed Files > **Verify integrity of game files**.

Post-Installation Optimization
==============================

Once the **Teardown installer** has finished its task:

1. **Verify the version:** Check the bottom corner of the main menu to ensure you are on the latest build.
2. **Configure Graphics:** Upon first launch, the game will auto-detect your GPU. If you experience lag, adjust the "Render Scale" in the options.
3. **Steam Workshop:** After a successful setup, you can begin installing mods directly from the Steam community hub.

.. note::
   If the installer hangs at 99%, it is likely extracting large voxel assets. Please wait at least 5-10 minutes before force-closing the application.