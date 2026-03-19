# Published-CGM-Data

Continuous Glucose Monitoring data (CGM) data which are publically available  
This repository is here for anyone running [GVC-Calc](https://gvc-calc.streamlit.app/) that does not have access to CGM data and would like to demonstrate its features.

---

## Repository Organization

```
Published-CGM-Data/
├── data/                              ← top level data folder
│   ├── hall_data/                     ← Data from Hall (2018 Study)
│   ├── osuna_data/                    ← Data from Osuna (2025 Osuna)
└── README.md                          ← you are here
```
The data in this repository comes from the following sources and have been preprocessed for easy use in the app and to mimic how data comes from a CGM.

[Data Source - Hall](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2005143#pbio.2005143.s010) <br>
Hall H, Perelman D, Breschi A, Limcaoco P, Kellogg R, et al. (2018) Glucotypes reveal new patterns of glucose dysregulation. PLOS Biology 16(7): e2005143. https://doi.org/10.1371/journal.pbio.2005143

[Data Source - Osuna](https://physionet.org/content/cgmacros/1.0.0/) <br>
Gutierrez-Osuna, R., Kerr, D., Mortazavi, B., & Das, A. (2025). CGMacros: a scientific dataset for personalized nutrition and diet monitoring (version 1.0.0). PhysioNet. RRID:SCR_007345. https://doi.org/10.13026/3z8q-x658

---

## Suggested download instructions:
1. **Navigate to this Repository's Opening Page** — Click the green `Code` button, then `Download ZIP`.
   
<img width="713" height="338" alt="image" src="https://github.com/user-attachments/assets/337e5e3e-1254-4dc2-97a8-1ca57e4a9c8f" />

2. **Unzip the folder** — Unzip the folder in some place that you are able to find when using GVC-Calc by right-clicking it and using the `Extract All...` option. The extracted file structure will look the same as the `Repository Organization`. Since the structure of the data in each folder is the same, the `hall_data` folder  

<img width="598" height="302" alt="image" src="https://github.com/user-attachments/assets/dffc602e-6e59-454f-a0c3-d53ebc59de85" />

3. **Data in Folders** — Each of these folders can be processed with GVC-Calc. Follow the directions in the following section.

```
Published-CGM-Data-main/
├── data/                              ← top level data folder
│   ├── hall_data/                     ← Data from Hall (2018 Study)
│   ├── osuna_data/                    ← Data from Osuna (2025 Osuna)
├── README.md                          ← you are here
└── LICENSE                            
```

---
## Using GVC Calc with this data

1. **GVC-Calc App** — visit the app site [GVC-Calc](https://gvc-calc.streamlit.app/).
2. **Select `Data Structure`** - this is the first step. It let's the app know the structure of the data files (datetime column, glucose column, header row, etc.)

<img width="748" height="228" alt="image" src="https://github.com/user-attachments/assets/8a37b5cc-30de-4ebd-88c8-5bf606235635" /> <br>


3. **Click Browse files** — select one of the folders and use that data. In this example, we use the first file in `hall_data`.<br>

<img width="602" height="420" alt="image" src="https://github.com/user-attachments/assets/374b7e37-7cfc-4acb-9edf-6cc70d5d9d77" />

<img width="543" height="144" alt="image" src="https://github.com/user-attachments/assets/9a30a545-cafa-4a4f-80c2-99db97b12509" /> <br>

4. **Select the appropriate settings for the files in this folder.** — Choose the header row, the number of rows to be skipped, time deltas used (1 or 5 for this data), the datetime column and the glucose column. Click `OK -> Import` to allow that option on the sidebar. <br>

<img width="749" height="549" alt="image" src="https://github.com/user-attachments/assets/9a24d2eb-215b-47e7-b0d5-9118b7c2334b" /> <br>

5. **Import Data** — Select the `Import Data` menu from the sidebar which only appears after Step 4. Select the `Browse files` from this page and then select the files from the folder that contain CGM files that are similar in structure to the file you browsed in Step 3. Select the data by holding down the \<Shift\> ⬆️ or \<Ctrl\> 🔼 keys to select multiple files.<br>

<img width="601" height="552" alt="image" src="https://github.com/user-attachments/assets/f49bd38b-c477-43a0-a80a-3c80b3195f04" /> <br>

6. Click `OK` and `Explore Data`.
