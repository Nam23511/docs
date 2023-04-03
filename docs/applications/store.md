# Store

The store application is fully fuctional. Allowing a user to install apps from our commuity app store.

:::tip

To add an app to the store visit [here](https://win11react-docs.andrewstech.me/docs/Store/add-app).
:::

# Custom Store

You can use a third party store json by launching with the query customstore=https://json-file-link-goes-here

:::warning

Third party stores are not monitored by win11react devs.
:::

{
  "name": "Messenger", // unique name (check if it has been used already in the file)
  "icon": "![image](https://user-images.githubusercontent.com/129754815/229508710-9c4cb12a-cb5d-4c9d-81cb-196c6d285fec.png)", // logo image, preferrably 1:1 and less than 128px of width
  "type": "game", // game or app
  "data": {
    "type": "IFrame", // type currently supports IFrame only
    "url": "https://messenger.com", // url of the app and make sure they accept Iframe
    "gallery": [
      // three or more images for gallery view in store app
      "![image](https://user-images.githubusercontent.com/129754815/229508243-e9559bc3-5d40-4386-a3ca-fa89d49fb306.png)",
      "![image](https://user-images.githubusercontent.com/129754815/229508318-1f1cc31b-5cfa-4479-9f60-22c14d802e6d.png)",
      "![image](https://user-images.githubusercontent.com/129754815/229508374-da7b39da-0a68-42b3-b5a2-418e6caf5bfb.png)"
    ],
    "desc": "A Chattng app for windows 11", // description for store app
    "feat": "1.1Fix Some Bugs.1.2a Fix some error and lags", // features for store app
    "invert": true // when true it forces dark theme for game/app window, default is false.
  }
}
