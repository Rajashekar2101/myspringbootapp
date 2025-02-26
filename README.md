# Github Actions pipeline for Springboot application

### Task:

+ Fork this repository and create a GitHub actions pipeline following given below instructions.

1. Fork this Github repository and create a public repo.
2. This sample springboot application requires below command to build a jar file.

```bash
 mvn package -Dmaven.test.skip=true
 ```

3. Create a reusable workflow yaml and call that workflow from main.yaml.
4. The workflow should run when there is a commit in main branch.
5. Add below mentioned environment variable at the repo level. Print the variable value through one task in the pipeline.

```
ENVNAME=dev
```

6. The build process will generate a jar at target/simple-springboot-app-0.0.1-SNAPSHOT.jar location. Please upload the generate jar in the pipeline.
