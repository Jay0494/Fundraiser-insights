# EDUCATION FOR ALL
# TABLE OF CONTENT
- [Introduction](#introduction)
- [Thought Process](#thought-process)
- [Data Cleaning](#data-cleaning)
- [Insights](#insights)
- [Recommendations & Data-Guided Strategic Planning](#recommendations-&-data-guided-strategic-planning)
- [Next Steps](#next-steps)

---

## **Introduction**
### **Business Problem**
Within the Fundraising team at Education for All, our key objectives are:
- **Increase the number of donors in our database.**
- **Increase the donation frequency of our donors.**
- **Increase the value of donations in our database.**

In two weeks, the team will be holding a **fundraising strategy meeting** for the upcoming year. The goal is to present insights from the donation data to inform and optimize our fundraising strategy, ultimately increasing overall donations.

---

## **Thought Process**

To effectively analyze the donor data and derive meaningful insights, I first retrieved the relevant data stored as an **SQL file**. Using SQL queries, I performed an initial **SELECT function** to extract the tables containing donor and donation information. Since the dataset contained multiple tables, I merged them into a **comprehensive master table** for a holistic view of donor behavior and contribution trends.
After consolidating the data, I **exported it to Power BI** for advanced processing and visualization.

---

## **Data Cleaning**

The dataset initially contained **approximately 11,000 data points**, which included duplicate records and irrelevant information. To ensure accuracy and efficiency in dashboarding, I performed the following cleaning steps using Power Query in Power BI:

- **Removed duplicates** to prevent inflated donor counts and misleading trends.
- **Eliminated irrelevant tables and columns** to streamline the dataset and improve processing speed.
- **Standardized tables** to maintain consistency in formatting and data structure.
- **Created comprehensive table headers** for clarity and ease of interpretation.
By executing these cleaning steps, I ensured that the dataset was **optimized for visualization and analysis**, enabling more precise and actionable insights to support our fundraising strategy.

---

## **Insights**
![page 2 now](https://github.com/user-attachments/assets/de90a68c-af90-4d86-9c57-38349626ed28)

---
### **Donor Composition and Contribution**
- The total number of donors is **1,000**, with **102 high-value donors** and **898 regular donors**.
- Total donations received amount to **$249,085**, with **high-value donors contributing $48,302** and **regular donors contributing $200,783**.
- The **top 10% donation threshold** is **$450**, indicating a benchmark for high-value donors.
- The **average donation amount** is **$249.09**.
- Donor segmentation shows that **10.2%** of donors are classified as high-value, while **89.8%** are regular donors.

---

![Page 1](https://github.com/user-attachments/assets/585e96cc-620e-4825-be41-4f8904b6d3e4)

---

### **Demographic Distribution**
- Gender distribution is nearly balanced, with **50.8% female** and **49.2% male** donors.
- Among high-value donors, **54.9% are male** and **45.1% are female**.
- For regular donors, **48.55% are male**, and **51.45% are female**.

### **Donor Profession Insights**
- The **top professions contributing high-value donations** include **Business Development (13.73%)**, **Product Management (11.76%)**, and **Engineering (9.8%)**.
- The **lowest participation from high-value donors** comes from the **Legal (3.92%)** and **Marketing (5.88%)** sectors.
- In general donor distribution, the **highest donor percentages** come from **Business Development (9.4%)**, **Engineering (9.3%)**, and **Human Resources (9.3%)**.

### **Donation Frequency Insights**
- **High-value donors tend to donate yearly (32.35%)**, monthly (24.51%), and weekly (22.55%) respectively.
- **Regular donors donate most frequently once (27.06%)** or yearly (25.17%), followed by monthly (23.05%).
- Overall, donations are **most frequent once (26.4%)**, yearly (25.9%), weekly (24.5%), and monthly (23.2%).

---

## **Recommendations & Data-Guided Strategic Planning**

### **Increase the Number of Donors**
- **Target underrepresented professions:** Expand outreach to Legal, Marketing, and Support sectors to increase their participation in donations.
- **Leverage gender insights:** Tailor marketing campaigns differently for male and female donors, focusing on male donors for high-value conversions.
- **Employer Matching Programs:** Encourage corporate partnerships with businesses where donors frequently come from, such as Business Development and Engineering sectors.

### **Increase Donation Frequency**
- **Encourage Monthly Giving:** High-value donors already show a strong preference for yearly and monthly donations, so campaigns should promote the convenience and impact of monthly giving.
- **Use Recurring Donation Incentives:** Provide incentives like exclusive reports or event invitations for donors who opt for recurring donations.
- **Personalized Engagement:** Implement automated follow-ups and appreciation messages to encourage repeat donations from once-a-year donors.

### **Convert One-Time Donors into Recurring Donors**  

- **Follow-up Campaigns:** Implement an automated follow-up system that sends personalized thank-you emails and impact stories to one-time donors, encouraging them to donate again.  
- **Easy Recurring Options:** Simplify the donation process by offering a seamless "opt-in for monthly giving" feature at the donation checkout.  
- **Exclusive Membership Benefits:** Create a donor club with benefits (e.g., early access to reports, donor appreciation gifts) for those who transition to recurring giving.  
- **Impact-driven Messaging:** Show tangible outcomes of recurring donations, such as how a monthly gift can sustain a child's education over time.  
- **Re-engagement Initiatives:** Identify lapsed one-time donors and retarget them with compelling campaigns, testimonials, or limited-time matching fund offers.  

### **Increase the Value of Donations**
- **Upsell Regular Donors to High-Value Donors:** Since regular donors contribute significantly more in volume, targeted messaging and engagement strategies should encourage them to increase their donation amounts.
- **Highlight the Impact of Larger Donations:** Use storytelling and data to show the direct impact of higher donations, particularly in successful campaigns.
- **Exclusive Recognition for High-Value Donors:** Offer tailored experiences like networking events or recognition on digital platforms to retain and increase high-value contributions.

---

## **Next Steps**
- **Develop targeted marketing campaigns** focused on increasing donor acquisition from underrepresented professions and retaining high-value donors.
- **Implement a subscription-based donation model** encouraging donors to commit to recurring monthly or yearly donations.
- **Create a segmented communication strategy** that provides customized messaging based on donation frequency and donor category.
- **Organize donor appreciation events** to engage high-value donors and encourage higher donations from regular donors.
- **Monitor and analyze donor engagement data** to refine fundraising strategies based on donor behavior trends.


