# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.

**Good visualization**
*[Official World Happiness Report 2021 Ranking](https://public.tableau.com/app/profile/worldhappinessreport/viz/Figure2_1_16157724652500/2021WorldHappinessReport), published on the World Happiness Report’s Tableau Public profile.*

    I classify this as a good visualization because its design makes the main message clear while still allowing the viewer to explore additional detail.

    **The first reason** is its clear organization and accurate visual encoding. The chart presents countries as horizontal stacked bars, ordered from the highest to the lowest life-evaluation score. This ordering immediately communicates the ranking and allows the viewer to identify the highest- and lowest-scoring countries without needing to read every number. Because the bars share a common baseline, their total lengths can be compared accurately. Research on graphical perception shows that viewers generally compare position and length more accurately than area, angle, or volume, which supports the effectiveness of this design (Cleveland & McGill, 1984; Heer & Bostock, 2010).

    **The second reason** is the chart’s readable layout and effective use of context. The horizontal orientation is a major strength. Country names can be written clearly beside the bars, whereas a vertical bar chart would likely require rotated or abbreviated labels. The title and explanatory text also provide important context by identifying the topic, reporting year, and meaning of the overall score. This allows the visualization to be interpreted without requiring extensive outside explanation.

    **The third reason** is that the stacked sections add a useful second level of information. In addition to showing each country’s overall life-evaluation score, the chart separates the estimated contributions of factors such as social support, healthy life expectancy, freedom, generosity, and perceptions of corruption. The consistent use of colour across countries enables viewers to see that the same factor is represented in the same way throughout the chart. This supports comparison of both the total score and its components. The visualization therefore follows the useful principle of presenting an overview first and then allowing the audience to examine details.

    **The fourth reason** is that the chart uses a restrained and focused design. It avoids decorative three-dimensional effects, unnecessary icons, and excessive text. Most of the visual space is devoted to the data itself, which improves the data-to-ink ratio and reduces distraction. The ranking structure creates a clear narrative: countries differ in their reported happiness, and those differences are associated with several measurable factors.

    - How could this data visualization have been improved?  

    Despite these strengths, the visualization could still be improved. **The first improvement** would be to use a colour-blind-safe palette, stronger contrast, direct labels, or patterns because some colours are light or visually similar. **The second improvement** would be to add a complementary dot plot, heatmap, or small-multiple chart because stacked segments that do not begin at the same baseline are difficult to compare precisely across countries. **The third improvement** would be to provide an accessible data table for users who rely on screen readers or need exact values.

**Bad visualization**
*[World Happiness Report](https://public.tableau.com/app/profile/sara.hamdoun4060/viz/WorldHappinessReport_15657272841480/WorldHappinessReport), created by Sara Hamdoun on Tableau Public.*
      
      ```
    I classify this visualization as ineffective for communicating an overview of country differences. It places 20 countries in rows, shows their ranks for happiness and six related indicators in separate vertical columns, and connects each country’s ranks across the columns.

    **The first reason** is that the many crossing lines produce a “spaghetti” effect. A viewer must trace one thin line through several intersections to follow a country, which demands sustained attention and creates unnecessary cognitive load. The repeated circles and lines have almost equal visual weight, so there is no clear focal point or narrative. Parallel-coordinate displays can be useful for interactive exploration of a few highlighted cases, but displaying all countries equally makes both comparison and pattern detection difficult.

    **The second reason** is that the chart encodes rank rather than the underlying values. Rank removes information about magnitude: a one-rank difference may represent either a very small or a large difference in the original measure. It also makes relationships across indicators harder to interpret because the viewer cannot tell whether changes between columns are substantively meaningful. The visualization therefore gives a strong impression of movement while withholding the scale needed to evaluate it.

    **The third reason** is that the chosen encodings do not support accurate comparison. Although each column has a common vertical order, the viewer is mainly asked to interpret slopes, crossings, and line paths rather than straightforward position or length. Research on graphical perception shows that aligned position and length are generally decoded more accurately than less direct encodings.

    **The fourth reason** is that accessibility is limited. The labels and connecting lines are small and low contrast, and hover-based identification would disadvantage users who cannot use a pointer or distinguish fine marks.

      ```
    - How could this data visualization have been improved? 

      ```
    **The first improvement** would be to replace this display with a heatmap or a set of aligned dot plots. Countries could remain in rows, sorted by overall happiness, while each indicator is shown in a separate aligned column. Using actual scores—or clearly labelled standardized scores—would retain magnitude. **The second improvement** would be to use a restrained, colour-blind-safe palette and add text labels or symbols as redundant encodings. **The third improvement**, if the parallel-coordinate form were retained, would be to show only a few selected countries by default, fade the other lines, directly label the selected countries, and provide an accessible table and a concise explanation of the measures and source.

      ```    

- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 -  2026-06-09`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
