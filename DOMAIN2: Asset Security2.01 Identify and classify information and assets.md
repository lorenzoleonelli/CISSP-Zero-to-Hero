## 2.1.1 Data Classification ##

Data is the lifeblood of any organization. From financial records to customer information, strategic plans, and trade secrets, the variety and volume of data are immense, even for small manufacturing companies. Protecting this data from unauthorized access, use, disclosure, modification, or destruction is not just good practice, it's crucial for survival. Data security strictly requires a proper data classification.

:link: Keep in mind what you learned in [1.2 Understand and apply security concepts](https://github.com/lorenzoleonelli/CISSP-Zero-to-Hero/blob/main/DOMAIN1%3A%20Security%20and%20Risk%20Management/1.02%20Understand%20and%20apply%20security%20concepts.md#121-confidentiality-integrity-and-availability-authenticity-and-nonrepudiation-5-pillars-of-information-security)

To understand the concept behind data classification you can think of it like sorting your clothes: you wouldn't throw your delicates in with your work boots, right? Similarly, data classification is the process of organizing data into categories that reflect its sensitivity and value. This careful categorization allows organizations to apply the appropriate level of security controls, ensuring that the "crown jewels" are kept under lock and key while less critical information can be accessed more easily.

:link: I do not want you to be scared, but to be aware of what may happen to your data. Giva a look at [The 18 biggest data breaches of the 21st century](https://www.csoonline.com/article/534628/the-biggest-data-breaches-of-the-21st-century.html).

By classifying data, organizations can:

- **Prioritize Protection**: Allocate resources effectively, focusing more stringent security measures on highly sensitive data. 
- **Facilitate Informed Decision Making**: Make data-driven decisions about security investments and policies. 
- **Meet Compliance Requirements**: Adhere to legal and regulatory frameworks like GDPR.
- **Reduce Risk**: Minimize the likelihood and impact of data breaches. 
- **Streamline Data Management**: Improve data handling, storage, and retrieval processes.

:necktie: There's no one-size-fits-all approach to data classification. Different organizations may use different schemes, but the underlying principle is the same: assigning a level of sensitivity that dictates the level of protection. 

Organizations use various criteria to determine the appropriate classification level for data. These criteria may include:
- The value of the data
- The age of the data
- The usefulness of the data
- The level of damage that could be caused if the data were disclosed
- Legal, regulatory, or contractual responsibility to protect the data
- Effects the data has on security
- Who should be able to access the data
- Who should be able to modify the data
- Who should be able to reproduce the data
- Lost opportunity costs that could be incurred if the data were not available or were corrupted

:link: [NIST SP 800-122, Guide to Protecting the Confidentiality of Personally Identifiable Information (PII)](https://csrc.nist.gov/pubs/sp/800/122/final), provides recommendations for identifying and securing PII to prevent unauthorized access and data breaches. It outlines risk assessment methods, security controls, and best practices for minimizing the collection, storage, and exposure of sensitive personal data.

:link: Protected Health Information (PHI) is defined by [HIPAA (Health Insurance Portability and Accountability Act)](https://www.hhs.gov/hipaa/for-professionals/privacy/laws-regulations/index.html) as "individually identifiable health information" that is transmitted or maintained in any form or medium (electronic, paper, or oral). This includes information related to an individual's past, present, or future physical or mental health, healthcare services, or payment for healthcare, which can be linked to a specific person. 

The following Infographic tries to recap all the sensitive data you may encounter in organizations:

<img width="512" height="503" alt="PI" src="https://github.com/user-attachments/assets/fe0e7985-8333-4dab-923f-3f966c5d04b8" />

Some common data classification levels for commercial businesses include:

- Confidential: The most sensitive data, unauthorized disclosure of which could severely impact the company. Think trade secrets, financial algorithms, or strategic plans. 
- Private: Data that requires more than normal protection to ensure its confidentiality. Examples include employee records, medical information, or legal documents. 
- Sensitive: Data that requires special precautions but is not as critical as confidential or private data. Financial reports, marketing strategies, or upcoming projects fall under this category. 
- Public: Information that is generally available and poses no risk if disclosed. This might include company addresses, press releases, or product brochures

Military and government organizations employ a different classification scheme, reflecting the potential impact on national security. These are common military classification levels:

- Top Secret: Unauthorized disclosure could cause exceptionally grave damage to national security, such as jeopardizing military operations or revealing sensitive intelligence sources.
- Secret: Data that, if disclosed, could cause serious damage to national security. 
- Confidential: Information that could cause damage to national security if compromised. 
- Unclassified: Data that doesn't meet the criteria for classified information but may still require some level of protection. 
- Controlled Unclassified Information (CUI): Sensitive information that is not classified but requires safeguarding. 

| Environment               | Classification Level         | Description & Examples                                                                 |
|---------------------------|------------------------------|----------------------------------------------------------------------------------------|
| **Commercial (e.g., business)** | **Confidential**           | Most sensitive data—trade secrets, financial algorithms, strategic plans. Unauthorized disclosure could severely impact the company.  |
|                           | **Private**                 | Data needing more protection than typical internal info—e.g., employee records, medical data, legal documents. |
|                           | **Sensitive**               | Important data still requiring special handling—e.g., financial reports, marketing strategies, upcoming projects.  |
|                           | **Public**                  | Freely shareable information—e.g., press releases, product brochures, company addresses. No risk if disclosed.  |
| **Military / Government** | **Top Secret**              | Unauthorized disclosure could cause exceptionally grave damage to national security.  |
|                           | **Secret**                  | Disclosure could cause serious damage to national security. |
|                           | **Confidential**            | Disclosure could reasonably cause damage to national security.|
|                           | **Unclassified**            | Information not meeting higher classification criteria; still may require minimal protection. |
|                           | **Controlled Unclassified Information (CUI)** | Unclassified but sensitive information requiring safeguarding under law, regulation, or policy. Includes export‑controlled technical data, contracts, and similar.  |

:link: The National Cybersecurity Center of Excellence (NCCoE) has released a preliminary draft of NIST Special Publication (SP) 1800-39A, Implementing Data Classification Practices, for public comment. You can find it [here](https://csrc.nist.gov/News/2023/implementing-data-class-practices-sp-1800-39a)

Data classification is more than just slapping labels on data. It's an ongoing process that involves defining clear criteria for classification, assigning roles and responsibilities, implementing security controls and regularly reviewing and updating the classification scheme.

:necktie: As an information security manager, it’s crucial to monitor and prevent data creep. In data management, this phenomenon occurs when data continuously accumulates without proper oversight, resulting in increased complexity and inefficiencies in handling and processing. If left unchecked, excessive data growth can strain resources and make data management more challenging.

Here are some key steps in building a robust data classification program:

1. **Define Classification Levels**: Clearly define the different levels of data sensitivity and their corresponding security requirements. 
2. **Establish Ownership**: Identify data owners who are responsible for classifying data and ensuring its protection. 
3. **Develop Procedures**: Create a documented process for classifying data, including criteria, guidelines, and review mechanisms. 
4. **Implement Security Controls**: Deploy appropriate technical and administrative controls to safeguard data at each classification level. 
5. **Train and Educate**: Provide comprehensive training to all employees on data classification policies and procedures. 

```mermaid
flowchart LR
  A[Start: Establish Data Classification Program] --> B[Define Classification Levels]
  B --> C[Establish Data Ownership]
  C --> D[Develop Classification Procedures]
  D --> E[Implement Security Controls]
  E --> F[Train & Educate Employees]
  F --> G[Maintain & Review Programme]

    classDef center fill:#ffffff,color:#000000,stroke:#000000,stroke-width:1px,font-weight:bold
    classDef node fill:#e0e0e0,color:#000000,stroke:#000000,stroke-width:1px
```

**Data Categorization** comes before Data Classification and focuses on grouping data based on its inherent content, purpose, or characteristics. For example, you might categorize data into types like "financial records," "employee records," "customer data," or "transaction logs." The goal of data categorization is to organize the data in a way that makes sense for the organization, so that it can be better managed and analyzed. It doesn't necessarily involve sensitivity or security at this point; it's more about understanding and grouping the data for practical use.

Categorization Criteria are usually:
1. Content-based: Categorizing data based on the actual content of the data, such as personally identifiable information (PII), financial data, or intellectual property.
2. Context-based: Categorizing data based on its source, ownership, location, or other contextual information.
3. User-based: Categorizing data based on its intended use or the users who have access to it.

Usually after categorization data is classified. Data classification assigns sensitivity levels to the categorized data based on its potential impact if exposed, modified, or destroyed.

:brain: Data classification and data categorization are distinct concepts. Data classification focuses on assigning sensitivity levels to data based on its potential impact. Data categorization, on the other hand, involves grouping data into specific categories based on its content, purpose, or other relevant characteristics. 

:necktie: **Data classification and categorization are ongoing processes.** As data changes over time, its classification and categorization may need to be updated.
**Data classification and categorization should be integrated with other security controls.** This includes access control, encryption, data loss prevention, and incident response.
**User training and awareness are essential for the success of data classification and categorization programs.** Employees need to understand the importance of these processes and how to properly handle data at different classification levels.

### Open Questions ###

1. What are the primary goals of data classification?
<details>
  <summary>Show answer</summary>
Data classification aims to identify sensitive data, group it based on its level of sensitivity, and apply appropriate security controls to protect it from unauthorized access, use, disclosure, modification, or destruction. This helps organizations comply with legal, regulatory, and contractual requirements and reduce the risk of data breaches.
</details>

2. What are the key differences between commercial and military data classification levels?
<details>
  <summary>Show answer</summary>
Commercial data classification levels typically focus on the potential impact on the organization's business operations, while military data classification levels emphasize the potential impact on national security. For example, "Confidential" data in a commercial setting might involve sensitive business information, while "Confidential" data in a military context could relate to information that, if disclosed, could cause damage to national security.
</details>

3. Provide three examples of criteria that can be used to determine the classification level of data.
<details>
  <summary>Show answer</summary>
The value of the data (e.g., financial, strategic, personal), the age of the data (e.g., current, historical), and the potential impact of disclosure (e.g., financial loss, reputational damage, legal liability) are all criteria used to determine the appropriate classification level.
</details>

4. Describe the role of data owners in a data classification program.
<details>
  <summary>Show answer</summary>
Data owners are responsible for determining the initial classification level of data, reviewing the classification periodically, and ensuring that appropriate security controls are in place to protect the data. They play a crucial role in managing and safeguarding sensitive information within an organization.
</details>

5. Briefly explain how data categorization differs from data classification.
<details>
  <summary>Show answer</summary>
Data classification focuses on assigning a sensitivity level to data (e.g., confidential, public) based on its potential impact if compromised. Data categorization, on the other hand, involves grouping data into specific categories based on its content, purpose, or other characteristics to facilitate data management, retrieval, and compliance.
</details>

6. What are the potential benefits of implementing a data categorization system?
<details>
  <summary>Show answer</summary>
Data categorization can improve data management by organizing data into logical groups, enhance data discoverability by making it easier to search for and retrieve specific information, and facilitate compliance with data privacy regulations by enabling organizations to identify and protect sensitive data more effectively.
</details>

7. Explain the concept of context-based data categorization.
<details>
  <summary>Show answer</summary>
Context-based categorization involves classifying data based on factors such as its source, ownership, location, or the context in which it was created or used. For example, data related to a specific project or department might be categorized together, regardless of its specific content.
</details>

8. Why is it important to have a procedure for declassifying data?
<details>
  <summary>Show answer</summary>
A procedure for declassifying data is important because it allows organizations to release data that is no longer sensitive or to lower the classification level of data that has become less sensitive over time. This ensures that data is not unnecessarily protected, reducing the burden of security controls and facilitating information sharing.
</details>

9. What security awareness training should be provided to employees regarding data classification and categorization?
<details>
  <summary>Show answer</summary>
Employees should receive training on the organization's data classification policy, including the different classification levels, the criteria used to determine classification, and their responsibilities for handling data at each level. They should also understand the importance of data categorization and how it relates to data protection.
</details>

10. Why are data classification and categorization considered ongoing processes?
<details>
  <summary>Show answer</summary>
Data classification and categorization are ongoing processes because the sensitivity and value of data can change over time, and new data is constantly being created. Organizations must regularly review and update their classification and categorization schemes to ensure that data is appropriately protected.
</details>

---



