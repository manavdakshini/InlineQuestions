**Region** and **Availability Zone** are key concepts in cloud computing infrastructure, especially in platforms like AWS, Azure, and Google Cloud. Here's a brief overview:

### **Region**
- A **Region** is a geographical area where a cloud provider has multiple data centers (availability zones) to host its services.
- Each region is isolated from others for fault tolerance, data sovereignty, and performance reasons.
- A cloud provider may have multiple regions across the globe, allowing users to choose the region closest to their customers or where they need to meet regulatory requirements.
- Regions usually have at least two availability zones to ensure high availability.
- Examples:
  - AWS: `us-west-1` (Northern California), `eu-central-1` (Frankfurt)
  - Azure: `East US`, `Central India`
  - Google Cloud: `asia-south1` (Mumbai)

### **Availability Zone (AZ)**
- An **Availability Zone** is a distinct, isolated data center within a region.
- Each AZ is independent and has its own power, cooling, and network to ensure redundancy and resilience.
- Multiple AZs in a region allow cloud users to design highly available and fault-tolerant applications by replicating resources across zones.
- Typically, regions have 2-6 AZs.
- Data transferred between AZs within the same region is usually fast and low-latency, making it suitable for disaster recovery and high-availability applications.
- Examples:
  - AWS: `us-east-1` region has six Az like `us-east-1a`, `us-east-1b`, `us-east-1c`, `us-east-1d`, `us-east-1e`, `us-east-1f`.

In summary, **Regions** are larger geographic areas containing multiple **Availability Zones**, which are independent data centers designed to ensure high availability and resilience.

<question source="https://raw.githubusercontent.com/manavdakshini/InlineQuestions/main/questions/question-12.md" />
