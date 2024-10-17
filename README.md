# kolesaconf-2024-materials
Публичная репка для материала, схем, кода, ссылок из презентации на тему DORA - Kolesa Conf 2024

Все материалы будут загружены в репозиторий до вечера 18 октября 2024 года.

- [Книга про DORA от самих создателей DORA](https://www.amazon.com/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339)
- [Курсы по Jira от Coursera](https://www.coursera.org/courses?partners=Atlassian)
- [Сайт проекта DORA](https://dora.dev/)

#### Другие книги от создателей DORA

- [DevOps Handbook](https://www.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1942788002)
- [The Phoenix Project](https://a.co/d/feBNR5Y)

### Useful prompts:

```
Prompt for creating simple data pipeline between Jira and Google Sheet:

You are an expert enterprise solution architect and Atlassian specialist.
You must help me design a technical solution for visualizing my jira data.

Problem with native jira site and its reports is that it can't do any sophisticated calculations and show customized charts. Like ones we see in Google Sheet charts or even Power BI. Just a quick example: I need to construct a historical chart of Change Failure Rate, which is bad release count divided by an overall release count in a period of time. There should also be selectors for project name, author, issue component etc. Jira doesn't have a way to create this customized report chart.

For solution simplicity, you should use Google Sheet as main data source and create sync pipeline that will continuously extract several project issues into it.
After setting up the extraction and loading, write down the steps to integrage Looker Studio to navigate through Jira data stored in Google Sheet and Construct a simple dashboard for measuring Deployment Frequency for a selected period.

Do not jump into specific details. First lay out the high level implementation plan for me and only after I approve a section you dive in and give me detailed steps.
```
