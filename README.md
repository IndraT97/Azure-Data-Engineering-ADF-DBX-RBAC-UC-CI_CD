# Azure-Data-Engineering-ADF-DBX-RBAC-UC-CI/CD

# Project Objective

Ingesting on-premise (SQL and SFTP) data and transforming it using Azure Data Factory, Databricks followed by analyzing and reporting using PowerBI

In this project the main aim is to understand the Flow of data from Various Data Sources to Azure Cloud Platform while transforming the data to get the final set of tables for further analysis and visualization in Tableau software
This project involves use of Databricks Unity Catelog instead of Databricks MetaStore. The reason for the discontinuation of the Metastore is that it will be replaced by Unity Catalog, which is a unified data governance platform designed to work across all environments. Unity Catalog offers centralized management of data access, security, and compliance, making it a more comprehensive solution for governing data across multiple platforms and cloud environments compared to the Metastore

This project includes migrating the metadata store from MetaStore to Unity Catalog. It also involves creating roles using Role-Based Access Control (RBAC) and transferring those roles within the Databricks Catalog using the SCIM connector     

For More information on Unity Catelog and RBAC, please visit this website [Link](https://github.com/IndraT97/Tech-Learning/tree/main/RBAC%20and%20Unity%20Catelog)

In real-time scenarios, organizations often grapple with petabytes of structured data dispersed across numerous on-premises locations. Leveraging cloud solutions streamlines data processing, circumventing the limitations and inefficiencies of current infrastructure. This shift not only sidesteps the extensive planning, time, and financial investment required for new infrastructure setup but also mitigates the risk of such investments becoming obsolete. Ultimately, transitioning to the cloud facilitates swift, cost-effective achievement of data processing objectives with minimal complexity

<p align="center">
  <img src="https://github.com/IndraT97/Azure-Data-Engineering-ADF-DBX-RBAC-UC-CI_CD-/blob/main/Screenshot%202024-04-03%20202030.png">
</p>

## 👩🏻‍💻 Usage Instructions

To explore the contents of this repository:

1. **Clone the repository**:

    ```sh
    git clone https://github.com/IndraT97/Azure-Data-Engineering-ADF-DBX-RBAC-UC-CI_CD.git
    ```

2. **Navigate through the directories** to find case studies, platform solutions, or projects of interest.

3. **Review the SQL queries and accompanying documentation** to understand the problem-solving approaches and methodologies.


## ✏️ Contribution Guidelines

Contributions to this repository are welcome. 🚀

If you have suggestions for improvements, additional case studies, solutions, or projects, please follow these steps:

1. Fork the repository.

2. Create a new branch (`git checkout -b feature-branch`).

3. Commit your changes with detailed messages (`git commit -m 'Add detailed feature description'`).

4. Push to the branch (`git push origin feature-branch`).

5. Submit a pull request for review.

## Support

Do ⭐ the repository, if it inspired you, gave you ideas of your own or helped you in any way !!

I hope you find these resources informative and useful for your SQL learning and application. Should you have any questions or feedback, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/i97/). 🙌


