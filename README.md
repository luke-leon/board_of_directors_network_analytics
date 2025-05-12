# Board of Directors Network Analytics

This project explores how social network analysis can uncover structural dynamics within corporate boards. By treating board members and companies as nodes in a bipartite graph, we identified key influencers, potential governance risks, and network-driven insights that wouldn’t appear in traditional org charts or resumes.

## Project Overview
- **Goal:** Understand how individuals and organizations are connected through board memberships and analyze the influence and centrality of key players.
- **Data Source:** Simulated or anonymized BoardEx-style data (bipartite graph of people and companies)
- **Approach:**
  - Constructed a bipartite network graph of directors and firms.
  - Projected one-mode networks (firm-to-firm, director-to-director).
  - Computed metrics like degree, betweenness, closeness, and eigenvector centrality.
  - Visualized network structures and highlighted central nodes.
  - Interpreted network structure to evaluate organizational risk and influence.

## Tools & Techniques
- **Python**: `networkx`, `pandas`, `matplotlib`
- **Analytics**: Centrality measures, community detection, graph projection
- **Visualization**: Network diagrams and centrality plots

## Files
- `board_network_analysis.ipynb`: Full notebook with data processing, network construction, and analysis
- `slides.pdf`: Presentation summarizing findings and insights

## Key Takeaways
- Revealed hidden connections and potential conflicts of interest in a board network.
- Applied graph theory and social network analysis to a corporate governance use case.
- Demonstrated how network centrality can inform strategic decisions around leadership and risk.
