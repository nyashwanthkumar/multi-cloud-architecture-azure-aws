# Multi-Cloud Architecture – Azure & AWS

This project demonstrates a basic multi-cloud architecture where services are distributed across Microsoft Azure and Amazon Web Services (AWS).

The objective is to design and document interoperability between two cloud platforms using secure communication over HTTPS.

## Overview

The architecture consists of:

- Azure Virtual Machine acting as the Frontend Layer  
- AWS EC2 Instance acting as the Backend Application Layer  
- AWS S3 Bucket acting as the Storage / Backup Layer  

Communication between Azure and AWS is established using a secure HTTPS REST API call.

## Architecture Flow

1. A user interacts with the application hosted on an Azure Virtual Machine.
2. The Azure Virtual Machine communicates with the AWS EC2 backend using secure HTTPS-based REST API calls, demonstrating cross-cloud interoperability.
3. The AWS EC2 backend processes the request.
4. Application data is stored or backed up in an AWS S3 bucket.

This setup demonstrates secure cross-cloud communication and service interoperability between platforms.

## Services Used

### Microsoft Azure
- Azure Virtual Machine (Frontend Layer)

### Amazon Web Services (AWS)
- Amazon EC2 (Backend Application)
- Amazon S3 (Storage / Backup Layer)

## Interoperability Details

- Communication Protocol: HTTPS  
- API Type: REST API  
- Cloud Interaction: Azure to AWS  
- Storage Location: AWS S3  

This design ensures secure communication and separation of application layers across cloud providers.

## Result

The architecture successfully demonstrates a multi-cloud design where services are distributed between Azure and AWS.

It highlights secure communication, backend processing, and storage integration across platforms. This model can be extended for scalability, high availability, and disaster recovery scenarios.

<img width="835" height="752" alt="multi-cloud-architecture-diagram" src="https://github.com/user-attachments/assets/4daa78e5-b982-488f-950e-c3d734d7301c" />

![azure-virtual-machine-frontend](https://github.com/user-attachments/assets/7fe25f77-89d5-4cbf-a73d-9dfb25e556c0)

<img width="1902" height="305" alt="ec2-backend-instance" src="https://github.com/user-attachments/assets/1161cf62-7db4-44fe-bfce-788f792eccd5" />

![s3-storage](https://github.com/user-attachments/assets/a33bae84-fcb8-4369-a740-c81a58b6d9c9)




