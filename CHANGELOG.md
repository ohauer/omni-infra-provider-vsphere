## [omni-infra-provider-vsphere 0.1.0-alpha.1](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/releases/tag/v0.1.0-alpha.1) (2026-03-06)

Welcome to the v0.1.0-alpha.1 release of omni-infra-provider-vsphere!  
*This is a pre-release of omni-infra-provider-vsphere*



Please try out the release binaries and report any issues at
https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/issues.

### Contributors

* Olli Hauer
* Spencer Smith
* Fritz Schaal
* Kevin Tijssen
* Paul Verhoeven

### Changes
<details><summary>12 commits</summary>
<p>

* [`382ebcb`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/382ebcbc27449263535fe4e5c795dab924aa61d3) chore: update machinery and use standard patching for CA certs
* [`bd32c4a`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/bd32c4af4199e1f2c134946cad3571b244f9f8f1) feat: support root CA injection, support only Talos >= v1.12
* [`be84955`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/be84955670128ea659d10fe7aaf7344e1a78206f) chore: rekres and fix config patch naming
* [`f004d94`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/f004d94e481a643c41b79c17100e29bf25255f64) chore: fix hostname setting for created VMs
* [`a0c3ffa`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/a0c3ffa866eec6b8fa6dc43150825c11d54cf77d) feat: add optional folder parameter for VM placement
* [`a336fb7`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/a336fb78115ba3ffeddfeaacd017f6d00aa639d9) fix: improve vSphere session keepalive with active SOAP handler
* [`e16143d`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/e16143dad22e34af412fb01bef9e07316db3c85f) fix: improve error handling and add config validation
* [`a8a039c`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/a8a039cb499e2e8802af509471e5486948c4a5fb) feat: implement network configuration for VM provisioning
* [`4070104`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/4070104306d301cfc4e9530a33baee7e0f081374) feat: implement disk resizing for VM provisioning
* [`36478f5`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/36478f5b935986def37189ea068a2eccbd78be2c) fix: add vSphere session keep-alive and reconnection logic
* [`66e937c`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/66e937c387062f0734b9e4a0a5547f85f2fd09f6) chore: fix typo in readme
* [`cd92dd7`](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/commit/cd92dd7c8678b0b8419b19e1b573b6a40e5e3ab2) fix: properly handle unset datacenter on node deprovision
</p>
</details>

### Dependency Changes

* **github.com/cosi-project/runtime**            v1.12.0 -> v1.13.0
* **github.com/planetscale/vtprotobuf**          79df5c4772f2 -> ba97887b0a25
* **github.com/siderolabs/omni/client**          3244ac4f41f5 -> v1.5.0
* **github.com/siderolabs/talos/pkg/machinery**  10f49ca91a61 **_new_**
* **github.com/spf13/cobra**                     v1.10.1 -> v1.10.2
* **go.uber.org/zap**                            v1.27.0 -> v1.27.1
* **google.golang.org/protobuf**                 v1.36.10 -> f2248ac996af

Previous release can be found at [v0.1.0-alpha.0](https://github.com/https://github.com/siderolabs/omni-infra-provider-vsphere/releases/tag/v0.1.0-alpha.0)

## [ 0.1.0-alpha.0](https://github.com///releases/tag/v0.1.0-alpha.0) (2025-11-05)

Welcome to the v0.1.0-alpha.0 release of !



Please try out the release binaries and report any issues at
https://github.com///issues.

### Contributors

* Spencer Smith

### Changes
<details><summary>1 commit</summary>
<p>

* [`45ade1c`](https://github.com///commit/45ade1ca017bf37438ed07d793a5ca5204d92ef6) feat: initial commit of working vsphere provider
</p>
</details>

### Dependency Changes

This release has no dependency changes

