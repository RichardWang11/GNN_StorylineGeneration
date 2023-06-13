We're working on a research project that generates storylines using Graph Neural Networks. Our approach uses Graph Convolutional Networks to group news sentences into topic-based clusters, which are arranged by regular time intervals. This gives us a topic-specific storyline that shows the event's timeline, including the breaking point and end time.

We're comparing our method with others to evaluate its effectiveness.
| paper | meeting or journal | task | method | datasets |datasets_size |
|----|-------|------|--------|-----|-----|
|CStory| CIKM 22|storyline classification& storyline generation|BERT & DBSCAN clustering|Chinese news datasets|600MB|
|Growing Story Forest Online|CIKM 17|storyline generation|GDBT&LR 4keyword extraction&A tow-layer graph based clustering|Chinese news datasets|60GB|
|GNN_SG|To be continue|news classification& storyline generation|BERT& Graph Convolutional Networks|Chinese news datasets|unknow|
