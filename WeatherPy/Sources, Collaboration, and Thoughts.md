### Sources
- Question that needs to be answered?
  - More ellaboration and information.
  - How was the question answered.
    - Source: Basic description of the source [hyperlink text](URL GOES HERE)

### Collaborations
- Primary Collaborators
  - Sy Flores and Benjamin Wankmuller
- List any other collaborations here

### Thoughts
- What is Being Asked?
  - Plotting multiple scatterplots to show latitude relationships for temp, humidity, cloudiness, and wind speed
  - Break these apart into Northern and Southern hemispheres
  - Run a linear regression on all 8 relationships
- Pseudocode
  - Pull in data from cities.csv
  - Pull the data in using an API call on those cities (iterate)
  - Convert to a DataFrame using pandas
  - Pop any rows that have humidity > 100%
