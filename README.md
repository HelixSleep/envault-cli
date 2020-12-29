# Envault CLI

[Envault](https://github.com/envault/envault) is a repository for your .env secrets. It lets you manage and sync your entire team’s local .env variables across all your projects, so you’re all kept up to date with the latest changes. Simply install your Envault server and you're ready to sync. 🚀

The Envault CLI allows you to connect to your Envault server and sync its credentials to your local .env file.

## Usage

To use the Envault CLI, you must have [Node.js](https://nodejs.org/) installed on your computer.

On your Envault dashboard, you will find a setup command for each app, which you can run to establish a connection to your Envault server, and sync your local .env. This command only needs to be run the first time you connect your .env to Envault. An example setup command:

```
npx envault vault.envault.dev 84632 iCNaGGLou6v0mRas
```

After you've run your app setup command for the first time, you can sync your .env again easily:

```
npx envault
```

## Need Help?

🐞 If you spot a bug with Envault, please [submit a detailed issue](https://github.com/envault/envault/issues/new), and wait for assistance.

🤔 If you have a question or feature request, please [start a new discussion](https://github.com/envault/envault/discussions/new).

🔐 If you discover a vulnerability within Envault, please review our [security policy](https://github.com/envault/cli/blob/master/SECURITY.md).
