# DSC_211_Karate_Club_Assignment
## Discussion: Central Nodes and Influence of Community Structure

Across the iterative spectral splits, certain nodes consistently remain central—especially **node 0** and **node 33**, which act as major hubs in the Karate Club network. Their high values in **degree**, **betweenness**, and **closeness** persist across iterations because they serve as key connectors between different subgroups.

The evolving community structure strongly influences these metrics:

- Nodes located near **community boundaries** show higher **betweenness**, since they bridge separate regions during early splits.
- Nodes inside **tightly knit subcommunities** tend to have higher **clustering coefficients**, especially once they become isolated into smaller groups.
- As communities become smaller, centrality becomes more **localized**, highlighting internal connectivity rather than global influence.

Overall, spectral partitioning reveals how global hubs (like nodes 0 and 33) gradually shift to **local community-level centrality** as recursive splits continue.
## libraries used
- numpy
- matplotlib
- networkx
