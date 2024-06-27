# RAPTOR-text-comparison
An experiment exploring how RAPTOR can be used to provide insight as to how a translation compares to it's source text


## General Idea
Given translation A and source text B, we can generate a tree for A (A_tree) and B (B_tree) and compare similar custerers summary values. 

Hopefully, this will assist translation Consultants and help them verify that major themes are consistant across translation clusters. A possible red flag would be if tree_A and tree_B do not have similar clusters for lower level nodes.

Additionally, this gives us summary vectors that can potentially improve context retrieved during the retreval step of a RAG implementation for a "Bible Copilot". 
