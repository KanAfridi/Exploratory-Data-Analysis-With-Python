# 🖥️ Developer Survey Analysis

In this analysis, I explored survey data from developers, focusing on coding experience, demographics, employment status, education, and the tools they use. Here’s a breakdown of my findings:

## 🧹 Data Cleaning and Preprocessing
1. **Initial Columns**: The dataset initially contained **84 columns**. I removed all non-essential columns, reducing it to only **12 columns** relevant for analysis.
   
2. **Handling Missing Values**:
   - Filled the **YearsCode** and **Age1stCode** columns with the median values.
   - Identified columns with around **20%** of data as null and opted to remove them for simplicity.

3. **Coding Experience Insights**:
   - The average age at which respondents started coding is **15 years or younger**.
   - **80%** of respondents started coding by the age of **20**.
   - The mean number of years spent coding is **12**, with **80%** having coded for up to **20 years**.

## 🔍 Demographics
### Gender and Hobbyist Status
| Gender     | Hobbyist | Percentage (%)  |
|------------|----------|-----------------|
| Man        | Yes      | 74.18           |
|            | No       | 18.01           |
| No Gender  | Yes      | 0.78            |
|            | No       | 0.20            |
| Woman      | Yes      | 4.14            |
|            | No       | 2.69            |

### Employment Status
| Employment Type                                                | Percentage (%)  |
|--------------------------------------------------------------|-----------------|
| Employed full-time                                           | 86.98           |
| Independent contractor, freelancer, or self-employed        | 9.30            |
| Employed part-time                                          | 3.72            |

### Common Job Titles
The top 10 most common job titles among respondents are:
1. Developer, full-stack: **11.73%**
2. Developer, back-end: **6.72%**
3. Developer, back-end; Developer, front-end; Developer, full-stack: **3.37%**
4. Developer, back-end; Developer, full-stack: **2.94%**
5. Developer, mobile: **2.92%**
6. Developer, desktop or enterprise applications: **1.33%**
7. Developer, back-end; Developer, desktop or enterprise applications: **1.17%**

## 📚 Education Levels and Coding Experience
### Educational Distribution
| Education Level                                          | Percentage (%)  |
|--------------------------------------------------------|-----------------|
| Bachelor’s degree (BA, BS, B.Eng., etc.)              | 49.59           |
| Master’s degree (MA, MS, M.Eng., MBA, etc.)           | 25.16           |
| Some college/university study without earning a degree | 11.57           |

### Education Level vs. Years Coding
| Education Level                                          | YearsCode Categorization | Percentage (%)  |
|--------------------------------------------------------|-------------------------|-----------------|
| Bachelor’s degree (BA, BS, B.Eng., etc.)              | 20 to 30                | 30.48           |
|                                                        | More than 30            | 18.83           |
| Master’s degree (MA, MS, M.Eng., MBA, etc.)           | More than 30            | 13.65           |
|                                                        | 20 to 30                | 11.48           |
| Some college/university study without earning a degree | More than 30            | 5.66            |
|                                                        | 20 to 30                | 5.34            |

## 🌍 Top 5 Countries with Highest Survey Participation
| Country            | Respondents  |
|--------------------|--------------|
| United States       | 14,705       |
| India               | 5,059        |
| United Kingdom      | 4,140        |
| Germany             | 3,762        |
| Canada              | 2,219        |

## 📱 Social Media Usage Among Developers
| Platform       | Percentage (%)  |
|----------------|-----------------|
| Reddit         | 17.76           |
| Facebook       | 15.96           |
| WhatsApp       | 15.93           |
| YouTube        | 15.21           |

## 🛠️ Tools and Technologies
- **Visual Studio** is the most popular Integrated Development Environment (IDE) among respondents.
- **Windows** is the most widely used operating system for development.

## 🔑 Key Insights
- A significant majority of respondents are men, with a high percentage identifying as hobbyist programmers.
- Most developers are employed full-time, with a notable presence of independent contractors and freelancers.
- The majority hold at least a Bachelor's degree, contributing to a substantial coding experience in the industry.
  
Explore the code and visualizations in the repository for further insights and details on the developer community!
