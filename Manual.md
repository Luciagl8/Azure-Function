1. Edit azuredeploy.parameters.json
2. Run the next command
    >>> az group create --name ArcAppfunc --location eastus
    >>> az deployment group create --resource-group ArcAppfunc --name ArcAppFunc --template-file ./azuredeploy.json --parameters ./azuredeploy.parameters.json