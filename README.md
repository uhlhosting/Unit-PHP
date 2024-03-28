[![Build NGINX Unit with PHP Support](https://github.com/uhlhosting/Unit-PHP/actions/workflows/build.yml/badge.svg)](https://github.com/uhlhosting/Unit-PHP/actions/workflows/build.yml)
# NGINX Unit with PHP Support

This repository contains the build configuration for [NGINX Unit](https://unit.nginx.org) with support for multiple PHP versions. It utilizes GitHub Actions for automated building and testing, producing separate Debian packages for each specified PHP version.

## Supported PHP Versions

- PHP 7.4
- PHP 8.0
- PHP 8.1
- PHP 8.2
- PHP 8.3

You can find the detailed support matrix in the [official NGINX Unit documentation](https://unit.nginx.org/configuration/#php).

## Features

- **Multiple PHP Versions**: Provides a separate NGINX Unit build for each supported PHP version, allowing seamless integration with various PHP-based applications.
- **Automated Builds**: Utilizes GitHub Actions for automated building, testing, and deployment, ensuring consistent and up-to-date packages.

## Building

The build process is handled through GitHub Actions and defined in the `build.yml` file. Each PHP version has a separate build job that configures and compiles NGINX Unit with the corresponding PHP support.

### Dependencies

The build process requires the following dependencies:

- Build tools (build-essential)
- PHP development libraries (libphp*-embed)
- OpenSSL development library (libssl-dev)
- PCRE2 development library (libpcre2-dev)

## Usage

The built NGINX Unit packages are available as GitHub releases and can be [downloaded from here](https://github.com/uhlhosting/Unit-PHP/releases). Refer to the [official NGINX Unit documentation](https://unit.nginx.org/installation/) for instructions on deploying and configuring NGINX Unit with your PHP applications.

## License

Please refer to the [LICENSE file](LICENSE) for details on the project's licensing.

## Community

- The go-to place to start asking questions and share your thoughts is
  our [Slack channel](https://community.nginx.org/joinslack).

- Our [GitHub issues page](https://github.com/uhlhosting/Unit-PHP/issues) offers
  space for a more technical discussion at your own pace.

- The [project map](https://github.com/orgs/nginx/projects/1) on
  GitHub sheds some light on our current work and plans for the future.

- Our [official website](https://unit.nginx.org/) may provide answers
  not easily found otherwise.

- Get involved with the project by contributing! See the
  [contributing guide](CONTRIBUTING.md) for details.

- To reach the team directly, subscribe to the
  [mailing list](https://mailman.nginx.org/mailman/listinfo/unit).

- For security issues, [email us](security-alert@nginx.org), mentioning
  NGINX Unit in the subject and following the [CVSS
  v3.1](https://www.first.org/cvss/v3.1/specification-document) spec.

## Additional Resources

- [NGINX Unit Official Website](https://unit.nginx.org)
- [NGINX Unit Configuration Guide](https://unit.nginx.org/configuration/)
- [PHP Language Module for NGINX Unit](https://unit.nginx.org/configuration/#php)
