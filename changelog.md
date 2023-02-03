# Version 0.16.6
- NEW: option to insert empty pages and delete existing ones.

- NEW: added an indicator for page numbers and zoom level.

- NEW: click on zoom indicator to reset zoom level to match window width.

- NEW: added three options for window visibility at start: Windowed, Maximized, FullScreen.

- NEW: added option to disable VSync when drawing (Windows only).

- NEW: added dialog warning a document is being saved on exit.

- FIX: selection now becomes inactive when deleting strokes (if appropriate option is enabled).

- FIX: auto save on exit now works correctly.

- FIX: grid snapping enabled when copying and pasting elements.

- FIX: erase highlighter only option didn't work sometimes.

- FIX: crash using partial eraser.

- FIX: selecting highlighted strokes without converting them to pen strokes.

- Improved ink prediction algorithm.

- Increased time taken to enter "non-snapping" mode when using press and hold twice.

- Using press and hold twice now disables snapping to shapes.

- Tweaking of press and hold for drawing lines algorithm.

- Minor performance improvements during scrolling.

- Improved visibility of page separators when using custom background colours.

# Version 0.15.5
- NEW: option to enable automatic straightening of lines using the highlighter.
- NEW: Position of documents is now remembered between sessions.
- FIX: Crash in the rendering engine.
- FIX: Rare crash while saving a document.
- FIX: ability to select ink inside shapes.
- FIX: bug when copy and pasting ink.
- FIX: bug causing undo/redo buttons to become disabled.
- FIX: bug that caused input lag on some devices when input prediction was enabled.
- Major performance improvements to the rendering engine.
- Improved handling of background tasks such as autosaving and exporting to PDF.
- Added notification bar when a PDF is exported.

# Version 0.14.7
- NEW: area eraser mode to delete all strokes inside or intersecting a path.
- NEW: option to enable eraser for highlighted strokes only.
- NEW: option to change eraser size.
- NEW: option to enable/disable automatic switching of tools.
- NEW: option to exclude images when using the selection tool.
- NEW: automatic snapping of lines to other lines or shapes.
- NEW: 2D axis shape.
- NEW: selection now automatically snaps to grid when grid snapping is enabled.
- NEW: option to draw using fingers.
- NEW: optional input prediction algorithm to reduce input latency.
- NEW: experimental two fingers gesture to erase ink.
- NEW: option to disable hiding the cursor when drawing.
- FIX: bug that caused background to not move when stickers are made visible.
- FIX: bug that caused stickers and pasted strokes to dissappear.
- FIX: rare crash during PDF importing.
- FIX: bug that caused the app to crash when using the partial eraser.
- FIX: rare crash when using undo/redo buttons.
- Major internal rewrite of application's data structures.
- Noticeably improved speed and power consumption of rendering engine.
- Ink strokes are now smoothed out when drawing with a mouse.
- Increase performance of vertical space tool on multicore machines.
- Improved drawing of shapes with grid snapping enabled.
- Shortcuts for side menu are now shown on hover.
- Minor bug fixes and improvements.

# Version 0.13.8
- FIX: crash when using "Erase everything" option.
- FIX: improved scrollbar behaviour to prevent accidental scrolling.
- FIX: dashed and dotted styles are now remembered when switching between pens.
- FIX: drawing lines with highlighter by pressing and holding.
- FIX: custom fill colors are now correctly assigned when using dark mode.
- Improve PDF rendering quality on high DPI screens.
- Other minor tweaks.

# Version 0.13.6
- FIX: bug that caused scrolling and pinching to stop working (Windows only).

# Version 0.13.5
- FIX: bug causing change in ink color and thickness when inserting stickers.
- Improved rendering quality of thick ink strokes.
- Minor improvements for rendering of selected strokes.

