# The Open Standards Community for Electron Microscopy

The *Open Standards Community for Electron Microscopy* (OSC-EM) is a community of
scientists, developers, and users interested in standardizing and sharing electron
microscopy metadata.

![Microscope metadata is converted to OSC-EM format, which can then be read by
processing software, data repositories, and knowledge
sharing.](assets/img/conversion.svg)

Producing scientific results from EM data requires more than just the raw micrographs,
image stacks, or spectrograms. It also requires metadata about instrument settings,
sample preparation, and processing. Rather than relying on user notes or method
descriptions, OSC-EM can capture this metadata in a standard format that can then be
imported by processing software or published with the dataset to enable reuse and
reproducible science.

Central to this effort is the [OSC-EM Schema](https://github.com/osc-em/OSCEM_Schemas),
which defines a common format for describing microscope metadata. The schema is modular
to allow for the inclusion a diverse experimental techniques and data types. OSC-EM can
be used to store metadata for the full data lifecycle, from data acquisition through
processing and deposition.

Metadata is collected from microscopes or added by users. Currently, importers are
available for [life science](https://github.com/SwissOpenEM/LS_Metadata_reader) and
[material science](https://github.com/SwissOpenEM/MS_Metadata_reader) data.
Interconversion with the [mmCIF](https://github.com/osc-em/converter-JSON-to-mmCIF)
format is also available for single particle cryoEM and tomography, allowing deposition
in [EMDB](https://www.ebi.ac.uk/emdb/) and the [PDB](https://www.wwpdb.org/) Additional
importers for other instruments and experimental techniques are anticipated in the
future.

## Community

OSC-EM is an inclusive community that aims to represent the needs of diverse electron
microscopy users. We are actively looking for additional contributors to add additional
experimental methods, instruments, and software.
If you would like to contribute, please join the
[OSC-EM mailing list](https://listas.csic.es/cnb/wws/info/oscem) or start a discussion
on our [github organization](https://github.com/orgs/osc-em/discussions). You can also
contact project leaders [Spencer Bliven](mailto:spencer.bliven@psi.ch) (PSI)
and Carlos Oscar Sanchez Sorzano (CSIC) directly.

The following projects use OSC-EM:

- The [**OpenEM** consortium](https://swissopenem.github.io/) uses OSC-EM for metadata
  at 8 major Swiss EM facilities. An [example
  dataset](https://discovery.psi.ch/datasets/20.500.11935%2Fe9958228-11b9-42ea-a099-813150c3ccea)
  is available using the OSC-EM schema for the scientific metadata.
- CryoEM processing framework [**Scipion**](https://scipion.i2pc.es/) will add support
  for importing and exporting OSC-EM metadata in a future version.
- The **European Bioinformatics Institute** (EMBL-EBI) contributes to OSC-EM through the
  [mmCIF converter](https://github.com/osc-em/converter-JSON-to-mmCIF). The mmCIF files
  produced are compatible with the [wwPDB
  OneDep](https://deposit-pdbe.wwpdb.org/deposition/) platform for deposition into
  [**EMDB**](https://www.ebi.ac.uk/emdb/) and [**PDB**](https://www.wwpdb.org/).

## Status

The OSC-EM schema is now considered a draft version. However, additional fields and
techniques are expected to be added in the future.
