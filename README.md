# Antibiotics-Data-Visualization-with-Tableau

Horizontal bars have been used to visualize the data. There are five variables namely Bacteria, Penicilin, Streptomycin, Neomycin and Gram straining. Bacteria is a nominal variable. Penicilin, Streptomycin, Neomycin are Quantitative ratio variables. Gram Straining is an ordinal variable. The three X axis scales for the three antibiotics Penicilin, Streptomycin and Neomycin are placed adjacent to each other to have a common Y axis.

The X axis represents values of antibiotics Penicilin, Streptomycin and Neomycin. The antibiotic data value is encoded to length. As length is at rank 2 for visual encoding of quantitative variables, it helps in effective visualization. Penicilin values for positively classified bacteria are very small(order of 10-2) compared to that of negatively classified bacteria(order of 102). The values were not expressive on the normal scale. Therefore, all the quantitative (Penicilin, Streptomycin and Neomycin) values are converted to log scale for better expressiveness.

On the Y axis, Bacteria are grouped by Gram staining as positive and negative. Gram straining has been encoded to color and position. Position is at rank 1 for ordinal variables. So it provides effective visualization. Negative gram straining is positioned above and encoded to the color red. Positive gram straining is positioned below and encoded to color green. These colors are chosen as usually red is chosen for ‘stop’ and green is used for ‘go’ in traffic lights and in a general sense also red is used for ‘danger’ and green is for ‘life’. That is why I have used red to map negative and green to map positive. They have good contrast. Also, they gather more attention than hues of blue. The Y axis also represents different Bacteria. The Bacteria is visually mapped to position. Position is at rank 1 visual encoding for nominal variables. Therefore, it provides effective visualization. Bacteria in each category of Gram Staining is alphabetically ordered.

The visualization is designed to effectively see Gram Staining category and their range of values for each antibiotic and compare these values for each category of Gram Staining. For example, in the visualization, we can clearly see that Penicilin values for positive Gram Staining are very low and for negative Gram Staining are very high. As log scale has been used in the X axis, it might be difficult to estimate the exact value as we are usually used to normal scale. In this visualization, for a given Bacteria looking at different antibiotic values may not as effectively represented as comparing a particular antibiotic value for each Bacteria.
