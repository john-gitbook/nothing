**Med Model Anxiety**	MED-Anxiety-PRGM

**Type:	Subtype:**

Program	Program

Program assessment

# Anxiety

1. **Do you ever experience anxiety?**

Anxiety\_Diagnosis	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  | 1.1, 1.2 |
| No |  |  |  |  |  |  |

1. **How long have you had anxiety?**

Anxiety\_Diagnosis\_Date	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Less than 3 months |  |  |  |  |  |  |
| 3 \- 12 months |  |  |  |  |  |  |
| 1 \- 3 years |  |  |  |  |  |  |
| 3 \- 5 years |  |  |  |  |  |  |
| 5 \- 10 years |  |  |  |  |  |  |
| More than 10 years |  |  |  |  |  |  |
| Unsure/Unknown |  |  |  |  |  |  |

2. **What type(s) of anxiety disorder do you have?**

Anxiety\_Diagnosis\_Type	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Acute stress disorder |  |  |  |  |  |  |
| Generalized anxiety disorder |  |  |  |  |  |  |
| Obsessive-compulsive disorder |  |  |  |  |  |  |
| Panic disorder |  |  |  |  |  |  |
| Phobia |  |  |  |  |  |  |
| PTSD |  |  |  |  |  |  |
| Other |  |  |  |  |  | 1.2.1 |
| Unsure/unknown |  |  |  |  |  |  |

2. **Do you have a provider(s) who provides primary treatment for your anxiety?**

Current\_Anxiety\_Provider	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | :---: |
| No |  |  |  |  |  | 2.2 |
| Mental Health Specialist (Psychologist, Psychiatrist) |  |  |  |  |  | 2.3, 2.4 |
| Therapist |  |  |  |  |  | 2.3, 2.4 |
| Primary care doctor |  |  |  |  |  | 2.3 |
| Other |  |  |  |  |  | 2.1, 2.3, 2.4 |

1. **What other type of provider cares for your anxiety?**

Current\_Anxiety\_Provider\_Other	Free text

2. **Do you need help finding a provider?**

Provider\_Search\_Assistance	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |

3. **How often are you seen for your anxiety?**

Frequency\_Anxiety\_Appointments	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Weekly |  |  |  |  |  |  |
| Every two weeks |  |  |  |  |  |  |
| Every month |  |  |  |  |  |  |
| Every 2-3 months |  |  |  |  |  |  |
| Every 4-6 months |  |  |  |  |  |  |
| Once a year |  |  |  |  |  |  |
| Other frequency |  |  |  |  |  | 2.3.1 |

1. **What other frequency are you seen?**

Frequency\_Anxiety\_Appointments\_Other	Free text

4. **What type of therapy program are you attending?**

Therapy\_Type	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Cognitive Behavioral Therapy |  |  |  |  |  | 2.4.2, 2.4.3, 2.4.4 |
| Family Therapy |  |  |  |  |  | 2.4.2, 2.4.3, 2.4.4 |
| Group Therapy |  |  |  |  |  | 2.4.2, 2.4.3, 2.4.4 |
| Marital (Couples) Therapy |  |  |  |  |  | 2.4.2, 2.4.3, 2.4.4 |
| Psychoanalysis |  |  |  |  |  | 2.4.2, 2.4.3, 2.4.4 |
| 12-step recovery programs |  |  |  |  |  | 2.4.2, 2.4.3, 2.4.4 |
| Other |  |  |  |  |  | 2.4.1, 2.4.2, 2.4.3, 2.4.4 |
| Prefer not to answer |  |  |  |  |  |  |

1. **What other type of therapy program?**

Therapy\_Type\_Other	Free text

2. **How long have you been going to therapy?**

Therapy\_Duration	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| \< 6 months |  |  |  |  |  |  |
| 6 months \- \< 1 year |  |  |  |  |  |  |
| 1 year \- \< 2 years |  |  |  |  |  |  |
| \> 2 years |  |  |  |  |  |  |

3. **What is your consistency with attending your scheduled appointments?**

Therapy\_Adherence	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| All of the time (\> 75% of the time) |  |  |  |  |  |  |
| Some of the time (50-75% of the time) |  | 1 |  |  |  |  |
| Intermittently (\< 50% of the time) |  | 1 |  |  |  |  |
| Never attend scheduled appointments |  | 1 |  |  |  |  |
| Prefer not to answer |  |  |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Some of the time (50-75% of the time) | MP0090 | Attention Priority: Member is not attending behavioral therapy appointments consistently |
| Intermittently (\< 50% of the time) | MP0090 | Attention Priority: Member is not attending behavioral therapy appointments consistently |
| Never attend scheduled appointments | MP0090 | Attention Priority: Member is not attending behavioral therapy appointments consistently |

