In your project repository, create a new file named StatusReport.md that contains:

○ An update on each of the tasks described on your project plan including
references and links to specific artifacts in your repository (such as datasets,
scripts, workflows, workflow diagrams, etc).

○ An updated timeline indicating the status of each task and when they will be
completed.
| Task | Description | Target Completion | Responsible Team Member(s) | Status |
|---|---|---|---|---|
| **1. Project Plan** | Finalize our research questions, datasets, methodology, and team responsibilities. Submit the project plan through GitHub. | October 22 | All Team Members | Completed |
| **2. Data Acquisition & Organization** | Download the IMF, OECD, and World Bank datasets, verify their integrity, review licensing restrictions, and organize files in the repository. | November 1 | Anthony | Completed |
| **3. Initial Data Quality Assessment** | Evaluate the datasets for accuracy, completeness, timeliness, and consistency. Identify missing values, duplicates, and differences in country and year coverage. | November 3 | Zoe | Completed |
| **4. Data Cleaning** | Address missing values, standardize country names and year formats, remove duplicates, and document cleaning decisions. | November 7 | Zoe | Completed |
| **5. Data Integration** | Merge the cleaned datasets by country and year, identify unmatched records, and document the integration process. | November 11 | Sarah | Completed |
| **6. Post-Integration Quality Assessment** | Evaluate the merged dataset for accuracy, completeness, timeliness, and consistency to verify that the integration was successful. | November 14 | Sambhavi | Completed |
| **7. Data Analysis & Visualization** | Calculate summary statistics, examine correlations between higher education and unemployment, identify outliers, and create visualizations comparing countries and trends over time. | November 30 | Sarah, Anthony | In-progress |
| **8. Workflow Automation & Reproducibility** | Develop separate scripts connected by an automated workflow. Document software dependencies and test that the project runs from data acquisition through analysis. | December 2 | Zoe, Anthony | In-progress |
| **9. Metadata & Documentation** | Create a data dictionary, machine-readable metadata, and documentation covering data sources, licensing, file organization, and reproducibility. | December 4 | Sambhavi, Zoe | In-progress |
| **10. Final Report & Submission** | Complete the README with our methodology, findings, challenges, and conclusions. Review the project requirements, verify contributions, and create the final GitHub release. | December 7 | All Team Members | In-progress |

○ A description of any changes to your project plan itself, in particular about your
progress so far. Also include changes you made to your plan based on feedback
you may have received for Milestone 2.
Our project plan has slightly changed in terms of an updated timeline of when we expect to finish our tasks for the project. Previously, we expected to be done with the analysis and final report by the end of November, but we decided to push back to early December to ensure the quality of our data processing, analysis, curation, and report. Thus, most of our pre-processing and evaluation will be conducted before spring break, while the analysis and documentation will be finished during and after thanksgiving break. 

Based on our feedback for Milestone 2, we received an ungraded "gaps" part of the project plan. Although this might be a grading issue, we still looked into how well the three datasets link with each other, and observed how different the timeframe for each dataset is. We observed that the World bank data has entries since 1980s, while the OECD and IMF datasets begin in 2017 and 2020. Furthermore, we also observed how each dataset had different number of countries included, with the OECD dataset including only 48, and the World bank dataset having more than 200. Based on these identified gaps, we will need to narrow our analysis to the years and countries that is covered by all datasets. 

○ Summarize any challenges or problems you have encountered so far. For each
issue, explain how you resolved it or describe your plan to address it in the near
future.

○ Each team member has to write a short summary of their contributions to the
current milestone. Each team member should add and commit their contribution
summary themselves to the shared github repo.

Anthony: As of now, I acquired the three datasets from the websites. After downloading the raw data and the metadata, I fitted the dataset for this project by filtering for columns that would help answer our research question. The raw data created and filtered can help teammates more conveniently process and analyze the datasets for this research project. Next, I checked the licensing of the datasets for CC licenses and researched the reuse of each data from their respective websites. Since this project is for academic-use, there would be no licensing conflict. Once I downloaded the data, I also verified the integrity of the dataset by examining the columns, the number of fields, unique countries, and no duplicates. For the status report, I updated the timeline for each step of our project, with each status either as "completed" or "in-progress", as well as the expected completion date for each task.
