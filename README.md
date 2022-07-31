# Shopify Github connection

This repo contains dev explorations into Shopify theme support through cli.

## Workaround for developing in AWS Cloud9 environment

Copy the failed localhost link, and paste the command in a new Cloud9 terminal:

wget 'http://127.0.0.1:3456/?code=XXXXX&state=YYYYY'

Do not forget the single quotes around the link to prevent & from executing as a background process operator.

### Reference
https://blog.klaudsol.com/how-to-run-shopify-cli-in-aws-cloud-9/