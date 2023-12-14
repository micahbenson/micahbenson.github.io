---
title: "Analyzing Migrant Health Data for MdC"
last_modified_at: 2023-12-13
---

In a recent project for Misión de Caridad, I cleaned and analyzed data from medical fairs that we run to provide medical care to an underserved community on the Mexican side of the US border. Many people we work with never seen a doctor outside of these medical fairs, which means we have a responsibility to provide the best care possible and keep track of their health changes over time. 

At the start of the summer, I was given the task of cleaning a large spreadsheet of medical history data. The data had been collected at all our medical fairs by translating handwritten Spanish notes in to English and then inputing them into Excel. There were significant problems with including spelling errors, inconsistent values, and incorrect information. I spent a month cleaning the data by normalizing the dataset, standardizing string values, and identifying data-entry errors. Now that the data is cleaned, MdC has a reliable record of health in the community we serve, helping us to better target our programs. 

After cleaning the data, I led a team of doctors to analyze changes in population health over time using the cleaned data. We found that applying silver dioxide fluoride to teeth significantly improved dental health in the short term but wore off over time. MdC used this information to change its strategy for dental care. 

You can learn more about our medical fairs here: https://mdcaridad.org/medical-fairs 

Check out some of the code I used to clean the data on my Github: https://github.com/micahbenson/mdc-data-cleanup 