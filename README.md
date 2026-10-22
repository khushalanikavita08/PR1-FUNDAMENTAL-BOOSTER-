# PR1-FUNDAMENTAL-BOOSTER-
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:21A366,50:1BA3A3,100:0B5ED7&height=230&section=header&text=FUNDAMENTAL%20BOOSTER&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=Formulas%20%7C%20Lookups%20%7C%20Functions%20%7C%20Analytics&descSize=22&descAlignY=60" width="100%" alt="FUNDAMENTAL BOOSTER"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=2500&pause=800&color=FF8C00&center=true&vCenter=true&width=800&height=60&lines=Learning+Excel+one+formula;Turn+raw+data+into+smart+decisions;VLOOKUP+%E2%80%A2+XLOOKUP+%E2%80%A2+INDEX%2FMATCH+%E2%80%A2+SUMIFS;Learn+Excel+by+doing%2C+not+just+reading" alt="Typing animation"/>

<br/><br/>

![Excel](https://img.shields.io/badge/TOOL-MICROSOFT%20EXCEL-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Sheets](https://img.shields.io/badge/SHEETS-3-0B5ED7?style=for-the-badge)
![Records](https://img.shields.io/badge/RECORDS-60-F59E0B?style=for-the-badge)
![Functions](https://img.shields.io/badge/FUNCTIONS-20-8E44AD?style=for-the-badge)
![Level](https://img.shields.io/badge/LEVEL-BEGINNER%20→%20INTERMEDIATE-2E7D32?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-ACTIVE-4CAF50?style=for-the-badge)
![Made with](https://img.shields.io/badge/MADE%20WITH-❤-E53935?style=for-the-badge)

<br/><br/>

💭 *"Data is just numbers until you learn to make it speak. Every formula you master gives it a new voice."* ✨

**📦 3 Sheets &nbsp;•&nbsp; 🔍 60 Records &nbsp;•&nbsp; 🧠 20 Functions &nbsp;•&nbsp; 📊 Microsoft Excel**

⭐ *Practice • Learn • Repeat • Master Excel* ⭐

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:21A366,50:1BA3A3,100:0B5ED7&height=4" width="100%" alt="divider"/>

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:21A366,50:1BA3A3,100:0B5ED7&height=120&section=header&text=About%20the%20Project&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="About the Project"/>

</div>


**Fundamental Booster** is a practice workbook that turns the most important Excel concepts into real, working examples. Instead of learning formulas in isolation, each concept is applied to a realistic dataset — **students, sales and employees** — so you can see *why* a formula is useful, not just *how* it works.

Every sheet has three parts:

| Part | What it contains |
|------|------------------|
| 🗂️ **Data Table** | 20 clean records with calculated columns |
| 🧪 **Task Examples** | A block of formula exercises with inputs, results and notes |
| 👀 **Result Preview** | A filtered / matched view of the output |


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E44AD,100:E91E63&height=120&section=header&text=Workbook%20Structure&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Workbook Structure"/>

</div>


```
📁 PR1_FUNDAMENTAL_BOOSTER_FINALL.xlsx
│
├── 🎓 STUDENT GRADE      →  Marks, grades, percentages, age, top performers
├── 💰 SALES DATA         →  Sales, discounts, lookups, dynamic ranges
└── 👔 EMPLOYEES DATA     →  Salaries, joining dates, text cleaning
```

<img width="2800" height="3246" alt="project_structure" src="https://github.com/user-attachments/assets/9611e918-f223-49f2-b7f3-155c26ae4003" />



<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF8C00,100:F44336&height=120&section=header&text=Key%20Highlights&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Key Highlights"/>

</div>


A quick snapshot of what the data shows:

| 🎓 Students | 💰 Sales | 👔 Employees |
|:-----------|:--------|:------------|
| **20** students tracked | **20** transactions | **20** employees |
| **11** earn Grade **A**, **8** Grade **B**, **1** Grade **C** | Total sales of **₹5,07,725** | **4** departments (Finance, HR, IT, Marketing) |
| **10** are labelled **Top Student** | **5** products across **4** regions | Finance **6** · HR **6** · IT **5** · Marketing **3** |
| **3** score above 80 in both Math & Science | Discount slabs: **0% · 5% · 10% · 20%** | Salary range **₹31,943 – ₹1,16,284** |


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B5ED7,100:00BCD4&height=120&section=header&text=Sheet%201%20%7C%20Student%20Grade&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Sheet 1 | Student Grade"/>

</div>


Tracks **20 students** across Math, Science and English, then calculates everything automatically.

**Columns:** `Student ID` · `Name` · `Math` · `Science` · `English` · `Enrollment Date` · `Student Grade` · `Date of Birth` · `Score` · `Total Marks` · `Percentage` · `Age` · `Math & Science > 80`


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B5ED7,100:00BCD4&height=85&section=header&text=Grading%20Logic&fontSize=28&fontColor=ffffff&fontAlignY=36" width="100%" alt="Grading Logic"/>

</div>


| Math Marks | Grade |
|:----------:|:-----:|
| 80 and above | 🟢 **A** |
| 60 – 79 | 🔵 **B** |
| 40 – 59 | 🟡 **C** |
| Below 40 | 🔴 **Fail** |

> 🏆 A student is labelled **Top Student** when Math is **above 80**.
> ⭐ The **Math & Science > 80** flag returns `Yes` only when *both* subjects are above 80.


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B5ED7,100:00BCD4&height=85&section=header&text=Task%20Examples&fontSize=28&fontColor=ffffff&fontAlignY=36" width="100%" alt="Task Examples"/>

</div>


| Task | Function Used | Purpose |
|------|---------------|---------|
| Count students with Math above 50 / 60 | `COUNTIFS` | Count rows matching a condition |
| Average Math score where Math > 60 | `AVERAGEIFS` | Conditional average |
| Find a student's name from their ID | `VLOOKUP` | Exact-match lookup |
| Calculate age from date of birth | `DATEDIF` + `TODAY` | Auto-updating age |
| List top-performing students (Math > 80) | Filter / Result Preview | Extract matching rows |


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:009688,100:8BC34A&height=120&section=header&text=Sheet%202%20%7C%20Sales%20Data&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Sheet 2 | Sales Data"/>

</div>


Contains **20 sales transactions** across 5 products, 4 regions and 10 months.

**Columns:** `Sales ID` · `Product Code` · `Product` · `Region` · `Salesperson` · `Amount` · `Date` · `Discount Rate` · `Discount Type` · `Month`

| Detail | Values |
|--------|--------|
| 🖥️ **Products** | Keyboard, Printer, Mouse, Monitor, Laptop |
| 🌍 **Regions** | North, South, East, West |
| 🏷️ **Discount Slabs** | No Discount · 5% · 10% · 20% |
| 📅 **Period** | January – October |


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:009688,100:8BC34A&height=85&section=header&text=Task%20Examples&fontSize=28&fontColor=ffffff&fontAlignY=36" width="100%" alt="Task Examples"/>

</div>


| Task | Function Used | Purpose |
|------|---------------|---------|
| Total sales for **East + Mouse** | `SUMIFS` | Sum with multiple conditions |
| Amount for product code **PC110** | `VLOOKUP` | Lookup by product code |
| Amount for **Person 4 in Feb** | `INDEX` + `MATCH` | Two-way lookup |
| Amount for **Person 12** | `XLOOKUP` | Modern, flexible lookup |
| Position of first **Mouse** | `MATCH` | Find a position in a list |
| Total of a range stored as text | `INDIRECT` | Dynamic range reference |
| Total of all Amount rows | `OFFSET` + `COUNTA` | Self-adjusting range |
| Days between two dates | `DATEDIF` | Date difference |
| Round amount to whole rupee | `ROUND` | Clean number formatting |
| Round up to next 1,000 | `CEILING` | Pricing / budgeting |


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3F51B5,100:9C27B0&height=120&section=header&text=Sheet%203%20%7C%20Employees%20Data&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Sheet 3 | Employees Data"/>

</div>


Holds **20 employees** across 4 departments (Finance, HR, IT, Marketing).

**Columns:** `Employee ID` · `Name` · `Department` · `Salary` · `Joining Date` · `Days Since Joining` · `First Name` · `UPPER Name` · `lower Name`


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3F51B5,100:9C27B0&height=85&section=header&text=Task%20Examples&fontSize=28&fontColor=ffffff&fontAlignY=36" width="100%" alt="Task Examples"/>

</div>


| Task | Function Used | Purpose |
|------|---------------|---------|
| Salary of Employee ID **3007** | `XLOOKUP` | Lookup by ID |
| Same result, classic way | `INDEX` + `MATCH` | Works in every Excel version |
| Extract first name | `LEFT` + `FIND` | Split text at the first space |
| Convert name to CAPITALS | `UPPER` | Text standardisation |
| Convert name to lowercase | `LOWER` | Text standardisation |
| Days since joining | `IF` + `TODAY` | Shows **"Not joined yet"** for future dates |


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E91E63,100:FF8C00&height=120&section=header&text=Formula%20Cheat%20Sheet&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Formula Cheat Sheet"/>

</div>


The key formulas used in this workbook — copy, paste and adapt them for your own data:

| Purpose | Formula |
|---------|---------|
| Assign grade from Math | `=IF(C3>=80,"A",IF(C3>=60,"B",IF(C3>=40,"C","Fail")))` |
| Mark Top Student | `=IF(C3>80,"Top Student","Normal")` |
| Total marks | `=SUM(C3:E3)` |
| Percentage | `=J3/300*100` |
| Age from date of birth | `=DATEDIF(H3,TODAY(),"Y")` |
| Both subjects above 80 | `=IF(AND(C3>80,D3>80),"Yes","No")` |
| First name from full name | `=LEFT(B2,FIND(" ",B2&" ")-1)` |
| Days since joining | `=IF(E2>TODAY(),"Not joined yet",TODAY()-E2)` |
| Exact-match lookup | `=VLOOKUP(B27,B3:F22,5,FALSE)` |


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:21A366,50:1BA3A3,100:0B5ED7&height=120&section=header&text=Excel%20Functions%20Covered&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Excel Functions Covered"/>

</div>


<div align="center">

| 🔍 Lookup | ➕ Math & Aggregate | 🧠 Logical | 📅 Date | 🔤 Text |
|:---------:|:-------------------:|:----------:|:-------:|:-------:|
| `VLOOKUP` | `SUM` | `IF` | `TODAY` | `LEFT` |
| `XLOOKUP` | `SUMIFS` | `AND` | `DATEDIF` | `FIND` |
| `INDEX` | `COUNTIFS` | | | `UPPER` |
| `MATCH` | `AVERAGEIFS` | | | `LOWER` |
| `INDIRECT` | `ROUND` | | | |
| `OFFSET` | `CEILING` | | | |

</div>


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E44AD,100:E91E63&height=120&section=header&text=Requirements&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Requirements"/>

</div>


| Requirement | Details |
|-------------|---------|
| 💻 **Software** | Microsoft Excel 2021 / Microsoft 365 (recommended) |
| 🕰️ **Older Excel (2016 / 2019)** | Everything works except `XLOOKUP` — use the `INDEX` + `MATCH` examples instead |
| 🔌 **Add-ins / Macros** | None needed — only built-in formulas |
| 📁 **Skill level** | Beginner friendly, no prior experience required |


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B5ED7,100:00BCD4&height=120&section=header&text=How%20to%20Use&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="How to Use"/>

</div>


1. **Download** or clone this repository.
2. **Open** `PR1_FUNDAMENTAL_BOOSTER_FINALL.xlsx` in Microsoft Excel.
3. **Explore** each sheet — click any calculated cell to see its formula in the formula bar.
4. **Experiment** — change a mark, amount or date and watch the results update instantly.

> ⚠️ **Compatibility:** `XLOOKUP` works in **Excel 365 / Excel 2021 or later**. Older versions can use the `INDEX` + `MATCH` examples, which give the same result.


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF8C00,100:F44336&height=120&section=header&text=Common%20Errors%20and%20Fixes&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Common Errors and Fixes"/>

</div>


| Error | Likely Cause | Fix |
|:-----:|--------------|-----|
| `#NAME?` | `XLOOKUP` used in an older Excel version | Use `INDEX` + `MATCH`, or upgrade to Excel 2021 / 365 |
| `#VALUE!` | Multi-condition `INDEX`/`MATCH` is an array formula | Use Excel 365, or press `Ctrl` + `Shift` + `Enter` in older versions |
| `#N/A` | Lookup value not found | Check the ID or spelling and use exact match (`FALSE` / `0`) |
| `#REF!` or "update links" prompt | Formula points to another workbook | Point references to the sheet inside this same file (Data → Edit Links) |
| `DATEDIF` missing from suggestions | It is a hidden Excel function | Type it in full — it works normally |


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:009688,100:8BC34A&height=120&section=header&text=What%20You%20Will%20Learn&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="What You Will Learn"/>

</div>


- ✅ Build **nested IF** conditions for grading systems
- ✅ Use **multi-condition** functions (`COUNTIFS`, `SUMIFS`, `AVERAGEIFS`)
- ✅ Choose between **VLOOKUP, INDEX/MATCH and XLOOKUP**
- ✅ Work with **dates** — age, day counts and date differences
- ✅ Clean and reshape **text** with `LEFT`, `FIND`, `UPPER`, `LOWER`
- ✅ Create **dynamic ranges** using `INDIRECT` and `OFFSET`
- ✅ Present results with **Excel Tables** and a clear result preview


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3F51B5,100:9C27B0&height=120&section=header&text=Future%20Improvements&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Future Improvements"/>

</div>


- 📈 Add charts and a summary **dashboard**
- 🎛️ Add **slicers** and drop-down filters
- 🧾 Introduce **PivotTables** for sales analysis
- 🎨 Add more conditional formatting for grades and discounts


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E91E63,100:FF8C00&height=120&section=header&text=Feedback%20and%20Contributions&fontSize=38&fontColor=ffffff&fontAlignY=42" width="100%" alt="Feedback and Contributions"/>

</div>


Found a mistake or have an idea to make this workbook better? Suggestions are always welcome!

1. 🍴 **Fork** the repository
2. 🛠️ Make your improvement
3. 📬 Open a **Pull Request** or raise an **Issue**


<div align="center">

> 💭 *"Practice turns formulas into instinct — keep exploring, keep experimenting, and let every cell teach you something new."*

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:21A366,50:1BA3A3,100:0B5ED7&height=4" width="100%" alt="divider"/>

<br/>

![Excel](https://img.shields.io/badge/TOOL-MICROSOFT%20EXCEL-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Sheets](https://img.shields.io/badge/SHEETS-3-0B5ED7?style=for-the-badge)
![Records](https://img.shields.io/badge/RECORDS-60-F59E0B?style=for-the-badge)
![Functions](https://img.shields.io/badge/FUNCTIONS-20-8E44AD?style=for-the-badge)
![Level](https://img.shields.io/badge/LEVEL-BEGINNER%20→%20INTERMEDIATE-2E7D32?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-ACTIVE-4CAF50?style=for-the-badge)
![Made with](https://img.shields.io/badge/MADE%20WITH-❤-E53935?style=for-the-badge)

<br/>

⭐ **If you found this project helpful, please give it a star!** ⭐

*Made with ❤️ and a lot of formulas*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B5ED7,50:1BA3A3,100:21A366&height=170&section=footer&text=Kavita%20Khushalani&fontSize=34&fontColor=ffffff&fontAlignY=62&desc=%E2%9C%8D%EF%B8%8F%20Author&descSize=16&descAlignY=82" width="100%" alt="Author - Kavita Khushalani"/>

</div>
