az staticwebapp create \
    --subscription Visual Studio Enterprise Subscription \
    --resource-group static_web_app_rg \
    --name jugis-staticwebapp-with-api \
    --source https://github.com/jugi92/static-web-app \
    --token YOUR-GITHUB-REPO-PERSONAL-ACCESS-TOKEN \
    --location YOUR-LOCATION \
    --branch main \
    --app-location "app" \
    --output-location "build"