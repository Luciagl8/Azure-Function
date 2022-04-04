1. Edit azuredeploy.parameters.json
2. Run the next command
    >>> az group create --name ArcAppfunc --location eastus
    >>> az deployment group create --resource-group ArcAppfunc --name ArcAppFunc --template-uri https://raw.githubusercontent.com/Luciagl8/Azure-Function/main/azuredeploy.json --parameters ./azuredeploy.parameters.json