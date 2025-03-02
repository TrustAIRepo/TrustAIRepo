# 👋 Welcome to: 

![Banner](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/images/Banner.PNG)

## 🚀 Introduction
Generative artificial intelligence (GenAI), powered by large language models (LLMs), is revolutionizing accessibility and collaboration for non-technical users. GenAI models excel across various digital data types, impacting diverse populations. However, their widespread use raises trustworthiness challenges, particularly in explicability and transparency. The Retrieval-Augmented Generation (RAG) architecture addresses these issues by integrating external, verifiable information sources, enhancing reliability and explainability. This article proposes an improved RAG architecture that leverages LLMs and Resource Description and Access (RDA) to ensure responses align with trustworthiness principles, improving transparency, accountability, and interoperability.

Additionally, this repository contains supplementary information related to the article, including test data, evidence of tests, code, and other resources.

## 📊 Test Data
To evaluate the applicability of our proposed architecture improvement, we developed a dataset consisting of fictional documents detailing the flora and fauna of Europa, one of Jupiter's moons. This dataset was specifically crafted to ensure that the LLM had no prior knowledge of the information contained within, ensuring that its responses are based solely on the provided documents. Additionally, we included elements related to trustworthiness within these documents to thoroughly evaluate the system's ability to verify trustworthiness.

