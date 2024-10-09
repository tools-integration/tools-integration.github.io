---
layout: default
---

## Aurora Support

[back](./)

## Toolchains


One of the primary challenges on Perlmutter is handling the compiler wrapper
for the NVHPC compilers, in particular how they wrap MPI and CUDA.

<table class="toolchain_table">
  <thead>
    <tr>
      <th>Info</th>
      <th style="text-align: center">GCC Toolchain</th>
      <th style="text-align: center">NVHPC Toolchain</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        Version
      </td>  <!-- Info -->
      <td style="text-align: center">v11.2</td>  <!-- GCC Toolchain -->
      <td style="text-align: center">v22.4</td>  <!-- NVHPC Toolchain -->
    </tr>
    <tr>
      <td>
        Cray MPICH
      </td>  <!-- Info -->
      <td style="text-align: center">v8.2.3</td>  <!-- GCC Toolchain -->
      <td style="text-align: center">v8.2.3</td>  <!-- NVHPC Toolchain -->
    </tr>
    <tr>
      <td>
        CUDA
      </td>  <!-- Info -->
      <td style="text-align: center">v11.3</td>  <!-- GCC Toolchain -->
      <td style="text-align: center">v11.3</td>  <!-- NVHPC Toolchain -->
    </tr>
  </tbody>
</table>

<table class="status_table">
  <thead>
    <tr>
      <th>Project</th>
      <th style="text-align: center">GCC</th>
      <th style="text-align: center">GCC + CUDA</th>
      <th style="text-align: center">NVHPC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td markdown="span">
        [Darshan][DARSHAN]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + CUDA-->
      <td class="na" style="text-align: center">N/A</td><!-- NVHPC -->
    </tr>
    <tr>
      <td markdown="span">
        [Dynist][DYNIST]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + CUDA-->
      <td class="na" style="text-align: center">N/A</td><!-- NVHPC -->
    </tr>
    <tr>
      <td markdown="span">
        [HPCToolkit][HPCTOOLKIT]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + CUDA-->
      <td class="na" style="text-align: center">N/A</td><!-- NVHPC -->
    </tr>
    <tr>
      <td markdown="span">
        [PAPI][PAPI]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + CUDA-->
      <td class="na" style="text-align: center">N/A</td><!-- NVHPC -->
    </tr>
    <tr>
      <td markdown="span">
        [TAU][TAU]
      </td>
      <td class="na" style="text-align: center">N/A</td><!-- GCC -->
      <td class="na" style="text-align: center">N/A</td><!-- GCC + CUDA-->
      <td class="na" style="text-align: center">N/A</td><!-- NVHPC -->
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
