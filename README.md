# Enhanced Direction-Oriented Smooth Sensitivity (DOSS) based on Improved Direction-Oriented Local Sensitivity (DOLS)

This page contains the Python codes for our experiments (regarding TDT statistics and $\chi^2$-statistics based on a $3 \times 2$ contingency table) and the omitted proofs in the main paper.

In "distribution_evaluation" folder, the most advisable $(\alpha, \beta)$-admissible distributions for mechanisms using the enhanced DOSS were investigated.

"vs DOSS vs SS" folder provides the comparison results among mechanisms using the enhanced DOSS, the original DOSS, and the smooth sensitivity in terms of output accuracy.

"Biased vs Unbiased" folder provides the comparison results among the biased mechanism using the original DOSS, an unbiased mechanism using the enhanced DOSS, and the unbiaesd mechanism using the smooth sensitivity. 

The run time of our algorithm (Algorithm 1 in our paper) for computing the improved DOLS was measured for reference, in "Run Time" folder. We provide the results for $\chi^2$-statistics as well.

The full proofs of the theorems and lemmas in the main paper are provided in Proofs.pdf.

## Future Directions
・Constructing a novel DOLS concept that considers the privacy level of information associated with each dimension.

・Developing better unbiased (and bounded) mechanisms with higher accuracy, potentially using approaches other than varying the probabilities for noise generation.

・Applying the (idea of enhanced) DOSS to private selection tasks.

・Developing methods for handling dependencies between information in different dimensions.

## Note

For details of our methods and discussion, please see our paper entitled "Differentially Private Mechanisms Using Enhanced Direction-Oriented Smooth Sensitivity" (https://doi.org/10.1109/CCWC67433.2026.11393770) presented at IEEE CCWC 2026.  
(cf. [Direction-Oriented Smooth Sensitivity](https://github.com/ay0408/DOSS))

Errata:  
・The part following Definition 6, " $k > 1$ " → " $k \geq 2$ "

### Contact
Akito Yamamoto

Division of Medical Data Informatics, Human Genome Center,

the Institute of Medical Science, the University of Tokyo

a-ymmt@ims.u-tokyo.ac.jp
