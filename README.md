# PPKG

Gut microbiota are known to have a profound impact on the communication between the central nervous system and the enteric (gut) nervous system. These interactions are referred to as the Microbiota-Gut-Brain (MGB) axis. Dysfunction of the MGB axis is associated with a number of human diseases, including obesity, diabetes, and mental disorders. Improving the gut microbiome could therefore be a useful approach for treating diseases in which the MGB axis is involved. As modulators of gut microbiota, prebiotics and probiotics are widely used to alter the gut microbial communities for beneficial effects. The biomedical literature contains abundant knowledge regarding the beneficial effects of specific prebiotics and probiotics on MGB-axis diseases. However, papers are usually written by humans for humans and are thus not structured in a machine-accessible format that may support semantic integration and querying. We therefore integrate and normalize the unstructured literature data into a Pre-/Probiotics Knowledge Graph (PPKG) dataset.

This PPKG dataset comprises two subsets: (1) the ppstatement set, containing detailed facts composed of entities, attributes, and relations manually extracted from 134 articles; and (2) the ppconcept set, containing extensive concepts automatically annotated using a named entity recognition tool, and numerous relations between annotated concepts and source articles. PPKG not only offers detailed knowledge about pre-/probiotics treatment of diseases but also relates a concept from a specific work with other concepts from the same study and similar investigations. The two subsets are complementary which makes the PPKG dataset complete. Entities and concepts are mapped to existing term descriptions in online public biomedical databases, such as UMLS and SNOMED CT.

The PPKG dataset can be used in a wide range of biomedical applications. For example, we got meaningful results from this dataset for questions at different levels of detail, from very general (like "which probiotics benefit mental health") to completely specific (e.g. "does B. bifidum have an effect on BDNF"). Furthermore, this dataset has great potential to be expanded. For example, the detailed facts with entities, relations, and attributes can be further used to train a relation extraction model, thus enabling the automatic extraction of huge and accurate relationships from a large amount of literature. We believe that this dataset will aid both the biomedical researchers, who wish to investigate the relations between gut microbiota and human diseases, and the knowledge graph technology researchers, who intend to facilitate the application of knowledge graphs in the biomedical domain.

This dataset is fully publicly available. The authors are also more than willing to provide detailed explanations and instructions on the use of the dataset for interested users.

# Contact information
For help or issues using the PPKG dataset, please contact Ting Liu (`t.liu@vu.nl`or`ting.liu.vu@hotmail.com`).
