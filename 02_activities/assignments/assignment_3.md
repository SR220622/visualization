# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
     
   I have chosen the Toronto Traffic Volume dataset from the City of Toronto's Open Data Portal. This dataset provides detailed information on traffic flow across major roads in Toronto, including vehicle counts by time of day and location.
    > Visualization 1: Line Chart (Python - Matplotlib/Seaborn)
    What software did you use to create your data visualization?
    Python with Matplotlib and Seaborn libraries

    > Who is your intended audience? 
    City planners, transportation analysts, and policymakers.
    
    > What information or message are you trying to convey with your visualization? 
    This visualization highlights peak traffic hours in downtown Toronto, helping identify congestion patterns and informing traffic management strategies.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive Principle: Data was filtered to focus on high-traffic zones within the downtown core to emphasize critical traffic flow patterns.

    Perceptual Principle: The line chart uses clear color contrasts (e.g., red for peak hours) and labeled axes to guide viewers’ attention.

    Aesthetic Principle: The plot maintains a clean layout with consistent spacing, minimal clutter, and a balanced color palette for readability.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    The Python code includes comments and step-by-step instructions for dataset loading, cleaning, and visualization.

    All data manipulations are saved as reusable functions to ensure replicability
    
    > How did you ensure that your data visualization is accessible?  
    Added descriptive titles, axis labels, and colorblind-friendly palettes for inclusivity.
    
    > Who are the individuals and communities who might be impacted by your visualization?
    Insights from this visualization can inform improved traffic control measures, benefiting daily commuters and reducing environmental impact through efficient routing.  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Selected only key variables like Time of Day, Location, and Vehicle Count to maintain focus on traffic trends.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Data cleaning involved handling missing timestamps, inconsistent labels, and aggregating counts by hour.

    > Visualization 2: Line Chart (Python - Matplotlib/Seaborn)
    What software did you use to create your data visualization?
    Tableau Public

    > Who is your intended audience? 
    Local businesses, public transit authorities, and Toronto residents.

    > What information or message are you trying to convey with your visualization? 
    The heatmap visualizes congestion hotspots, emphasizing the busiest intersections and roads during rush hours.

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive Principle: Only intersections with consistently high traffic volumes were included to focus on areas requiring immediate attention.

    Perceptual Principle: The heatmap's gradient scale effectively visualizes intensity, with deeper colors indicating higher congestion.

    Aesthetic Principle: Clear legend placement and tooltips improve readability and interactivity.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    Tableau workbook files are shared publicly, along with clear instructions to load the dataset for reproducibility.

    > How did you ensure that your data visualization is accessible?  
    Used color gradients that remain distinguishable for viewers with color vision deficiencies.

    Interactive tooltips provide textual descriptions for improved accessibility.

    > Who are the individuals and communities who might be impacted by your visualization?
    The visualization supports city residents in identifying alternate routes and helps businesses plan delivery schedules by recognizing peak congestion periods

    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    Focused on Intersection ID, Vehicle Count, and Time Slot to convey core congestion patterns.
 
    > What ‘underwater labour’ contributed to your final data visualization product?
    Extensive dataset exploration was required to merge multiple data sources, format timestamps, and align inconsistent road labels.

    Conclusion

Both visualizations serve distinct yet complementary purposes: the line chart emphasizes temporal trends in traffic peaks, while the heatmap pinpoints spatial congestion hotspots. Together, they provide valuable insights for policymakers, commuters, and businesses, supporting informed decision-making to improve Toronto's urban traffic landscape.


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09/03/2025`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
