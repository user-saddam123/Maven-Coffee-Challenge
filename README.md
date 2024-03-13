# Maven-Coffee-Challenge

## Created & Analyzed by Saddam Ansari @Aspirirng Data Analyst [Linkedin](https://www.linkedin.com/in/saddam-ansari-dataanalyst/)

### Live Dashboard at Maven Analytics ShowPage [Link]()

### Live Dashboard at Novypro [Live_link_Novypro](https://www.novypro.com/project/maven-coffee-challenge-by-saddam-ansari)
#

## Objective
The objective of The Maven Coffee Challenge is develop a business plan akin to an "Analytics Consultant" hired by a group of investors aiming to enter the US coffee market.

They sought to utilize insights from "The Great American Coffee Taste Test" but lacked the necessary analytical skills. My task was to provide a data-driven strategy for launching their inaugural coffee shop. The 
investors were particularly interested in:
 * Identifying the Target Audience: Determining the ideal customer demographics and their preferences.
 * Optimizing Product Offering: Suggesting the types of coffee beans and beverages to be offered.
 * Formulating a Pricing Strategy: Aligning prices with customer value perception.

Before proceeding further, I would like to provide an overview of the dataset used in this project and the changes made to it:

## About the Dataset:
The project utilized a unique dataset containing survey responses from approximately 4,000 Americans.

This survey followed a blind coffee taste test conducted by James Hoffmann, a renowned YouTube coffee expert, in collaboration with Cometeer. This innovative experiment aimed to create a standardized tasting experience for participants across the country.