You can access the documents below:
- [Document 1](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/01.Flora%20on%20the%20Surface%20of%20Europa%20An%20In-Depth%20Analysis.txt): Flora on the Surface of Europa An In-Depth Analysis] 
- [Document 2](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/02.Fauna%20in%20the%20Subsurface%20Oceans%20of%20Europa%20A%20Hypothetical%20Exploration.txt): Fauna in the Subsurface Oceans of Europa A Hypothetical Exploration
- [Document 3](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/03.Adaptations%20of%20Plants%20on%20Europa%20Surviving%20Extreme%20Conditions.txt): Adaptations of Plants on Europa Surviving Extreme Conditions
- [Document 4](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/04.Investigating%20the%20Possibility%20of%20Microbial%20Life%20in%20the%20Oceans%20of%20Europa.txt): Investigating the Possibility of Microbial Life in the Oceans of Europa
- [Document 5](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/05.Hypothetical%20Ecosystems%20in%20the%20Ice%20Cracks%20of%20Europa.txt): Hypothetical Ecosystems in the Ice Cracks of Europa
- [Document 6](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/06.Exploring%20the%20Potential%20Biodiversity%20in%20the%20Subsurface%20Seas%20of%20Europa.txt): Exploring the Potential Biodiversity in the Subsurface Seas of Europa
- [Document 7](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/07.Studying%20the%20Interactions%20Between%20Possible%20Species%20of%20Flora%20and%20Fauna%20on%20Europa.txt): Studying the Interactions Between Possible Species of Flora and Fauna on Europa
- [Document 8](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/08.Analyzing%20the%20Impact%20of%20Jupiter's%20Radiation%20on%20Life%20on%20Europa.txt): Analyzing the Impact of Jupiter's Radiation on Life on Europa
- [Document 9](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/09.Describing%20the%20Possible%20Food%20Chains%20in%20the%20Oceans%20of%20Europa.txt): Describing the Possible Food Chains in the Oceans of Europa
- [Document 10](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/10.Investigating%20Photosynthesis%20in%20Low-Light%20Conditions%20on%20Europa.txt): Investigating Photosynthesis in Low-Light Conditions on Europa
- [Document 11](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/11.Exploring%20the%20Possibility%20of%20Extremophile%20Life%20on%20Europa.txt): Exploring the Possibility of Extremophile Life on Europa
- [Document 12](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/12-Describing%20the%20Nutrient%20Cycles%20in%20the%20Ecosystems%20of%20Europa.txt): Describing the Nutrient Cycles in the Ecosystems of Europa
- [Document 13](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/13.Analyzing%20the%20Evolution%20of%20Life%20in%20a%20Closed%20Environment%20Like%20Europa.txt): Analyzing the Evolution of Life in a Closed Environment Like Europa
- [Document 14](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/14.Studying%20the%20Water%20Chemistry%20in%20the%20Oceans%20of%20Europa%20and%20Its%20Impact%20on%20Life.txt): Studying the Water Chemistry in the Oceans of Europa and Its Impact on Life
- [Document 15](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/15.Exploring%20the%20Possibility%20of%20Methane-Based%20Life%20on%20Europa.txt): Exploring the Possibility of Methane-Based Life on Europa
- [Document 16](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/16.Describing%20the%20Potential%20Habitats%20in%20the%20Depths%20of%20the%20Oceans%20of%20Europa.txt): Describing the Potential Habitats in the Depths of the Oceans of Europa
- [Document 17](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/17.Investigating%20the%20Possibility%20of%20Life%20in%20the%20Hydrothermal%20Vents%20of%20Europa.txt): Investigating the Possibility of Life in the Hydrothermal Vents of Europa
- [Document 18](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/18.%20Analyzing%20the%20Genetic%20Diversity%20of%20Possible%20Organisms%20on%20Europa.txt): Analyzing the Genetic Diversity of Possible Organisms on Europa
- [Document 19](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/19-Exploring%20the%20Possibility%20of%20Symbiosis%20Between%20Species%20on%20Europa.txt): Exploring the Possibility of Symbiosis Between Species on Europa
- [Docuemnt 20](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/corpus/20-Describing%20the%20Research%20Methods%20to%20Detect%20Life%20on%20Europa.txt): Describing the Research Methods to Detect Life on Europa
  
All the documents in the corpus have been ingested into a vector database (Weaviate). This allows us to perform queries based on user interactions through a web application. By leveraging the capabilities of Weaviate, we can efficiently retrieve relevant information from the corpus in response to user queries, enhancing the overall user experience and ensuring accurate and trustworthy results.

## 🌐 Application Overview

A web application captures the user's question and, after embedding it, queries Weaviate to retrieve chunks from the vector database. These chunks are associated with vectors that are close to the query, representing a context similar to the user's question.

Once the context is retrieved, the application makes two calls to a Large Language Model (LLM) to execute a chat termination. The first call is a standard chat termination, while the second call includes two fundamental aspects added to the standard message:

- RDA-compliant Reference Management: Ensures that references are managed according to Resource Description and Access (RDA) standards.
  
- Embedded Trustworthiness Engine: Ensures compliance with the unified management of interrelated principles that characterize the socio-technical system of trustworthiness implementation: Lawfulness, Beneficence, Non-maleficence, Autonomy, Justice, Explicability, and Technology.

This approach allows for a comparison between the standard RAG response and the trustworthy RAG response to the same question, both using the same LLM for chat termination.

## 🔍 Evidence and Results

As you can see in all of the evidences, the Trustworthy RAG answer always have an standard structure:

- Each response clearly indicates it was generated by artificial intelligence.
- Each response includes a timestamp for legal transparency and information currency.
- Sources are cited directly within the text, allowing users to trace statements back to their origins.
- Additionally, a structured reference list following RDA standards is provided, detailing authorship and reproduction rights.
- Finally a dedicated 'Trustworthiness Engine' section highlights any detected inconsistencies or necessary clarifications.

Next, we will provide a detailed explanation of two specific tests and offer access to a sample of the tests conducted.

- **Finding 1**: Protection Against Unauthorized Data Exposure.

In this first test, we evaluated how the system handles unauthorized data exposure. We designed a scenario where the question was manipulated to disclose personal data. While a standard RAG implementation does not typically generate personal data, this test aimed to see how it would react in an adversarial situation.

Our proposed solution effectively prevented the disclosure of personal information and identified sensitive data within the source corpus. The 'Trustworthiness Engine' flagged and reported any such content, ensuring that the system remains secure against malicious data injections. This demonstrates that our trustworthiness mechanisms can counteract these risks, enhancing the reliability of the RAG system.
  
  ![Banner](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal11.png)

- **Finding 2**: Detection of Implicit Biases and Misclassification.
  
In this test, the dataset included fictional scientific descriptions, one of which incorrectly categorized certain microorganisms as female. Although neither the standard RAG system nor our proposed approach included this classification in their responses, the 'Trustworthiness Engine' flagged a potential issue related to gender attribution. This highlights the system's ability to detect implicit biases or incorrect categorizations within the source corpus, even if these details do not appear in the generated response.

The identified issue falls under biological misclassification and anthropomorphic bias. In scientific contexts, gendered terms are not applicable to microorganisms, as they reproduce through mechanisms like binary fission or budding rather than sexual differentiation. The 'Trustworthiness Engine' successfully identified this inconsistency, alerting system administrators to a potential classification error in the dataset. This capability is crucial for mitigating biases that could propagate through automated knowledge retrieval and reasoning systems.

 ![Banner](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal1.png)
  

You can view a sample of different evidences in the following links:
 [Evidence 1](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal1.png) | [Evidence 2](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal2.png) | [Evidence 3](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal3.png) | [Evidence 4](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal4.png) | [Evidence 5](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal5.png) | [Evidence 6](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal6.png) | [Evidence 7](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal7.png) | [Evidence 8](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal8.png) | [Evidence 9](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal9.png) | [Evidence 10](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal10.png) | [Evidence 11](https://github.com/TrustAIRepo/TrustAIRepo/blob/main/assets/evidences/TestFinal11.png) |

## 💻 Code
The code used in our research is available for review and replication. The code was developed specifically to test the Trustworthy RAG, without considering some necessary aspects for a real and production-ready system in certain steps of the process to facilitate the objective. You can find the code repository here:
- GitHub Repository

## 📷 Explanatory Images
Below are some images that help explain our research and findings:
!Description of Image 1
!Description of Image 2

## 📫 Contact
If you have any questions or would like to discuss our research further, please feel free to contact us:
- [LinkedIn](https://www.linkedin.com/in/carlosmariobragabigdata/)
- Orcid : [0009-0009-2373-0990](https://orcid.org/0009-0009-2373-0990)
- [Email](CarlosMario.Braga1@alu.uclm.es)

## 💬 Inspirational Quote
> "To live effectively is to live with adequate information." (Norbert Wiener)

## 🎉 Acknowledgements
This publication would not have been possible without the support of the following projects: Di4SPDS (PCI2023145980-2), funded by MCIN/AEI/10.13039/501100011033 and by the European Union (Chist-Era Program), KOSMOS-UCLM (PID2024-155363OB-C44) funded by MCIN/AEI/10.13039/501100011033, ALBA (TED2021-130355B-C31), funded by MICIU/AEI-/10.13039/501100011033 and the European Union NextGeneration EU/ PRTR, and MESIAS (2022-GRIN-34202) funded by FEDER

Thank you for visiting our presentation page. We appreciate your interest in our research!

