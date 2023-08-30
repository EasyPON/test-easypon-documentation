# 🍥 Guide for Debian 11

1. Register an account in the EasyPON personal cabinet [https://cabinet.easypon.in/login](https://cabinet.easypon.in/login)
2. Login to your EasyPON personal cabinet account, and choose the existing license or add a new license instance.
3. Download the distribution archive of the latest Easypon version from your license.
4. Install or upgrade EasyPON To install EasyPon, run the following command in your terminal:

{% code fullWidth="false" %}
```
apt update && apt install curl -y
```
{% endcode %}

```
bash <(curl -k https://cabinet.easypon.in/install_ep.sh) install
```

The installation process will prompt you for various configuration options, such as your domain name and login password for the EasyPon cabinet. App will be installed in \`/usr/apps/easypon\`

### Accessing EasyPon

To access EasyPon, open your browser and navigate to your domain name or IP address of your server. You will be prompted to log in with your credentials, which you received in the terminal during installation, or which can be found in \`/root/.tmp\_ep\_users\`.
