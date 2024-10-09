---
layout: default
---

## Aurora Support

[back](./)

## Toolchains

The primary challenges on Aurora is handling the compiler wrapper
for the oneAPI compilers, in particular how they wrap MPI and SYCL.

<table class="toolchain_table">
  <thead>
    <tr>
      <th>Info</th>
      <th style="text-align: center">GCC</th>
      <th style="text-align: center">oneAPI</th>
      <th style="text-align: center">SYCL</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        Version
      </td>  <!-- Info -->
      <td style="text-align: center">v11.2.0</td>  <!-- GCC  -->
      <td style="text-align: center">v2023.0.0</td>  <!-- oneAPI -->
      <td style="text-align: center">v2023.0.0</td>  <!-- oneAPI -->
    </tr>
  </tbody>
</table>

<table class="status_table">
  <thead>
    <tr>
      <th>Project</th>
      <th style="text-align: center">GCC</th>
      <th style="text-align: center">oneAPI</th>
      <th style="text-align: center" markdown="span">oneAPI + ([SYCL](#verified_on_sunspot))</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td markdown="span">
        [Darshan][DARSHAN]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI + SYCL -->
    </tr>
    <tr>
      <td markdown="span">
        [Dynist][DYNIST]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI + SYCL -->
    </tr>
    <tr>
      <td markdown="span">
        [HPCToolkit][HPCTOOLKIT]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI + SYCL -->
    </tr>
    <tr>
      <td markdown="span">
        [PAPI][PAPI]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI + SYCL -->
    </tr>
    <tr>
      <td markdown="span">
        [TAU][TAU]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI -->
      <td class="na" style="text-align: center">N/A</td><!-- oneAPI + SYCL -->
    </tr>
  </tbody>
</table>

<p style="text-align:center; border-width:3px; border-style:solid; border-color:#4393c3; padding: 0.5em;">✅ - <b>Verified</b>&emsp;🔎 - <b>In Progress</b>&emsp;🚫 - <b>Broken</b>&emsp;N/A - <b>Not Applicable</b></p>

[back](./)

## Notes

<span id="verified_on_sunspot">**Aurora**</span> - Due to the similarity between the toolchains on Aurora and Sunspot, the results for the Aurora system are currently marked as verified as builds on Aurora progress. As issues are found on Aurora, these values will be updated to reflect the target system status.


[back](./)

[DARSHAN]: https://www.mcs.anl.gov/research/projects/darshan/
[DYNIST]: https://github.com/dyninst/dyninst
[HPCTOOLKIT]: https://hpctoolkit.org/
[PAPI]: https://icl.utk.edu/papi/
[TAU]: http://www.cs.uoregon.edu/research/tau/home.php
