# Deutsche Welle Website Analysis: Graph Mining Perspective

## Project Overview

Our project delves into the graph mining aspects of the Deutsche Welle (DW) website, a leading German international broadcaster. Focused on news articles published between October 1, 2023, and December 31, 2023, our primary objective is to employ graph mining techniques to analyze the correlation among the Region, Category, and Related Topics. The hypothesis driving our investigation posits that DW provides unbiased global news coverage, transcending diverse categories and regions.

## Tasks

### Task 1-2:

Our initial steps involve the extraction of data from DW.com, forming the basis for graph mining exploration. We aim to uncover intricate relationships within the news articles, emphasizing the interconnectedness of Regions, Categories, and Related Topics.

### Task 3:

Graph mining techniques are applied to visualize daily article counts, emphasizing primary regions and categories. Noteworthy insights include daily count fluctuations, an average of 39 articles per day, and dominant categories like Politics and Conflicts, constituting over 40% of all article classifications.

### Task 4:

In-depth graph mining properties are applied to Region and Category attributes, unveiling network structure nuances. Categories such as Politics, Culture, Conflicts, Nature & Environment, and Arts are identified as pivotal in network connections. Pagerank analysis further supports the significance of these categories.

### Task 5:

Centrality analyses, including Degree Centrality, Closeness Centrality, and Betweenness Centrality, illuminate the pivotal role of the "Category" attribute in the DW news dissemination network. Nodes associated with "Category" exhibit central roles and close connections, underscoring its importance.

### Task 6:

Graph mining extends to community detection methods, employing the Louvain method and Girvan-Newman Algorithm. These methods successfully identify distinct communities, offering insights into thematic structures based on categories surrounded by the region = Germany and regions surrounded by the category = Politics.

## Future Work

While our current analysis, primarily focused on Region and Category attributes, aligns with the initial hypothesis of unbiased news coverage, future work could deepen insights through the exploration of additional attributes like Text, Related Topics, and Summary. Such an approach would enhance the graph mining perspective, providing a more nuanced understanding of DW's commitment to comprehensive and inclusive news reporting globally. Recognizing project limitations, future analyses are encouraged to broaden the scope and uncover deeper connections within the DW news network.