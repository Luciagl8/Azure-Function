1. Edit azuredeploy.parameters.json
2. Run the next commands
    >>> az group create --name ArcAppfunc --location "East US"
    >>> az deployment group create --resource-group ArcAppfunc --name ArcAppFunc --template-uri https://raw.githubusercontent.com/Luciagl8/Azure-Function/main/azuredeploy.json --parameters ./azuredeploy.parameters.json
3. Connect to the client VM via RDP