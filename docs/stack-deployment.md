# Deployment

**Deployment is to copy the Moodle pre-packaged online to your Cloud Server**. For example, after the user subscribe Moodle on the Cloud Platform, the Platform will automatically copy the Moodle to the corresponding Cloud Server.

- If Moodle has been deployed, go to [Initial Installation](/zh/stack-installation.md) to complete the operation.
- If Moodle is not deployed, you need to deploy Moodle to your cloud server first.

We offer two deployment Moodle scenarios (the deployment results are the same):

## Deploy by Image

**Deploy by Image** means starting instance from Moodle images. **Moodle Image** provide OS and software environment needed for Moodle.

For users with experience with cloud servers, Deploy by Image equated with "one-click deployment".

Websoft9 published [Moodle image](https://apps.websoft9.com/moodle) on Cloud Platform, three methods for your deployment:

* When **Create New Instance** , select the Moodle image as the system boot template.
* When **Subscribe Moodle** on Marketplace, the system will promote you to create a new instance for this image at the same time.
* When **Re-install OS** for you instance, you can replace the existing image with a Moodle image.

## Deploy by Script

**Deploy by Script** means running a script on your cloud instance to pull the pre-packages online to your instance and configure it at the same time.

Websoft9 provide the [Moodle ansbile automation script](https://github.com/Websoft9/ansible-moodle) on Github. If you are familiar with Ansible, you can deploy the Moodle to the instance automaticly.

## Comparison

Although the results of the **deploy by image** are consistent with the results of **deploy by script**, what is the difference between the two deployment methods?

Suggest you read the document [Deploy by Image vs Deploy by Script](https://support.websoft9.com/docs/faq/bz-product.html#deployment-comparison)