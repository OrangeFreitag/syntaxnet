# HOW to
- use this commands in the project dir
- https://docs.polyaxon.com/concepts/quick-start/


## Check CLI
> polyaxon version --cli

## Check user
> polyaxon whoami

## Create project
> polyaxon project create --name=syntaxnet --description='playing with syntaxnet'
> polyaxon project -p quick-start git --url="THE RIGHT GITHUB CLONE URL"
> polyaxon init syntaxnet


# Run a experiment 
> polyaxon run -p syntaxnet -f polyaxonfile.yaml