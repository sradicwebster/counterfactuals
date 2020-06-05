# Counterfactuals explanations
University of Bristol Interactive AI CDT first year module "Advanced topics in AI" coursework to research or implement one of the topics covered in lectures.

Using a synthetic data set and then [building energy efficiency data set][uci] I generated counterfactuals by:
- nearest neighbour to achieve the desired classification;
- minimising a loss function to find "the closest possible world", an approach suggested by [Wachter et. al][wachter];
- finding the shortest path in a density-weighted graph, an approach suggested by Poyiadzi et. al in [Feasible and Actionable Counterfactual Explanations][face](FACE).

# Files
face_counterfactuals.ipynb -- implementing FACE on a synthetic dataset

wachter_counterfactuals.ipynb -- implementing smallest possible change counterfactuals on a synthetic dataset

heating_load.ipynb -- generating counterfactuals using energy efficiency data set



   [wachter]: <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3063289>
   [face]: <https://dl.acm.org/doi/10.1145/3375627.3375850r>
   [uci]: <https://archive.ics.uci.edu/ml/datasets/Energy+efficiency#>


