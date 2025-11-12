| [home page](https://varaun2002.github.io/tswd-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Redesigning “Which is the Best Performing Marvel Movie?”

For this assignment, I selected a data visualization from MakeoverMonday that analyzes the financial performance of Marvel movies. The original visualization aimed to answer a question that appeals to both movie fans and business-minded viewers: “Which is the best performing Marvel movie?”

The original graphic presents each Marvel movie as a point on a scatterplot, plotting release year against % of budget recovered, with colors representing different Marvel sub-franchises. While visually striking and data-rich, the presentation felt overwhelming due to cluttered labeling, a large color palette, and difficulty extracting key takeaways quickly.

This redesign challenge allowed me to apply Stephen Few’s Data Visualization Effectiveness Profile, reflect on clarity vs aesthetics, sketch alternative layouts, gather feedback, and build an improved version in Tableau that prioritizes interpretability and storytelling.

## Step one: the visualization

Source: Which is the Best Performing Marvel Movie? - Created by InformationIsBeautiful as part of MakeoverMonday
Data: the-numbers.com & rottentomatoes.com (Mar 2025 update)

[Link](https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/)

Screenshot - <img width="1438" height="538" alt="Screenshot 2025-11-11 at 9 36 07 PM" src="https://github.com/user-attachments/assets/ad00f17b-3a53-462e-a41c-bf63fc51ed61" />


Description:
I chose this visualization because:
- The topic is widely relatable, making insights meaningful to a broad audience.
- The original scatterplot has strong intent but tries to communicate too much at once, creating visual overload.

- There is an opportunity to simplify the interface, improve labeling and data grouping, and show clear rankings.
- User-focused redesign helps demonstrate impact — from “information overload” to “insight first.”

Screen capture of original visualization included above.

## Step two: the critique

1. The use of many franchise colors and direct labels for nearly every movie creates visual clutter. With so many competing elements, viewers must work harder to understand the chart, slowing comprehension and reducing engagement.
2. Clarity suffers from overlapping labels and tightly clustered points. Many movie names sit on top of each other, especially around the mid-range budget recovery line. This makes it difficult to clearly identify individual films without hovering or zooming.
3. The chart format does not fully support the question posed. The title asks which movie performs best, yet a scatterplot makes ranking difficult to see at a glance. Users have to visually search for the highest-performing films instead of being guided to them.
4. The tone feels analytical rather than audience-friendly. Although Marvel content appeals to a broad, entertainment-oriented audience, the visualization feels like a finance dashboard. A simpler design with fewer colors, selective labeling, and more obvious highlights would help make the insights more accessible.

## Step three: Sketch a solution

<img width="921" height="791" alt="Screenshot 2025-11-11 at 9 54 46 PM" src="https://github.com/user-attachments/assets/dfad5e26-a44e-4fae-92ac-60960c4791ac" />


## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
| What do you think this is? | A dashboard comparing Marvel movies by performance. | A dashboard comparing Marvel movies by performance. |
| Can you describe to me what this is telling you? | It ranks Marvel movies by how much money they made relative to budget and shows a comparison with critic scores. | It shows the top Marvel films by ROI. |
| Is there anything you find surprising or confusing? | The abbreviations like IM2 are not super clear and the scatter labels are hard to interpret. | It is unclear what the dotted line represents. |
| Who do you think is the intended audience for this? | Marvel fans or general viewers curious about movie success. | Students or analysts exploring movie performance data, or entertainment industry audiences. |
| Is there anything you would change or do differently? | Add clearer movie names and maybe use icons or colors to help differentiate. | Add audience score as a filter, refine titles/labels, and adjust spacing for readability. |

## Step five: build the solution

For my final redesign, I built an interactive Tableau dashboard to answer one clear question: Which Marvel movies delivered the best financial returns, and how does that compare to their critics' scores?

<div class='tableauPlaceholder' id='viz1762984542101' style='position: relative'><noscript><a href='#'><img alt='Marvel - Best Performers ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MarvelBestPerformers&#47;Marvel-BestPerformers&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MarvelBestPerformers&#47;Marvel-BestPerformers' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MarvelBestPerformers&#47;Marvel-BestPerformers&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1762984542101');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else { vizElement.style.width='100%';vizElement.style.height='877px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>




I replaced the original Makeover Monday scatterplot with a ranked horizontal bar chart showing return on investment (% of budget recovered). This makes the top-performing films immediately visible instead of forcing viewers to scan dozens of labels. I also added a Top-N per category parameter - a key improvement over the original.

Below the bar chart, I included a scatterplot comparing ROI to critics' ratings, with average reference lines to help users spot trends. Filters for year and franchise, plus click-to-highlight interaction, let viewers explore without clutter.

My design choices focused on clarity: minimal labels, color only for franchise category, and a compact control panel. The dashboard now feels like a clean movie-performance tool rather than an overwhelming chart.

## References

[Data](https://data.world/makeovermonday/what-is-the-best-performing-marvel-movie/workspace/file?filename=What+is+The+Best+Performing+Marvel+Movie_+PUBLIC+DATA.xlsx)
[Visualization](https://informationisbeautiful.net/visualizations/which-is-the-best-performing-marvel-movie/)

## AI acknowledgements

Parts of the written content were refined with the help of AI language tools to improve clarity, tone, and readability.
