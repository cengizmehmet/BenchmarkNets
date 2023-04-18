# Predicting the Performance of a Computing System with Deep Networks

Predicting the performance and energy consumption of computing hardware is critical for many modern applications. This will inform procurement decisions, deployment decisions, and autonomic scaling. Existing approaches to understanding the performance of hardware largely focus around benchmarking -- leveraging standardised workloads which seek to be representative of an end-user's needs. Two key challenges are present; benchmark workloads may not be representative of an end-user's workload, and benchmark scores are not easily obtained for all hardware. Within this paper, we demonstrate the potential to build Deep Learning models to predict benchmark scores for unseen hardware. We undertake our evaluation with the openly available SPEC 2017 benchmark results. We evaluate three different networks, one fully-connected network along with two Convolutional Neural Networks (one bespoke and one ResNet inspired) and demonstrate impressive R2 scores of 0.96, 0.98 and 0.94 respectively.

## Cite Us

This work first published in [Proceedings of the 14th ACM/SPEC International Conference on Performance Engineering (ICPE '23)]([https://dl.acm.org/doi/abs/10.1145/3427921.3450241](https://dl.acm.org/doi/proceedings/10.1145/3578244)). If you use our data or preprocessing scripts, please cite the following [bibkey](CITE.md):

	@inproceedings{10.1145/3578244.3583731, 
	    author = {Cengiz, Mehmet and Forshaw, Matthew and Atapour-Abarghouei, Amir and McGough, Andrew Stephen}, 
	    title = {Predicting the Performance of a Computing System with Deep Networks}, 
	    year = {2023}, 
	    isbn = {9798400700682}, 
	    publisher = {Association for Computing Machinery}, 
	    address = {New York, NY, USA}, 
	    url = {https://doi.org/10.1145/3578244.3583731}, 
	    doi = {10.1145/3578244.3583731}, 
	    booktitle = {Proceedings of the 2023 ACM/SPEC International Conference on Performance Engineering}, 
	    pages = {91–98}, 
	    numpages = {8}, 
	    keywords = {benchmarking, performance, deep networks}, location = {Coimbra, Portugal}, 
	    series = {ICPE '23} 
	}
