| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Outline
Air travel is one of the clearest indicators of global mobility, economic health, and resilience in the face of crises. This project explores U.S. domestic and international flight trends from 2002–2025, focusing on how passenger volumes and flight counts evolved across major events such as the post-9/11 recovery, the 2008 financial crisis, the COVID-19 pandemic, and the rebound in the 2020s.

The goal is to tell a story about how external shocks reshape air travel patterns and how recovery trajectories differ between domestic and international markets. By visualizing long-term trends, seasonal cycles, and sudden disruptions, the project will highlight both the fragility and resilience of the aviation industry. Ultimately, the project aims to help audiences understand the broader narrative of mobility, globalization, and recovery through the lens of flight data.

## Introduction (Setup)

1. Present the dataset and explain why air travel is a meaningful lens for global change.
2. One-sentence summary: “Air travel reflects the world’s resilience and vulnerability to crises.”

## Rising Action (Patterns & Growth)

1. Show steady growth in flights and passengers from 2002–2019.
2. Highlight seasonal cycles (summer peaks, winter dips).
3. Compare domestic vs. international growth rates.

## Climax (Disruption)

1. Visualize the dramatic collapse in 2020 due to COVID-19.
2. Emphasize the scale of decline (e.g., April 2020: only ~1,464 flights vs. ~14,000 pre-pandemic).
3. Contrast domestic vs. international recovery speeds.

## Falling Action (Recovery & Rebound)

1. Show gradual recovery from 2021–2023.
2. Highlight differences in passenger vs. flight recovery (fewer flights but fuller planes).
3. Note international lag compared to domestic.

## Resolution (Future Outlook)

1. Present 2024–2025 data showing stabilization and return to pre-pandemic levels.
2. Pose questions about future resilience: climate change, geopolitical tensions, and new mobility technologies.

## Initial sketches

<img width="648" height="484" alt="Screenshot 2025-11-19 at 3 58 32 PM" src="https://github.com/user-attachments/assets/62976a7f-c016-4f58-aa51-87e23f744c8b" />

Line Chart (Flights Over Time)

- X-axis: Year/Month

- Y-axis: Flights_Total

- Highlight disruptions (2008 dip, 2020 collapse).


<img width="652" height="544" alt="Screenshot 2025-11-19 at 3 59 00 PM" src="https://github.com/user-attachments/assets/471ca8c0-33e1-4eb0-93aa-fa2ef5d59d15" />

- Stacked Area Chart (Domestic vs. International Passengers)

- Show proportions shifting over time.

- Emphasize international recovery lag.

# The data

Source
The primary dataset for this project comes from the U.S. Bureau of Transportation Statistics (BTS).

For this project, I’ve cleaned and aggregated the raw BTS data into a structured CSV file (cleaned_flights_data.csv) that covers 2002–2025. The cleaned dataset includes:

Flights_Domestic – monthly count of domestic flights
Flights_International – monthly count of international flights
Flights_Total – combined monthly flights
Passengers_Domestic – monthly domestic passenger totals
Passengers_International – monthly international passenger totals
Passengers_Total – combined monthly passenger totals


| Name | URL | Description |
|------|-----|-------------|
| Air Carrier Statistics (Form 41 Traffic) – T-100 Segment data | [URL](https://www.transtats.bts.gov/Data_Elements.aspx?Qn6n=E) | This dataset provides monthly records of domestic and international flights, along with passenger counts, spanning multiple decades. |

## Planned Use

- Identify long-term growth trends in U.S. air travel.
- Highlight disruptions such as the 2008 financial crisis and the 2020 COVID-19 pandemic.
- Compare domestic vs. international recovery trajectories, showing how international travel lagged behind domestic.
- Visualize seasonal cycles (summer peaks, winter dips) to emphasize recurring travel patterns.
- Build interactive dashboards that allow audiences to filter by year, flight type, and passenger counts.

# Method and medium
The project will be completed using:
- Shorthand for narrative storytelling (scroll-based story arc).
- Tableau for interactive visualizations (line charts, area charts, dashboards).

## References
1. Data elements. (n.d.). [https://www.transtats.bts.gov/Data_Elements.aspx?Qn6n=E](https://www.transtats.bts.gov/Data_Elements.aspx?Qn6n=E)

## AI acknowledgements
Parts of the written content were refined with the help of AI language tools to improve clarity, tone, and readability.
