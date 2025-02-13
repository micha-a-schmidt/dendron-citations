---
title: 'The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks'
desc: ''
created: 1646170271817
updated: 1646172460160
bibliography: [../refs_miv.bib, ../refs_knc.bib]
__defaults__:
  filters: [$FILTERS$/get_markdown_links.py]
traitIds: [journalNote]
tags: [ML, CS]
attached_files: []
authors: [Jonathan Frankle, Michael Carbin]
bibtex_key: frankle_carbin_2019
__bibtex__: {title: 'The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural
    Networks', url: 'https://arxiv.org/abs/1803.03635', abstractnote: "Neural network\
    \ pruning techniques can reduce the parameter counts of trained networks by over\
    \ 90%, decreasing storage requirements and improving computational performance\
    \ of inference without compromising accuracy. However, contemporary experience\
    \ is that the sparse architectures produced by pruning are difficult to train\
    \ from the start, which would similarly improve training performance. We find\
    \ that a standard pruning technique naturally uncovers subnetworks whose initializations\
    \ made them capable of training effectively. Based on these results, we articulate\
    \ the \u201Clottery ticket hypothesis:\u201D dense, randomly-initialized, feed-forward\
    \ networks contain subnetworks (\u201Cwinning tickets\u201D) that - when trained\
    \ in isolation - reach test accuracy comparable to the original network in a similar\
    \ number of iterations. The winning tickets we find have won the initialization\
    \ lottery: their connections have initial weights that make training particularly\
    \ effective. We present an algorithm to identify winning tickets and a series\
    \ of experiments that support the lottery ticket hypothesis and the importance\
    \ of these fortuitous initializations. We consistently find winning tickets that\
    \ are less than 10-20% of the size of several fully-connected and convolutional\
    \ feed-forward architectures for MNIST and CIFAR10. Above this size, the winning\
    \ tickets that we find learn faster than the original network and reach higher\
    \ test accuracy.", journal: ICLR, author: 'Frankle, Jonathan and Carbin, Michael',
  keywords: 'ML,CS', year: '2019'}
---
# The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks

# Authors
 - Jonathan Frankle
 - Michael Carbin

# Links
 - [`https://arxiv.org/abs/1803.03635`](https://arxiv.org/abs/1803.03635)

# Keywords
 - #ML
 - #CS


# Abstract  
Neural network pruning techniques can reduce the parameter counts of trained networks by over 90%, decreasing storage requirements and improving computational performance of inference without compromising accuracy. However, contemporary experience is that the sparse architectures produced by pruning are difficult to train from the start, which would similarly improve training performance. We find that a standard pruning technique naturally uncovers subnetworks whose initializations made them capable of training effectively. Based on these results, we articulate the “lottery ticket hypothesis:” dense, randomly-initialized, feed-forward networks contain subnetworks (“winning tickets”) that - when trained in isolation - reach test accuracy comparable to the original network in a similar number of iterations. The winning tickets we find have won the initialization lottery: their connections have initial weights that make training particularly effective. We present an algorithm to identify winning tickets and a series of experiments that support the lottery ticket hypothesis and the importance of these fortuitous initializations. We consistently find winning tickets that are less than 10-20% of the size of several fully-connected and convolutional feed-forward architectures for MNIST and CIFAR10. Above this size, the winning tickets that we find learn faster than the original network and reach higher test accuracy.
