**# Introduction**

"Learn more skills, earn a higher salary." This is one of the most repeated pieces of career advice for aspiring data analysts, and at first glance, the data seems to back it up: postings that list more required skills tend to show higher average salaries.

But coming from an economics background, I wanted to ask a more careful question: is that relationship really that simple, or is something else driving it? A role like Data Engineer, for example, naturally requires more skills and pays more because of the complexity of the work itself, not necessarily because of the skill count on its own. If that's true, the raw correlation between skill count and salary could be biased, and advice like "collect as many skills as possible" might be misleading.

This project sets out to test that assumption rather than take the surface-level correlation at face value. By controlling for confounding factors, I aimed to get a more honest picture of what actually drives salary in the data job market. I used a 2023 data science job postings dataset (32,672 rows) to work through four research questions.

**# Research Questions**
1. After controlling for job title, does the number of required skills still have a statistically significant effect on salary, or is the surface-level effect largely a reflection of differences between roles?
1. Is the salary gap between US and non-US jobs statistically significant, or could it just be sampling variation?
1. What are the most in-demand skills among data professionals?
1. Which skills offer the highest "value," combining scarcity (how rarely they're requested) with pay (median salary)?
