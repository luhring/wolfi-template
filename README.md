# template

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/chainguard-images/template/actions/workflows/release.yaml/badge.svg)](https://github.com/chainguard-images/template/actions/workflows/release.yaml)

WORK IN PROGRESS

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/template:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `latest` | `sha256:7962922080117896a9ae4dbb40e3facd672f19e3eaad7b7bfee1ac601f95aee2`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7962922080117896a9ae4dbb40e3facd672f19e3eaad7b7bfee1ac601f95aee2) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


## Usage

WORK IN PROGRESS


## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/template:latest | jq
```

Output:
```
Verification for cgr.dev/chainguard/template:latest --
The following checks were performed on each of these signatures:
  - The cosign claims were validated
  - Existence of the claims in the transparency log was verified offline
  - Any certificates were verified against the Fulcio roots.
[
  {
    "critical": {
      "identity": {
        "docker-reference": "ghcr.io/chainguard-images/template"
      },
      "image": {
        "docker-manifest-digest": "sha256:7962922080117896a9ae4dbb40e3facd672f19e3eaad7b7bfee1ac601f95aee2"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "a241d8c8a71a952677a047f3cb0bf020824bec28",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIH5idOERNn8bniyi/QYe2zdeFSWfdf29muMyB9mOfaukAiBHglunpfv9/GPvYa0YQHwVHIRIu3n5cmii505mwtIb9g==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI4MTEwMTVlMTAyOGFmMjFkNTY4NDRhYjFiMjkzN2YxZTI4OWY1ZTU3Njk3MTA0NDEzNWNhN2ZhZTMxYjdjYTI2In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUUMzbXNEMnkrTDlHaWo4QXlLZjYrYVNjYXNuSysyLzZKMTVxcWwrMGtuaTVRSWhBTlJ5a0thcTY2SGFISmg3Q2YxL2NGaXdCQXJmY3JNNkErVjR2S0ZzTUFJQyIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwaFowRjNTVUpCWjBsVlMxRnlVM3AzVVM5QlRtODFhMGwyVG5ad1Z6ZDBNWE5xWVdJMGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFU1hkTlJFa3dUWHBOTVZkb1kwNU5ha2w0VFVSSmQwMUVTVEZOZWsweFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZoZFVSbFFUWldVV0YyTVVoR1ExVkdZalZwUW1zd05FTTBWR2M0T1RaWVlVSkpZMFFLYWtKNlJHOHJaWE5aVFVNMWVUZ3piVUpIYVVvcmJqTnpWRTVTY0ZSemQyWTNVa05tVlRoT2NqbEZibGh4U3pabVdtRlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlV4WlN0R0NtMHJaMWx6VnpaeFJreDJZbXROTldsS0wzaFRNVTlWZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdoTmFsRjRXa1JvYWs5SFJUTk5WMFUxVGxSSk1rNTZaR2hOUkZFeldtcE9hbGxxUW1sYWFrRjVDazFFWjNsT1IwcHNXWHBKTkUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtY3ZUa2RWTXpCQlFVRlJSRUZGWjNkU1owbG9RVTV3TldSYVdqSUtUbEpuYlcwNUwzZ3hWVXRZUVZwdk1uQkpOVTVCVFVaWmNXdDZZbWMwZG1oWVFrVktRV2xGUVRWNU1rWkNObGhzVFc5QllXUjBWVGx1VUdjM1JDODFOUXB2Wm1KMmRVZ3JOREJHUWpkRVpsbEJjRVJCZDBObldVbExiMXBKZW1vd1JVRjNUVVJhZDBGM1drRkpkMkZFZFRaMWRHbEhOMVJ2UjBWNVZHWlBRMmRFQ25aeGVUWmFTMWRVTTNCeGFtdFdNM0JHTjNSNGFtWldlSEpLTkhobFZYTklRakp0ZDJkamEyd3JlVmRXUVdwQ05XZ3dNMGt3WVZOelJqUnZNMjE0Tm5nS1pIZHllVE41VkhWdFIyNVNjekZsWkVORVYxbDJRMjR6WXpGaE5pODJja00yYUdJeGVVZFJMMk54TDFkUWMyTTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1666233837,
          "logIndex": 5469895,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "a241d8c8a71a952677a047f3cb0bf020824bec28",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3286434655",
      "sha": "a241d8c8a71a952677a047f3cb0bf020824bec28"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

