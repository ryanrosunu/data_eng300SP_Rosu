## How to Run
1. Open the Jupyter notebook `hw2.ipynb`
2. Ensure the following required libraries are installed in local python environment:
- pandas
- numpy
- datarec-lib 
- boto3 
- torch 
- transformers 
- faiss-cpu
3. Run the code in order

## Expected Output
- After providing AWS credentials and running the notebook code, the users, movies, and ratings data tables should be loaded from S3 into dataframes. Several embedding index files should be created and uploaded to S3 as well, along with recommendation csv files for each user and a my-profile.csv file.

## Generative AI Disclosure
Tools Used: ChatGPT

Key Prompts: I used ChatGPT to debug issues with my IP getting blocked for SSH access and for guidance on passing AWS credentials for boto3 client S3 access. I also used it for help on writing the parts of functions that load files from S3 into Dataframes, and for help on how to prevent the bert_embed function from crashing the kernel.


What I changed and how I verified: All code was implemented by me and suggestions from generative AI were verified by running the code, and cross checking with documentation and other online sources.