# Version 0.13.4
- NEW: Custom background and pattern colours.
- NEW: Fountain pen style.
- NEW: Added the possibility of customising fill colour and opacity.
- NEW: Press and hold pen to prevent lines from automatic snapping.
- NEW: HEX code field in colour picker.
- NEW: ability to start application in fullscreen mode.
- FIX: bugs with undo/redo when using the partial eraser.
- FIX: rotation of ellipses now works correctly.
- FIX: prevent accidental strokes when using main colour picker.
- FIX: bug that caused the screen to go back when resizing windows.
- Moved default format settings to a new dialog.
- Eraser type and selection are now remembered between different app sessions.
- Improved selection of shape strokes when using lasso.
- Improved selection implementation for small strokes.
- Improved rendering of ink strokes.
- You can now scroll and pinch when using laser mode.
- Minor improvements in the detection of two fingers tap gesture.
- Small improvements to the file dialog.
- Reduced delay that prevents scrolling after drawing on canvas.
- Minor improvements to the highlighter tool.
- Linux only: internal changes to build system for future Flatpak release.
- Other minor improvements.

# Version 0.12.6
- FIX: bug that caused canvas to move at the bottom of the document.
    
# Version 0.12.5
- FIX: Exporting PDF files with dark theme now works again.
- FIX: Occasional crashes when opening PDF files.
- Slightly improved startup times.
- Increased resolution of PDF rendering.

# Version 0.12.4
- NEW: Ability to import PDF files.
- NEW: Ability to change orientation of documents.
- NEW: Use "desktop-like" scrolling behaviour with touchpads and mice.
- FIX: Duplicating images now preserve the angle of rotation.
- FIX: Crash at starup when using Wayland (Linux).
- Major improvements for rendering large documents and smoother pinch to zoom.
- Minor improvements in the behaviour of the partial eraser tool.
- Window is automatically centered on startup.
- Document zoom level is now set to 90% of thes screen width at startup.

# Version 0.11.3
- NEW: Tap to select an image when using selection tool.
- NEW: Ability to open files directly from the system's file manager.
- NEW: Ability to rotate images.
- NEW: Ability to disable pressure sensitivity.
- FIX: Title bar color now follows app's theme (requires restart).

# Version 0.10.13
- FIX: Bug that caused application to hang on AMD machines
- FIX: Bug that file dialog to stop working when a folder was deleted on the disk
- Improved detection of tap with two fingers gesture.

# Version 0.10.10
- NEW: Tap with two fingers to undo.
- NEW: Keyboard shortcuts for toolbar buttons (hover to see).
- FIX: Automatically switch to previous tool when selecting using dedicated pen button.
- FIX: Rendering artifacts on some devices.
- File dialog is now faster and more responsive.
- Reduced startup time.

# Version 0.10.3
- NEW: Added tooltips for toolbar buttons when hovered.
- FIX: Bug that prevented images from being deleted when selected.
- Reduced latency of ink strokes on Windows 11.
- Disabled visual feedback when pen is pressed on the canvas on Windows.
- Improved precision of eraser tool.

# Version 0.9.11
- NEW: Partial eraser for erasing parts of a stroke or shape.
- NEW: Added option to clear the entire document.
- FIX: changing width of a selected stroke now works properly.
- FIX: bug that cause some parts of the canvas to become invisible when zooming out.
- PDF are now exported in dark mode when it is enabled.
- Spacing for thin dashed strokes has been adjusted.
- Arrow heads now have a more appropriate for small thicknesses.
- Fixed some typos in the about dialog.
- Other minor adjustments.

# Version 0.9.9
- Fixed critical bug that prevented the application from crashing during startup

# Version 0.9.8
- Fixed bug that caused the canvas to not add pages automatically.

# Version 0.9.6
- Smoother and faster scrolling.
- Faster processing of changes when inserting vertical space in large documents.
- NEW: unidirectional and bidirectional arrows (can also be snapped to grid).
- NEW: insert space tool now snaps to grid if grid snapping is enabled.
- Fixed crash when loading new documents.
- Fixed crash when changing page size.
- Other small bugfixes.

# Version 0.9.3
- First release.