4. **Do you feel the therapy or counseling sessions are beneficial?**

Perception\_Therapy\_Benefits	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes, all of the time (\> 75% of the time) |  |  |  |  |  |  |
| Yes, some of the time (50-75% of the time) |  |  |  |  |  |  |
| Yes, but less than 50% of the time |  |  |  |  |  |  |
| No, not at all |  |  |  |  |  |  |
| Prefer not to answer |  |  |  |  |  |  |

3. **Which of the following physical symptoms do you frequently experience due to anxiety? (Select all that apply)**

Anxiety\_Symptoms	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| None |  |  |  |  |  |  |
| Rapid heartbeat or palpitations |  |  |  |  |  |  |
| Shortness of breath or difficulty breathing |  |  |  |  |  |  |
| Sweating or trembling |  |  |  |  |  |  |
| Nausea or stomach discomfort |  |  |  |  |  |  |
| Headaches or migraines |  |  |  |  |  |  |
| Other |  |  |  |  |  | 3.1 |
| Unsure/Unknown |  |  |  |  |  |  |

1. **What other physical symptoms?**

Anxiety\_Symptoms\_Other	Free text

4. **What are the biggest problems your anxiety has caused? (Select all that apply)**

Anxiety\_Cause\_Problems\_Details	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Difficulty concentrating |  |  |  |  |  |  |
| Difficulty maintaining friendships or forming new relationships |  |  |  |  |  |  |
| Digestive issues |  |  |  |  |  |  |
| Increased conflicts or arguments |  |  |  |  |  |  |
| Substance Use |  |  |  |  |  |  |
| Withdrawal or social isolation |  |  |  |  |  |  |
| Other |  |  |  |  |  | 4.1 |

1. **What other problems has your anxiety caused?**

Anxiety\_Cause\_Problems\_Details\_Other	Free text

5. **Which of these problems make it hard for you to manage your condition? (Select all that apply)**

Barriers\_To\_Care	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| Believe treatments don't work |  | 1 |  |  |  |  |
| Embarrassed to get help |  | 1 |  |  |  |  |
| Do not have enough information about my condition |  | 1 |  |  |  |  |
| Do not know where to go for treatment |  | 1 |  |  |  |  |
| Lack of money |  | 1 |  |  |  |  |
| Lack of social support |  | 1 |  |  |  |  |
| Lack of transportation |  | 1 |  |  |  |  |
| Limited access to healthcare resources |  | 1 |  |  |  |  |
| Multiple health conditions |  | 1 |  |  |  |  |
| Other issues |  | 1 |  |  |  | 5.1 |
| No problems managing my condition |  |  |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Believe treatments don't work | MP2031 | Concern: Member anticipates difficulty following care plan |
| Embarrassed to get help | MP2031 | Concern: Member anticipates difficulty following care plan |
| Do not have enough information about my condition |  MP2031 |  Concern: Member anticipates difficulty following care plan |
| Do not know where to go for treatment | MP2031 | Concern: Member anticipates difficulty following care plan |
| Lack of money | MP2031 | Concern: Member anticipates difficulty following care plan |
| Lack of social support | MP2031 | Concern: Member anticipates difficulty following care plan |
| Lack of transportation | MP2031 | Concern: Member anticipates difficulty following care plan |
| Limited access to healthcare resources | MP2031 | Concern: Member anticipates difficulty following care plan |
| Multiple health conditions | MP2031 | Concern: Member anticipates difficulty following care plan |
| Other issues | MP2031 | Concern: Member anticipates difficulty following care plan |

1. **What other issues are making it hard for you to manage your condition?**

Barriers\_To\_Care\_Other	Free text

6. **How much do you think anxiety affects your everyday life?**

Symptoms\_Affect\_Daily\_Activties	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| Mild impact |  |  |  |  |  |  |
| Moderate impact |  | 1 |  |  |  |  |
| Significant impact |  | 1 |  |  |  |  |
| Severe impact |  | 1 |  |  |  |  |
| Unsure/Unknown |  |  |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Moderate impact | MP3456 | Reinforce: Managing anxiety |
| Significant impact | MP3456 | Reinforce: Managing anxiety |
| Severe impact | MP3456 | Reinforce: Managing anxiety |

