# Tracking Excessive Force Against Protesters in Iran (2016-2026)
## 🌐 My Site
Visit the interactive map: (https://ccb2195-ux.github.io/acled-mapping/)
## My Goals
- I wanted to get comfortable both analyzing and mapping ACLED data, as I'm sure it will be coming up a lot for me. While I feel like I got a lot better at **understanding** the ACLED data, I don't feel confident yet in my storytelling ability across mediums (from Analysis → Dev → Writing → Publishing).
- I went in blind just hoping to find something shocking, and shocking it was. The excessive violence against protesters sub-category of data showed a huge spike in late 2025 corresponding directly with the start of the Iran protests in 2025, which I was able to confirm with the geolocation data.
- I didn't however touch on the most interesting finding yet, which is that the ACLED data shows a steady and unrelenting growth in peaceful protest movements across MENA, which I will be diving into next.
- My analysis was mostly accomplished with facet wrapping in ggplot, though I think the area where I tried and failed the hardest was the design and execution of my interactive mapping feature. I wanted to have a sliding bar and a density measurement allowing the user to manually control the displayed data, and I wanted each point to contain relevant data for researchers to use, though I feel like I got only the bare minimum accomplished.
- I did all the analysis myself in R & Python, and I employed Claude Code to help me quickly build the site. All of the text on the site is written by me, but Claude helped me transition my ggplot from RStudio into an Altair graphic since I can't seem to get the %%R magic box working in my Python instance.

## This Project Uses Python, Pandas, Folium, & Altair

## 📁 Project Structure
```
├── index.html                  # Main website
├── ACLED_MENA_Map2.html       # Interactive Folium map
├── density_plot.png           # Timeline visualization
├── protest_map_MENA.ipynb    # Jupyter notebook with analysis
├── ACLED_MENA_Data.xlsx      # Source data
└── SETUP_GITHUB_PAGES.md     # Deployment guide
```

## Data
Data provided by the [Armed Conflict Location & Event Data Project (ACLED)](https://acleddata.com/), from which I took all available incident data from the MENA region and filtered it in my notebooks.

## How AI Was Used
I used the teams version of Claude Code available at the time to help me build the visualizations. For the Altair chart, I had it provide me with a template to change myself, and for the Folium visualization, it did almost all of the work, which is why it looks so wonky. In the future I will not be doing that again.

I do think AI is bad for the world in the way it is being implemented at the moment, but I hope that through learning how to use it I will be able to better report on it, and also be more capable of destroying or changing the institutions using AI to harm our labor, our information, and our environment.
