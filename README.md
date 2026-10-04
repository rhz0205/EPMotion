# EPMotion

**EPMotion: Endpoint-Guided Temporal Patterns for Multimodal Motion Forecasting**

Official project repository for EPMotion.

## Overview

EPMotion is a multimodal motion forecasting framework that separates spatial hypothesis construction from temporal motion modeling. It predicts and refines probabilistic endpoints, constructs endpoint-conditioned motion patterns, and combines their learned temporal contributions into time-indexed contexts for dense trajectory decoding.

The framework follows an Endpoint–Pattern–Motion hierarchy:

1. **Probabilistic endpoint modeling:** construct and refine candidate destination hypotheses using scene context.
2. **Ordered pattern modeling:** represent reusable motion content with learned temporal centers and widths.
3. **Dense trajectory decoding:** combine time-indexed motion contexts with endpoint conditions to predict future trajectories.

## Code and Model Availability

This repository currently serves as the project landing page.

**The source code and trained model weights will be released here after the paper is formally accepted for publication.** They are not available in this repository yet.

Usage instructions and publication details will be added with the release.
