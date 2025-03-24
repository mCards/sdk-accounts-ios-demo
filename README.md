# mCards iOS Accounts SDK Demo App

The mCards iOS Accounts SDK encapsulates the following functionality:

1. Link bank accounts
2. Link credit accounts
3. Deactivate accounts
4. Reorder account priority

# Importing
The SDK can be imported via SPM (Swift Package Manager).

- In XCode, go to: File -> Add Package Dependencies
- In the search bar enter: `https://github.com/Wantsa/sdk-accounts-ios-framework`
- Choose a dependency rule (e.g. `Up to Next Major` with `1.0.0`
- Click `Add Package`

# Usage
Implementing apps must take additional steps if using the SDK and Auth0 as a token provider. In Xcode:
- Go to the info tab of your app target settings
- In the `URL Types` section, click the `+` button to add a new entry
- Enter `auth0` into the `Identifier` field and `$(PRODUCT_BUNDLE_IDENTIFIER)` in the `URL Schemes` field. Leave other fields blank
