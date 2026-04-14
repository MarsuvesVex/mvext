# mvext

A fork of [tsgg](https://github.com/strims/tsgg), the terminal client for Strims.gg.

This fork targets my current chat stack and is built around the **v2 chat deployment**, which uses the **Go backend** rather than the older Node.js backend.

## Compatibility

This project expects:

- **v2 chat** to be deployed
- the **Go chat backend** to be running

It is **not** aimed at older deployments that still use the legacy Node.js backend, and compatibility with those setups is not guaranteed.

## Notes

The codebase began as `tsgg` and has been adjusted to fit my own infrastructure and workflow.



# tsgg
sgg chat in the terminal

![](.github/tsgg.png)

`cp sample-config.toml config.toml`
`go build`
