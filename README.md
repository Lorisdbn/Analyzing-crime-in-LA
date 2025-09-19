# 🌴 Los Angeles Crime Data Analysis

![Los Angeles Skyline](la_skyline.jpg)

**Los Angeles, California 😎**.  
The City of Angels. Tinseltown. The Entertainment Capital of the World!

Known for its **warm weather**, **palm trees**, **sprawling coastline**, and **Hollywood**, along with producing some of the most iconic films and songs.  
However, as with any highly populated city, it isn’t always glamorous — and there can be a **large volume of crime**.  
---

## 🎯 Project Context

We have been asked to support the **Los Angeles Police Department (LAPD)** by **analyzing crime data** to identify **patterns in criminal behavior**.  
They plan to use the insights to **allocate resources effectively** and tackle various crimes across different areas.

---

## 📊 The Data

We have been provided with a single dataset: **`crimes.csv`**.  
It is a **modified version** of the original data, which is publicly available from **Los Angeles Open Data**.

### Columns Description

| Column         | Description                                                                                                                         |
|----------------|-------------------------------------------------------------------------------------------------------------------------------------|
| `DR_NO`        | Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits.                                  |
| `Date Rptd`    | Date reported — format: MM/DD/YYYY.                                                                                                 |
| `DATE OCC`     | Date of occurrence — format: MM/DD/YYYY.                                                                                            |
| `TIME OCC`     | Time of occurrence in 24-hour military time.                                                                                        |
| `AREA NAME`    | The 21 Geographic Areas or Patrol Divisions, each with a name referencing its landmark/community (e.g., 77th Street Division).       |
| `Crm Cd Desc`  | Indicates the type of crime committed.                                                                                              |
| `Vict Age`     | Victim's age in years.                                                                                                              |
| `Vict Sex`     | Victim's sex: `F = Female`, `M = Male`, `X = Unknown`.                                                                              |
| `Vict Descent` | Victim's descent: <br/>A - Other Asian<br/>B - Black<br/>C - Chinese<br/>D - Cambodian<br/>F - Filipino<br/>G - Guamanian<br/>H - Hispanic/Latin/Mexican<br/>I - American Indian/Alaskan Native<br/>J - Japanese<br/>K - Korean<br/>L - Laotian<br/>O - Other<br/>P - Pacific Islander<br/>S - Samoan<br/>U - Hawaiian<br/>V - Vietnamese<br/>W - White<br/>X - Unknown<br/>Z - Asian Indian |
| `Weapon Desc`  | Description of the weapon used (if applicable).                                                                                     |
| `Status Desc`  | Crime status.                                                                                                                       |
| `LOCATION`     | Street address of the crime.                                                                                                        |
