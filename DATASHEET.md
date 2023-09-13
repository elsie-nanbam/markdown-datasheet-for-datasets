# Datasheet: School Shootings Dataset

Author: Elsie David

Organization: The Washington Post


## Motivation

*The questions in this section are primarily intended to encourage dataset creators to clearly articulate their reasons for creating the dataset and to promote transparency about funding interests.*

1. **For what purpose was the dataset created?** Was there a specific task in mind? Was there a specific gap that needed to be filled? Please provide a description.

	The creators  of the School Shootings dataset recognised the lack of official public comprehensive records, documentation or tracking for school shootings and the ease with which these violent events quickly fade from memory until the next time it happens. To remedy this, the authors created a dataset that records details of the events and its victims, both silent and otherwise.

2. **Who created this dataset (e.g. which team, research group) and on behalf of which entity (e.g. company, institution, organization)**?

	The Washington Post is the author of the School Shootings dataset, the information was collected and recorded by reporters for The post on behalf of the organisation. Specific credit to reporters is recorded on their website [1]. 

3. **What support was needed to make this dataset?** (e.g. who funded the creation of the dataset? If there is an associated grant, provide the name of the grantor and the grant name and number, or if it was supported by a company or government agency, give those details.)

	While it is not explicitly mentioned, by all indications, the creation of this dataset was funded by the Washington Post.

4. **Any other comments?**

	*Your Answer Here*


## Composition

*Dataset creators should read through the questions in this section prior to any data collection and then provide answers once collection is complete. Most of these questions are intended to provide dataset consumers with the information they need to make informed decisions about using the dataset for specific tasks. The answers to some of these questions reveal information about compliance with the EU’s General Data Protection Regulation (GDPR) or comparable regulations in other jurisdictions.*

1. **What do the instances that comprise the dataset represent (e.g. documents, photos, people, countries)?** Are there multiple types of instances (e.g. movies, users, and ratings; people and interactions between them; nodes and edges)? Please provide a description.

	Each instance is a record of a school shooting incident with details of the event and the subjects involved across 50 columns, each event is unique and there are no duplications.

2. **How many instances are there in total (of each type, if appropriate)?**

	The dataset consists of 387 unique instances

3. **Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?** If the dataset is a sample, then what is the larger set? Is the sample representative of the larger set (e.g. geographic coverage)? If so, please describe how this representativeness was validated/verified. If it is not representative of the larger set, please describe why not (e.g. to cover a more diverse range of instances, because instances were withheld or unavailable).

	The data recorded is not a sample but was selected after collection from different sources, reviewed against the criteria of events that happened on school premises either during classes or immediately before/after and entered manually into the database. The data is not sourced from an official pre-existing comprehensive source and so it very possibly does not contain all possible instances.

4. **What data does each instance consist of?** "Raw" data (e.g. unprocessed text or images) or features? In either case, please provide a description.

	Each instance consists of processed alphanumeric text of values.

5. **Is there a label or target associated with each instance?** If so, please provide a description.

	There is no label associated with the instances.

6. **Is any information missing from individual instances?** If so, please provide a description, explaining why this information is missing (e.g. because it was unavailable). This does not include intentionally removed information, but might include, e.g. redacted text.

	Some information for the instances like the time of event and the race of the shooter are missing most likely due to its unavailability, some columns like the second shooter information column are also left blank most likely because they do not apply to the particular instance. Most of the information for the instances are provided with few of them missing or unaccounted for.

