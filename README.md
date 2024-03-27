
# 34th Street Magazine Headline Scraper

## Overview
This project modifies an existing scraper by @jlumbroso to fetch the top headline and its subtitle from the 34th Street Magazine's homepage. The change in focus from The Daily Pennsylvanian to 34th Street Magazine reflects a broader interest in the cultural and artistic discussions within the Penn community.

## Modification Details

### Target Website Change
- **Previous Target**: The Daily Pennsylvanian (thedp.com)
- **New Target**: 34th Street Magazine (34st.com)
- **Reason**: To capture the essence of Penn's cultural and artistic scene, providing a snapshot of the vibrant discussions and expressions within the University.

### CSS Selector Update
- **Updated Elements**: 
  - The main headline is identified by the class `headline-link` within an `h2` tag.
  - The subtitle is extracted from the `abstract` class within a `p` tag.
- **Rationale**: In the 34st publications, both the title and subtitle form the overall name of the article. For example, in the latest publication as of March 26th, 2024, the title of the headline article is "Pounding Pavement," and its subtitle is "Catching up with the sole–breaking collegiate marathon craze". Both the title and subtitle play a crucial role in highlighting what the article is about.

### Subtitle Inclusion
- **Format**: "(Title): (Subtitle)"
- **Importance**: Adds depth and context to the headline, offering a comprehensive glimpse into the article's content without directly visiting the site.

### Technical Implementation
The scraper's logic was adjusted to target the specific HTML structure of 34th Street Magazine's homepage. This involved updating the `scrape_data_point` function to fetch the headline and subtitle, combining them in a user-friendly format that enriches understanding at a glance.

### Rationale for Scraper Focus Shift
The decision to focus on 34th Street Magazine stems from an intent to delve into the nuanced cultural fabric of the Penn community. By showcasing artistic and cultural narratives, the scraper broadens its lens to include a diverse range of student activities and discussions, enriching the data collected with layers of cultural significance.

## Conclusion
This modified scraper serves as a tool for engaging with the cultural and artistic dimensions of campus life at Penn, emphasizing the importance of student expressions and activities beyond the conventional news narrative. It is a testament to the dynamic, multifaceted nature of student life and interests at the University.

