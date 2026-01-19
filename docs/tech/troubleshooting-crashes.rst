=======================
Troubleshooting Crashes
=======================

.. meta::
   :description: Common fixes for Teardown crashing on startup, black screen issues, and fatal errors.
   :keywords: teardown keeps crashing, teardown black screen, fatal error teardown, crash fix

Common Issues & Fixes
=====================

**Crash on Startup**
* **Cause:** Often due to outdated drivers or unsupported hardware.
* **Fix:** Update GPU drivers. Verify your GPU meets the minimum requirements (Integrated graphics are not supported).

**"No Physical Device" Error**
* **Cause:** The game cannot find a dedicated GPU.
* **Fix:** If on a laptop, ensure the game is set to run on the High-Performance Nvidia/AMD GPU in Windows Graphics Settings.

**Game Freezes during Gameplay**
* **Cause:** CPU overload or running out of RAM.
* **Fix:** Close other applications. Avoid creating infinite loops of destruction in modded maps which can hang the physics engine.

Reporting Bugs
==============

If you verify it's a game bug, report it on the official Tuxedo Labs Discord or Steam Community Hub with your ``log.txt`` file.
