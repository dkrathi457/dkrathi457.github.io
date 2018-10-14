Human actions may be observed from multi-view, i.e., different cameras at the same time. Cross-view action recognition based on visual content is very challenging because the
actions in different views may be internally related, but they look very different in the videos. With the help of improved dense trajectories (IDT), hand-crafted features satisfactory
performance has been achieved on single-view, but these often fail for cross-view action recognition, due to non-discriminative features or feature space shift across the
views. In this study, we proposed a novel method for cross-view action recognition by getting discriminative features for each view and bringing them into a common subspace
via a novel joint dictionary and transfer learning framework. The dictionary learning method aims to learn a structured dictionary shared by all classes, and the learned
dictionary shares the latent representation of data through a group of linear mappings and learns the sparse discriminative coefficients for each view. In the meanwhile, the encoded
discriminative features are projected to a common feature space across different views through transfer learning. The dictionary and transfer learning are alternatively optimized
to ensure discriminative and transferable features for cross-view action recognition. The proposed method has been extensively evaluated on PKUMMD dataset to validate the
effectiveness of the proposed approach.
