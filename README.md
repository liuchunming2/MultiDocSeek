# MultiDocSeek: A Benchmark for a Large-Scale Cross-Document QA Dataset 

## Dataset Overview  
MultiDocSeek is a **large-scale cross-document question-answering (QA) dataset** designed to evaluate the fine-grained capabilities of Retrieval-Augmented Generation (RAG) systems. Its core objective is to validate the impact of different retrieval granularities (coarse-grained vs. fine-grained) on generation quality, providing a standardized benchmark for multimodal retrieval and generation tasks.  


## Core Features  
### 1. **Multi-Level Retrieval Label System**  
- **Coarse-Grained (Page-Level)**: Labels relevant document pages to assess the system’s ability to understand overall document content.  
- **Fine-Grained (Element-Level)**: Further annotates specific intra-page elements (e.g., charts, text blocks, tables) to support in-depth evaluation of the system’s fine-grained localization capabilities.  

### 2. **Cross-Document QA Scenarios**  
- Covers real-world documents across multiple domains (e.g., academic papers, reports, manuals), containing **X** QA pairs (replace with actual data size).  
- Includes question types such as factual queries, inferential analysis, and cross-page correlation, comprehensively evaluating the system’s complex information integration capabilities.  

### 3. **Gold Standard Annotations**  
- Based on manually annotated **ideal retrieval labels** (page-level + element-level) to ensure accuracy and authority.  
- Supports two evaluation scenarios:  
  - **Coarse-Grained Retrieval**: Uses only page-level labels to assess the system’s macro-level document retrieval capabilities.  
  - **Fine-Grained Retrieval**: Incorporates element-level labels to evaluate the system’s localization of critical intra-document information.  


