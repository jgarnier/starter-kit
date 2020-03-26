# Let's Encrypt

[Let's Encrypt](https://letsencrypt.org/): A nonprofit Certificate Authority providing TLS certificates to 190 million websites.
To enable HTTPS on your website, you need to get a certificate (a type of file) from a Certificate Authority (CA). Let’s Encrypt is a CA. In order to get a certificate for your website’s domain from Let’s Encrypt, you have to demonstrate control over the domain. With Let’s Encrypt, you do this using software that uses the ACME protocol which typically runs on your web host.
If you're deploying your website or server instance of services like JIRA as describe before, you will need Let's Encrypt.
To better understand how it works, see [this documentation](https://letsencrypt.org/how-it-works/).

## Using Certbot

In order to generate your certificates, you will need Let's Encrypt client which is certbot. Follow [these instructions](https://certbot.eff.org/) for installing the client.



