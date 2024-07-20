# CS416 Narrative Visualization Final Project
# US COVID-19 Cases and Deaths by State

#### Project by: Tahir Bagasrawala (tahirib2)

## Project Details
*Leaderboard Competition* soure code consists of following:
- /docs: Documentation for (1) [Project Final Presentation](https://github.com/tahirbags/cs410_project_public/blob/main/docs/final-project-slides.pdf) (2) [Project Progress Status Report](https://github.com/tahirbags/cs410_project_public/blob/main/docs/cs410_project_status_report.pdf) (3) [Project Presentation Video]([https://www.youtube.com/watch?v=QKsb__Nze-c](https://github.com/tahirbags/cs410_project_public/blob/main/docs/CS410%20Final%20Demo.mov))
- /models: 11 total models (incl. baseline), a combination of discriminative and generative classifiers, were developed, tuned and tested against the dataset.
  1. **Messaging [10 points]**: The message of the narrative visualization is to provide an understanding of the distribution and impact of COVID-19 cases and mortalities across the United States. Specifically, it aims to highlight the differences between case counts and mortality rates in various states, showing how high case counts do not necessarily correlate with high mortality rates. 
  2. **Narrative Structure [10 points]**: The narrative visualization follows an interactive slide show structure. This structure allows users to progress through a series of visualizations in a linear sequence while providing opportunities for deeper exploration and interaction at each stage. The heat maps and the interactive plotter allow users to drill down into specific data points as they move through the narrative.
  3. **Visual Structure [10 points]**: The visual structures are designed to be intuitive and easy to navigate, with clear color codes and interactive elements that guide the viewer's focus to the most important data points.
  - Chart 1: Heat map of COVID-19 cases - This heat map uses color intensity to represent the number of COVID-19 cases across different states. It ensures the viewer can quickly identify states with high case counts, such as Florida, Texas, and New York, through the use of darker colors. The visual structure focuses the viewer's attention on these high-impact areas.

  - Chart 2: Heat map of COVID-19 mortalities - This heat map uses a similar color scheme to represent mortality rates, with the US Northeast highlighted for its high mortality rates. The contrast between high case counts and lower mortality rates in states like California, Texas, and Florida is emphasized.

  - Chart 3: Interactive plotter - This plotter allows users to compare cases and mortality rates interactively for the top 5 states in each category. The interactive elements enable users to explore the data dynamically, reinforcing the message by providing a deeper, more personalized look at the statistics.
