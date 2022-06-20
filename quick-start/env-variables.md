# Env variables

For running locally create a file called `.env.local` and fill it with the following default parameters (or replace with your own values):

| Variable Name                         | Required? | Description                                                                                   |
| ------------------------------------- | :-------: | --------------------------------------------------------------------------------------------- |
| **AW\_WEB\_STORAGE\_API\_KEY**        |    yes    | obtain your own api key on [web3.storage ](https://web3.storage/).                            |
| **NEXT\_PUBLIC\_CHAIN\_TYPE**         |    yes    | set to `mainnet` or `testnet` to indicate which chain to use by default.                      |
| **NEXT\_PUBLIC\_GA\_MEASUREMENT\_ID** |     no    | a tag value for Google Analytics tracking. For local dev purposes you can skip it completely. |
| **NEXT\_PUBLIC\_SENTRY\_DSN**         |     no    | a tag value for Sentry error tracking. For local dev purposes you can skip it completely.     |
