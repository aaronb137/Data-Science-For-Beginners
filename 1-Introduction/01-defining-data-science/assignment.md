# Assignment: Data Science Scenarios

In this first assignment, we ask you to think about some real-life process or problem in different problem domains, and how you can improve it using the Data Science process. Think about the following:

1. Which data can you collect?
1. How would you collect it?
1. How would you store the data? How large the data is likely to be?
1. Which insights you might be able to get from this data? Which decisions we would be able to take based on the data?

Try to think about 3 different problems/processes and describe each of the points above for each problem domain.

Here are some of the problem domains and problems that can get you started thinking:

1. How can you use data to improve education process for children in schools?
1. How can you use data to control vaccination during the pandemic?
1. How can you use data to make sure you are being productive at work?
## Instructions

Fill in the following table (substitute suggested problem domains for your own ones if needed):

| Problem Domain | Problem | Which data to collect | How to store the data | Which insights/decisions we can make | 
|----------------|---------|-----------------------|-----------------------|--------------------------------------|
| Education | How can we improve a student's success in high school? Students in lower income areas tend to have low success rates. We hypothesize that schools that have higher funding tend to have significant increases in standardized test scores. | Data we can collect are the median school budgets from each county and the median standardized test scores (ACT/SAT) from each county. | To store the data, this data should already be structured where for each county we may need to create an aggregate of processed data of each school in a county (structured still). This data is possibly available through publicly released documents and would be stored as a table. | Insights from this data can yield information on which county would require more funding; allowing for accurate allocation and possible increases of student success in low income communities where more funding could be placed. |
| Vaccination | In the event of a pandemic, how can we improve control of our vaccination process? When outbreaks occur, whole communities can be hotbeds for a pandemic. We hypothesize that by observing virus data transmission locations we can identify locations that have high possibilities of transmission in order to give end-users insight on possible decisions they can make to prevent transmission at vaccination clinics. | The data we would collect would be from surveys clinics possibly hand out which can detail a patient's name, address, ZIP of possible transmission (which can be provided by tracking their location using a possible iteration of the COVID tracker on mobile devices) | We could store the data on a data lake (given how many possible transmissions could occur in just one city) and the data would be structured within a table. | By creating a heatmap for each ZIP within a city, local municipalities can observe communities that are heavily affected by a pandemic and adjust accordingly to prevent further transmission |
| Productivity | How can I maintain productivity while at work? My main problem with productivity is being distracted by my phone while doing work. I hypothesize that by reducing my phone screen time, my productivity with work will increase. | Data we can collect can be data from my phone's screentime data. At the moment Apple does not allow for data exporting so possible jailbreak scripting may be required to retrieve this data. Another piece of data we can collect is my time spent working on my desktop/laptop. | To store the data, it might be structured/semi-structure depending on how the data is stored on my computer and IPhone. I would also need to store the times I usually work which would be structured. We can store this data in a SQL database. | For this I can compute the average time spent between my IPhone and computer. With the IPhone data, I can also see which application is taking most of my screen time. I would correlate these times with the stored times of when I am working and see if there is a correlation between these three pieces of data. To increase my productivity, I can delete the applications that are taking most of my time on my IPhone and/or create a script that will run during times I am most distracted to remind me to get back on track. |

## Rubric

Exemplary | Adequate | Needs Improvement
--- | --- | -- |
One was able to identify reasonable data sources, ways of storing data and possible decisions/insights for all problem domains | Some of the aspects of the solution are not detailed, data storage is not discussed, at least 2 problem domains are described | Only parts of the data solution are described, only one problem domain is considered.
