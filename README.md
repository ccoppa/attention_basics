# Attention Mechanism Basics
## Introduction
> "One important property of human perception is that one does not tend to process a whole scene in its entirety at once. Instead humans focus attention selectivly on parts of the visual space to acquire information when and where it is needed, and combine information from different fixations over time to build up an internal representation of the scene..." - Recurrent Models of Visual Attention, 2014

Our brains don't just process content with a visual snapshot all at once. Instead, we selectively focus on different parts of the content and sequentially collect and process information over time. Attention is a model mechanism that powers up some of the best performing models spanning both natural language processing and computer vision. These models include: neural machine translation, image captioning, speech recognition, text summarization, as well as others. In this notebook, we look at how attention is implemented by going through its derivations.
