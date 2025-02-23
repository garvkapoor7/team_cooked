# team_cooked

##AWS Serverless Chatbot for Customer Service

I have created a chatbot fro customer service using LLMs and Langchain.
I have wriiten the whole code in AWS Sagemaker.

Here are the steps for createing buckets to creating notebook instances for this model:

1. First create an IAM user and give access permissions for accessing Sagemaker, S3 Bucket:
   
   ![Alt text](https://github.com/garvkapoor7/team_cooked/blob/main/AWS%20Images/IAM_policies.png)
   
2. Then, create a S3 bucket to upload the dataset which will be loaded by Sagemaker later.
    ![Alt text](https://github.com/garvkapoor7/team_cooked/blob/main/AWS%20Images/s3_bucket.png)
   
3. Now open Sagemaker and create a notebook instance.

    ![Alt text](https://github.com/garvkapoor7/team_cooked/blob/main/AWS%20Images/sagemaker.png)


#Tech Used for Chatbot:
1. hUGGING Face
2. LangChain
3. Numpy
4. Pandas
5. ChromaDB
   
#Tech used in AWS:
1. IAM
2. S3 Bucket
3. AWS Sagemaker


#Here is the output of chatbot if asked a question:
 ![Alt text](https://github.com/garvkapoor7/team_cooked/blob/main/AWS%20Images/output.png)
