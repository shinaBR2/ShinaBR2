# ActiveImage

Site: [activeimage.io](https://activeimage.io/)

Architecture: serverless with GCP, a small ERC-1155 smart contract on the Arbitrum Ethereum, ReactJS on the frontend.

### Architecture

Do 90% of the backend development workload, including:
- Set up a new GCP project from scratch
- Configure and optimize IAM roles
- Setup, implement, deploy, and manage Cloud Functions beside CI (Github Actions)
- Setup and run long-running tasks using Google Cloud Tasks, configure retry behavior of queues
- Run migration tasks to backup the data, denormalization data
- Working with Google's services like Google Cloud Armor, Google API Gateway, and Load Balancing to have the production quality architecture and connect all the pieces together.
- Set up webhooks for 3rd services like Stripe payment.
- Set up Slack integration for monitoring and error reporting
- Configure database security rules
- Setup and config the CDN for Cloud Storage
- Monitor the blockchain, find and debug the issues, keep the data between the database and blockchain consistent.

### Stripe payment

Design data model, implement and connect to the backend:
- Choose the pricing model to fit the business
- Choose the split payment approach to fit the business
- Setup and configure all webhooks

### Frontend development

Do all daily basis, basically, everything as a Frontend Developer should do: building ReactJS components, integration with serverless backend solutions, using feature flag system, etc.

### Documentation

I wrote 99% document of the project.
