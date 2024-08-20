# GitHubComparisonCharts
This repository contains the dataset used in the paper "A Hybrid Keyword-Driven Rule-Based Approach for Automatic Generation of Comparison Charts of GitHub Repositories"

The dataset is collected from 283 readme files obtained from GitHub repositories. To ensure diverse coverage of repositories, we retrieve repositories whose primary programming language is Java, JavaScript, C#, Python, or C++. We obtain the readme files of the top 100 repositories for each of these languages, where the results are sorted in descending order based on repository stars. Then, we filter the results by including only the repositories with readme files written in English and exceeding 1000 bytes. These filtering rules aim to include only mature repositories with high stars, which increases the likelihood of obtaining well-written readme files. 

The following table shows the number of instances in the dataset, grouped by programming language.

|Language   |No. of Instances|Class     |Pct. |
|...........|................|..........|.....|
|Java       | 617            |Training  |13.5%|
|JavaScript | 1112           |Training  |24.3%|
|C#         | 977            |Training  |21.3%|
|C++        | 876            |Training  |19.1%|
|Python     | 984            |Testing   |21.5%|

