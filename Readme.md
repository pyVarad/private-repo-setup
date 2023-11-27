# How to use private repository.

The artifactory runs at port `http://localhost:4873`. So use `--registry http://localhost:4873` during `npm install` or `yarn`

Step 1: docker-compose up -d
Step 2: Login to the artifactory using the command `npm login --registry http://localhost:4873`.
Step 3: Build your package.
Step 4: Publish your package using the command `yarn publish / npm publish`.