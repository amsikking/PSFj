# PSFj
A backup repository for PSFj: a convenient tool for analyzing 3D PSF data to estimate microscope resolution.
- Original publication: "PSFj: know your fluorescence microscope" (https://www.nature.com/articles/nmeth.3102).
- Original repository: https://github.com/cmongis/psfj.


## Quick start:
- Download the repository and run **"psfj.exe"**.
- Drag and drop your image stack into the GUI and follow the instructions.
- You'll need to know the **XYZ pixel size** of the data and have **good SNR** for meaningful results.

## Details:
This build (245) has a nice additional feature for volumetric data compared to the published build (231). Build 231 works well for fluorescent beads that are mostly confined to a thin layer on the coverslip (traditional resolution test).
- For particles distributed through a **3D volume** (like beads in gel) use the **"Advanced settings..."** tab at the start of the GUI and select **"Use 3D localization"**.
- Consider using the **"Generate Quick PDF Report"** (global summary) and **"Bead reports PDF file"** (all beads details) at the end of the process to capture results.
- The **"Results CSV file"** option can be used to extract data for further analysis.
- Consider re-using the **".ini"** file that is created after a successful run to avoid needing to fill out the "Microscope settings" and "Calibration" data each time.
## Acknowledgments:
All credit to the original authors: Patrick Theer, Cyril Mongis & Michael Knop

