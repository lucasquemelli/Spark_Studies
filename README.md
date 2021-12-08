# Spark_Studies
This is a repository for deploying my studies with Spark. 

# Functions

- Initialization:

![image](https://user-images.githubusercontent.com/81119854/145231033-0f694e78-dc58-4a7f-a615-91e16ce6874e.png)

- Creating a RDD - resilient distributed data - and working with it:

![image](https://user-images.githubusercontent.com/81119854/145231430-97f847c3-1c25-41ba-91de-54562e7eed8f.png)

- Performing an operation:

![image](https://user-images.githubusercontent.com/81119854/145231707-7ff0514e-7b59-44be-bfc7-d784e6da5a4f.png)

- Collecting RDD unique values:

![image](https://user-images.githubusercontent.com/81119854/145231797-e761b44b-7716-4861-a1bd-03ea2f4cc5e8.png)

- Transforming RDD into a dataframe:

![image](https://user-images.githubusercontent.com/81119854/145244036-b19814b3-f006-4da4-9083-d4b9097f310c.png)

- Displaying the data in the dataframe:

![image](https://user-images.githubusercontent.com/81119854/145244195-b58e9ada-d2a5-4633-909d-46309c3adb63.png)

- Calling a list and its order:

![image](https://user-images.githubusercontent.com/81119854/145244519-66b231be-4692-4867-b2c4-4c1e985462fc.png)

- Creating and displaying a temporary view/table:

![image](https://user-images.githubusercontent.com/81119854/145244940-26399203-c457-4363-a2e6-35d3b3a8d83c.png)

- Selecting column "n" from table "numeros":

![image](https://user-images.githubusercontent.com/81119854/145245185-bfd96d02-5822-4148-9be7-73d9c9639fa1.png)

- Selecting the sum of the column "n":

![image](https://user-images.githubusercontent.com/81119854/145245492-c7ac61b1-5855-4838-ae8d-00490accb668.png)

![image](https://user-images.githubusercontent.com/81119854/145245683-a69c4666-ea6a-4046-8efe-b32d3d330148.png)

- Working with a larger dataframe:

![image](https://user-images.githubusercontent.com/81119854/145248992-f676ff6a-3004-41be-8d71-47cfdafb4a13.png)

- Selecting "data" and "id" and displaying the first row:

![image](https://user-images.githubusercontent.com/81119854/145249206-943004ae-5300-45df-b57c-0c1b74b04012.png)

- Selecting "data" and "id" and displaying all the elements of the first row:

![image](https://user-images.githubusercontent.com/81119854/145249339-329515cf-943e-4a6a-b9b5-23cd0c78a758.png)

- Using the explode function to display all the elements of the first row of "data":

![image](https://user-images.githubusercontent.com/81119854/145253956-6c42d794-b93f-49c6-b293-f0030858722f.png)

- Renaming the "col" field to "tweets" and selecting all the elements of the first row:

![image](https://user-images.githubusercontent.com/81119854/145255130-33fff4c1-a422-4d3b-91cb-ea4781f42974.png)

- *public_metrics* is also a structure. Thus, we need to explode this structure too. It will be available now in a flat format:

![image](https://user-images.githubusercontent.com/81119854/145257339-92797c00-45f3-4a61-a515-0a01bb1569e4.png)

- Displaying all the transformed structure:

![image](https://user-images.githubusercontent.com/81119854/145257832-6d967efe-5da8-4479-b8c4-4ca27c943acc.png)
![image](https://user-images.githubusercontent.com/81119854/145257921-4094e771-49ed-4af5-9342-27bea3ad7301.png)

- Only the first row to better visualize the new format:

![image](https://user-images.githubusercontent.com/81119854/145258446-150df8ea-e555-417b-a813-a2568dd82f9a.png)

- Now, we are going to perform the same steps as before, yet with "users" instead of "data". It is important to note that it is only possible to apply explode function in arrays. 

![image](https://user-images.githubusercontent.com/81119854/145259804-b96d3fa9-f2b6-4d05-8a4f-c8f90d00c990.png)

![image](https://user-images.githubusercontent.com/81119854/145260563-6a464268-c1ec-4525-beb7-77581ec8137a.png)

![image](https://user-images.githubusercontent.com/81119854/145261179-95339c97-5d4a-4b10-acd4-b683f13cd2d3.png)
