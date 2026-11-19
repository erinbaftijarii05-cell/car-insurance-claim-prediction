
# AI Collaboration Log

This log records significant AI interactions for the AIAS Level 3 requirement. It feeds the
300–500 word AI Collaboration Statement at the end of the notebook.

**Tool:** Claude (Anthropic), model Claude Opus 5.5, used through claude.ai.

| Date | Task | What the AI produced | What I checked, changed or decided |
|---|---|---|---|
| 08-Nov-2026 | Stakeholders and success criteria | Pointed out potential users and stakeholders; wrote technical and practical criteria to help me choose points | Chose the points to write on |
| 10-Nov-2026 | Understanding the data | Explained the meanings of a few values I couldn't make sense of | Caught that I'd misread "0-9y" as an age group when it's driving experience |
| 10-Nov-2026 | Exploration questions | Helped with questions I could ask, e.g. "Which groups seem to have a higher rate than average" | Only used numbers that came from running the code myself |
| 10-Nov-2026 | Histograms and diagrams | Helped write the histograms and charts and gave pointers on what to look for | Claude pointed out my reason for using the median didn't fit, because the columns with missing values aren't skewed. I checked the numbers and rewrote it |
| 12-Nov-2026 | Q4 and Q5: past accidents and driving experience | Recommendations on what to add to my code (median with dotted lines) | I wrote the code and used its suggestion for the median line |
| 12-Nov-2026 | Q4 interpretation | Pointed out I had read numbers off the chart instead of the table, and that my reason was wrong (a rate already accounts for group size); explained the likely reason (new drivers all have 0 accidents) and gave example wording | Wrote the first draft myself and reworded the example |
| 12-Nov-2026 | Q5 and dropping PAST_ACCIDENTS | Gave the weaknesses of dropping it; checked SPEEDING_VIOLATIONS and DUIS | Used the same method as my Q2 gender check. Decided to drop PAST_ACCIDENTS because drivers with accidents claim less even with the same experience. Kept SPEEDING_VIOLATIONS and DUIS as they don't show the same pattern |
|17-Nov-2026| Data Qaulity Report | Recomendations on What i should check| AI produced that i should check for missing values and pointed back to my Report earlier | I wrote and adapted my Code to the recomendations that AI gave me  |
|17-Nov-2026| Data Quality report - Duplicates | AI produced some of the Code to check if the values in the dataset are duplicate values| I overlooked on the code it gave me and used it to check it and used the Result it gave me  | 
|17-Nov-2026| Data Qaulity report - Outliers and unusual values | I asked AI to explain what it is and what i could mention AI Produced 'Check weather values are strange to be in a model  check 1. Very high counts, 2. Rounded values, 3. Postal code , 4. New drivers have zero of everything'| I decided to go ahead with these checks|
|17-Nov 2026|Outliers and unusual values| AI produced that i should check the 2 patterns that was found earlier which was new drivers and postal codes in Q1| I Decided to check these patterns|
|17-Nov - 2026| Outlier and unusual values Code | Ai suggested I check the IQR way to which will give me the Potential Outliers | I then choose to Apply these to give my Qaulity report a more accurate Reponse |


