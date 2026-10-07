My name is Chrysanthi (but my friends call me Sunny)!

I am currently a senior researcher at HKUST in the Department of Computer Science and Engineering.

My research interests are in the area of graph analytics with a focus on a new class of networks called Temporal Interaction Networks (TINs). In these networks, a quantity (flow) transfers from one vertex to another within a time window. TINs can model dynamic systems where entities exchange quantities, such as financial transactions, transportation flows, or communication data. Over the past few years, I have been developing efficient solutions to optimize classical problems, such as max-flow computation, by introducing the temporal dimension. My work in this area also covers the discovery of flow motifs and flow patterns, and tracking the ring (provenance) of the quantities transferred among vertices.

Currently, I am working on provenance tracking for streaming systems. As real-time analytics pipelines grow in complexity, understanding how outputs are derived from inputs becomes crucial for debugging, auditing, and explainability. However, fine-grained provenance (which identifies the exact input tuples behind each output), becomes very expensive in production. I am developing how-much provenance, which starts from the outputs: from an output tuple, or for all outputs of a sink within a time window, it reports how much data each source or processing path contributed. Operators produce and propagate aggregates whose size is bounded by the number of sources and paths, adding negligible overhead to the dataflow

If you’re curious, feel free to check out my latest work:
https://dl.acm.org/doi/pdf/10.14778/3828612.3828635

I am also interested in downstream provenance, which reverses the direction of traditional provenance. It starts from a problematic source and identifies how many outputs that source fed, over an interval of production time and along a processing path. Each batch of tuples carries a tag naming a source, a production-time bucket, and a path, together with a count, and operators merge tags by summing their counts. 

You can also check my personal webpage for more details: https://kosyfakicse.github.io