7. **Over the last two weeks, how often have you been bothered by feeling nervous, anxious or on edge?**

Nervous\_GAD7	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---: | :---- | :---- | :---- | :---- | ----- |
| Not at all | 0 |  |  |  |  |  |
| Several days | 1 |  |  |  |  |  |
| More than half the days | 2 |  |  |  |  |  |
| Nearly everyday | 3 |  |  |  |  |  |

8. **Over the last two weeks, how often have you been bothered by not being able to stop or control worrying?**

Stop\_Worrying\_GAD7	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---: | :---- | :---- | :---- | :---- | ----- |
| Not at all | 0 |  |  |  |  |  |
| Several days | 1 |  |  |  |  |  |
| More than half the days | 2 |  |  |  |  |  |
| Nearly everyday | 3 |  |  |  |  |  |

9. **Over the last two weeks, how often have you been bothered by worrying too much about different things?**

Different\_Worries\_GAD7	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---: | :---- | :---- | :---- | :---- | ----- |
| Not at all | 0 |  |  |  |  |  |
| Several days | 1 |  |  |  |  |  |
| More than half the days | 2 |  |  |  |  |  |
| Nearly everyday | 3 |  |  |  |  |  |

10. **Over the last two weeks, how often have you been bothered by trouble relaxing?**

Trouble\_Relaxing\_GAD7	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---: | :---- | :---- | :---- | :---- | ----- |
| Not at all | 0 |  |  |  |  |  |
| Several days | 1 |  |  |  |  |  |
| More than half the days | 2 |  |  |  |  |  |
| Nearly everyday | 3 |  |  |  |  |  |

11. **Over the last two weeks, how often have you been bothered by being so restless that it is hard to sit still?**

Restless\_GAD7	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---: | :---- | :---- | :---- | :---- | ----- |
| Not at all | 0 |  |  |  |  |  |
| Several days | 1 |  |  |  |  |  |
| More than half the days | 2 |  |  |  |  |  |
| Nearly everyday | 3 |  |  |  |  |  |

12. **Over the last two weeks, how often have you been bothered by becoming easily annoyed or irritable?**

Easily\_Annoyed\_GAD7	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---: | :---- | :---- | :---- | :---- | ----- |
| Not at all | 0 |  |  |  |  |  |
| Several days | 1 |  |  |  |  |  |
| More than half the days | 2 |  |  |  |  |  |
| Nearly everyday | 3 |  |  |  |  |  |

13. **Over the last two weeks, how often have you been bothered by feeling afraid as if something awful might happen?**

Fearful\_GAD7	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---: | :---- | :---- | :---- | :---- | ----- |
| Not at all | 0 |  |  |  |  |  |
| Several days | 1 |  |  |  |  |  |
| More than half the days | 2 |  |  |  |  |  |
| Nearly everyday | 3 |  |  |  |  |  |

14. **GAD-7**

GAD7\_Score	Sum

| Score Evaluation Range |  Evaluation Description | Plan of Care |  Tasks |  Notifications | AWF Rules |  Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| 0-4 | Minimal Anxiety |  |  |  |  |  |
| 5-9 | Mild Anxiety |  |  |  |  |  |
| 10-14 | Moderate Anxiety |  |  |  |  |  |
| 15-21 | Severe Anxiety |  |  |  |  |  |

| \# | Score Data Source | Custom Code |
| :---- | :---- | :---- |
| 7\. | Over the last two weeks, how often have you been bothered by feeling nervous, anxious or on edge? | Nervous\_GAD7 |
| 8\. | Over the last two weeks, how often have you been bothered by not being able to stop or control worrying? | Stop\_Worrying\_GAD7 |
| 9\. | Over the last two weeks, how often have you been bothered by worrying too much about different things? | Different\_Worries\_GAD7 |
| 10\. | Over the last two weeks, how often have you been bothered by trouble relaxing? | Trouble\_Relaxing\_GAD7 |
| 11\. | Over the last two weeks, how often have you been bothered by being so restless that it is hard to sit still? | Restless\_GAD7 |
| 12\. | Over the last two weeks, how often have you been bothered by becoming easily annoyed or irritable? | Easily\_Annoyed\_GAD7 |
| 13\. | Over the last two weeks, how often have you been bothered by feeling afraid as if something awful might happen? | Fearful\_GAD7 |

15. **Has your anxiety caused problems with friendships and connections with others?**

