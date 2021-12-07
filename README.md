# Approve an Issuing authorization

This sample shows you how to integrate with Stripe [Issuing](https://stripe.com/issuing) leveraging [Real-time authorizations](https://stripe.com/docs/issuing/controls/real-time-authorizations).

# How to run locally

The Stripe CLI is the fastest way to clone and configure a sample to run locally.

## Using the Stripe CLI

If you haven't already installed the CLI, follow the installation steps. The CLI is useful for cloning samples and locally testing webhooks and Stripe integrations.

In your terminal, run the Stripe CLI command to clone the sample:

```sh
stripe samples create issuing
```

The CLI will walk you through picking your integration type, server and client
languages, and configuring your `.env` file with your Stripe API keys.

## Start the server


Pick the server language you want and follow the instructions in the server folder README on how to run.

For example, if you want to run the Node server:

```sh
cd server
npm install
npm start
```


## Start forwarding webhooks

```sh
stripe listen --forward-to "http://localhost:4242/webhook"
```

## FAQ

Q: Why did you pick these frameworks?

A: We chose the most minimal framework to convey the key Stripe calls and
concepts you need to understand. These demos are meant as an educational tool
that helps you roadmap how to integrate Stripe within your own system
independent of the framework.


## Get support

If you found a bug or want to suggest a new [feature/use case/sample], please [file an issue](../../issues).

If you have questions, comments, or need help with code, we're here to help:
- on [Discord](https://stripe.com/go/developer-chat)
- on Twitter at [@StripeDev](https://twitter.com/StripeDev)
- on Stack Overflow at the [stripe-payments](https://stackoverflow.com/tags/stripe-payments/info) tag

Sign up to [stay updated with developer news](https://go.stripe.global/dev-digest).

## Author(s)

- [@stevekaliski-stripe](https://twitter.com/stevekaliski)
- [@cjavilla-stripe](https://twitter.com/cjav_dev)

