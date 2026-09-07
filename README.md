# FlowCense Windows Agent releases

This public repository distributes compiled FlowCense Windows Agent update artifacts. The application source code and development history are maintained in a separate private repository and are not included here.

Normal Git history contains only update metadata, its detached signatures, schema, and these public instructions. Versioned binaries are attached to GitHub Releases. They are intended for installed FlowCense clients and authorized manual repair.

FlowCense executables and installers are currently Authenticode-unsigned. Windows can therefore display **Unknown Publisher**, including at an administrator/UAC prompt. Update authorization comes from the separately signed release manifest; the unsigned status is intentional and must not be mistaken for publisher identity.

Do not post secrets, credentials, customer data, or suspected signing-key material in a public issue. Follow [SECURITY.md](SECURITY.md) for private security reporting.
