# Lob Insomnia
An Insomnia REST client collection for calling Lob API endpoints.


## Steps to get up and running
Follow these steps to quickly get up and running with the Lob API and Insomnia.

---

### 1. Download Insomnia Client
Visit Insomnia and download the desktop client.
> http://insomnia.rest/

---

### 2. Sign up for a Lob account

Create an account at [Lob.com](https://dashboard.lob.com/#/register).

Login to Lob dashboard and navigate to [Settings](https://dashboard.lob.com/#/settings/account).

Click on the API Keys tab. Look at your Secret and Publishable API Keys. You'll use the test\_\*. for your Test API key and live\_\*. for your Live API key.

![settings and api key](images/lob-account-settings-api-keys.png)
----

## 3. Import the Lob Insomnia collection

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Lob%20Insomnia&uri=https%3A%2F%2Fraw.githubusercontent.com%2FSidneyAllen%2Flob-insomnia%2Fmain%2Flob-insomnia-1.0.0.json%3Ftoken%3DAAERP75JPF6KZIIBNLNJEPDBBMH46)

Click Create in the Insomnia app and choose file.

Locate either `lob-insomnia-1.0.0.json` or `lob-insomnia-1.0.0.yaml` in your file system and then click Import.




---

### 4. Add your Test API key to the environment in Insomnia

Get the test API key from [Settings](https://dashboard.lob.com/#/settings/account) in Lob.

Go to the environment dropdown in Insomnia desktop and select `Manage Environments`.

![manage environment](images/manage-environment.png)

Paste your Lob Test API key as the value for `httpUsername` in your OpenAPI env and click Done.

![paste API keys in environment](images/set-api-keys-in-enviroment.png)


---
### 5. Start exploring Lob APIs

A good place to start it to `Create` one or more addresses and `List` the addresses.  Other endpoints will use the address id returned from the `List` operation.

You'll also want to `Create` one or more templates and `List` the templates prior to exploring Postcards and Self-mailers.

---

**Coming Soon**

Watch this space

_Video tutorial on setting up Insomnia_
> coming soon

_Blogpost on setting up Insomnia_
> coming soon