Anxiety\_Cause\_Problems	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  | 15.1 |
| No |  |  |  |  |  |  |

1. **What type of problems has your anxiety caused between friends and connections? (Select all that apply)**

Anxiety\_Cause\_Friends\_Problems\_Details	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| Increased conflicts or arguments |  |  |  |  |  |  |
| Difficulty maintaining friendships or forming new relationships |  |  |  |  |  |  |
| Withdrawal or social isolation |  |  |  |  |  |  |
| Other Issues |  |  |  |  |  | 15.1.1 |

1. **What other problems has your anxiety caused?**

Anxiety\_Cause\_Friends\_Problems\_Details\_Other	Free text

16. **Who is available to you for emotional or social support? (Select all that apply)**

Social\_Emotional\_Support	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| Spouse or significant other |  |  |  |  |  |  |
| Parent(s) and/or sibling(s) |  |  |  |  |  |  |
| Friend(s) or neighbor(s) |  |  |  |  |  |  |
| Church or religious institution |  |  |  |  |  |  |
| Other |  |  |  |  |  | 16.1 |
| None |  | 1 |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| None | MP2321 | Concern: Lack of social/emotional support system |

1. **Who else is available for emotional support?**

Social\_Emotional\_Support\_Other	Free text

17. **Are there any specific situations that make your anxiety symptoms worse? (Select all that apply)**

Anxiety\_Triggers	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| None |  |  |  |  |  |  |
| Social situations or crowds |  |  |  |  |  |  |
| Public speaking or performance |  |  |  |  |  |  |
| Specific phobias (e.g., heights, flying, spiders, etc.) |  |  |  |  |  |  |
| Health-related concerns or medical procedures |  |  |  |  |  |  |
| Work or school stress |  |  |  |  |  |  |
| Other |  |  |  |  |  | 17.1 |
| Unsure/Unknown |  |  |  |  |  |  |

1. **What other situations?**

Anxiety\_Triggers\_Other	Free text

18. **Are you taking any medications for your anxiety?**

Anxiety\_Medication	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| Yes, and taking medication(s) as instructed |  |  |  |  |  | 18.1 |
| Yes, but occasionally miss one or more doses |  | 1 |  |  |  | 18.1 |
| Yes, but only take sporadically or irregularly |  | 1 |  |  |  | 18.1 |
| Not taking medication(s) |  |  |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Yes, but occasionally miss one or more doses | MP2153 | Action Needed: Medication nonadherence identified |
| Yes, but only take sporadically or irregularly | MP2153 | Action Needed: Medication nonadherence identified |

1. **What side effects are you experiencing as a result of your medication? (Select all that apply)**

Medication\_Side\_Effects\_Details	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| None |  |  |  |  |  |  |
| Headaches or migraines |  | 1 |  |  |  | 18.1.3 |
| Insomnia or other sleep disturbances |  | 1 |  |  |  | 18.1.3 |
| Nausea or stomach discomfort |  | 1 |  |  |  | 18.1.3 |
| Rapid heartbeat or palpitations |  | 1 |  |  |  | 18.1.3 |
| Shortness of breath or difficulty breathing |  | 1 |  |  |  | 18.1.3 |
| Suicidal thoughts |  | 1 |  |  |  | 18.1.2, 18.1.3 |
| Sweating or trembling |  | 1 |  |  |  | 18.1.3 |
| Weight gain |  | 1 |  |  |  | 18.1.3 |
| Other |  | 1 |  |  |  | 18.1.1, 18.1.3 |
| Unsure/unknown |  |  |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Headaches or migraines | MP2333 | Attention Priority: Medication side effects reported |
| Insomnia or other sleep disturbances | MP2333 | Attention Priority: Medication side effects reported |
| Nausea or stomach discomfort | MP2333 | Attention Priority: Medication side effects reported |
| Rapid heartbeat or palpitations | MP2333 | Attention Priority: Medication side effects reported |
| Shortness of breath or difficulty breathing | MP2333 | Attention Priority: Medication side effects reported |
| Suicidal thoughts | MP2333 | Attention Priority: Medication side effects reported |
| Sweating or trembling | MP2333 | Attention Priority: Medication side effects reported |
| Weight gain | MP2333 | Attention Priority: Medication side effects reported |
| Other | MP2333 | Attention Priority: Medication side effects reported |

1. **What other side effects?**

Medication\_Side\_Effects\_Details\_Other	Free text

2. **(Care manager to answer) What action was taken?**

