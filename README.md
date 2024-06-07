# Working_with_AWS_Cloudformation
In this project, I am going to create, update and delete an AWS Cloudformation stack. This was part of my AWS re/Start training. I have also uploaded the final YAML template I used for the stack.

## Create the stack

First I am going to create a YAML template containing all the parameters, resources and outputs I want for my Cloudformation stack.

![Screenshot (31)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/621d156a-859d-449b-9fea-9cf7d01bffa2) 
![Screenshot (32)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/f6eafd60-c883-4675-a160-700288b75634) 
![Screenshot (33)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/ced9ca70-b05d-4082-b1a3-0f88d66260e6)


After that, I log in the AWS management console and go to Cloudformation. 

![Screenshot (35)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/95075ace-9aff-4878-9b38-eedcfb89a034)


I choose create a stack and upload my YAML template.

![Screenshot (34)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/b84620c7-46e8-4389-86f9-bdc5ee31300c)


I then specify a name, submit and wait while it is being created.

![Screenshot (36)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/ebc73289-5ab7-449f-9a48-7a0f1d3d11b5)
![Screenshot (38)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/95032925-92f5-4296-8df8-142be6d70826)


In the resources section, I can view the progress.

![Screenshot (41)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/8d92b1ea-4ffd-44d1-b6b8-70b97d611b52)


The stack is created!

![Screenshot (42)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/701c0a38-90d9-408c-a899-85c6d84502d5)


## Update the stack with an S3 bucket

Next, I am going to update the stack by adding an S3 bucket. I edit the template by adding the bucket in the resources.

![Screenshot (43)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/8536c809-7e9e-4e18-95de-fafa8b714319)


Then, in the console, I click on update and upload my edited template.

![Screenshot (44)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/13b9a44a-9b3f-45fa-b53b-1944b41af2be)


In the Events tab, I can see that it is being updated and in the Resources tab I can see the bucket I configured.

![Screenshot (45)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/117749ba-5f50-4112-9c43-b368b0d264f9)
![Screenshot (46)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/102afebc-71d2-4f22-928f-10d15f5a1d25)


## Update the stack with an EC2 instance

Next, I am going to add an EC2 instance to the stack. Again, I configure it in the YAML template.

![Screenshot (47)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/a1c4a847-bd77-438c-92af-7d518459debc)


And I update the stack in the console.

![Screenshot (48)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/150884d7-eef6-4cc8-93ac-6ba13a983602)
![Screenshot (49)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/5adde500-f231-477b-9c3b-0a95a3fa3a1f)


## Delete the stack

Finally, I need to delete the stack. I choose delete and then view the progress.

![Screenshot (50)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/ae8e0ac6-899b-469d-8905-8cea38b04672)
![Screenshot (51)](https://github.com/DespoinaTikt/Working_with_AWS_Cloudformation/assets/166096217/82204311-091e-4ecc-80df-c48966e7597b)


After a while, the stack has disappeared.









