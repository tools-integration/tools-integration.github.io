---
layout: default
---

## TOOLS-SDK

[back](../)

### Description

The tools (TOOLS) software development kit (SDK), or TOOLS SDK, is an integration effort for a collection of software packages used to monitor, analyze, and diagnose the performance and behavior of computational science applications and systems software developed under the Department of Energy (DOE) Advanced Scientific Computing Research (ASCR). The software products target using Spack, an HPC-targeted source-based package manager, for deployment on HPC platforms and beyond. The primary product of this project is the toolssdk Spack meta-package which builds a set of TOOLS SDK member packages together in a way that enables optimal features for target environments as well as interoperable features provided by other packages within the TOOLS SDK. The TOOLS SDK is an outcome of the work within the DOE STEP project and is sustained and advanced by the DOE PESO project.

### Impact, Sustainability, and Quality

<table class="isq_table">
  <thead>
    <tr>
      <th>Property</th>
      <th style="text-align: center">State</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <strong>Impact</strong>
      </td>
      <td>
        We designed the TOOLS-SDK Spack meta-package to build and deploy a collection of TOOLS SDK member packages, including Darshan, Dyninst, HPCToolkit, PAPI, and TAU. This capability enables optimal features for specific environments and facilitates interoperability with other packages within the TOOLS SDK.
      </td>
    </tr>
    <tr>
      <td>
        <strong>Sustainability</strong>
      </td>
      <td>
        We established the fundamental capabilities of TOOLS-SDK as a Spack meta-package. The ongoing support and development of these capabilities in updated or new systems and their application in evolving or new high-performance computing systems rely heavily on funding from the Department of Energy (DOE).
      </td>
    </tr>
    <tr>
      <td>
        <strong>Quality</strong>
      </td>
      <td>
        The TOOLS-SDK, while still in its early stages, benefits from quality assurance provided by Spack and the continuous integration and testing of member packages such as Darshan, Dyninst, HPCToolkit, PAPI, and TAU.
      </td>
    </tr>
  </tbody>
</table>

### Software Quality Characteristics

<table class="status_table">
  <thead>
    <tr>
      <th style="text-align: center">Website</th>
      <th style="text-align: center">Documentation</th>
      <th style="text-align: center">Repository</th>
      <th style="text-align: center">Test Suite</th>
      <th style="text-align: center">Spack</th>
      <th style="text-align: center">E4S</th>
      <th style="text-align: center">Smoke Test</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td markdown="span">
        [Website][TOOLS-SDK]
      </td><!-- Website -->
      <td style="text-align: center" markdown="span">🚫</td><!-- Documentation -->
      <td markdown="span">
        [Repository][TOOLS-SDK-REPO]
      </td><!-- Repository -->
      <td style="text-align: center" markdown="span">🚫</td><!-- Test Suite -->
      <td style="text-align: center" markdown="span">🚫</td><!-- Spack -->
      <td style="text-align: center" markdown="span">🚫</td><!-- E4S -->
      <td style="text-align: center" markdown="span">🚫</td><!-- Smoke Test -->
    </tr>
  </tbody>
</table>

**Note**: Working with the STEP leadership to refine metrics and identify methods to demonstrate how project efforts lead to measurable increases in software quality.

[back](../)

[TOOLS-SDK]: https://tools-integration.github.io/
[TOOLS-SDK-REPO]: https://github.com/tools-integration/
