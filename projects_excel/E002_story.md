---
Last update: 03-Jun-2025
Planned update: N/A
---


# Monte Carlo simulation: My Expected Annual Spend in Jumpin Gym U.S.A. (美國冒險樂園)


## Project Name
Investigate through simulation to learn about the expected annual spend in topping up tokens in Jumpin Gym U.S.A. (美國冒險樂園)

[Click to download my Excel workbook](/projects_excel/E002_MCsimulation_v1.5.xlsx)

If the above fails, please proceed to download with the below weblink:

https://github.com/craig-lwy/my_portfolio_1/blob/4c7b002e21b0cb3ddb008476a711e7a45b99241f/projects_excel/E002_MCsimulation_v1.5.xlsx

This is the **storytelling** page. The tehnical page is [here](/projects_excel/E002_technicals.md).


## Story Origin

Since Jan'2024 my sister and I found a fun weekly escape at Jumpin Gym U.S.A. if our schedule permits. On high-energy days, we could easily top up our game tokens by as much as HKD 1,800. On slower days, it might be closer to HKD 390–460.

Curious about how this hobby was adding up, I decided to model my spending behavior with a Monte Carlo simulation. The goal is to estimate my expected annual spending and gain insights for personal budgeting — all while turning a casual pastime into a data-driven story.

![E002_Graph_1](/images/E002/E002_Graph_1.png)

[E002_Graph_1](/images/E002/E002_Graph_1.png)


---


## Looking at the Results

![E002_Graph_5](/images/E002/E002_Graph_5.png)

[E002_Graph_5](/images/E002/E002_Graph_5.png)

### Let’s start with Graph 5 – the Box Plot:

- There are 17 outliers, ranging from HKD 60,000 to HKD 91,800. If I assume we visit Jumpin Gym U.S.A. every week (52 times a year), spending HKD 60,000 annually would mean topping up around HKD 1,153 per visit. Realistically? That is not happening.
- A more reasonable annual range sits between the lower whisker (HKD 14,040) and upper whisker (HKD 58,800) — a zone that feels much closer to reality.
- That said, the lower whisker, equivalent to about HKD 270 per week, feels a bit too low for our typical visits. If this is happening due to budget constraints, it might be a good sign that it is time to explore alternatives, more budget-friendly ways to unwind.
- Zooming into the interquartile range (IQR) — from HKD 21,500 to HKD 36,800, with a median of HKD 31,200 — the numbers begin to make sense. Spread over 52 weeks, that translates to:
  - Median: ~HKD 600 per visit
  - Lower quartile: ~HKD 413
  - Upper quartile: ~HKD 707

  So, on those “all-in” high-energy days, I would consider HKD 700 as a reasonable max top-up.
- And on slower days? I might just skip a session and carry that budget forward.
- The probability of spending at or below the median is listed as 50.3% which is just slightly above the 50% mark. Why the subtle skew? Graph 4 provides a hint.


### Now, let’s shift to Graph 4 and Graph 6:

![E002_Graph_4](/images/E002/E002_Graph_4.png)

![E002_Graph_6](/images/E002/E002_Graph_6.png)

[E002_Graph_4](/images/E002/E002_Graph_4.png)

[E002_Graph_6](/images/E002/E002_Graph_6.png)

- Graph 4 reveals a positively skewed (right-skewed) distribution, which, combined with [my recent spending habits](images/E002/E002_Graph_2.png), suggests that I am more likely to top up below the average amount.
- Meanwhile, Graph 6 shows a 65.21% probability of my annual spending staying under HKD 40,040 — or roughly HKD 770 to HKD 910 per visit, depending on whether we go 52 or 44 weeks.


---


## Key Takeaways

- After reviewing the graphs and summary statistics, I am confident that I can keep this year’s spending within the IQR which serves a realistic and manageable goal.
- This was my first time building a Monte Carlo simulation from scratch. **It was genuinely fun!**
- If I could automate and optimize the process in the future, I see exciting potentials to apply simulations like this to other personal and financial decisions.


## Up Next

Now that I have estimated a reasonable annual spend, **the next question is: how am I tracking so far in 2025, with five months already behind us?** Time to put the numbers to the test. Let’s find out — stay tuned!


---


### References

[The Basic Excel Business Analytics: Highline BI 348 Class section, videos #64-69](https://people.highline.edu/mgirvin/excelisfun.htm)

[Histogram with Normal Curve Overlay](https://real-statistics.com/tests-normality-and-symmetry/histogram-with-normal-curve-overlay/)


---
[Back to previous page](/projects_excel.md)
---
