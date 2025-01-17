# Supported Cinema 4D versions:
R23, S24, R25, S26, 2023, 2024, and 2025
# Supported RizomUV versions:
2022.2.4 and greater
# Special conditions about versions supported:
If RizomUV 2022.2.4 is the only version you have installed, it is only supported up to Cinema 4D 2023 (Python 3.10.8)

If RizomUV 2023.0.71 is the only version you have installed, it is only supported up to Cinema 4D 2023 (Python 3.10.8)

If you happen to have any version 2022.2.4 or higher up to 2023.1.71 installed alongside 2024.1.56 (or higher), then 2022.2.4 will work in Cinema 4D 2024+

# Screenshots
![TexSettings](https://github.com/user-attachments/assets/8b6ac69e-d25f-43e4-b6ae-495f599eea28)

# Feature List for RizomLink for Cinema 4D

1.	Seamless Integration with RizomUV

      Sends UVW data from Cinema 4D to RizomUV, and retrieves updated UV data back to Cinema 4D for seamless UV editing workflow.

2.	Automatic RizomUV Detection

      Detects and connects to RizomUV via the Windows registry. Automatically starts RizomUV if it is not already running.

	  Note: Please see the Version Selection feature below for further details.

3.	Manual and Automatic UV Update Modes

      Send Button: Manually send UV and polygon data from Cinema 4D to RizomUV for processing.

      Get Button: Manually retrieve updated UV data from RizomUV and apply it to the selected Cinema 4D object.

      Auto Update Mode: Enables continuous monitoring of UV changes in RizomUV in real-time and sends that data back to Cinema 4D. (Disabled Currently)

4.	Edge Export Functionality

      Export Edges Option: Allows exporting selected edges from the active polygon object to RizomUV for more precise edge-based operations. (Disabled for NGons Currently)

5.	UV Data Normalization and Adjustment

      Ensures UV coordinates are adjusted correctly for both Cinema 4D and RizomUV.

      Automatically adjusts UVs during the export and import process to maintain accurate UV mappings.

6.	RizomUV Connection and Data Exchange

      Automatically establishes a connection with RizomUV when sending or retrieving UV data.

      Utilizes the RizomUVLink API to load and save polygon and UV data efficiently.

7.	Detailed Polygon and Edge Data Handling

      Retrieves detailed polygon information including sizes, 3D coordinates, and UV indices.

      Provides options to select specific edges or polygons to be processed in RizomUV, ensuring precise control over the UV seams.

8.	Intuitive User Interface

      Features an easy-to-use dialog with options to manually send and receive data, enable/disable auto-update, and manage edge exports.

      Automatically enables and disables buttons based on the current object selection and the running status of RizomUV.

9.	Version Selection

      Allows the user to select from a list of RizomUV versions that support the RizomLink API.
	  
	  Note: Default will always execute the newest version of RizomUV installed.

10.	Basic Scripting

      Allows the user to Create/Save/Execute custom script commands. Please see the example included in the Scripts directory.


# RizomLink Usage
      Basic workflow is open up the UVEdit tab in Cinema 4D
      Select an object to send to Rizom UV
      Load RizomLink and select options as desired then click 'Send' button
      Once UVs are adjusted the way you want, click the 'Get' button
      If you prefer to have your UVWs updated automatically, check the "Auto Update"
      checkbox after your file is finished sending to RizomUV (Disabled currently)

# Known Issues
      -- No MacOS support yet. Unknown when or if I can support it.
      -- Higher polygon counts will result in much longer sending times.
      -- The RizomUV developer is looking into this issue.
      -- With the addition of n-gon support, the edge selection logic needs updated.
         For now it DOES work properly with non ngon meshes and meshes that are completely ngons.