7. **Are relationships between individual instances made explicit (e.g. users' movie ratings, social network links)?** If so, please describe how these relationships are made explicit.

	There are no explicit relationships between instances

8. **Are there recommended data splits (e.g. training, development/validation, testing)?** If so, please provide a description of these splits, explaining the rationale behind them.

	No there are not.

9. **Are there any errors, sources of noise, or redundancies in the dataset?** If so, please provide a description.

	It is assumed that the data in the dataset was carefully recorded after verification but there could be errors as a result of the human factor in collection and recording.

10. **Is the dataset self-contained, or does it link to or otherwise rely on external resources (e.g. websites, tweets, other datasets)?** If it links to or relies on external resources, a) are there guarantees that they will exist, and remain constant, over time; b) are there official archival versions of the complete dataset (i.e., including the external resources as they existed at the time the dataset was created); c) are there any restrictions (e.g. licenses, fees) associated with any of the external resources that might apply to a future user? Please provide descriptions of all external resources and any restrictions associated with them, as well as links or other access points, as appropriate.

	Yes it is self contained and does not contain any links to external resources.

11. **Does the dataset contain data that might be considered confidential (e.g. data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)?** If so, please provide a description.

	Most of the data is sourced from public records and so is publicly available data and would not be considered confidential.

12. **Does the dataset contain data that, if viewed directly, might be offensive, insulting, threatening, or might otherwise cause anxiety?** If so, please describe why.

	No it does not.

13. **Does the dataset relate to people?** If not, you may skip the remaining questions in this section.

	Yes it does.

14. **Does the dataset identify any subpopulations (e.g. by age, gender)?** If so, please describe how these subpopulations are identified and provide a description of their respective distributions within the dataset.

	The dataset does specify the age, gender and race of individuals. Demographic information of students was sourced from the US Education department and relies on their means of identification.

15. **Is it possible to identify individuals (i.e., one or more natural persons), either directly or indirectly (i.e., in combination with other data) from the dataset?** If so, please describe how.

	No, the dataset on its own does not provide enough information to identify individuals.

16. **Does the dataset contain data that might be considered sensitive in any way (e.g. data that reveals racial or ethnic origins, sexual orientations, religious beliefs, political opinions or union memberships, or locations; financial or health data; biometric or genetic data; forms of government identification, such as social security numbers; criminal history)?** If so, please provide a description.

	The dataset does provide information on the race and gender of subjects, all of which is publicly available information from public records and so would not be considered sensitive.


18. **Any other comments?**

	*Your Answer Here*


## Collection

*As with the previous section, dataset creators should read through these questions prior to any data collection to flag potential issues and then provide answers once collection is complete. In addition to the goals of the prior section, the answers to questions here may provide information that allow others to reconstruct the dataset without access to it.*

1. **How was the data associated with each instance acquired?** Was the data directly observable (e.g. raw text, movie ratings), reported by subjects (e.g. survey responses), or indirectly inferred/derived from other data (e.g. part-of-speech tags, model-based guesses for age or language)? If data was reported by subjects or indirectly inferred/derived from other data, was the data validated/verified? If so, please describe how.

	The data was collected from a combination of sources including news articles, police reports, school records and other publicly available information, some information may have been gotten directly from schools. The Post’s team of reporters worked to verify and cross-reference the information to ensure accuracy.

2. **What mechanisms or procedures were used to collect the data (e.g. hardware apparatus or sensor, manual human curation, software program, software API)?** How were these mechanisms or procedures validated?

	The data was most likely compiled using manual human curation.

3. **If the dataset is a sample from a larger set, what was the sampling strategy (e.g. deterministic, probabilistic with specific sampling probabilities)?**

	More than 1000 shooting incidents were reviewed but only the ones that happened on school premises, immediately before, during or just after classes and involved casualties other than the perpetrator were included in the dataset.

4. **Who was involved in the data collection process (e.g. students, crowdworkers, contractors) and how were they compensated (e.g. how much were crowdworkers paid)?**

	The data was collected by The Washington Post’s reporters from a combination of sources, mostly public records. There is no record of compensation offered or paid.

5. **Over what timeframe was the data collected?** Does this timeframe match the creation timeframe of the data associated with the instances (e.g. recent crawl of old news articles)? If not, please describe the timeframe in which the data associated with the instances was created. Finally, list when the dataset was first published.

	Historical data in the dataset was collected and compiled over a period of one year, it contains information on school shootings in the United States since April 20, 1999. The dataset was first published and made publicly accessible on their website on April 20, 2018.

