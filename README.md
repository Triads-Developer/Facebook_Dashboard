
# Transforming Election Data into Actionable and Dynamic Dashboards

Social media has become an essential part of political campaigns and can influence the political discourse. 
However, monitoring and analyzing vast amounts of data is challenging. 
In this project the <a href="https://triads.wustl.edu">  TRIADS </a> development team takes existing  <a href="https://help.crowdtangle.com/en/articles/2346958-using-crowdtangle-for-elections-coverage">CrowdTangle </a> election data and transforms it into dynamic dashboards using metabase.  

# Social Media Analytics Tool

<a href="https://help.crowdtangle.com/en/articles/2346958-using-crowdtangle-for-elections-coverage">CrowdTangle </a> is a social media analytics tool that provides real-time monitoring and analysis of public content on social media platforms like Facebook, Instagram, Twitter, and Reddit. <a href="https://polisci.wustl.edu/people/jacob-montgomery"> Jacob Montgomery </a>, a political science professor at Washington University in St. Louis, uses CrowdTangle to track and analyze social media activity related to election campaigns, candidates, and issues.

# Analytics Dashboard 

The TRIADS development team has assisted Professor Montgomery turn the data he collected through CrowdTangle into dynamic dashboards. By using 
<a href="https://www.metabase.com">Metabase</a>,  Professor Montgomery can visualize his data and gain deeper insights into the electoral landscape.
These custom dashboards allow for tracking essential metrics, including engagement levels, sentiment, and other relevant data, which facilitates a more comprehensive analysis of the electoral data. 

CrowdTangle provides measures for different types of social media reactions, including anger, haha, and wow. Here are some of the measures that CrowdTangle can provide specifically for these types of reactions:

- **Total reactions:** The total number of all reactions for a given social media account or post, including anger, haha, wow, and others.
- **Reactions breakdown:** The breakdown of the different types of reactions for a given social media account or post, including anger, haha, wow, and others.
- **Reaction rate:** The percentage of people who reacted with a specific type of reaction (e.g. anger, haha, wow) out of the total number of people who saw a given social media account or post.
- **Top posts by reaction type:** The most engaging posts for a given social media account or topic, ranked by a specific type of reaction (e.g. anger, haha, wow).
- **Influencer identification by reaction type:** The identification of top influencers for a given topic or set of keywords based on a specific type of reaction (e.g. anger, haha, wow).
- **Hashtag analysis by reaction type:** The total number of posts, engagements, and top posts for a given hashtag on a social media platform, broken down by a specific type of reaction (e.g. anger, haha, wow).



Using Metabase and CrowdTangle, it is possible to create a map that shows the total number of reactions by state and the specific type of reaction (e.g. anger, haha, wow). By collecting social media reaction data through the CrowdTangle API and formatting it into a table, it can be used as the source for a Metabase question. When visualized as a map, each state is grouped together and represented by the total number of reactions for that state, while different types of reactions are represented by different colors or shading. This can provide valuable insights into the sentiment and engagement of social media users across different regions.<table>
  <tr>    
    <td><img src="/states.png" alt="Image 3"></td>
  </tr>
</table>
