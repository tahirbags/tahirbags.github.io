# CS416 Narrative Visualization Final Project
# US COVID-19 Cases and Deaths by State

#### Project by: Tahir Bagasrawala (tahirib2)

## Project Details

  1. **Messaging [10 points]**: The message of the narrative visualization is to provide an understanding of the distribution and impact of COVID-19 cases and mortalities across the United States. Specifically, it aims to highlight the differences between case counts and mortality rates in various states, showing how high case counts do not necessarily correlate with high mortality rates. 
  2. **Narrative Structure [10 points]**: The narrative visualization follows an interactive slide show structure. This structure allows users to progress through a series of visualizations in a linear sequence while providing opportunities for deeper exploration and interaction at each stage. The heat maps and the interactive plotter allow users to drill down into specific data points as they move through the narrative.
  3. **Visual Structure [10 points]**: The visual structures are designed to be intuitive and easy to navigate, with clear color codes and interactive elements that guide the viewer's focus to the most important data points.
    - Chart 1: Heat map of COVID-19 cases - This heat map uses color intensity to represent the number of COVID-19 cases across different states. It ensures the viewer can quickly identify states with high case counts, such as Florida, Texas, and New York, through the use of darker colors. The visual structure focuses the viewer's attention on these high-impact areas.

    - Chart 2: Heat map of COVID-19 mortalities - This heat map uses a similar color scheme to represent mortality rates, with the US Northeast highlighted for its high mortality rates. The contrast between high case counts and lower mortality rates in states like California, Texas, and Florida is emphasized.

    - Chart 3: Interactive plotter - This plotter allows users to compare cases and mortality rates interactively for the top 5 states in each category. The interactive elements enable users to explore the data dynamically, reinforcing the message by providing a deeper, more personalized look at the statistics.
  4. **Scenes [10 points]**: The scenes are ordered logically to first present the overall case distribution, followed by the mortality distribution, and finally, an interactive tool to explore the data in greater detail. This progression helps build a comprehensive understanding of the data.
    - Heat map of COVID-19 cases - Introduces the viewer to the distribution of cases across the US.
    - Heat map of COVID-19 mortalities - Provides a comparison to the case distribution, highlighting differences in mortality rates.
    - Interactive plotter - Allows for detailed exploration of the top states with the highest cases and mortalities.
  5. **Annotations [10 points]**: The annotations follow a descriptive template, providing key insights and highlighting important data points within each scene. For example, annotations in the heat maps might point out specific states with high case counts or mortality rates, while the interactive plotter might include tooltips and labels to guide user interaction. Annotations are used to support the messaging by calling attention to significant patterns and outliers in the data. They help ensure that the viewer understands the key takeaways from each scene. Annotations may change within a scene, particularly in the interactive plotter, where tooltips and dynamic labels provide context-specific information based on user interactions.
  6. **Parameters [10 points]**: The states of the narrative visualization are determined by the combination of these parameters, defining what data is displayed and how it is presented in each scene. Each scene's parameters are configured to highlight specific aspects of the data, guiding the viewer through the narrative
    - Geographic regions (states) - Defines the scope of the heat maps and interactive plotter.
    - Case counts and mortality rates - The primary data points visualized in each scene.
    - Interactivity options - Such as selecting specific states or toggling between different data views in the interactive plotter.
  8. **Triggers [10 points]**: Affordances provided to the user include clear visual cues (e.g., buttons, highlighted regions) and instructions (e.g., tooltips, labels) that indicate how they can interact with the visualization. These affordances help users understand the available options and how to navigate through the narrative, ensuring an engaging and informative experience.
    - Clicking on states in the heat maps - To view detailed case and mortality data for specific regions.
    - Interactive elements in the plotter - Such as dropdown menus, sliders, or clickable legends that allow users to customize their view and compare different states.
