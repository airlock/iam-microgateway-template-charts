# Airlock Microgateway Helm Charts

*Airlock Microgateway helps you to protect your services and APIs from unauthorized or malicious access with little effort. It is a lightweight Web Application Firewall (WAF) and API security gateway designed specifically for use in container environments.*

*Airlock IAM is a comprehensive authentication and identity management solution for web applications and services that features a high degree of customization.*

<picture>
<img alt="Airlock IAM" src="https://raw.githubusercontent.com/airlock/iam-helm-charts/main/media/Airlock_IAM_Icon.svg" align="left" width="120">
</picture>

This repository contains Helm Charts to configure Microgateway to protect Airlock IAM. This includes filtering rules to protect against OWASP Top 10 threats and OpenAPI specification enforcement to ensure that only valid requests are sent to Airlock IAM.

For more information about Airlock IAM and its respective Helm Charts, please refer to the READMEs in the respective IAM version directories.

<br/>


## Disclaimer

The Helm Charts contained in this repository are production-ready. 

## Documentation and Links

Documentation on Airlock IAM may be found at **[docs.airlock.com](https://docs.airlock.com/iam/latest/)** or the product website at **[Airlock Identity and Access Management](https://www.airlock.com/en/secure-access-hub/components/iam)**.

For setting up Airlock Microgateway 4.0 and above, please check the following repository:

* [Airlock Microgateway on Github](https://github.com/airlock/microgateway)


## Integration Example

The [Airlock IAM Helm Charts](https://github.com/airlock/iam-helm-charts) repository can be used as an example on how to integrate this Helm Chart.

## Support

If you have a paid license, please follow the [premium support process](https://techzone.ergon.ch/support-process).

# License
The Helm Charts in this repository are released under the MIT License.

For the software contained in the Airlock IAM image, please view the [license terms on the official website](https://www.airlock.com/en/airlock-license).
* Note that decompiling or reverse engineering of the software in the image is not permitted.

Airlock<sup>&#174;</sup> is a security innovation by [ergon](https://www.ergon.ch/en)

<!-- Airlock SAH Logo (different image for light/dark mode) -->
<a href="https://www.airlock.com/en/secure-access-hub/">
<picture>
    <source media="(prefers-color-scheme: dark)"
        srcset="https://raw.githubusercontent.com/airlock/iam-helm-charts/main/media/Airlock_Logo_Negative.png">
    <source media="(prefers-color-scheme: light)"
        srcset="https://raw.githubusercontent.com/airlock/iam-helm-charts/main/media/Airlock_Logo.png">
    <img alt="Airlock Secure Access Hub" src="https://raw.githubusercontent.com/airlock/iam-helm-charts/main/media/Airlock_Logo.png" width="150">
</picture>
</a>
