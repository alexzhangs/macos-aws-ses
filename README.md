# macos-aws-ses

Setup sendmail to use AWS SES Service send Email on MacOS.
Tested on Mac OS X 10.11.

# Installation

```
git clone https://github.com/alexzhangs/macos-aws-ses
sudo sh macos-aws-ses/install.sh
```

# Usage

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
