# Data_Visualisation-AWS
A project employing AWS QuickSight and S3 for insightful, interactive, and cloud-powered data analysis.

Click here to view : [Simple Architecture](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&layers=1&nav=1&title=AWSDV%20w%2F%20QS.drawio#R7VhbcxsnFP41mmkfpNmLLvajLlaajj11rZk6efKgXbRLjZYNsJbUX58Dy0oLi2IldTKdtok95nzAAQ7f%2BRboxfPt%2Fh1HZX7HUkx7UZDue%2FGiF0XhMB7CH4UcamRyHdVAxklqGp2AFfkLGzAwaEVSLKyGkjEqSWmDCSsKnEgLQ5yznd1sw6g9aoky3AFWCaJd9JGkMjdoOL4%2BVfyCSZaboa%2BiSV2xRU1jsxKRo5TtWlB804vnnDFZl7b7OaYqeE1c6n7LM7XHiXFcyEs6%2FPrxqWQxiu8WU3xzu35%2B9%2FDbXd94eUG0MguePq4AmFNWpWbe8tAEo2SkkDqgoxn8wHjzoDeCmrmyBtHIAVx7YgNh11I%2BbMC1JzYQuu5DZ%2FzQnWAL6FiW%2B8AZP2hNEH7iGaskJQWeH6kXAJhxlBLYkjmjjANWsAKiN8vlloIVQnGXE4lXJUpUVHeQNoBtWCEN%2BcOosU3glVegt0QwFjc%2B9E5gfvOC6w2p21CKSkHWx14cJxUX5AU%2FYFE7VygQsVTl7T5TOTtAOzEcZJxVpZ7%2BexjLW%2FsExadEEeMJUakcSc6ecbPQXhTD%2F6Ui32xDKHUC8IK5JJBXU0oy5V8yNRwyFsUb7RGiQorsVluLODCR8A2RIpHj1CzJsBiGwPuz6REekw7UCrMtlvwATUyHaGLy1AjVlTF3p6yfjA2WtxJ%2BODQgMkqTHV2fkhEKJh%2B%2FIjfHndzsRWMd%2BDUUMqnXXQMqSFaqjj9VrKno13s%2FhQbhqNzX3Ux946jO%2BhXZluAACpJxJYxKUsyQvGm6wvyFJKrup1X8c1MPK6wnYU8M4NZkHTkRz1gmudlCr7Z49cWnMV6d6WqN1Uxnv2cEF%2FRhky4Ydps1gtEFfZhPHd3eoad36PQ%2Br03ncqmdroBPplP4wPkSfKP%2FudnXpPYtWmN6zwSRREvImknJtq%2FmfoKVlNka%2BZoeIlHWy9qQvZqHX9Q4FqziCa4lDeRQ%2BMRNxJcqyPlP6FlZGY5tWQmjrq5EgUdXjuCb68roh%2BvK7xVJnlfv1dqiMdqqzS%2FWorR14n%2F5%2BJfIx9V8uFwu%2FzPy8UmRW9SJ%2B91kJAz%2BcTJy7ZERJ0NxkU7VHUztEkVCkESzAnHZhVu7B4fNIj3SA8LGDx%2FaxkdlAIuNudi3KxeHtnWPOYHl6nOzBvdEfjDDqHLLFVgnT8o4tAzXT71UnHYuj5fsMsRI8%2Bp1jYZQZfhL%2FsZ%2B1rRYMfKQosE4pkjC9cC%2BNXuIYka4VyJ7ImUcOaQcOVyrl2l6ta%2BmriPn7B26pK3j0HEELEKHVjPzEXCZfQzMt5O9eY74EtsbDSFb%2FabQZrRfwV4VPqoqZih5znRK%2BJRUDzZt5MyrbWY%2Bi1xK9WgyVcGJlklaRAMCerYhkGx8kMCI0TJFEsEfhUMcl7scYEXqPhE6hiTp7%2FC6nzMh4Z7WF3AXwFy1VFu%2FVFVr9eaCeZ8VfbiNwkL7YXQ1KIvsDe5oQ5smoIKDUUcGw8moy%2Fgj%2BOYyGHpkD2Sh%2BdowLnOWsQLRmxPqKNypzS1TxNCU%2BRNLeTDfMFRJZhPqm3TsLYX0AgG8VOua3HpV7EZ%2BclysYn9vn2Pfsdk6zC508gR%2FEFHB4UQgnc5R8EiAmlHQPgprYgJUpOqyDZ6DvjKJyHeIH5STB%2Fi9h3MVIh162eTxvSa1iGKfwcxbzFukonOvibvnkfjK8%2BmJv%2F44AubplbQW9NNbc3zzGQ%3D%3D)

# What do we need for this project:
1. S3: To store the csv and json file.
2. QuickSight: To visualise data.

#Step 1: Download the Dataset
1. Download any dataset that you'd like from the web or similar dataset like [amazon sales data.csv](https://github.com/aishup7/Data_Visualisation-AWS/files/12780710/amazon.sales.data.csv)

#Step 2: Create or download .json file
1. Create a policy json file that allows QuickSight to access S3 data like [policy.txt](https://github.com/aishup7/Data_Visualisation-AWS/files/12780695/policy.txt)

#Step 3: Create a bucket to upload files with AWS S3. 
1. Open AWS console and navigate to AWS S3 console.
2. Click on create bucket.
     1. Name your bucket.
     2. Leave other settings as default.
     3. Click on create bucket.
3. Upload Objects.
     1. Upload the CSV file into the bucket.
     2. Replace the URL in the "policy.json" file with the S3 URL of your dataset.
     3. Upload the .json file into the bucket.
           
#Step 4: Connect S3 Bucket with Amazon Quicksight. 
1. Open AWS console and navigate to AWS Quciksight console.
2. Sign up for a free trial of the Enterprise edition if you don't have an account.
3. Select Amazon S3 and tick the box for the S3 bucket you created.
4. Enter the link to your .json file and connect to Quicksight.
5. Select "interactive sheet" to start creating visualizations.

#Step 5: Create Visualizations
1. Drag fields into the graph to create visualizations (e.g., Most popular products).
2. Sort, filter, and customize the graphs as desired.
3. Experiment with different types of graphs like bar charts, pie charts, line graphs, etc.

#References :
[AWS QuickSight Workshop](https://catalog.workshops.aws/quicksight/en-US)
<br>[Tech with lucy : Video Tutorial for the same](https://www.youtube.com/watch?v=4-8cXuZzKTg&list=PLWBfjpfzscb7rCHCeZHZgm5PgifCZdr1M&index=6)


