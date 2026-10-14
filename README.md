# B-vac

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-4285F4?style=flat-square" alt="Windows and Linux">
  <img src="https://img.shields.io/badge/Interface-GUI-34A853?style=flat-square" alt="Graphical interface">
  <img src="https://img.shields.io/badge/Internet-Not%20Required-FBBC04?style=flat-square" alt="Offline software">
  <img src="https://img.shields.io/badge/License-Apache%202.0-EA4335?style=flat-square" alt="Apache 2.0">
</p>

<p align="center">
  <strong>Reverse Vaccinology. Simplified.</strong>
  <br>
  A standalone desktop application for bacterial vaccine candidate discovery.
</p>

<p align="center">
  Screen bacterial proteomes, explore potential vaccine targets, and map epitopes through an intuitive graphical interface.
  <br>
  No command line. No internet connection. No advanced bioinformatics expertise required.
</p>

<p align="center">
  <a href="https://samavinasir.github.io/b-vac/"><strong>Download B-vac →</strong></a>
  &nbsp; · &nbsp;
  <a href="#features">Features</a>
  &nbsp; · &nbsp;
  <a href="#citation">Citation</a>
</p>

---

## Overview

B-vac is a standalone software package developed to make reverse-vaccinology-based bacterial vaccine design more accessible. It combines protein localization analysis, non-host homology screening, virulence factor identification, and epitope mapping in a single desktop application.

Designed for researchers, students, and laboratory teams, B-vac transforms a bacterial proteome in FASTA format into a filtered set of potential vaccine candidates using adjustable analysis modules and curated reference datasets.

## Features

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔵 Subcellular Localization</h3>
      Identify proteins associated with relevant cellular locations using reference data from LocTree3.
    </td>
    <td width="50%" valign="top">
      <h3>🔴 Non-Host Homology</h3>
      Apply non-host homology screening to help prioritize potential vaccine targets.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🟡 Virulence Factor Analysis</h3>
      Screen protein sequences against curated virulence factor reference data from VFDB.
    </td>
    <td width="50%" valign="top">
      <h3>🟢 Epitope Mapping</h3>
      Map potential B-cell and T-cell epitopes using reference data from IEDB.
    </td>
  </tr>
</table>

### Designed for accessibility

- **Four adjustable filters** to configure the analysis workflow.
- **Graphical user interface** built with Python and Tkinter.
- **Offline operation** without requiring an active internet connection.
- **Standalone executables** for Windows and Linux.
- **Integrated workflow** for screening and prioritizing candidate proteins.

## How It Works

<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" width="700" height="420" font-family="Arial, sans-serif">
    <!-- FASTA Proteome -->
    <rect x="200" y="20" width="300" height="60" fill="#4A90E2" stroke="#333" rx="12"/>
    <text x="350" y="55" text-anchor="middle" fill="white" font-size="18" font-weight="bold">FASTA Proteome</text>
    
    <!-- Arrow -->
    <line x1="350" y1="80" x2="350" y2="110" stroke="#333" stroke-width="2"/>
    <polygon points="345,110 355,110 350,120" fill="#333"/>
    
    <!-- Configurable Screening -->
    <rect x="200" y="130" width="300" height="60" fill="#50E3C2" stroke="#333" rx="12"/>
    <text x="350" y="165" text-anchor="middle" fill="black" font-size="18" font-weight="bold">Configurable Screening</text>
    
    <!-- Arrow -->
    <line x1="350" y1="190" x2="350" y2="220" stroke="#333" stroke-width="2"/>
    <polygon points="345,220 355,220 350,230" fill="#333"/>
    
    <!-- Screening Details -->
    <rect x="100" y="240" width="500" height="70" fill="#F5A623" stroke="#333" rx="12"/>
    <text x="350" y="270" text-anchor="middle" fill="black" font-size="16">
      Localization · Non-Host Homology · Virulence Factors · Epitope Mapping
    </text>
    
    <!-- Arrow -->
    <line x1="350" y1="310" x2="350" y2="340" stroke="#333" stroke-width="2"/>
    <polygon points="345,340 355,340 350,350" fill="#333"/>
    
    <!-- Final Output -->
    <rect x="150" y="360" width="400" height="60" fill="#9013FE" stroke="#333" rx="12"/>
    <text x="350" y="395" text-anchor="middle" fill="white" font-size="16" font-weight="bold">
      Filtered Candidate Proteins & Mapped Epitopes
    </text>
  </svg>
</p>

B-vac uses a string-based sequence-matching approach against curated reference datasets.  
The results support the identification and prioritization of potential vaccine candidates for further investigation.

*Note: B-vac is a computational screening tool. Predicted candidates require appropriate downstream validation.*

## Software Information

| Property | Details |
|:--|:--|
| Version | 1.0 |
| Category | Reverse vaccinology · Bacterial vaccine design |
| Language | Python 3.10 |
| Interface | Tkinter desktop GUI |
| Platforms | Windows and Linux |
| Internet requirement | Not required |
| Distribution | Standalone executable |
| License | Apache License 2.0 |

## Download

<p align="center">
  <a href="https://samavinasir.github.io/b-vac/">
    <img src="https://img.shields.io/badge/Download-B--vac-4285F4?style=for-the-badge&logo=github&logoColor=white" alt="Download B-vac">
  </a>
</p>

<p align="center">
  Get the standalone application and access the available release information.
  <br>
  <a href="https://samavinasir.github.io/b-vac/">samavinasir.github.io/b-vac</a>
</p>

## Publication

If you use B-vac in your research, please cite the original publication:

Ali, A., Hamid, M. H. B., Nasir, S., Ishaq, Z., & Anwer, F. (2025). B-vac: A robust software package for bacterial vaccine design. *Scientific Reports*, **15**, 31745.

**DOI:** [10.1038/s41598-025-01201-0](https://doi.org/10.1038/s41598-025-01201-0)

## Development Team

Developed by the **Integrative Biology Laboratory**, Atta-ur-Rahman School of Applied Biosciences (ASAB), National University of Sciences and Technology (NUST), Islamabad, Pakistan.

🌐 **Laboratory website:** [mgbio.asab.nust.edu.pk](https://mgbio.asab.nust.edu.pk/)

## License

B-vac is released under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

---

<p align="center">
  <strong>Built for accessible, data-driven vaccine research.</strong>
  <br>
  <sub>B-vac · Reverse Vaccinology · NUST Islamabad</sub>
</p>
