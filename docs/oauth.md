---
sidebar_position: 8
sidebar_label: "OAuth Setup"
---

# OAuth

The only things needed to give your users EVM accounts on any network, and integrate with Keyp is:

1. An OAuth2 server
2. An App ID from Keyp

We use extremely standard industry tools to improve the developer experience. If there is another way you would like to access Keyp logins, please contact us.

## Redwood OAuth

[Redwood](https://redwoodjs.com/) is a javascript framework that uses the same kind of code on the front end as the back end. We love them.

Keyp has open sourced a Redwood implementation of a standard OAuth2 server, which you can use to add Keyp logins to your app: https://www.npmjs.com/package/oauth2-server-redwood

## Passportjs

For React apps, we suggest you follow the Passport docs: https://www.passportjs.org/concepts/authentication/oauth/

# Apps without Backends

Your app might be built without a backend, and just built on top of smart contracts, like [Juicebox](https://juicebox.money) for example. This makes it more complicated to create logins, because you have no OAuth server running to verify your users are who they say they are. We're currently exploring some solutions for this. If your app has no backend, please reach out to us and we can talk about the additional security implications required for the integration.

<hr>
Other wallet integrations coming soon.