Suicidal\_Thoughts\_Action\_Taken	Free text

3. **Have you told your doctor about these side effects?**

Provider\_Aware\_Medication\_SE	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |

19. **Are you doing anything else to help with your anxiety? (Select all that apply)**

Self\_Management\_Activities	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| None |  |  |  |  |  |  |
| Breathing techniques |  |  |  |  |  |  |
| Exercise |  |  |  |  |  |  |
| Herbal supplements |  |  |  |  |  |  |
| Journaling |  |  |  |  |  |  |
| Support groups |  |  |  |  |  |  |
| Yoga/Meditation |  |  |  |  |  |  |
| Other |  |  |  |  |  | 19.1 |

1. **What other activities to help with your anxiety?**

Self\_Management\_Activities\_Other	Free text

20. **How often do you drink alcohol?**

Alcohol\_Use\_Frequency	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| None |  |  |  |  |  |  |
| Occasional |  |  |  |  |  |  |
| 1 drink a day |  |  |  |  |  |  |
| 2 drinks a day |  |  |  |  |  |  |
| More than 2 drinks a day |  | 1 |  |  |  | 20.1, 20.2, 20.3, 20.4 |
| Prefer not to answer |  |  |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| More than 2 drinks a day | MP2132 | Attention Priority: Excessive alcohol consumption reported |

1. **Have you ever had a drink first thing in the morning to steady your nerves or get rid of a hangover (eye-opener)?**

CAGE\_Drinking\_Drugs\_In\_Morning	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |

2. **Have you ever felt bad or guilty about your drinking?**

CAGE\_Drinking\_Drugs\_Guilty	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |

3. **Have people annoyed you by criticizing your drinking?**

CAGE\_Drinking\_Drugs\_Criticize	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |

4. **Have you ever felt you should cut down on your drinking?**

CAGE\_Drinking\_Drugs	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |

21. **How often does anyone, including family and friends, physically hurt you?**

HITS\_Physically\_Hurt	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| Never |  |  |  |  |  |  |
| Rarely |  | 1 |  |  |  |  |
| Sometimes |  | 1 |  |  |  |  |
| Fairly often |  | 1 |  |  |  |  |
| Frequently |  | 1 |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Rarely | MP2013 | Attention Priority: Potential conflict or problems with domestic violence or abuse |
| Sometimes | MP2013 | Attention Priority: Potential conflict or problems with domestic violence or abuse |
| Fairly often | MP3057 | Action Needed: Violence or abuse suspected |
| Frequently | MP3057 | Action Needed: Violence or abuse suspected |

22. **How often does anyone, including family and friends, insult or talk down to you?**

HITS\_Insult	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| Never |  |  |  |  |  |  |
| Rarely |  | 1 |  |  |  |  |
| Sometimes |  | 1 |  |  |  |  |
| Fairly often |  | 1 |  |  |  |  |
| Frequently |  | 1 |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Rarely | MP2013 | Attention Priority: Potential conflict or problems with domestic violence or abuse |
| Sometimes | MP2013 | Attention Priority: Potential conflict or problems with domestic violence or abuse |
| Fairly often | MP3057 | Action Needed: Violence or abuse suspected |
| Frequently | MP3057 | Action Needed: Violence or abuse suspected |

23. **How often does anyone, including family and friends, threaten you with harm?**

HITS\_Threaten	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| Never |  |  |  |  |  |  |
| Rarely |  | 1 |  |  |  |  |
| Sometimes |  | 1 |  |  |  |  |
| Fairly often |  | 1 |  |  |  |  |
| Frequently |  | 1 |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Rarely | MP2013 | Attention Priority: Potential conflict or problems with domestic violence or abuse |
| Sometimes | MP2013 | Attention Priority: Potential conflict or problems with domestic violence or abuse |
| Fairly often | MP3057 | Action Needed: Violence or abuse suspected |
| Frequently | MP3057 | Action Needed: Violence or abuse suspected |

24. **How often does anyone, including family and friends, scream or curse at you?**

HITS\_Scream\_Curse	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| Never |  |  |  |  |  |  |
| Rarely |  | 1 |  |  |  |  |
| Sometimes |  | 1 |  |  |  |  |
| Fairly often |  | 1 |  |  |  |  |
| Frequently |  | 1 |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Rarely | MP2013 | Attention Priority: Potential conflict or problems with domestic violence or abuse |
| Sometimes | MP2013 | Attention Priority: Potential conflict or problems with domestic violence or abuse |
| Fairly often | MP3057 | Action Needed: Violence or abuse suspected |
| Frequently | MP3057 | Action Needed: Violence or abuse suspected |

