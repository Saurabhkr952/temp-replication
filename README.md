# temp-replication
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/6603423415a84019ac6d364526d704c6)](https://app.codacy.com/gh/Saurabhkr952/temp-replication/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Codacy Badge](https://app.codacy.com/project/badge/Coverage/6603423415a84019ac6d364526d704c6)](https://app.codacy.com/gh/Saurabhkr952/temp-replication/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_coverage)

test  . 

[tests](/tests/certificate.yaml)
<iframe width="560" height="315" src="[https://www.youtube.com/embed/VIDEO_ID_HERE](https://www.youtube.com/watch?v=IJeSR-LJBnk&list=RDMMIJeSR-LJBnk&start_radio=1)" frameborder="0" allowfullscreen></iframe>


```mermaid
graph LR
    A[create KEY] --> B[create CSR]
    B --> C[K8s API]
    C --> D[download CRT 
            from API]
    D --> E[use 
            CRT+KEY]

    style A fill:#F5F5DC,stroke:#333,stroke-width:1px,color:black
    style B fill:#F5F5DC,stroke:#333,stroke-width:1px,color:black
    style C fill:#00BFFF,stroke:#333,stroke-width:1px,color:black
    style D fill:#F5F5DC,stroke:#333,stroke-width:1px,color:black
    style E fill:#F5F5DC,stroke:#333,stroke-width:1px,color:black
