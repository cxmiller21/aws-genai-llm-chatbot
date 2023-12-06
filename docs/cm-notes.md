# CM Demo Notes

## 12/6/2023 Notes

Project is set to create resources without using SageMaker resources. However, the RAG chatbot isn't working at the moment because the "Cross encoder model not found". This is from updating the `./bin/config.json` file but I need to figure out why this cross encoder is needed in the first place. From my understanding, the Bedrock and OpenSearch index should be able to run independently of the SageMaker resources.
