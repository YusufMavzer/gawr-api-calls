# Execute easy and fast GAWR rest calls in vscode

## Prerequisite
- [VSCode](https://code.visualstudio.com/download)
- [Rest Client (VSCode extension)](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

## Usage
Each registry has its own file with requests.<br/>
When you're faced a single `@host` in a file then it means that the api is not publicly availabe.<br/>
In those cases you'll have to run the api on your local machine and execute the call after.<br/>
If there are multiple `@host` lines than it most is publicly available.<br/>
Uncomment the `@host` you want to test and press on the `Send Request` line above each request.<br/>
A new view will pop up and show the results as well as the request, response header and execution time.<br/>
More info you can take a look at the rest client extension documentation.
