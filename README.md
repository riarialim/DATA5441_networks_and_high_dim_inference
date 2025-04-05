# DATA5441 Networks and High-dimensional Inference

This course covered methods and theories used in analysing high-dimensional data with an emphasis on network structures and statistical inference. 
Some of the key areas covered were graph theory, network robustness, strength of ties, and concepts such as network susceptibility and critical thresholds in network failure.

## Group Project: Understanding Weak Ties in Social Networks
### Summary
* Group project, collaborated with [Jimnena](https://github.com/jimenaspi).
* Investigated the "strength of weak ties" hypothesis in social networks.
* Focused on how social network robustness is affected by removing links.
* Methods were based on the study by Onnela et al. (2007).
* Used two datasets:
  * A real-world social network from an Australian university residence hall.
  * A synthetic network generated using the Power-Law Cluster model.
* Examined the impact of deleting links based on:
  * Edge weight.
  * Node overlap.

### Problem statement
* How do weak ties impact the structural stability of social networks?
* Specifically: Does the removal of weak ties trigger network collapse?

### Solution
* Analysed both real and synthetic weighted, directed social networks.
* Simulated the deletion of links in:
  * Ascending/descending order of edge weight.
  * Ascending/descending order of node overlap.
* Observed fragmentation patterns in the networks.
* Found that removing weak ties (low weight or low overlap):
  * Leads to early structural collapse.
  * Supports the theoretical expectations of the weak tie hypothesis.
* Tracked key metrics:
  * Size of the largest connected component.
  * Susceptibility during each stage of link removal.

### Tools and Technologies
* Languages & Libraries: Python, NetworkX, Pandas, Matplotlib, Scipy
* Network Visualisation: Gephi

### Methodologies:
* Graph-based data modeling
* Link removal experiments by weight/overlap
* Power-Law Cluster model simulation
* Susceptibility analysis and critical fraction analysis
