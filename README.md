# Recipe_Preparation_Agent

# AI Service Deployment for Recipe Preparation Agent

## Overview
This project demonstrates the deployment of a Recipe Preparation Agent as an AI Service using IBM watsonx.ai. The agent assists users in cooking meals using only the ingredients available to them by providing tailored recipe suggestions and step-by-step instructions. The deployment process includes setting up the environment, defining the AI service function, promoting assets, deploying the service, and testing the deployed AI service.

## Contents
- Setup environment including IBM Cloud credentials and service connection
- Define AI service function using IBM watsonx.ai and langchain_ibm libraries
- Promote required assets and set deployment space
- Store, deploy, and manage the AI service in watsonx.ai repository
- Test the deployed AI service both locally and remotely

## Prerequisites
- IBM Cloud Lite account and API key
- Python 3.11
- IBM watsonx.ai access with a configured space
- Basic knowledge of Python programming

## Setup Instructions
1. **API Credentials**: Provide your IBM Cloud API key to connect to the watsonx API.
2. **Set Space**: Configure the space ID for deployment and asset hosting.
3. **Promote Assets**: Promote required project assets to the designated space.
4. **Define AI Service**: Implement the service function with the necessary imports, model configuration, and tool integrations.
5. **Store AI Service**: Upload the AI service definition to the watsonx.ai repository.
6. **Deploy AI Service**: Deploy the stored AI service in the chosen IBM Cloud space.
7. **Test AI Service**: Run test queries against the deployed service to verify functionality.

## How to Run
- Use the provided Jupyter notebook with step-by-step code to execute the deployment process.
- Modify input questions to test different scenarios and agent responses.
- Use streaming or non-streaming mode to invoke the AI service.
- Monitor logs and responses for debugging and verification.

## Technologies
- IBM watsonx.ai platform and API
- Python client SDK (`ibm_watsonx_ai`)
- LangChain integration for AI agent creation
- IBM Cloud infrastructure for deployment and management

## License
Licensed under the ILAN License by IBM. See [License Terms](https://www14.software.ibm.com/cgi-bin/weblap/lap.pl?li_formnum=L-AMCU-BYC7LF) for details.

## Support
For questions and troubleshooting, refer to IBM watsonx.ai documentation or open an issue on the project repository.

---

This notebook and the accompanying AI service enable seamless deployment and management of generative AI agents tailored for practical recipe preparation and cooking assistance.
