# qualistack

## Abstractions

| Status | Repository                                                                    | Tags                                                                                                         |
|--------|-------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| ✅     | [bumper](https://github.com/omariosouto/bumper)                               | `[base]`                                                                                                     |
| ✅     | [tsconfig](https://github.com/omariosouto/tsconfig)                           | `[base]`                                                                                                     |
| ✅     | [common-core](https://github.com/omariosouto/common-core)                     | `[base]`                                                                                                     |
| ✅     | [common-errors](https://github.com/omariosouto/common-errors)                 | `[base]`                                                                                                     |
| ✅     | [common-schema](https://github.com/omariosouto/common-schema)                 | `[peers:@omariosouto/common-core]`                                                                           |
| ✅     | [common-http-client](https://github.com/omariosouto/common-http-client)       | `[peers:@omariosouto/common-schema]`,`[peers:@omariosouto/common-errors]`,`[peers:@omariosouto/common-core]` |
| ✅     | [common-ui-web](https://github.com/omariosouto/common-ui-web)                 | `[peers:@omariosouto/common-errors]`,`[peers:@omariosouto/common-core]`                                      |
| 🚫     | [common-error-tracking](https://github.com/omariosouto/common-error-tracking) | `[peers:@omariosouto/common-errors]`,`[peers:@omariosouto/common-core]`                                      |

## Integrations
- https://github.com/omariosouto/microsaas-toolkit


## Projects using
- https://app-the-club.vercel.app/
- https://omariosouto-common-ui-web.vercel.app/