7. **Were any ethical review processes conducted (e.g. by an institutional review board)?** If so, please provide a description of these review processes, including the outcomes, as well as a link or other access point to any supporting documentation.

	Unknown

8. **Does the dataset relate to people?** If not, you may skip the remainder of the questions in this section.

	Yes it does

9. **Did you collect the data from the individuals in question directly, or obtain it via third parties or other sources (e.g. websites)?**

	Data was collected from multiple publicly available sources including calls to schools and police departments.

10. **Were the individuals in question notified about the data collection?** If so, please describe (or show with screenshots or other information) how notice was provided, and provide a link or other access point to, or otherwise reproduce, the exact language of the notification itself.

	Since most of the information was already on the public record, it is unlikely any subjects were given notification of data collection.

11. **Did the individuals in question consent to the collection and use of their data?** If so, please describe (or show with screenshots or other information) how consent was requested and provided, and provide a link or other access point to, or otherwise reproduce, the exact language to which the individuals consented.

	Not Applicable (refer to response above)

12. **If consent was obtained, were the consenting individuals provided with a mechanism to revoke their consent in the future or for certain uses?** If so, please provide a description, as well as a link or other access point to the mechanism (if appropriate).

	Not Applicable

13. **Has an analysis of the potential impact of the dataset and its use on data subjects (e.g. a data protection impact analysis) been conducted?** If so, please provide a description of this analysis, including the outcomes, as well as a link or other access point to any supporting documentation.

	unknown

14. **Any other comments?**

	*Your Answer Here*


## Preprocessing / Cleaning / Labeling

*Dataset creators should read through these questions prior to any pre-processing, cleaning, or labeling and then provide answers once these tasks are complete. The questions in this section are intended to provide dataset consumers with the information they need to determine whether the “raw” data has been processed in ways that are compatible with their chosen tasks. For example, text that has been converted into a “bag-of-words” is not suitable for tasks involving word order.*

1. **Was any preprocessing/cleaning/labeling of the data done (e.g. discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)?** If so, please provide a description. If not, you may skip the remainder of the questions in this section.

	7 percent was deducted from the enrollment total to account for students that miss school each day (this is the approximate value according to the National Center for Education Statistics) and 50 percent was deducted if the incident occurred outside school hours (immediately before or after)

2. **Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (e.g. to support unanticipated future uses)?** If so, please provide a link or other access point to the "raw" data.

	Unknown

3. **Is the software used to preprocess/clean/label the instances available?** If so, please provide a link or other access point.

	Unknown

4. **Any other comments?**

	*Your Answer Here*


## Uses

*These questions are intended to encourage dataset creators to reflect on the tasks  for  which  the  dataset  should  and  should  not  be  used.  By  explicitly highlighting these tasks, dataset creators can help dataset consumers to make informed decisions, thereby avoiding potential risks or harms.

1. **Has the dataset been used for any tasks already?** If so, please provide a description.

	This dataset has been cited and used by researchers, journalists, and policymakers to track and analyse school shootings.

2. **Is there a repository that links to any or all papers or systems that use the dataset?** If so, please provide a link or other access point.

	No there is not.

3. **What (other) tasks could the dataset be used for?**

	The school shooting dataset can prove useful for analysis on gun violence and its far reaching effects on individuals 

4. **Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses?** For example, is there anything that a future user might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g. stereotyping, quality of service issues) or other undesirable harms (e.g. financial harms, legal risks) If so, please provide a description. Is there anything a future user could do to mitigate these undesirable harms?

	Unknown

5. **Are there tasks for which the dataset should not be used?** If so, please provide a description.

	The dataset should not be used for commercial purposes.

6. **Any other comments?**

	*Your Answer Here*


## Distribution