![Screenshot 2024-03-12 120111](https://github.com/user-saddam123/Maven-Coffee-Challenge/assets/123800896/8157a56f-ebd0-4dab-b061-d2dcc4c086c6)

## Data Formatting and Modifications:
Initially, the dataset was loaded into Power BI, where each column was aligned with its corresponding data type.

### Handling Missing Values:
Several key columns contained missing values, which were addressed as follows:
 1. "what is your age": 31 missing values were replaced with values from the 18-24 age range.
 2. "how many cups of coffee do you drink typically per day": 93 missing values were replaced with "1" (one cup of coffee).
 3. "where do you typically drink coffee": 70 missing values were replaced with "At home."
 4. "where do you typically drink coffee (at home)": 63 missing values were replaced with "TRUE."

#

## Dashboard Overview:
In response to the project request and problem statement, I have developed a single-page Power BI dashboard that encompasses each requested question along with corresponding recommendations.

I have divided my dashboard into four sections:
 1. **Demographic Understanding:** This section provides insights into the demographic composition of the survey respondents.
 2. **Respondents Preferences Understanding:** Here, the dashboard delves into the preferences of the respondents regarding coffee consumption.
 3. **Recommendations:*** This section presents actionable recommendations based on the analysis of the survey data.
 4. ***Price Understanding and Pricing Strategy:** The final section focuses on understanding pricing dynamics and formulating an effective pricing strategy.

Each section of the dashboard is designed to provide a holistic view of the data while offering actionable insights and recommendations to guide decision-making for Maven Coffee's entry into the US coffee market.

**Understanding respondent demographics and preferences is crucial for determining the target audience and the products we can offer to meet their needs effectively.**
 * Firstly, analyzing respondent demographics provides insights into the characteristics of our potential customers, such as age, gender, and employment etc. This understanding helps us identify the primary demographic segments within our target market.
 * Secondly, delving into respondent preferences offers valuable insights into their tastes, preferences, and consumption habits regarding coffee. By understanding which types of coffee, flavors, and beverages are favored by our target audience, we can tailor our product offerings to meet their specific preferences and expectations.
 * Therefore, a thorough understanding of both respondent demographics and preferences serves as the foundation for identifying the target audience and determining the types of products we can offer to cater to their needs effectively.

#
Lets get started!
#
## Dashboard Top Section;

![Screenshot 2024-03-12 193020](https://github.com/user-saddam123/Maven-Coffee-Challenge/assets/123800896/a8a24ebc-aef3-4670-948a-99f5062f872a)

The top section of the dashboard aims to provide a visually appealing overview of the challenge and its objectives. It includes:
 * A brief overview of the challenge and its objectives.
 * Buttons for "Objective" and "About Dataset" for detailed information on the project objective and dataset.
 * A filter bookmark for customized filtering and a reset button to clear slicer selections.
 * Key performance indicators (KPIs) displaying the total number of surveyed individuals, as well as the counts for male, female, and other genders.

These elements are designed to offer a quick and engaging glimpse into the challenge and its key components, facilitating easy navigation and understanding for users.

#

## Respondent Demographic Understanding;

![Screenshot 2024-03-13 091137](https://github.com/user-saddam123/Maven-Coffee-Challenge/assets/123800896/174d5c74-4f28-43a3-8f89-a125d2fff949)

Understanding demographics is essential in this project as it provides insights and recommendations that are crucial for comprehending the evolving landscape before advancing further
 1. Approximately 49.13% of the surveyed individuals fall within the prime 25-35 age group, indicating a significant portion of potential target customers.
 2. A predominant number of respondents, constituting 2708 out of 4209, are employed full-time, suggesting a busy lifestyle that could influence their coffee consumption habits and preferences.
 3. In terms of ethnicity distribution, the majority of surveyed individuals, totaling 2626, identified themselves as White/Caucasian, providing insights into the cultural background of the target audience.
 4. The preferred daily coffee consumption among respondents is two cups on average, indicating moderate coffee consumption habits.
 5. Home emerges as the favored location for coffee consumption among the majority of respondents, suggesting a preference for convenience and comfort in their coffee-drinking experience.

#

## Respondents Preference Understanding;
To identify our target customers, we first aim to understand their preferences to ascertain what they enjoy. Therefore, this preference understanding section will present insights based on respondents' preferences.

### 1. Coffee Making Preference Analysis:

![1](https://github.com/user-saddam123/Maven-Coffee-Challenge/assets/123800896/dd1f4925-498f-4d5b-8aa8-4f512bef3aae)

Among the surveyed individuals, there's a clear inclination towards artisanal brewing methods. Pour-over stands out as the top choice, favored by a substantial proportion of respondents, followed closely by espresso and French press. This preference suggests a desire for carefully crafted and personalized coffee experiences.

### 2. Purchase Preferences when Traveling:

![2](https://github.com/user-saddam123/Maven-Coffee-Challenge/assets/123800896/cfb43c11-9643-4e66-bbda-fddba5902497)

When it comes to purchasing coffee while traveling, specialty coffee shops and national cafes are the preferred destinations for a significant majority of respondents. Although the origin of coffee purchase during travel seems less crucial, there's a noticeable inclination towards establishments offering specialty coffee offerings. This highlights the importance of focusing on unique and high-quality offerings to cater to consumer preferences.

### 3. Respondents by Their Favorite Coffee Drink:

![3 ](https://github.com/user-saddam123/Maven-Coffee-Challenge/assets/123800896/24e9e8fd-5790-4854-b734-3cbaede03ef9)

Pour-over stands out as the top preference, with 26.82% of respondents favoring it. Latte follows with 16.82% preference, while regular drip coffee is favored by 10.94% of respondents. Together, these three categories represent the preferred choices for over half of the surveyed individuals.

### 4. Additions to Coffee:

![4](https://github.com/user-saddam123/Maven-Coffee-Challenge/assets/123800896/eb014343-6084-418b-8279-93c197fbbb55)

Analysis indicates that a significant majority of respondents (~88%) prefer their coffee black, without any additions. However, there's a notable preference for adding milk or dairy among around 1700 respondents, while approximately 515 respondents prefer adding sugar. This insight underscores the importance of offering customizable options to accommodate varying preferences.

### 5. Pre-Tasting Coffee Preferences:

![5 ](https://github.com/user-saddam123/Maven-Coffee-Challenge/assets/123800896/9b9185ec-51de-4fee-9f41-a6455dd7d275)
Before the tasting session, it was observed that a majority of respondents have a preference for coffee with fruity flavors. This preference suggests a growing interest in lighter and more aromatic coffee profiles, signaling an opportunity to introduce blends with vibrant and fruity notes to cater to consumer tastes.

### 6. Coffee Roast Preferences:

![6](https://github.com/user-saddam123/Maven-Coffee-Challenge/assets/123800896/df1ad6c6-8661-4653-a317-766bdf2de1ea)

The majority of respondents express a preference for light roast coffee, indicating a desire for subtle flavors and higher acidity levels in their coffee. This preference aligns with the growing trend towards lighter roasts and emphasizes the importance of offering a diverse range of roast profiles to cater to different taste preferences.

### 7. Caffeine Preference in Coffee:


An overwhelming majority of respondents (~88%) indicate a preference for full caffeine in their coffee. This preference reflects a desire for stronger and more stimulating beverages, highlighting the importance of ensuring consistency in caffeine content across product offerings.

### 8. Preference for Coffee Variants A, B, and C:


Among the provided coffee variants, variant A emerges as the clear favorite among respondents when compared to options B and C. This preference may stem from factors such as flavor profile, aroma, or perceived quality, indicating the potential for variant A to resonate well with the target audience.

### 9. Preference for Coffee Variants A and D:


When given a choice between coffee variants A and D, the majority of respondents indicate a preference for variant D. This preference underscores the importance of offering diverse and differentiated product options to meet the varied preferences of consumers.

### 10. Overall Favorite Coffee Preference:


When asked about their overall favorite coffee, a significant proportion of respondents (~37%) choose coffee variant D. This preference highlights the appeal of variant D's taste profile and suggests its potential to be a flagship product for Maven Coffee, catering to the preferences of a substantial portion of the target audience.








































