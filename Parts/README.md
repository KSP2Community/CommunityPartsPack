# Parts Folder Organization
This folder helps you organize the artistic/modeling files associated with the parts in your parts pack. You don't have to do things this way, but it may help you keep things organized as you add more parts.
* **Create** part category folders here (e.g., `Engines`, `Fuel Tanks`, etc.)
* **Create** part-specific folders located in the appropriate category (e.g. `.\Engines\cpp_VIKAS_1v`, etc.), where the part folder name should be the same as the part name you plan to use. This is not *required*, but it will help you to keep things organized.
* **Copy** the clean version of the icon generator blend file (`KSP2_IconGenerator_clean.blend`) from here to the part-specific folder and rename it for the part (e.g., `KSP2_IconGenerator_cpp_vikas_1v.blend`, etc.). Again, not required but definitely a good practice.
* **Put** the part's actual blend file, resulting FBX, and textures in the part-specific folder.
* **Put** the part's texturing file in the part-specific folder. It may be very large, but the `.gitignore` will skip it so that your parts pack repo doesn't bloat with its size or trip any non-commercial thresholds. Anyone forking your repo will get only the files they would actually need to build your mod without your actual texturing files.
