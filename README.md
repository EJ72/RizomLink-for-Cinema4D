# RizomLink-for-Cinema4D
Feature List for RizomLink for Cinema 4D
#1.	Seamless Integration with RizomUV
Automatically sends UVW data from Cinema 4D to RizomUV, and retrieves updated UV data back to Cinema 4D for seamless UV editing workflow.
#2.	Automatic RizomUV Detection
Detects and connects to RizomUV via the Windows registry. Automatically starts RizomUV if it is not already running.
#3.	Manual and Automatic UV Update Modes
o	Send Button: Manually send UV and polygon data from Cinema 4D to RizomUV for processing.
o	Get Button: Manually retrieve updated UV data from RizomUV and apply it to the selected Cinema 4D object.
o	Auto Update Mode: Enables continuous monitoring of UV changes in Cinema 4D, automatically sending updates to RizomUV in real-time and vice versa.
#4.	Edge Export Functionality
o	Export Edges Option: Allows exporting selected edges from the active polygon object to RizomUV for more precise edge-based operations.
#5.	UV Data Normalization and Adjustment
o	Ensures UV coordinates are adjusted correctly for both Cinema 4D and RizomUV.
o	Automatically adjusts UVs during the export and import process to maintain accurate UV mappings.
#6.	Live UV Change Detection
o	New UVs Checkbox: Detects and processes only newly created or modified UVs when checked.
o	Monitors the selected object's UVs in Cinema 4D and compares them with the previously stored UVs to detect any changes.
#7.	RizomUV Connection and Data Exchange
o	Automatically establishes a connection with RizomUV when sending or retrieving UV data.
o	Utilizes the RizomUVLink API to load and save polygon and UV data efficiently.
#8.	Detailed Polygon and Edge Data Handling
o	Retrieves detailed polygon information including sizes, 3D coordinates, and UV indices.
o	Provides options to select specific edges or polygons to be processed in RizomUV, ensuring precise control over the UV editing workflow.
#9.	Enhanced Error Handling and Notifications
o	Alerts the user via pop-up dialogs for critical issues such as missing UV data, polygon mismatches, or connection failures with RizomUV.
o	Handles common errors like "No Polygon Object selected" and "Polygon count mismatch."
#10.	Intuitive User Interface
o	Features an easy-to-use dialog with options to manually send and receive data, enable/disable auto-update, and manage edge exports.
o	Automatically enables and disables buttons based on the current object selection and the running status of RizomUV.

