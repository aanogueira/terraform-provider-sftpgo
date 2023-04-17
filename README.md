# Terraform Provider SFTPGo

[![CI Status](https://github.com/drakkan/terraform-provider-sftpgo/workflows/CI/badge.svg?branch=main&event=push)](https://github.com/drakkan/terraform-provider-sftpgo/workflows/CI/badge.svg?branch=main&event=push)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Terraform Registry: https://registry.terraform.io/providers/drakkan/sftpgo

This provider is a bridge between Terraform and the [SFTPGo](https://github.com/drakkan/sftpgo) API.
Terraform objects have slightly different structures than the ones defined in the SFTPGo REST API, refer to the documentation for more details.

You can find some usage examples [here](./examples).

Please note that this provider is experimental, I'm not happy with its code, if you have experience using the [terraform-plugin-framework](https://github.com/hashicorp/terraform-plugin-framework) any help to improve the provider is appreciated. Thank you.
