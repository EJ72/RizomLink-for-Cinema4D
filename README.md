# Feature List for RizomLink for Cinema 4D

1.	Seamless Integration with RizomUV

      Automatically sends UVW data from Cinema 4D to RizomUV, and retrieves updated UV data back to Cinema 4D for seamless UV editing workflow.

2.	Automatic RizomUV Detection

      Detects and connects to RizomUV via the Windows registry. Automatically starts RizomUV if it is not already running.

3.	Manual and Automatic UV Update Modes

      Send Button: Manually send UV and polygon data from Cinema 4D to RizomUV for processing.

      Get Button: Manually retrieve updated UV data from RizomUV and apply it to the selected Cinema 4D object.

      Auto Update Mode: Enables continuous monitoring of UV changes in Cinema 4D, automatically sending updates to RizomUV in real-time and vice versa.

4.	Edge Export Functionality

      Export Edges Option: Allows exporting selected edges from the active polygon object to RizomUV for more precise edge-based operations.

5.	UV Data Normalization and Adjustment

      Ensures UV coordinates are adjusted correctly for both Cinema 4D and RizomUV.

      Automatically adjusts UVs during the export and import process to maintain accurate UV mappings.

6.	Live UV Change Detection

      New UVs Checkbox: Detects and processes only newly created or modified UVs when checked.

      Monitors the selected object's UVs in Cinema 4D and compares them with the previously stored UVs to detect any changes.

7.	RizomUV Connection and Data Exchange

      Automatically establishes a connection with RizomUV when sending or retrieving UV data.

      Utilizes the RizomUVLink API to load and save polygon and UV data efficiently.

8.	Detailed Polygon and Edge Data Handling

      Retrieves detailed polygon information including sizes, 3D coordinates, and UV indices.

      Provides options to select specific edges or polygons to be processed in RizomUV, ensuring precise control over the UV editing workflow.

9.	Intuitive User Interface

      Features an easy-to-use dialog with options to manually send and receive data, enable/disable auto-update, and manage edge exports.

      Automatically enables and disables buttons based on the current object selection and the running status of RizomUV.
