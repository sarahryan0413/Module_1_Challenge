# Crowdfunding Analysis: Unlocking the Secrets to a Successful Campaign
## Background
Crowdfunding platforms like Kickstarter and Indiegogo have been blowing up since the late 2000s. From indie creators to big-name celebrities, everyone seems to be using crowdfunding to launch their ideas. But not every campaign finds success.  
To get funded, a project has to meet or exceed its goal, so organizations spend a lot of time analyzing past projects to figure out the magic formula for success. My task? Take a database of 1,000 sample projects and dig into the trends. Let's go! 🚀
## The Setup 🛠️
Before jumping in, I created a new project folder called excel-challenge and stored my workbooks there. No mixing with other projects—keeping it clean and organized.
## What I Did 🏗️
I worked with a dataset containing crowdfunding projects and did the following:
### Data Cleaning & Prep 🧼📊
- Used conditional formatting to color-code the Outcome column so I could easily see which campaigns were successful, failed, canceled, or still live.
- Created a Percent Funded column to calculate how much funding each campaign received relative to its goal.
- Applied a three-color scale to the Percent Funded column: 🔴 red for low, 🟢 green for fully funded, and 🔵 blue for well-exceeded goals.
- Created an Average Donation column to see how much each backer contributed on average.
- Split the Category column into two: Parent Category and Sub-Category (because clarity is key!).
- Converted Unix timestamps in the deadline and launched_at columns into readable dates (nobody wants to read raw Unix timestamps!).
### Pivot Tables & Charts 📊📈
- Built a Category Stats pivot table to analyze campaign outcomes per category.
- Created a stacked-column pivot chart that filters by country.
- Built a Subcategory Stats pivot table and another stacked-column chart to break things down further.
- Created an Outcomes by Launch Date pivot table and a line graph to see trends over time.
### Crowdfunding Goal Analysis 🎯💸
- Built a new sheet analyzing campaign success based on funding goals.
- Used COUNTIFS() to count the number of successful, failed, and canceled projects for different goal ranges.
- Calculated percentages for each outcome per goal range.
- Created a line chart to visualize how goal size affects success rates.
### Statistical Analysis 📊🤓
- Built a summary stats table comparing successful vs. unsuccessful campaigns based on number of backers.
- Calculated:
  - Mean 
  - Median 
  - Minimum/Maximum values
  - Variance 
  - Standard deviation
- Analyzed whether mean or median is a better representation of the data.
- Checked if successful campaigns have more variability in backers than unsuccessful ones—and whether that makes sense.
## Insights & Takeaways 🤔💡
After crunching all this data, here’s what I found:
1. Success rates vary significantly by category – Some categories perform way better than others. Creative projects? Pretty solid. Tech gadgets? More of a gamble.
2. Lower funding goals = higher success rates – Makes sense. Smaller goals are easier to hit, while bigger goals often miss the mark.
3. Backer count is a strong indicator of success – Successful campaigns tend to have way more backers, and their backer numbers show less variability.

But, of course, there are limitations to this dataset:
- It’s a sample of 1,000 projects, not the full universe of crowdfunding campaigns.
- Factors like marketing, social media influence, and campaign storytelling aren’t included, but they play a huge role in real-world success.
- No insight into backer demographics, which could also impact results.

## Future Analysis? 🔮
If I had more data, I’d love to:
- Analyze how campaign length impacts success.
- Compare funding trends by country and currency.
- Look at stretch goals and whether they help or hurt campaigns.

## Final Thoughts 💭
This challenge was a great deep dive into Excel’s analytical power. Pivot tables, formulas, and conditional formatting all helped uncover patterns in crowdfunding success. If I were running a campaign, I’d definitely use these insights to optimize my funding goal, category, and marketing strategy. 🚀

📂 All files are stored in my excel-challenge folder, ready for review!

📊 Data provided by edX Boot Camps LLC for educational purposes.

👩‍💻 Project complete!
