---
title: "Automated segmentation of rheumatoid arthritis immunohistochemistry stained synovial tissue"
collection: publications
permalink: /publication/2023-09-13-ihc-segmentation-of-synovial-tissue
excerpt: 'We train a UNET on a hand-curated, heterogeneous real-world multi-centre clinical dataset R4RA, which contains multiple types of IHC staining. The model obtains a DICE score of 0.865 and successfully segments different types of IHC staining, as well as dealing with variance in colours, intensity and common WSIs artefacts from the different clinical centres.'
date: 2023-09-13
venue: '27th Conference on Medical Image Understanding and Analysis'
paperurl: 'https://arxiv.org/abs/2309.07255.pdf'
citation: 'Gallagher-Syed, A., Khan, A., Rivellese, F., Pitzalis, C., Lewis, M.J., Slabaugh, G. and Barnes, M.R., 2023. Automated segmentation of rheumatoid arthritis immunohistochemistry stained synovial tissue. arXiv preprint arXiv:2309.07255.'

---

Rheumatoid Arthritis (RA) is a chronic, autoimmune disease which primarily affects the joint's synovial tissue. It is a highly heterogeneous disease, with wide cellular and molecular variability observed in synovial tissues. Over the last two decades, the methods available for their study have advanced considerably. In particular, Immunohistochemistry stains are well suited to highlighting the functional organisation of samples. Yet, analysis of IHC-stained synovial tissue samples is still overwhelmingly done manually and semi-quantitatively by expert pathologists. This is because in addition to the fragmented nature of IHC stained synovial tissue, there exist wide variations in intensity and colour, strong clinical centre batch effect, as well as the presence of many undesirable artefacts present in gigapixel Whole Slide Images (WSIs), such as water droplets, pen annotation, folded tissue, blurriness, etc. There is therefore a strong need for a robust, repeatable automated tissue segmentation algorithm which can cope with this variability and provide support to imaging pipelines. We train a UNET on a hand-curated, heterogeneous real-world multi-centre clinical dataset R4RA, which contains multiple types of IHC staining. The model obtains a DICE score of 0.865 and successfully segments different types of IHC staining, as well as dealing with variance in colours, intensity and common WSIs artefacts from the different clinical centres. It can be used as the first step in an automated image analysis pipeline for synovial tissue samples stained with IHC, increasing speed, reproducibility and robustness.
