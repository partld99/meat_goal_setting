# meat_goal_setting

# Meat Reduction Goal Setting Analysis

This repository contains the R code and data analysis for a master's thesis, which explores the factors influencing meat reduction goal setting.



## Methods

This thesis has been preregistered on the Open Science Framework (OSF) [https://osf.io/e3vsb](https://osf.io/e3vsb)

### Sample

The sample was recruited in October 2024 through an introductory class of the psychology bachelor’s program of the University of Vienna. Participants were compensated with laboratory credits (required for completion of psychology bachelor’s program) and monetary payment for completing the entire study. 

Participants with reported eating disorders were excluded from the original study to avoid potential triggering effects of monitoring and restricting food intake. In this thesis, individuals with self-diagnosed meat product allergies and vegetarians/vegans were also excluded, as they are unable to reduce meat consumption. Participants identifying with a gender other than "male" or "female" were reported, but due to the expected low sample size, they were not included in the analysis of H1. For H6, participants who completed fewer than 12 of the 14 meat consumption survey questionnaires were excluded. Participants with missing data on other variables were also excluded.



### Procedure and Study Design

This thesis utilizes data from a larger daily experience sampling study focused on 'Willingness to Reduce Consumption of Animal Products.' While the variables analyzed here were collected within that broader study, they were examined as an independent analysis. Data collection occurred between October and November 2024.

The study design consisted of three phases. First, participants completed a pre-study questionnaire via an online survey. This was followed by two weeks of daily assessments of meat consumption using the SEMA application. After this period, participants set personal goals for reducing their meat intake. While data collection continued for an additional four weeks, only the pre-study, baseline, and goal-setting data are relevant to this thesis.

### Measures

The study was conducted in German, which is why the example items are translated into English for this report. With the exception of goal setting, gender identity, and actual meat consumption, all items were measured on 7-point scales, with every odd number verbally anchored. Table 2 displays the number of items, mean scores, standard deviations, and Cronbach’s alpha for all constructs used in this thesis.

**Goal setting:** On the first day of the treatment period, participants in the treatment conditions (TG 1 and 2) were given the opportunity to set a personal goal for reducing their meat consumption over the next four weeks. They could specify a percentage between 0% and 100%, with 0% indicating no intention to reduce consumption and 100% representing a commitment to completely abstain from meat during this period.

**Gender identity:** Participants had the option to identify as male, female, choose not to answer, or specify their preferred label in an open-ended question.

**Descriptive / injunctive social norms and Personal norms:** The items assessing the social and personal norms are newly constructed but based on Severijns et al. (2023) and Seffen & Dohle (2023). A single item assesses perceived descriptive norms regarding animal product consumption (“How many of the people important to you are reducing their consumption of animal products (e.g., meat, dairy, eggs) or follow a vegan diet?”). Injunctive norms are measured using two items (“People who are important to me expect me to reduce my consumption of animal products in the future or maintain a vegan diet.”; “People who are important to me believe that one should reduce the consumption of animal products or eat a vegan diet.”). Personal norms are assessed with four items (e.g., “It goes against my principles to consume animal products.”).

**Personality:** To measure personality along the dimensions of openness, emotionality, honest-humility, extroversion, agreeableness, and conscientiousness, the HEXACO-60 personality inventory has been used (Moshagen et al., 2014). [ADD EXAMPLE ITEMS AND NUMBER OF ITEMS PER SCALE, AND CRONBACH'S ALPHA]

**Actual meat consumption:** Actual meat consumption was assessed for two weeks, using a daily questionnaire via the SEMA application. The questionnaire was randomly scheduled between 9:00 and 22:00 each day, with participants receiving a push notification and having a two-hour window to respond. Participants were asked to identify their most recent meal (breakfast, lunch, or dinner) and indicate whether it contained meat. If they answered affirmatively, they selected the type of meat from a predefined list (e.g., beef, fish, or mixed products of unclear origin, such as certain sausages). The level of meat consumption was then calculated based on participants' average daily meat intake over the assessment period.

**Self-efficacy:** Self-efficacy was assessed using an adapted version of the political self-efficacy questionnaire from the European Social Survey (ESS) core catalogue (Bischof & Müller, 2020). The adapted version included four items specifically addressing aspects of animal product consumption (e.g. "From your perspective: To what extent do people like you have the ability to influence the food industry through their consumer choices?”; "How capable do you feel to take on an active role in a group that is engaged in climate policy issues?”).

**Self-control:** The German short-scale adaptation of the Self-Control Scale (SCS) (Bertrams & Dickhäuser, 2009) was used to measure self-control. The scale consists of 13 items, including four reverse-coded items for example “I am good at resisting temptations.” and “I sometimes do things that are bad for me if they are fun.”.

**Non-zero-sum beliefs:** General and environmental non-zero-sum beliefs were assessed using separate scales. General non-zero-sum beliefs were measured with an 8-item scale, including statements such as, „Normally, it is possible to resolve disagreements in a mutually beneficial way.”. Environmental non-zero-sum beliefs were assessed using a 3-item scale including items like “If vegan diets become more popular in society, non-vegan people will eat more meat.”. [ADD SCALE CITATIONS]

**Willpower beliefs:** The willpower beliefs scale consisted of 12 items, including statements like, “After a challenging mental activity, my energy is depleted, and I need to recover to recharge it.” [ADD SCALE CITATION]

### Analysis

The analyses were performed using RStudio 2024.ete based on R version 4.3.2. The relationships between variables and goal setting were initially assessed using Pearson product-moment correlation coefficients. Although the use of Pearson's r for Likert-scale data is subject to discussion, it was deemed appropriate for this analysis due to the 7-point Likert scales used and the multiple items (Choi et al., 2010; Harpe, 2015; Keown & Hakstian, 1973). All hypotheses were tested using multiple linear regression. The model included the hypothesized predictor variables and goal setting. A second model was calculated incorporating all variables, including exploratory ones. Finally, an exploratory stepwise forward regression was performed, utilizing the [AIC/p-value] criterion. The assumptions of the regression analysis (normality, homoscedastic
