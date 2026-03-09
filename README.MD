Add the General sources data to a folder called Data somewhere on your computer

Make sure to unzip everything. You should have this file structure:
Location/Data/GENERAL SOURCES
inside which five files/folders:
1. cbs_vk500_2024_v1.gpkg
2. rmbw2025_resultaten.csv
3. cbs_vk100_2024_v1.gpkg
4. WijkBuurtkaart_2025_v1
5. 2025-cbs_pc4_2024_v1
6. rmbw2025_data.csv (This one was downloaded and added by me Mark, not provided by Heijmans)
7. rmbw2025_meta.csv (This one was also downloaded and added by me)


After this create an environmental variable (create a file .env) and add a variable:
- DATA_LOC="your_chosen_location/Data/"