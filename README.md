# Runway Calculator

A simple tool to calculate how many months your current cash can sustain your monthly spending.

## What it does
- Takes cash on hand and monthly expenditure as input  
- Calculates runway using: **cash ÷ monthly burn**  
- Shows the result in months  
- Routes to different result pages based on the outcome:
  - Safe (6+ months)
  - Borderline (3–5 months)
  - Danger (<3 months)

## How it works
1. Enter your cash and monthly spend  
2. Click calculate  
3. You’re redirected to a result page  
4. The result page displays your runway and a chart of cash over time  

## Project structure
```
index.html
style.css
/results
  safe.html
  borderline.html
  danger.html
```

## Tech used
- HTML  
- CSS  
- JavaScript  
- Chart.js  

## Notes
- Inputs are validated before calculation  
- Data is passed between pages using URL parameters  
- The chart shows how your cash declines month by month  

## Future improvements
- Keep everything in one page instead of routing  
- Add better financial inputs (income, variable expenses)  
- Improve UI transitions  