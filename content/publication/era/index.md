---
abstract: Video summarization aims to simplify large scale video browsing by generating concise, short summaries that diver from but well represent the original video. Due to the scarcity of video annotations, recent progress for video summarization concentrates on unsupervised methods, among which the GAN based methods are most prevalent. <!--more--> This type of methods includes a summarizer and a discriminator. The summarized video from the summarizer will be assumed as the final output, only if the video reconstructed from this summary cannot be discriminated from the original one by the discriminator. The primary problems of this GAN based methods are two folds. First, the summarized video in this way is a subset of original video with low redundancy and contains high priority events/entities. This summarization criterion is not enough. Second, the training of the GAN framework is not stable. This paper proposes a novel Entity relationship Aware video summarization method (ERA) to address the above problems. To be more specific, we introduce an Adversarial Spatio Temporal network to construct the relationship among entities, which we think should also be given high priority in the summarization. The GAN training problem is solved by introducing the Wasserstein GAN and two newly proposed video patch/score sum losses. In addition, the score sum loss can also relieve the model sensitivity to the varying video lengths, which is an inherent problem for most current video analysis tasks. Our method substantially lifts the performance on the target benchmark datasets and exceeds the current leaderboard Rank 1 state of the art CSNet (2.1% F1 score increase on TVSum and 3.1% F1 score increase on SumMe). We hope our straightforward yet effective approach will shed some light on the future research of unsupervised video summarization.
authors:
- admin
- Jianzhe Lin
- Claudio T. Silva
date: "2021-11-22T00:00:00Z"
doi: ""
featured: true
image:
  focal_point: ""
  preview_only: false
links:
- name: BMVC 2021
  url: 'https://www.bmvc2021.com/'
projects:
- c2smart-project
publication: To Appear on *British Machine Vision Conference 2021*
publication_short: To Appear on *BMVC 2021*
publication_types:
- "1"
publishDate: "2021-10-15T00:00:00Z"
summary: Video summarization aims to simplify large scale video browsing by generating concise, short summaries that diver from but well represent the original video... 
tags:
- Video Summarization 
title: "ERA: Entity–relationship Aware Video Summarization with Wasserstein GAN"
url_code: 'https://github.com/jnzs1836/ERA-VSum'
url_pdf: https://arxiv.org/pdf/2109.02625.pdf
url_project: ""
---