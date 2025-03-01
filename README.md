# belly-button-challenge
Build and interactive dashboard to explore dataset given

## Belly Button Link

<https://bgrlgymnast.github.io/belly-buton-challenge/

## Instructions
Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
 
- Use sample_values as the values for the bar chart.

- Use otu_ids as the labels for the bar chart.

- Use otu_labels as the hovertext for the chart.

![hw](./hw01.jpg)

3. Create a bubble chart that displays each sample.

    - Use otu_ids for the x values.

    - Use sample_values for the y values.

    -  Use sample_values for the marker size.

    - Use otu_ids for the marker colors.

    - Use otu_labels for the text values.

![bubble](./bubble_chart.jpg)

4. Display the sample's metadata, i.e., an individual's demographic information.

    - Loop through each key-value pair from the metadata JSON object and create a text string.

    - Append an html tag with that text to the #sample-metadata panel.

        ![hw3](./hw03.jpg)

5. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:


![hw2](./hw02.jpg)

6. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

## Hints
- Use console.log inside of your JavaScript code to see what your data looks like at each step.

- Refer to the Plotly.js documentationLinks to an external site. when building the plots.

## References
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.

- https://plotly.com/javascript/bubble-charts/
- https://plotly.com/javascript/horizontal-bar-charts/
- Classmates & TA

## Copyright
© 2024 edX Boot Camps LLC
