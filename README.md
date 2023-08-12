[![Build NGINX Unit with PHP Support](https://github.com/uhlhosting/Unit-PHP/actions/workflows/build.yml/badge.svg)](https://github.com/uhlhosting/Unit-PHP/actions/workflows/build.yml)
# NGINX Unit with PHP and NJS Support

This repository contains the build configuration for NGINX Unit with support for multiple PHP versions and NJS (NGINX JavaScript). It utilizes GitLab CI/CD to automate the build process and produces separate binaries for each specified PHP version.

## Supported PHP Versions

- PHP 7.0
- PHP 7.4
- PHP 8.0
- PHP 8.1
- PHP 8.2

## Features

- **NJS Support**: Enables the use of njs scripts in the NGINX Unit configuration.
- **Multiple PHP Versions**: Provides a separate NGINX Unit build for each supported PHP version.
- **Automated Builds**: Utilizes GitLab CI/CD for automated building and testing.

## Building

The build process is handled through GitLab CI/CD and defined in the `.gitlab-ci.yml` file. Each PHP version has a separate build job that configures and compiles NGINX Unit with the corresponding PHP version and NJS support.

### Dependencies

The build process requires the following dependencies:

- Build tools (build-essential)
- PHP development libraries (libphp*-embed)
- OpenSSL development library (libssl-dev)
- PCRE2 development library (libpcre2-dev)
- NJS

## Usage

The built NGINX Unit binaries are available as artifacts in GitLab and can be downloaded for deployment. Refer to the NGINX Unit documentation for instructions on deploying and configuring NGINX Unit with your applications.

## Contributing

Feel free to submit issues or pull requests if you have suggestions, improvements, or bug fixes.

## License

Please refer to the license file for details on the project's licensing.

## Contact

For any questions or support, please contact the repository maintainers.
