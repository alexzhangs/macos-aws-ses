# macos-aws-ses

## **This project is depracated and the feature is moved to project xsh-lib/aws, and can be called as xsh ses/ec2/setup.**

Setup sendmail to use AWS SES Service send Email on macOS.

Tested on macOS High Sierra.

## Installation

```
git clone https://github.com/alexzhangs/macos-aws-ses
sudo sh macos-aws-ses/install.sh
```

## Usage

macos-aws-ses-setup needs to be run under root.

```
macos-aws-ses-setup
	-d SES_DOMAIN
	-r REGION
	-u SMTP_USERNAME
	-p SMTP_PASSWORD
	[-t TEST_EMAIL_SEND_TO]
	[-h]

OPTIONS
	-d SES_DOMAIN

	Domain setup in AWS SES.

	-r REGION

	AWS Region used by SES.

	-u SMTP_USERNAME

	Username of AWS SES SMTP.

	-p SMTP_PASSWORD

	Username of AWS SES SMTP.

	[-t TEST_EMAIL_SEND_TO]

	An Email address to test this setup.

	[-h]

	This help.
```
