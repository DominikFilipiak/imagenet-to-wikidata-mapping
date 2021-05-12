Mapping of Imagenet and Wikidata for Knowledge Graphs Enabled Computer Vision
====

We linked the ILSVRC 2012 dataset (often simply referred as ImageNet) labels to Wikidata entities.
This enables using rich knowledge graph structure and contextual information for several computer vision tasks, traditionally benchmarked with ImageNet and its variations.
For instance, in few-shot learning classification scenarios with neural networks this mapping can be leveraged for weight initialisation, which can improve the final performance metrics value.
We mapped all 1000 ImageNet labels -- 461 were already directly linked with the _exact match_ property (P2888), 467 have exact match candidates, and 72 cannot be matched directly.
For these 72 labels, we propose semantically close non-exact match candidates are presented as well.

For more details, please refer to the paper:
```
D. Filipiak, A. Fensel, A. Filipowska. Mapping of Imagenet and Wikidata for Knowledge Graphs Enabled Computer Vision. International Conference on Business Information Systems, 2021.

```
