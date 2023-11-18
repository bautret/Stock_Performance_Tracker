# Stock_Performance_Tracker

[LINK TO THE TOOL]

PLEASE MAKE A COPY TO BE ABLE TO USE/EDIT IT

## Description

Tool in Google Sheets using the GOOGLE FINANCE formula to get **stock prices** and calculate **evolution over time**.

Central sheets of the tool:

- **Top_500_Performers_All**: order traded stocks by % of evolution depending on the timeline selected.
- **Top_Performers_Industry**: filter the Top_500_Performers_All by the chosen industry.

Other sheets:

- **All_Companies**: 8,258 Symbols with the associated company name, industry, and market cap * *(not in real-time to avoid crashing the file).* *
- **Calculations**: where the prices are updated and then the performances over time * *(from 1 week to 5 years - 7 timelines available).* *

## Purpose

Track the **best-performing stocks** (in % evolution) in the **timeline** desired * *(week, month ... 5 years). (e.g., to track the yearly growth, it would be the price from the last trading day vs. the price one year ago).* *

## Criteria selected

The files would crash if it were calculating the prices for the 8,258 symbols. Only the symbols with a market cap over $10B have been kept for calculations * *(once copied, you can modify this initial selection to suit your needs best).* *

## How to play with the file
* *(you need to copy the file first)* *

1. You can play with the timeline to rank the symbols:
    - Cell **B2** (drop-down list) in the sheets: **Top_500_Performers_ALL** and **Top_Performers_INDUSTRY**

2. You can filter by industry (only one at a time):
    - Cell **B1** (drop-down list) in the sheet: **Top_Performers_INDUSTRY**

## How to modify the file (examples - do whatever you want with it)
* *(you need to copy the file first)* *

1. Modify the symbols (e.g,: you only need NASDAQ symbols):
    - Change the symbols in **A:A** in the sheet Calculations (it starts in **A5**, and you need to keep one space between each symbol * *([look at this video](https://www.youtube.com/watch?v=uMy3N1I173U&ab_channel=LearnAdvanceGoogleSheetByAnandGaur) to add one empty row between each row quickly).* *

2. Modify the filter by market cap:
    - In the sheet All_Companies, modify the cell M1 to adapt it to the market cap filter you want * *(then you will get the list of stock below and will need to modify the symbols as seen above).* *
