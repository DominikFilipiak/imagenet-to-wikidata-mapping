Mapping of Imagenet and Wikidata for Knowledge Graphs Enabled Computer Vision
====

We linked the ILSVRC 2012 dataset (often simply referred as ImageNet) labels to Wikidata entities.

This enables using rich knowledge graph structure and contextual information for several computer vision tasks, traditionally benchmarked with ImageNet and its variations.
We mapped all 1000 ImageNet labels - 461 were already directly linked with the _exact match_ property (P2888), 467 have exact match candidates, and 72 cannot be matched directly.
For these 72 labels, we proposed semantically close non-exact match candidates are presented as well.

For more details, please refer to our [paper (presented at BIS 2021)](https://www.tib-op.org/ojs/index.php/bis/article/view/65).

If you use the mapping, please cite it accordingly:
```
Filipiak, D., Fensel, A., & Filipowska, A. (2021, July). Mapping of ImageNet and Wikidata for Knowledge Graphs Enabled Computer Vision. In Business Information Systems (pp. 151-161).
```
