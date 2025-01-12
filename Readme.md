# Big Data Management & Entity Resolution Project

## Overview

This project focuses on evaluating a set of data integration techniques within the domain of product data from two well-known companies: Google and Amazon. The project follows a complete entity resolution process, utilizing tools such as PyJedAI and Magellan, as studied during practical sessions. The goal is to efficiently merge the datasets from these two companies, leveraging blocking and entity resolution techniques.

The datasets used for the project are sourced from the Database Group at the University of Leipzig, which has published and validated them as part of research on entity resolution. These data have been widely used in scientific papers, making them suitable and reliable for evaluating various entity resolution techniques.

## Project Structure

The project is divided into several parts, with a focus on the following areas:

- **Data Integration & Entity Resolution**: 
   - Using **PyJedAI** and **Magellan**, the project evaluates different techniques of entity resolution, blocking, and matching of product data from Amazon and Google.
   
- **Blocking Process**:
   - The first part of the project focuses on blocking, where products are grouped based on matching attributes, such as `name`, `description`, `manufacturer`, and `price`.
   
- **Entity Matching**:
   - Using Magellan, the entity matching process is applied to the generated blocks, which involves comparing and matching entities (products) across the two datasets.

- **Implementation of Retrieval-Augmented Generation (RAG)**:
   - A small part of the project is dedicated to the implementation of a Retrieval-Augmented Generation (RAG) model, aimed at generating natural language responses based on the context of the merged product data.

## Datasets

The project uses datasets from the **Database Group Leipzig**, part of the University of Leipzig, which were published and validated as part of entity resolution research. These datasets include product information from Amazon and Google.

## Tools Used

- **PyJedAI**: A Python framework for Entity Resolution that offers efficient solutions for matching and clustering entities from multiple sources.
- **Magellan**: A Python library for entity resolution, widely used for matching entities from different sources.
- **FAISS**: A library for efficient similarity search and clustering of dense vectors.
- **Transformers (Hugging Face)**: A library to use pre-trained language models, like GPT-Neo, for text generation and other NLP tasks.

## Installation

### Clone the repository:

```bash
git clone https://github.com/yourusername/big-data-management-entity-resolution.git
cd big-data-management-entity-resolution
```

### Requirements:

To set up the environment, use the following command to install the necessary libraries:

```bash
pip install -r requirements.txt
```

### Running the Project:

1. **Data Preprocessing**:
   - The first step is to load and preprocess the product datasets from Amazon and Google.

2. **Entity Resolution**:
   - Run the script for entity resolution using PyJedAI or Magellan, depending on your selected approach.

3. **RAG Implementation**:
   - Optionally, run the RAG implementation to explore how the system generates responses based on the merged product data.

## Contributions

This project is part of a Master's course at the University of Modena and Reggio Emilia (Unimore), conducted by Enzo Sebiane during an Erasmus program. The aim is to compare different entity resolution techniques and explore new approaches to big data integration.

## License

This project is open-source and available under the MIT License.

