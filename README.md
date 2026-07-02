# RESTAURANT & CONSUMER ANALYTICS

## Project objective
To analyze the Restaurant Rating Dataset to identify customer preferences, popular cuisines, and the key factors influencing restaurant ratings and performance in Mexico. The analysis will provide actionable insights to help entrepreneurs and investors make informed business and investment decisions in the restaurant industry.

## Data set used 

https://drive.google.com/file/d/1c1HKM8UTqwWOgexRLOtEJuxjBiA2N6xf/view?usp=drive_link

## Question 

•	What can you learn from the highest rated restaurants? Do consumer preferences have an effect on ratings? 

•	What are the consumer demographics? Does this indicate a bias in the data sample?

•	Are there any demand & supply gaps that you can exploit in the market? 

•	If you were to invest in a restaurant, which characteristics would you be looking for?

## Dashboard interaction

https://drive.google.com/file/d/1kTUk3-U4hS_Rv11rBkFbE47xBxBNsnHU/view?usp=sharing

## process

•	No rows were removed — all 138 consumers were retained.

•	Missing categorical values were imputed using mode substitution (the most frequent value in each column): Smoker → "No"; Transportation_Method → "Public"; Children → "Independent"; Occupation → "Student"; Budget → "Medium"; Marital_Status → the majority category.

•	De-duplicated to exactly one preferred-cuisine record per consumer, keeping the first listed preference and discarding repeated/erroneous entries (this resolved the 103-row anomaly for consumer U1135 and the two exact duplicates).

•	Result: rows reduced from 330 to 138 — one row per consumer, ready for a clean one-to-one relationship with Consumers.

# Dashboard Screenshot 1
<img width="886" height="497" alt="RESTAURANT DASHBOARD 1" src="https://github.com/user-attachments/assets/f4574a79-46e9-4e52-b0a2-09b389d60f3e" />

# Dashboard Screenshot 2
<img width="865" height="485" alt="RESTAURANT DASHBOARD 2" src="https://github.com/user-attachments/assets/549badb1-a16d-4625-ab9a-0be99c1e928d" />






