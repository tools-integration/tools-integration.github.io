---
layout: default
---

## ERT (Empirical Roofline Tool)

[back](../scorecards.html)

### Description

ERT (Empirical Roofline Tools) is a tool using "micro-kernels" to determine
machine charateristics (CPU or GPU-accelerated) for generating roofline model data
for a given computer.

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
        Why is it important to DOE ASCR and others?
      </td>
    </tr>
    <tr>
      <td>
        <strong>Sustainability</strong>
      </td>
      <td>
        How are advancements and maintenance funded? How stable is the funding?
      </td>
    </tr>
    <tr>
      <td>
        <strong>Quality</strong>
      </td>
      <td>
        Based on E4S Community Policies (https://e4s-project.github.io/policies.html), Describe the activities and level of software quality mautrity.
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
        [Website][ERT]
      </td><!-- Website -->
      <td markdown="span">
        [Documentation][ERT-DOC]
      </td><!-- Documentation -->
      <td markdown="span">
        [Repository][ERT-REPO]
      </td><!-- Repository -->
      <td style="text-align: center" markdown="span">🚫</td><!-- Test Suite -->
      <td markdown="span">
        [Spack 🚫][ERT-Spack]
      </td><!-- Spack -->
      <td style="text-align: center" markdown="span">🚫</td><!-- E4S -->
      <td style="text-align: center" markdown="span">🚫</td><!-- Smoke Test -->
    </tr>
  </tbody>
</table>

**Note**: Working with the STEP leadership to refine metrics and identify methods to demonstrate how project efforts lead to measurable increases in software quality.

[back](../scorecards.html)

[ERT]: https://crd.lbl.gov/divisions/amcr/computer-science-amcr/par/research/roofline/software/ert/
[ERT-DOC]: https://crd.lbl.gov/divisions/amcr/computer-science-amcr/par/research/roofline/software/ert/
[ERT-REPO]: https://bitbucket.org/berkeleylab/cs-roofline-toolkit/src/master/
[ERT-Spack]: https://github.com/spack/spack/pull/48913
