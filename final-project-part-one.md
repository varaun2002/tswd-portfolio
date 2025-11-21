| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Outline
Air travel offers one of the most revealing windows into how people move, how economies grow, and how industries adapt to periods of disruption. This project analyzes U.S. air travel patterns from 2005–2025 using route-level data on passengers, carriers, and airports. By examining how airlines shift capacity across routes and hubs, the project uncovers how the aviation network evolves in response to long-term growth, competition between carriers, and major global events.

The objective is to tell a story about how airlines reshape their networks during times of stability and in the face of shocks-such as the 2008 recession and the COVID-19 pandemic-and how different carriers recover at different speeds. Through visualizing 20 years of trends, seasonality, declines, and rebounds, this project highlights both the vulnerabilities and remarkable resilience of the U.S. aviation system.

## Introduction (Setup)

1. This dataset captures monthly passenger volumes across U.S. routes, including carrier names, origin–destination airport pairs, and city-level information. Air travel data is a meaningful lens for global change because flight patterns quickly reflect economic cycles, evolving consumer behavior, and the impact of global crises.
2. One-sentence summary: “Air travel reflects how airlines and travelers adapt-revealing both resilience and vulnerability in times of crisis.”

## Rising Action (Patterns & Growth)

1. From 2005–2019, U.S. airlines show consistent growth across most major routes, alongside predictable seasonal cycles driven by summer travel peaks and winter slowdowns.
2. These long-term patterns reveal steady demand expansion and highlight how major carriers such as Southwest, United, American, and Delta shape the broader aviation ecosystem.
3. Domestic travel grows more consistently, while international travel shows sharper fluctuations due to global economic conditions and geopolitical events.

## Climax (Disruption)

1. The COVID-19 pandemic in 2020 triggered the most dramatic collapse in U.S. aviation history, with monthly passenger volumes falling to levels never seen in modern air travel.
2. Routes that previously carried tens of thousands of passengers per month dropped to a fraction of their normal volume, and entire categories of travel-especially international and business routes-were disproportionately affected.
3. Differences in recovery speeds become visible early on: airlines with heavy leisure or domestic focus stabilize sooner, while long-haul and international networks lag significantly.

## Falling Action (Recovery & Rebound)

1. Between 2021 and 2023, passenger volumes begin to rebound, though recovery paths differ across carriers and route types.
2. While total passenger numbers climb steadily, the number of flights remains lower, indicating fuller planes and more efficient scheduling.
3. International travel recovers more slowly compared to domestic routes, reflecting ongoing travel restrictions, uneven demand, and changing traveler behavior.

## Resolution (Future Outlook)

1. By 2024–2025, air travel stabilizes and approaches or exceeds pre-pandemic levels on many domestic routes. Carriers reconfigure their networks, with some hubs growing in prominence while others decline.
2. These patterns raise broader questions about the future of air travel: How will climate policies, fuel costs, or geopolitical uncertainty shape airline strategy? Will hybrid work permanently reduce business travel? What new mobility technologies might reshape demand?

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

The dataset used in this project is compiled from monthly U.S. airline activity between 2005 and 2025, based on data originally sourced from the U.S. Bureau of Transportation Statistics (BTS). For the purposes of this project, the raw data was cleaned, merged, and standardized into a structured CSV file containing route-level passenger counts across major U.S. airlines.

Each row in the dataset represents a single carrier operating a specific route in a specific month, allowing analysis at the carrier, route, airport, and city level.

The cleaned dataset includes the following variables:
PASSENGERS – number of passengers transported on a given route in a given month
UNIQUE_CARRIER_NAME – full airline name (e.g., United Air Lines Inc., Southwest Airlines Co.)
ORIGIN, DEST – airport codes representing the origin and destination airports
ORIGIN_CITY, DEST_CITY – readable city names mapped from airport codes
MONTH – month and year of service (formatted as MM-YYYY), covering 2005–2025

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
