---
layout: default
---

## Aurora Support

[back](./)

## Toolchains

One of the primary challenges on Frontier is handling the compiler wrappers
for the CCE and AMD compilers, in particular how they wrap MPI and HIP.

<table class="toolchain_table">
  <thead>
    <tr>
      <th>Info</th>
      <th style="text-align: center">GCC</th>
      <th style="text-align: center">CCE</th>
      <th style="text-align: center">AMD</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        Version
      </td>  <!-- Info -->
      <td style="text-align: center">v11.2</td>  <!-- GCC -->
      <td style="text-align: center">v15.0.0</td>  <!-- CCE -->
      <td style="text-align: center">v5.3.0</td>  <!-- AMD -->
    </tr>
    <tr>
      <td>
        Cray MPICH
      </td>  <!-- Info -->
      <td style="text-align: center">v8.1.23</td>  <!-- GCC -->
      <td style="text-align: center">v8.1.23</td>  <!-- CCE -->
      <td style="text-align: center">v8.1.23</td>  <!-- AMD -->
    </tr>
    <tr>
      <td>
        ROCm
      </td>  <!-- Info -->
      <td style="text-align: center">v5.3.0</td>  <!-- GCC -->
      <td style="text-align: center">v5.3.0</td>  <!-- CCE -->
      <td style="text-align: center">v5.3.0</td>  <!-- AMD -->
    </tr>
  </tbody>
</table>

<table class="status_table">
  <thead>
    <tr>
      <th>Project</th>
      <th style="text-align: center">GCC</th>
      <th style="text-align: center">GCC + ROCm</th>
      <th style="text-align: center">CCE</th>
      <th style="text-align: center">CCE + ROCm</th>
      <th style="text-align: center">AMD</th>
      <th style="text-align: center">AMD + ROCm</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td markdown="span">
        [Darshan][DARSHAN]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD + ROCm -->
    </tr>
    <tr>
      <td markdown="span">
        [Dynist][DYNIST]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD + ROCm -->
    </tr>
    <tr>
      <td markdown="span">
        [HPCToolkit][HPCTOOLKIT]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD + ROCm -->
    </tr>
    <tr>
      <td markdown="span">
        [PAPI][PAPI]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD + ROCm -->
    </tr>
    <tr>
      <td markdown="span">
        [TAU][TAU]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE -->
      <td class="na" style="text-align: center">N/A</td><!-- CCE + ROCm -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD -->
      <td class="na" style="text-align: center">N/A</td><!-- AMD + ROCm -->
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
