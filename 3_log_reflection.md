AI Log & Reflection

What I asked AI:
"Challenge my two questions: what is unclear, what data would I need, and what am I assuming?"
"Give me five alternative questions about these claims."

Checked and Rejected List (the 5 AI questions):
1. Which city has the higher average price?
   - ACCEPTED.
   - The city and price columns exist.
   - I checked: City 2 is 6 PKR higher than City 1 for every item on every date.

2. Did prices rise faster than people's incomes?
   - REJECTED.
   - There is no income or wage column in teaching_prices_clean.csv.

3. Are staples out of reach for poor families?
   - REJECTED.
   - "Out of reach" needs income and household data.
   - Our file only has prices.

4. Did any item stay almost the same price?
   - ACCEPTED.
   - I checked: Pulse C went from 203 to 210.5, only +3.7%.

5. Are these real Pakistan prices from PBS?
   - REJECTED.
   - The data_label column says "ILLUSTRATIVE TEACHING DATA - NOT ACTUAL PBS OBSERVATIONS".
   - So the data cannot tell us about real prices.

What I learned:
- My data can say how the prices of 4 items changed every week in 2 cities from January to March 2026.
- All 4 items went up, but not equally:
   - Sweetener D rose about 19%
   - Oil B rose about 15%
   - Staple A rose about 13%
   - Pulse C rose only about 4%
- So "everything costs more" is true here, but "everything" hides big differences.
- My data cannot say whether people can afford these prices, because there is no income data.
- It cannot say what people buy, because there are no quantities.
- It cannot say anything about real Pakistan prices, because it is made-up teaching data for only 12 weeks and 2 cities.

Most tempting AI suggestion:
- "Are staples out of reach for poor families?"
- It sounds like the real question people care about.
- But it was unsupported, because answering it needs income data that our file does not have.
