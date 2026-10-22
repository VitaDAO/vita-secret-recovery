# Temporary Vita credential migration configuration

This measured, non-debug workload exists only to recover selected existing Vita environment credentials for the authorized Phala migration. It returns only an encrypted envelope to a fixed owner-controlled recipient public key. The private key is never stored here. No production application, patient data, database access, or outbound network is involved. Existing Tinfoil instances remain unchanged.

The image is immutable, the recovery code and recipient public key are measured in the configuration, and client acceptance requires fresh attestation against this repository and exact release. A public endpoint cannot decrypt the envelope. Retire the temporary instance after verified secure recovery.
