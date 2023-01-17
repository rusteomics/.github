# Rusteomics

Rusteomics is an open and collaborative community for Rust development for computational proteomics and mass spectrometry.


## About Rusteomics

The computational proteomics and mass spectrometry community has created some exceptional software toolboxes over the past years, with some notable examples being [OpenMS][openms], [Pyteomics][pyteomics], and [mzR][mzr]. Most of these projects implement general computational tasks, such as reading and preprocessing proteomics data in a modular fashion, which is ideal for reuse in other projects. Nevertheless, most of these packages do not rely on a mutual code base or on the same internal data representation. This makes interoperability between these toolkits only possible by using ([HUPO-PSI][psi]) standardized file formats. Reading or writing these file formats without a common implementation may also introduce errors, further hampering interoperability.

Recently, the Rust programming language has been steadily gaining popularity, mostly due to its high performance as a low-level language and its developer-friendly toolchain. Furthermore, Rust is compatible with all major operating systems, and bindings can be created to extend its functionality to other programming languages, such as Python or R. These characteristics provide a unique opportunity for computational proteomics developers to unite and collaborate on a new open and flexible toolbox for computational proteomics and mass spectrometry.

The aim of Rusteomics is to facilitate the development of such a community-driven toolbox in an open and transparent manner. It spawned as a project of the European Bioinformatics Community for Mass Spectrometry ([EuBIC-MS][eubic-ms]) and was kickstarted as a hackathon at the [EuBIC-MS Developers Meeting 2023][eubic2023]. 


## Get started!

🧑‍🔧 Join the development at our [repositories](https://github.com/orgs/rusteomics/repositories)<br>
💬 Ask questions or share your ideas on the [discussion forum](https://github.com/orgs/rusteomics/discussions)<br>
🤝 Read our [code of conduct](https://github.com/rusteomics/.github/blob/main/profile/CODE_OF_CONDUCT.md)<br>


[openms]: https://www.openms.de/
[pyteomics]: https://pyteomics.readthedocs.io/
[mzr]: http://www.bioconductor.org/packages/devel/bioc/vignettes/mzR/inst/doc/mzR.html
[psi]: https://psidev.info/
[eubic-ms]: https://eubic-ms.org/
[eubic2023]: https://github.com/eubic/EuBIC2023/issues/10
