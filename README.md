# Beyond the Route: Transit Confidence Across Boston's MBTA System

An interactive Tableau dashboard exploring when, where, and why the MBTA system experiences delays and congestion — and what that means for commuter reliability.

🔗**https://public.tableau.com/app/profile/nikitha.vishnumolakala/viz/mbta_dashboard/MBTATransitReliabilityCongestionDashboard**


## The Question

Where and when does the MBTA system experience the most delay and congestion, and what does that mean for commuter reliability?

## Data Source

MBTA Travel Time Dataset (2026)

## Tools Used

- Tableau Public (data visualization + dashboard design)

## Key Metrics Tracked

- **Avg Travel Time** — system-wide average trip duration
- **Most Congested Line** — Red Line, with the highest average delay
- **Busiest Operational Windows** — 6–8 AM and 4–7 PM (rush hour peaks)
- **Most Reliable Travel Window** — 10 AM–12 PM

## What's in the Dashboard

1. **Usage by hour** — a bar chart showing when the system sees the most activity across the day, highlighting clear morning and evening peaks
2. **Most time-intensive commuter journeys** — the slowest station-to-station pairs (e.g. Braintree ↔ Alewife, Davis ↔ Braintree), surfacing where riders lose the most time
3. **Congestion heatmap by route and hour** — Blue, Orange, and Red Line congestion side by side across all 24 hours, showing the Red Line as consistently the most congested

## Key Insights

- The Red Line shows the highest and most sustained congestion of the three lines tracked, averaging 15.25 minutes per trip during peak periods
- Congestion is concentrated in predictable AM/PM commuter windows (6–8 AM, 4–7 PM), while 10 AM–12 PM is the most reliable window for travel
- The slowest commuter routes cluster around a handful of station pairs (Braintree, Alewife, Davis, Quincy Adams), suggesting these corridors are priority candidates for scheduling improvements

## What I'd Improve Next Time

- Add a filter/parameter to let users isolate a single line or station pair interactively
- Bring in a comparison year to show whether congestion patterns are improving or worsening over time
- Explore whether ridership volume (not just travel time) correlates with the congestion patterns on the Red Line

---
*This was my first dashboard built in Tableau — a hands-on project to practice translating raw transit data into a clear operational story.*
