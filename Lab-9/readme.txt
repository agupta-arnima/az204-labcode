Application(client) ID 5906f68a-a5ef-4128-92b4-7d1f4a5b5e93
Tenant ID	       8eb87a6e-8055-4135-b69d-f19c799ec045


dotnet new console

dotnet add package Microsoft.Identity.Client
dotnet add package dotenv.net

The app opens the default browser prompting you to select the account you want to authenticate with, if there are multiple accounts listed select the one associated with the tenant used in this app.

https://login.microsoftonline.com/8eb87a6e-8055-4135-b69d-f19c799ec045/oauth2/v2.0/authorize?scope=User.Read%20openid%20profile%20offline_access&response_type=code&client_id=5906f68a-a5ef-4128-92b4-7d1f4a5b5e93&redirect_uri=http%3A%2F%2Flocalhost%3A52211&client-request-id=51165055-5091-4906-a94e-63811923493f&x-client-sku=MSAL.NetCore&x-client-ver=4.84.2.0&prompt=select_account&code_challenge=dlyHUsoD6unc0QA_DeRjkfU4ViZ_TmHSFelDXTlfy1U&code_challenge_method=S256&state=6360b052-fe00-4968-8b8e-c6bed7d18b15a1889db3-effb-4933-8276-1953d01a9267&client_info=1&haschrome=1&response_mode=form_post