**Goals**
- What does a good result look like:
  - A notebook that is thorough and achieves the purpose of the project. Our data cleaning and analysis is done well. We are able to answer the project question. 
- What each person wants:
  - Prabhnoor: data cleaning and SQL practice
  - - Norah: data cleaning and analyzing sales trends and geographic patterns
  - Safaa Mahbub: data cleaning and answering the data cleaning questions
- What limits our time:
  - Class, work, extracurricular commitments 
- What to avoid:
  - Doing everything last minute
  - Not communicating about the work done

**Breakdown of the project**
 Piece | Weight | What we look for |
|---|---|---|
| Data cleaning | 25% | A clear cleaning pipeline: duplicates, missing values, SKU consolidation, type fixes. Code someone else can read |
| Weather API | 15% | A working call, parsed into a DataFrame, timezones handled, and a join to the sales data that you checked |
| The five questions | 30% | Code, a visualization, and a written explanation for each one |
| Visualizations | 15% | At least six plots, with clear titles, labels, and legends |
| Reflection | 15% | Five questions, one solid paragraph each. Every team member contributes |

**Who does what**
- Cleaning + decision log
- Weather API + join
- Analysis q1-q5
- Charts + presentation (2nd of November)

## Work Split

### Week 1: Data Cleaning

| Person | Ownership | Tasks | Feeds into |
|---|---|---|---|
| **Safaa** | Pipeline lead | Set up repo and pipeline skeleton (day 1); remove duplicates; standardize missing values (empty, NULL, N/A, NaN); convert text numbers and `$` prices to numeric; handle negative quantities | Q5 |
| **Norah** | Dates & categories | Parse all date/time formats into one datetime type; set the sales timezone; standardize category names, capitalization and spacing | Q1, Q3 |
| **C** | SKUs | Build SKU mapping table (multiple SKUs/names → one canonical ID); keep the pre-mapping version for comparison | Q2, Q5 |
| **Prabhnoor** | Stores + API prep | Standardize store IDs across files (finish first); confirm store file joins; get weather API key and a working test call | Q3, Q4 |

**End-of-week deliverables:** merged clean dataset · cleaning log (each step + rows affected)

### Week 2: API + Analysis

| Person | Question | Tasks | Depends on |
|---|---|---|---|
| **Safaa** | Q5: Signal or artifact | SQL on inventory database; cross-check against transactions; write recommendation | SKU and category cleanup |
| **Norah** | Q1: Demand surge | Define and justify baseline window; chart top 5 categories | Date cleaning |
| **Norah** | Q4: Stores and geography | Join store file; compare across stores | Store ID cleaning |
| **C** | Q2: SKU consolidation | Before-and-after comparison using the mapping table; final pass on plot titles, labels and legends | Mapping table |
| **Prabhnoor** | Q3: Weather correlation | Pull weather data; align timezones; check the join; run correlation and lag analysis | Weather API working |

**Every question needs:** code · at least 2 visualizations · written explanation · reflection paragraph

**Question Owners**
- One answers the questions
- One reviews

**How we work**
- Where we talk
  - Groupchat
  - how fast we answer: 
- When we meet
  - During class
- How we decide
- If someone goes quiet
  - Check in on them after 2 days and email professor if they do not respond.


