# Setup Amazon S3 Upload Provider Plugin in Strapi
Code container for the tutorial: [How to Setup Amazon S3 Upload Provider Plugin for your Strapi App](https://strapi.io/blog/how-to-set-up-amazon-s3-upload-provider-plugin-for-our-strapi-app)

## Prerequisites

- Node v14.x.x up to Node v18.x.x (LTS)
- Git
- AWS Account

## Getting Started

- Clone the repo
```bash
git clone https://github.com/Marktawa/strapi-aws-s3.git
```

- Change directory
```bash
cd strapi-aws-s3
```

## Strapi Setup

Install the dependencies
```bash
npm install
```

Edit `.env` file with your AWS Credentials
```js
AWS_ACCESS_KEY_ID=<Access Key ID>
AWS_ACCESS_SECRET=<Secret access key>
AWS_REGION=<region>
AWS_BUCKET=<s3-bucket-name>
```

Build Strapi app
```bash
npm run build
```

Run Strapi app
```bash
npm run develop
```

## Authors

- [Mark Tawanda Munyaka](https://github.com/Marktawa)

## Extra

- You are welcome to make [issues and feature requests](https://github.com/Marktawa/strapi-aws-s3/issues).
