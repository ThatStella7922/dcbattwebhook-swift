# Defaults Used

## Settings
- WebhookURL
  - String, contains the Discord Webhook URL
- UserpfpUrl
  - String, contains the URL of the user's avatar image
- UsrName
  - String, contains the user set display name
- UsrPronoun
  - String, contains the user set pronoun
- UsrDeviceName
  - String, contains the user set device name (for ios 16 not allowing this)
- ShowPfp
  - Bool, stores the user's preference on showing their pfp
- ShowPronoun
  - Bool, stores the user's preference on showing their pronoun
- SendDeviceName
  - Bool, stores the user's preference on sending their device name
- SendDeviceModel 
  - Bool, stores the user's preference on sending their device model
- SelectedServiceType
  - String, stores the user's preference on which service (discord, telegram, etc) they want to use. Must be selected from a predefined list. See serviceTypes array in WebhookSettingsView.swift

## Automation Settings
- SendOnPluggedIn
  - Bool, stores the user's choice on enabling the automated sending of battery info when they plug in their device
- SendOnUnplugged
  - Bool, stores the user's choice on enabling the automated sending of battery info when they unplug their device
- SendOnHitFullCharge
  - Bool, stores the user's choice on enabling the automated sending of battery info when their device reaches 100% charge

## Internal Use
- SavedDate
  - Date, stores a date to be used for other stuff
