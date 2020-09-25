# Global Giving
This is a skills test for the nonprofit Global Giving. The best way to review this project is in this order:
1. Read the process overview below.
2. Review the dataPrepation.ipynb file.
3. Review the corr.ipynb file.
4. Watch the linked video walk-through of the preliminary AWS QuickSight dashboard.

## Process Overview
To tackle this project, I engaged in the following process. 

**Preparation & Process (1 hour):** First, I closely read the assignment and tried to get a sense of who the consumers of this information and the dashboards would be. Ultimately, the goal of the assessment was to create a resource useful for the Global Giving Program team, so I spent some time reviewing the profiles of the individuals currently serving on this team to get a sense of how this team works with Global Giving's organizations. I also hoped to get a sense of their technical expertise to gauge how to put together the dashboards. From there I decided that my end goal for this project would be to create a GitHub Repository that connects houses Jupyter Notebook files that illustrates the data exploration process and initial analyses as well as an AWS QuickSight dashboard prototype.

**Data Exploration & Preliminary Analysis (4 hours):** I definitely spent the bulk of my time here, as I believe it is the second-most important piece of any data project. The first more important piece would be knowing the needs of the consumer of your products, a step you don't quite get to do in a skills test, though I mimicked it to the best of my ability in the preparation phase, through a review of the Global Giving website, including staff, project pages and the Accelerator Program overview. The general purpose of this phase is to understand as thoroughly as possible the data that was provided and to transform that data to a format that can be used in analysis and dashboard building. For this first step, I only made it to bivariate correlations, but as I obtain more data and information from the Program team, I would like to begin developing multivariate predictive models for each of the regions. I discuss some of the limitations of the current data set in the dataPreparation.ipynb and corr.ipynb files.

**Dashboard Design & Construction (2 hours):** In the next phase, I began constructing an AWS QuickSight dashboard, which includes a sample dashboard with both a global and regional view with visualizations for some of the variables I believe could be impacting retention based on this preliminary analysis. 

**Documentation Preparation (1 hour):** Finally, I built out the GitHub repository, wrote the README.md file (as I'm doing now) and recorded a short video walk-through of the AWS QuickSight dashboard.

Now that you've read through this--I recommend reviewing the dataPreparation.ipynb file and then the corr.ipynb file before watching the dashboard overview:

<iframe src="https://unt.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=f07cc209-5c0f-4a23-86fa-ac4100ef3a76&autoplay=false&offerviewer=true&showtitle=true&showbrand=false&start=0&interactivity=all" height="405" width="720" style="border: 1px solid #464646;" allowfullscreen allow="autoplay"></iframe>

## Next Steps
1. The first next step for me is actual to backtrack to what I believe the first-first step should be in a dashboard design process--communicating with the end-user about their needs. What would they like to see? What questions do they have? What would be helpful to them in their day-to-day work? What do they feel like is difficult to keep track of? 
2. This is another "first step" next step type issue, but it would be learning more about the history of this dataset and Global Giving generally. What changes have been made that could result in changes in delinquency rates? Have the goals or procedures changed at all over time? This might be a place to measure effects or it might just serve as a cut-off point for cohort analysis. As in, maybe we're not comparing apples to applies when we compare 2005 Global Giving to 2018. 
3. A real next step is to go through this analysis thoroughly to make sure I didn't make any mistakes! It's easy to lie with data (accidentally, of course), especially when you're under time pressure. So, I'd like to thoroughly go through this analysis again to make sure I didn't miss anything, as well as supplement the preliminary analyses with assumptions testing, basic visualizations and post-hoc testing before moving on to a consideration of multivariate analysis.
4. Speaking of multivariate analysis, while this data is just fine for establishing correlations (i.e. less funding = greater likelihood of being delinquent), I don't know that the data is great for building models with predictive capability. I believe I discussed this some in the analysis files, but for that I'd really like to see some time series data that includes snapshots of things like funding, unique donors, online activity, etc. over time. With time series data, we can start to talk about where the benchmarks are for different organizations and review in real-time whether an organization appears at-risk for lapsing into Delinquency and/or not deriving the full benefit they might from Global Giving. In addition to building multivariate predictive models, I'd like to explore whether different regions might require different models, as well as determine whether specific regions and/or project themes attract more donors and/or funds.
5. After these steps are taken, I'd like to build a predictive model to help the Global Giving Program team identify those organizations most in need of attention as well as improve the dashboards, ideally making a semi-custom dashboard for each regional group within the Global Giving Program team. 


