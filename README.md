# content-terraform-docker-service
Travis Terraform Course Repo 2
n the Jenkins dashboard, click New Item Enter an item name of PipelinePart2, and select Pipeline. Click Ok.

Check the box for This project is parameterized. Click Add Parameter and select Choice Parameter. Give it a Name of action. For Choices, enter Deploy and Destroy, and make sure they are on separate lines. Enter The action that will be executed as the Description.

Click Add Parameter and select Choice Parameter again. This time, name it image_name. Enter ghost:latest and ghost:alpine in the Choices box, making sure they are on separate lines. Enter The image Ghost Blog will deploy as a Description.

Click Add Parameter a third time, and select String Parameter. Give it a Name of ghost_ext_port. Set the Default Value to 80. Enter The Public Port as the Description.
