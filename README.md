# WeChat runtime releases

Public download channel for the WeChat runtime. This repository contains distribution documentation only. Implementation source and build logs are maintained separately.

## Downloads

Use the [Releases page](https://github.com/wuyouMaster/wechat-runtime-releases/releases). A release is usable only after its assets have been published; an empty repository is not an available runtime.

Each version provides:

- `wechat-runtime-<version>-<platform>-<arch>.zip`
- the matching `.zip.manifest.json`
- the matching `.zip.sha256`

Choose the exact version and platform supported by your application, and verify the checksums before installation. Development previews are identified as prereleases and are not signed/notarized production installers. Capability and validation limits are recorded per release.

Release downloads are public and do not require a client access token. Downloading a runtime does not sign in to an account or send messages.

GitHub's automatically generated Source code archives contain only this distribution repository's documentation, not the runtime implementation. Public binary availability does not itself grant an open-source license; refer to the notices and terms accompanying each release.
