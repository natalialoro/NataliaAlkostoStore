# Store-theme Natalia-Alkosto-Store 

NataliaAlkostoStore es una tienda de tecnología basada en la tienda oficial de Alkosto.

Preview
![image](https://user-images.githubusercontent.com/55117122/204119463-b0be341d-5bc4-4ae8-8c78-c0f017a733db.png)
![image](https://user-images.githubusercontent.com/55117122/204119466-d9092602-861f-4eab-af6f-a273134ab9b3.png)
![image](https://user-images.githubusercontent.com/55117122/204119477-e8516a17-a3d6-42b7-a287-d79a7b3cd10d.png)
![image](https://user-images.githubusercontent.com/55117122/204119487-49d38295-4835-4627-8d38-6497a65cb951.png)
![image](https://user-images.githubusercontent.com/55117122/204119495-c7e2aad3-9388-4043-9bae-35e6300ccb6b.png)
![image](https://user-images.githubusercontent.com/55117122/204119508-2c1d8e8f-a5c8-4ac2-8928-3de7a798efed.png)
![image](https://user-images.githubusercontent.com/55117122/204119539-33088be8-c54e-4eee-a2dc-596cae6a26ec.png)



It should be used only when you want to start a new store theme without any pre-set configurations, as is the case with [Store Theme](https://github.com/vtex-apps/store-theme). 

While Store Theme gives developers a ready-to-go default store front structure, the Minimum Boilerplate Theme will enable you to build you store freely from scratch.

## Configuration

### Step 1 -  Basic setup

Access the VTEX IO [basic setup guide](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) and follow all the given steps. 

By the end of the setup, you should have the VTEX command line interface (Toolbelt) installed along with a developer workspace you can work in.

### Step 2 - Cloning the Minimum Boilerplate Theme repository

[Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) this repository to your local files to be able to effectively start working on it.

Then, access the repository's directory using your terminal. 

### Step 3 - Editing the `Manifest.json`

Once in the repository directory, it is time to edit the Minimum Boilerplate `manifest.json` file. 

Once you are in the file, you must replace the `vendor` and `account` values. `vendor` is the account name you are working on and `account` is anything you want to name your theme. For example:

```json
{
  "vendor": "storecomponents",
  "name": "my-test-theme",
}
```

### Step 4 -  Installing required apps

In order to use Store Framework and work on your store theme, it is needed to have both `vtex.store-sitemap` and `vtex.store` installed.

Run  `vtex list`  and check whether those apps are already installed. 

If they aren't, run the following command to install them: `vtex install vtex.store-sitemap vtex.store -f`

### Step 5 -  Uninstalling any existing theme

By running `vtex list`,  you can verify if any theme is installed.

It is common to already have a `vtex.store-theme`  installed when you start the store's front development process. 

Therefore, if you find it in the app's list, copy its name and use it together with the command `vtex uninstall`. For example:

```json
vtex uninstall vtex.store-theme
```

### Step 6- Run and preview your store

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command. 

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.
