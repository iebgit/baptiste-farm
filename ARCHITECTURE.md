# High-Level Architecture Diagram

## Overview
The diagram illustrates the high-level architecture for the Baptiste Farm ecommerce platform, emphasizing simplicity and cost-effectiveness.

## Components
1. **Users/Browsers:** Interface for users to interact with the ecommerce platform.
2. **CloudFront CDN:** Content Delivery Network to speed up the delivery of static assets.
3. **React Frontend:**
   - Hosted on **AWS S3**.
   - Delivered via **CloudFront**.
4. **Magento Backend:**
   - Hosted on an **AWS EC2** instance.
   - Connected to an **RDS MySQL** database.
5. **S3 (Static Assets):** Storage for images and other static files.

## Diagram
![High-Level Architecture Diagram](sandbox:/mnt/data/A_high-level_architecture_diagram_for_a_simple_eco.png)