*Dataset creators should provide answers to these questions prior to distributing the dataset either internally within the entity on behalf of which the dataset was created or externally to third parties.*

1. **Will the dataset be distributed to third parties outside of the entity (e.g. company, institution, organization) on behalf of which the dataset was created?** If so, please provide a description.

	The Washington Post has made the school shooting dataset publicly accessible on their website.

2. **How will the dataset will be distributed (e.g. tarball on website, API, GitHub)?** Does the dataset have a digital object identifier (DOI)?

	The School Shooting dataset can be accessed through the Washington Post’s website. [1] [2]

3. **When will the dataset be distributed?**

	The dataset is already available on the Washington Post’s website

4. **Will the dataset be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?** If so, please describe this license and/or ToU, and provide a link or other access point to, or otherwise reproduce, any relevant licensing terms or ToU, as well as any fees associated with these restrictions.

	The dataset is published under an Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license [3] which grants users rights to reproduce and Share the dataset for noncommercial purposes only

6. **Have any third parties imposed IP-based or other restrictions on the data associated with the instances?** If so, please describe these restrictions, and provide a link or other access point to, or otherwise reproduce, any relevant licensing terms, as well as any fees associated with these restrictions.

	No, there are no other restrictions on the data associated with the instances.

7. **Do any export controls or other regulatory restrictions apply to the dataset or to individual instances?** If so, please describe these restrictions, and provide a link or other access point to, or otherwise reproduce, any supporting documentation.

	There er no export controls.

8. **Any other comments?**

	*Your Answer Here*


## Maintenance

*As with the previous section, dataset creators should provide answers to these questions prior to distributing the dataset. These questions are intended to encourage dataset creators to plan for dataset maintenance and communicate this plan with dataset consumers.*

1. **Who is supporting/hosting/maintaining the dataset?**

	The dataset is hosted and maintained by the Washington Post.

2. **How can the owner/curator/manager of the dataset be contacted (e.g. email address)?**

	The owner can be contacted using this email address: schoolshootings@washpost.com.

3. **Is there an erratum?** If so, please provide a link or other access point.

	There is no erratum.

4. **Will the dataset be updated (e.g. to correct labeling errors, add new instances, delete instances)?** If so, please describe how often, by whom, and how updates will be communicated to users (e.g. mailing list, GitHub)?

	The dataset is hosted by the Washington Post and is continuously updated to include new incidents and additional information as it becomes available. The frequency of updates or mode of communication is not explicitly mentioned.

5. **If the dataset relates to people, are there applicable limits on the retention of the data associated with the instances (e.g. were individuals in question told that their data would be retained for a fixed period of time and then deleted)?** If so, please describe these limits and explain how they will be enforced.

	There are no applicable limits on the retention of data associated with the instances.

6. **Will older versions of the dataset continue to be supported/hosted/maintained?** If so, please describe how. If not, please describe how its obsolescence will be communicated to users.

	Older versions are not stored, the dataset is updated and maintained on the existing version.

7. **If others want to extend/augment/build on/contribute to the dataset, is there a mechanism for them to do so?** If so, please provide a description. Will these contributions be validated/verified? If so, please describe how. If not, why not? Is there a process for communicating/distributing these contributions to other users? If so, please provide a description.

	ntending contributors are to reach out to the author of the dataset using the email address provided. It can be assumed that any information provided will be verified before being updated on the dataset.

8. **Any other comments?**

	*Your Answer Here*


**References:

[1] The Washington Post. (2018). data-school-shootings. GitHub. https://github.com/washingtonpost/data-school-shootings

[2] John Woodrow Cox, Steven Rich, Linda Chong, Lucas Trevor, John Muyskens and Monica Ulmanu . More than 356,000 students have experienced gun violence at school since Columbine. https://www.washingtonpost.com/education/interactive/school-shootings-database/

[3] Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license. https://github.com/washingtonpost/data-school-shootings/blob/master/LICENSE

