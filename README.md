# Coding Challange Backend Integration
`https://playgroundvwtestapp.azurewebsites.net/docs`
## Testsuit and Testcases
### Create a Testsuite that can run automated tests and is able to display/report the results of any given run
1. Create 100 VINs. Use the dedicated ID namespace provided to you for the creation of the VINs. The name of your VINs should start with the name of your company. Fill the rest of the string with random characters until it reaches a size of 17. The status of all VINs should be `available`
2. Search for all VINs that are present and validate from that response[^1]📄 that all 100 VINs you created are present. 
3. Change the status of every second VIN to `sold` and validate the status change. Save the responses📄 before and after the change as an artifact. 
4. Create a human readable report📄 for the testrun.

## Virtualization 
### Virtualize the API on your machine
1. Modify the API that you now run locally in such way that while creating a VIN you receive the errorcode 500.
2. Run the testsuite against you local virtualization.
3. Create a human readable report📄 for the testrun.
4. How would you report this error/bug?[^2]

## Protocols 
### Handling of different protocols in your testautomation
We work in a highly complex ecosystem with different protocols. How would you embed testcases that contain for example MQTT, Protobuf or Kafka messages into your Testsuite in such way that there will be no need for manual tests and the results are visible in the testreport?[^2]

## GitHub
### Working with version control and creating workflows
1. Create a GitHub account and push your code into a repository.
2. Create a GitHub Action that executes your testsuite. 
3. Your GitHub Action should save all artifacts at the end of each run.

[^1]: Make sure you save everything that is marked with 📄 as an artifact.
[^2]: Write down the answer in the Readme of your repository.
