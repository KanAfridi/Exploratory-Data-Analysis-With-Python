# 📝 Consumer Complaints Analysis

In this project, I analyzed consumer complaints data to gain insights into common issues faced by consumers and how they communicate these complaints to companies.

## 📊 Data Cleaning
First, I cleaned the data by:
- Checking for **duplicate values** and **null values**.
- Removing **unimportant columns** to streamline the dataset.

## 🔍 Exploratory Data Analysis (EDA)

<details>
<summary>Click to expand for EDA insights</summary>

### Complaints by Communication Method
| Method          | Count   |
|-----------------|---------|
| Email           | 301     |
| Fax             | 10,637  |
| Phone           | 51,261  |
| Postal Mail     | 48,593  |
| Referral        | 131,677 |
| Web             | 529,514 |

Most consumers prefer to submit complaints via **web**.

### Companies with the Most Complaints
| Company                                               | Count   |
|------------------------------------------------------|---------|
| BANK OF AMERICA, NATIONAL ASSOCIATION                | 65,621  |
| WELLS FARGO BANK, NATIONAL ASSOCIATION               | 53,473  |
| EQUIFAX, INC.                                       | 48,990  |

The majority of complaints are against **Bank of America**, followed by other companies.

### Complaints by State
| State | Count   |
|-------|---------|
| CA    | 110,646 |
| FL    | 73,587  |
| TX    | 59,397  |

Most complainants are from **California**, followed by **Florida**. States with the lowest complaint rates include **PW**, **AA**, and **AS**.

### Most Commonly Complained Products
| Product            | Count   |
|--------------------|---------|
| Mortgage           | 225,394 |
| Debt Collection     | 145,071 |
| Credit Reporting    | 139,929 |

These are the products about which people most frequently complain.

### Highest Complaints Recorded
| Date       | Count |
|------------|-------|
| 2017-01-19 | 2,058 |
| 2017-01-20 | 1,629 |

The highest complaint ever recorded was **2,058** on **January 19, 2017**.

### Issues by Company
| Company                                          | Issue                                          | Count   |
|--------------------------------------------------|------------------------------------------------|---------|
| EQUIFAX, INC.                                   | Incorrect information on credit report         | 34,345  |
| EXPERIAN DELAWARE GP                            | Incorrect information on credit report         | 32,385  |
| TRANSUNION INTERMEDIATE HOLDINGS, INC.         | Incorrect information on credit report         | 30,236  |

### Complaints Received by Year
| Year Received | Complaints Received |
|---------------|---------------------|
| 2011          | 2,521               |
| 2012          | 71,755              |
| 2013          | 107,160             |
| 2014          | 152,044             |
| 2015          | 167,379             |
| 2016          | 190,207             |
| 2017          | 80,917              |

While 2017 shows the lowest number of complaints, it is important to note that this data only includes the first three months of that year.

</details>

## 📈 Key Findings
- The majority of complaints are submitted via **web**.
- **Bank of America** has the highest complaint count among companies.
- Most complaints originate from **California**.
- The most common issues involve **incorrect information on credit reports**.

Feel free to explore the code and visualizations in this project to see my approach and findings!
