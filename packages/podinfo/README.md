# Steps for adding podinfo to the UDS Bundle
1. Added the podinfo source to the packages dir
2. edited and added a cmd to the tasks/create.yaml file task
    
name: k3d-slim-dev-bundle
- description: "Create the podinfo package"
  cmd: "uds zarf package create packages/podinfo --confirm --no-progress --skip-sbom -o build/"
3. Run the task: slim-dev-package
4. Run the task: k3d-slim-dev-bundle 