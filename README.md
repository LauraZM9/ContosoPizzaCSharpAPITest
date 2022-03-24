# ContosoPizzaCSharpAPITest
ASP.Net Core C sharp API Test

# Tutorial followed to build the API
Important! The tutorial only works with ASP.NET CORE > 6.0

https://docs.microsoft.com/en-us/learn/modules/build-web-api-aspnet-core/?WT.mc_id=beginwebapis-c9-cephilli

# Troubleshooting
- Error when running ls:

"https://localhost:7120/> ls
No directory structure has been set, so there is nothing to list. Use the "connect" command to set a directory structure based on an OpenAPI description."

Solution: 

run `dotnet dev-certs https --trust`

https://stackoverflow.com/questions/69278068/why-is-httprepl-unable-to-find-an-openapi-description-the-command-ls-does-not

- ASP.NET CORE requires a buildpack for HEROK. We used the one from this tutorial: https://circleci.com/blog/deploy-dotnetcore-heroku/
