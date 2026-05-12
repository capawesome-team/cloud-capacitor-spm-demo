# cloud-capacitor-spm-demo

[![Capawesome](https://github.com/capawesome-team/cloud-capacitor-spm-demo/actions/workflows/capawesome.yml/badge.svg)](https://github.com/capawesome-team/cloud-capacitor-spm-demo/actions/workflows/capawesome.yml)

A demo project that shows how to build a [Capacitor](https://capacitorjs.com/) app with [Swift Package Manager (SPM)](https://www.swift.org/documentation/package-manager/) for iOS dependencies using [Capawesome Cloud](https://capawesome.io/cloud/).

## Stack

- [Capacitor](https://capacitorjs.com/) — iOS
- [Swift Package Manager](https://www.swift.org/documentation/package-manager/) — native iOS dependencies
- [npm](https://www.npmjs.com/) — package manager
- [Vite](https://vitejs.dev/) — web build

## Continuous Integration

[`.github/workflows/capawesome.yml`](.github/workflows/capawesome.yml) builds the app on every push to `main`, on pull requests, and on manual dispatch using the [Capawesome CLI](https://capawesome.io/docs/cloud/cli/).

### Required GitHub Secrets

| Secret | Description |
| --- | --- |
| `CAPAWESOME_CLOUD_TOKEN` | API token for Capawesome Cloud. |
| `CAPAWESOME_CLOUD_APP_ID` | ID of the corresponding app in Capawesome Cloud. |

## License

See [LICENSE](LICENSE).
