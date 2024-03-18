# Project Overview

In this mini project, we explore advanced techniques within `Retrieval-Augmented Generation (RAG)` systems. Our objective is to enhance the RAG workflow by addressing issues that exist in conventional RAG methods.

Initially, the focus has been on "small-to-big retrieval," a technique that involves using smaller, more targeted text chunks during the retrieval process to improve accuracy while also providing sufficient context for synthesis by a large language model.

Two primary approaches are utilized in small-to-big retrieval:

1. Retrieving smaller child chunks referring to larger parent chunks.
2. Using sentence window retrieval to improve contextual information.

The following image illustrates the concept of `window retrieval`. This technique is used in the context of small-to-big retrieval, where smaller text chunks are retrieved within a sentence window. This approach enhances the contextual information available for synthesis by a large language model.

![window_retrieval](/images/window_retrieval.png)

The following image demonstrates the concept of `base retrieval`. This is a conventional method used in Retrieval-Augmented Generation (RAG) systems, where larger text chunks are retrieved. While this method provides a broad context, it may lack the precision of smaller, more targeted retrievals.

![base_retrieval](/images/base_retrieval.png)

You can find the updated of the mini project version here : [text](https://rb.gy/u8lo9w)
