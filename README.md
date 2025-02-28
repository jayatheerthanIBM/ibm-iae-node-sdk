[![Build Status](https://travis-ci.org/IBM/ibm-iae-node-sdk.svg?branch=master)](https://travis-ci.org/IBM/ibm-iae-node-sdk)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
# IBM Cloud Analytics Engine Node.js SDK
Node.js client library to interact with various [IBM Analytics Engine APIs](https://cloud.ibm.com/apidocs/ibm-analytics-engine).

## Table of Contents

<!--
  The TOC below is generated using the `markdown-toc` node package.

      https://github.com/jonschlinkert/markdown-toc

  You should regenerate the TOC after making changes to this file.

      npx markdown-toc -i README.md
  -->

<!-- toc -->

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Using the SDK](#using-the-sdk)
- [Questions](#questions)
- [Issues](#issues)
- [Open source @ IBM](#open-source--ibm)
- [Contributing](#contributing)
- [License](#license)

<!-- tocstop -->

<!-- --------------------------------------------------------------- -->
## Overview

The IBM Cloud iaesdk Node.js SDK allows developers to programmatically interact with the following 
IBM Cloud services:

Service Name | Import Path
--- | --- 
[IBM Analytics Engine](https://cloud.ibm.com/apidocs/ibm-analytics-engine) | iaesdk/ibm-analytics-engine-api/v2

## Prerequisites
* You need an [IBM Cloud][ibm-cloud-onboarding] account.
* **Node.js >=12**: This SDK is tested with Node.js versions 12 and up. It may work on previous versions but this is not officially supported.

[ibm-cloud-onboarding]: http://cloud.ibm.com/registration

## Installation

```sh
npm install iaesdk
```

## Using the SDK
For general SDK usage information, please see [this link](https://github.com/IBM/ibm-cloud-sdk-common/blob/master/README.md)

In [setting client options programatically](https://github.com/IBM/ibm-cloud-sdk-common/blob/master/README.md#setting-client-options-programmatically) to instantiate the class, provide the following two values:
1. [IAM API Key](https://cloud.ibm.com/docs/iam?topic=iam-userapikey#create_user_key)
1. [Service URLs](https://cloud.ibm.com/apidocs/ibm-analytics-engine#service-endpoints)

## Questions

If you are having difficulties using this SDK or have a question about the IBM Cloud services,
please ask a question at [dW Answers](https://developer.ibm.com/answers/questions/ask/?topics=ibm-cloud) or
[Stack Overflow](http://stackoverflow.com/questions/ask?tags=ibm-cloud).

## Issues
If you encounter an issue with the SDK, you are welcome to submit
a [bug report](https://github.com/IBM/ibm-iae-node-sdk/issues).
Before that, please search for similar issues. It's possible someone has
already encountered this issue.

## Open source @ IBM
Find more open source projects on the [IBM Github Page](http://ibm.github.io/)

## Contributing
See [CONTRIBUTING](CONTRIBUTING.md).

## License

This project is released under the Apache 2.0 license.
The license's full text can be found in
[LICENSE](LICENSE).