25. **What issues with sleep are you experiencing?**

Sleep\_Difficulty	Multiselect

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| No problems sleeping |  |  |  |  |  |  |
| Chronic fatigue, even after sleeping |  |  |  |  |  | 25.1 |
| Restless |  | 1 |  |  |  | 25.1 |
| Sleeping too long |  | 1 |  |  |  | 25.1 |
| Unable to fall asleep |  | 1 |  |  |  | 25.1 |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Restless | MP3359 | Concern: Member not maintaining a regular sleep pattern |
| Sleeping too long | MP3359 | Concern: Member not maintaining a regular sleep pattern |
| Unable to fall asleep | MP3359 | Concern: Member not maintaining a regular sleep pattern |

1. **Have you discussed your sleep problems/issues with your doctor?**

Provider\_Aware\_Sleep\_Difficulty	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |

26. **Have you ever been treated for, or been admitted to the hospital because of alcohol use or illegal substances?**

Hospitalization\_Alcohol\_Drug\_Use	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |
| Prefer not to answer |  |  |  |  |  |  |

27. **Have you gone to the Emergency Room (ER) or urgent care in the past 6 months for anxiety symptoms?**

Recent\_ER\_Or\_UC\_Anxiety	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| No history of ER or urgent care visits |  |  |  |  |  |  |
| Yes, once |  |  |  |  |  | 27.1 |
| Yes, twice |  |  |  |  |  | 27.1 |
| Yes, three or more times |  | 1 |  |  |  | 27.1 |
| Unsure/Unknown |  |  |  |  |  |  |
| Prefer not to answer |  |  |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Yes, three or more times | MP3434 | Action Needed: Member with frequent ER use related to anxiety |

1. **When was the last time you went to the ER or urgent care visit for anxiety?**

Recent\_ER\_Or\_UC\_Anxiety\_Date	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| In the last 30 days |  |  |  |  |  | 27.1.1 |
| 1 to 3 months ago |  |  |  |  |  | 27.1.1 |
| 4 to 6 months ago |  |  |  |  |  |  |
| Unsure/unknown |  |  |  |  |  |  |
| Prefer not to answer |  |  |  |  |  |  |

1. **Did you have a follow-up visit with your provider within 7-30 days after your ER/urgent care visit?**

ER\_Discharge\_Follow\_Up	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |
| Unsure/Unknown |  |  |  |  |  |  |

28. **Have you been admitted to the hospital in the past 6 months for your anxiety?**

Recent\_Admission\_Anxiety	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | ----- | :---- | :---- | :---- | ----- |
| No history of inpatient stay |  |  |  |  |  |  |
| Yes, once |  | 1 |  |  |  | 28.1 |
| Yes, twice |  | 1 |  |  |  | 28.1 |
| Yes, three or more times |  | 1 |  |  |  | 28.1 |
| Unsure/Unknown |  |  |  |  |  |  |
| Prefer not to answer |  |  |  |  |  |  |

**Plan of Care**

| Responses | POC | Description |
| :---- | :---- | :---- |
| Yes, once | MP3291 | Concern: Recent hospitalization/ER visits for behavioral health condition |
| Yes, twice | MP3291 | Concern: Recent hospitalization/ER visits for behavioral health condition |
| Yes, three or more times | MP3291 | Concern: Recent hospitalization/ER visits for behavioral health condition |

1. **When was the last time you were in the hospital for your anxiety?**

Recent\_Admission\_Anxiety\_Date	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| In the last 30 days |  |  |  |  |  | 28.1.1 |
| 1 to 3 months ago |  |  |  |  |  | 28.1.1 |
| 4 to 6 months ago |  |  |  |  |  |  |
| Unsure/Unknown |  |  |  |  |  |  |
| Prefer not to answer |  |  |  |  |  |  |

1. **Did you have a follow-up visit with your provider within 7-30 days after your hospital stay?**

Admission\_Discharge\_Follow\_Up	Single select

| Responses | Score | Plan of Care | Tasks | Notifications | AWF Rules | Child |
| :---- | :---- | :---- | :---- | :---- | :---- | ----- |
| Yes |  |  |  |  |  |  |
| No |  |  |  |  |  |  |
| Unsure/Unknown |  |  |  |  |  |  |

29. **Anxiety Clinical Summary**

Anxiety\_CS	Free text