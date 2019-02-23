# pochi

This code is only tested on macOS and python3.7!!!

## Dependencies

```bash
pip3 install --upgrade --user google-api-python-client google-auth-httplib2 google-auth-oauthlib
```

## How to use

First of all, you have to get a valid creadential file ( creadentials.json ) from Google. \
<https://developers.google.com/gmail/api/quickstart/python>

You write email_list.txt, body.txt and subject.txt, then run the follows:

```bash
python3 quickstart.py --body examples/body.txt --subject examples/subject.txt --email_list examples/email_list.txt
```