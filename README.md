DEPLOY: LLM application used docker

1.docker image_llm & conatainer_llm: for llm api service: network-a



2. docker: for applicaliton: network-a (make sure same docker network used as llm api service container)
   2.1: image_notebook_dev: create image seperately for futher applicaltion usage
   2.2: container_notebook： for each project: create for each project , especailly for devlopping phase, with VSCODE: devcontainer -for vs code
