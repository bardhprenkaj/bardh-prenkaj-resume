---
title: 'RAZOR: Sharpening Knowledge by Cutting Bias with Unsupervised Text Rewriting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shuo Yang
  - Bardh Prenkaj
  - Gjergji Kasneci

date: '2025-01-20T00:00:00Z'
doi: '10.48550/arXiv.2412.07675'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 39th Annual AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI 2025*

abstract: Despite the widespread use of LLMs due to their superior performance in various tasks, their high computational costs often lead potential users to opt for the pretraining-finetuning pipeline. However, biases prevalent in manually constructed datasets can introduce spurious correlations between tokens and labels, creating so-called shortcuts and hindering the generalizability of fine-tuned models. Existing debiasing methods often rely on prior knowledge of specific dataset biases, which is challenging to acquire a priori. We propose RAZOR (Rewriting And Zero-bias Optimization Refinement), a novel, unsupervised, and data-focused debiasing approach based on text rewriting for shortcut mitigation. RAZOR leverages LLMs to iteratively rewrite potentially biased text segments by replacing them with heuristically selected alternatives in a shortcut space defined by token statistics and positional information. This process aims to align surface-level text features more closely with diverse label distributions, thereby promoting the learning of genuine linguistic patterns. Compared with unsupervised SoTA models, RAZOR improves by 3.5% on the FEVER and 6.5% on MNLI and SNLI datasets according to the F1 score. Additionally, RAZOR effectively mitigates specific known biases, reducing bias-related terms by x2 without requiring prior bias information, a result that is on par with SoTA models that leverage prior information. Our work prioritizes data manipulation over architectural modifications, emphasizing the pivotal role of data quality in enhancing model performance and fairness. This research contributes to developing more robust evaluation benchmarks for debiasing methods by incorporating metrics for bias reduction and overall model efficacy. 


tags: ['deep learning','LLMs','shortcut mitigation']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2412.07675'
url_code: 'https://github.com/ShuoYangtum/RAZOR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Example of spurious correlation in sentiment classification tasks, where a classifier takes Spielberg and New York Subway as shortcuts and makes wrong predictions w.r.t. the ground truth. The classifier concentrates on the bold tokens to make the prediction; however, the underlined tokens might be more useful in producing the correct label'
  focal_point: ''
  preview_only: false

---