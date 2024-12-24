# Bulent's Notes

Guidance:
https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/deploy-a-react-based-single-page-application-to-amazon-s3-and-cloudfront.html


Whitepaper:
https://docs.aws.amazon.com/whitepapers/latest/serverless-multi-tier-architectures-api-gateway-lambda/single-page-application.html

Delete the lock files before running "npm install" and "yarn install".



To run locally, also install yarn:

```zsh
# Corepack is shipped with Node.js
corepack enable

# Update the global Yarn version
corepack prepare yarn@stable --activate

# Move into your project folder
yarn set version stable #latest stable version
yarn install

# Run the scripts in package.json, e.g. 
yarn dev
```

Clean up the resources as described [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/deploy-a-react-based-single-page-application-to-amazon-s3-and-cloudfront.html)

