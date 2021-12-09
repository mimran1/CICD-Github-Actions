# CICD-Github-Actions
A Sample Repo to understand GitHub Actions

All steps are explained here: https://www.youtube.com/watch?v=MhEa8fENJqM&list=PLhGL9p3BWHwtHPWX8g7yJFQvICdNhFQV7&index=21
You may have to follow this: https://stackoverflow.com/questions/50739869/web-app-is-not-loading-after-deploying
if even after successfull deploy the webapp is not loading.

Steps:
1. Create a Webapp using visual studio
2. Create a Webapp service in Azure
3. Create a Github Actions yaml file with instructions to build, test, publish and deploy options
4. Upload the webapp code to a Github repo along with the yml file.
5. Do minor update to code and push changes to repo. this triggers build action
6. your code now gets deployed to Azure App service
7. If you make any change to code and push to repo, it automatically build, test, publish and deploy based on the yml file.
8. Pretty cool.
