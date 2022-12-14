## My VA Analytics
### July 2022

### Why we use analytics:
The My VA team uses analytics in several ways. First, we use analytics to inform decision making regarding upcoming features or improvements to our product. Second, we utilize KPI dashboards to measure the success of our product and new features that we develop for My VA. Finally, through monitoring analytics we can determine if there are any bugs or issues with our product based on if key metrics are not meeting our expectations or show significant unexpected changes. 
### How we use analytics:
- Google Analytics - GA is a web analytics tool that allows us to view key metrics around My VA website traffic. Through GA we can view how many users are visiting My VA and what links and searches are most popular. Our dashboard is linked here.
- Domo - Domo is a business intelligence tool that allows us to create customized dashboards and reporting around My VA’s key metrics. It is a new tool to the VA and dashboards are currently being developed by our Platform team. Once complete, it will contain the same metrics that exist within GA today. Here is a mock up.
- Grafana - This is a performance monitoring tool that helps us ensure the reliability and stability of our product. It is used by engineers to monitor the health of VA.gov and identify key areas of performance improvements.
- Sentry - Sentry provides application log monitoring. It is utilized by engineers to monitor application errors and ensure applications are running smoothly for our users. You can access Sentry here with SOCKS access enabled.
- Medallia - This is a third party vendor that collects feedback from users on Va.gov. It is a short survey that asks what the user was trying to accomplish and if they were able to accomplish it. It then asks for a 1-5 satisfaction rating of Va.gov. Results of these surveys are visible on GA.

### Our KPIs and important metrics:
- Total unique visitors to My VA - this metric is important because it gives us an indication of who and how many users are visiting My VA in any given time period and allows us to track over time if My VA is becoming more or less popular with our users.

- User Feedback/Ratings - While we most commonly receive feedback through UAT sessions, directly from our users we also have Medallia which allows users to submit feedback through Va.gov. This feedback is then logged in a GA dashboard. User feedback is critical to allowing us to understand the reliability, usability and accessibility of our product.
- Searches - it is important for us to know what our users are searching for on Va.gov. It allows us to determine if there are key features that are missing from My VA that would allow our users to access their information quicker. It gives us insight into whether or not a user can reach their goal on My VA without having to use search functionality. Below is an example of how we could visualize this:

- Events (interactions) - By understanding what links our users are accessing the most or least we can determine if our features are meeting their intended goals or if links on the page should be removed or edited. Below are our top interactions:

- Failures - My VA is heavily dependent on other products such as VAOS (VA online scheduling) and VA Notify. In order to ensure we are making successful connections to these products we track event failures. When an increase in failures occurs we can assume that there is an issue with one of our connections or with My VA itself and troubleshoot accordingly.

### How we can improve our analytics:
1. Currently we do not track conversion rates or turn time for My VA. This would enable us to determine if users are able to achieve their goals quickly and efficiently. I.e How much time on average are users spending on My VA, What is the drop rate (going to My VA then leaving without taking any action).
2. We should regularly review metrics to help inform discovery for new features, we could benefit from reviewing our current metrics and taking note of any areas of opportunity. This is something we do today but not on a formalized cadence as far as I know
Metrics can bring visibility into issues or bugs within our product. By setting up alerting and monitoring we can be more proactive in addressing these issues and ensuring the reliability of our product. This is something we have already started but can continue to evolve
3. Lastly, we could utilize user feedback surveys and contact center data more heavily, and ensure we are reviewing them regularly for any pertinent feedback that could inform new features or adjustments to existing features. 







