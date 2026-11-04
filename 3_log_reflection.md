What I asked AI:
"Challenge my two questions: what is unclear, what data would I need, and what am I assuming?"
"Give me five alternative questions about these claims."

Challenge of My Two Questions:

Question 1: Between the first and last date, did the price of every item go up, and by what percent?
- Unclear: "every item" only means the 4 items in the file, not everything people buy. So it cannot fully test the claim "everything costs more".
- Unclear: it compares only two dates (1 Jan and 19 Mar). Prices go up and down week to week.
   - Staple A went down from 104 to 102.5 in week 2.
   - Pulse C keeps moving between 203 and 208.
   - A different start or end date would give a different percent.
- Assumption: that 12 weeks is long enough to say prices are rising in general.
- Data needed: more items, a longer time period, and real (not teaching) data.

Question 2: Which item had the biggest percent price increase between the first and last date?
- Unclear: "fastest" can mean percent or rupees, and the answer changes.
   - In percent, Sweetener D rose most (about 19%).
   - In rupees, Oil B rose most (+46 PKR, compared with +29.5 for Sweetener D).
   - So a person saying "oil is going up the fastest" could be right if they mean rupees.
- Unclear: the answer depends on which dates are used.
   - Comparing the average of the first 4 weeks with the last 4 weeks: Sweetener D was still highest (13.4%), but Staple A (11.1%) moved above Oil B (10.3%).
- Checked: the order is the same in City 1 and City 2, so the city does not change the answer.
- Assumption: that people notice percent changes, when they may notice rupee changes more.


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
