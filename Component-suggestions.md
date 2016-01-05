This is a list of component suggestions for potential inclusion into future versions of OpenHPC. Note that being listed here does not guarantee inclusion as a more formal selection and review process is likely to be instituted by a technical steering committee once the governance process is formalized. However, it is intended to provide an initial centralizing location to log suggestions.

| Type | Name | Location | Notes |
|------|------|----------|-------|
| admin         | clustershell | https://github.com/cea-hpc/clustershell | Python replacement for pdsh |
| admin         | spindle     | https://github.com/hpc/Spindle |  tool for loading dynamic libs at scale |
| | | | |
| configuration | ansible     | https://github.com/ansible/ansible       | |
| configuration	| chef        | https://www.chef.io/chef, https://github.com/chef/chef | |
| configuration	| cfengine    | https://cfengine.com                     | v2 (HPC/genderized) & v3 |
| configuration	| puppet      | https://puppetlabs.com                   | |
| | | | |
| debug	        | libdwarf    | http://www.prevanders.net/dwarf.html     | debugging information format |
| debug	        | MpiPView    | [MpiPView](https://computation.llnl.gov/casc/tool_gear/mpipview.html) | Visualize MpiP | 
| debug	        | StackWalker |	https://stackwalker.codeplex.com         | |
| | | | |
| library       | fgfs        | [fgfs](https://github.com/dongahn/MountPointAttributes) | turns expensive, non-scalable file system calls into simple string comparison operations |
| library       | gdal        | http://www.gdal.org                      | raster and vector geospacial data (GIS) |
| library       | gperf       | https://www.gnu.org/software/gperf       | gnu perfect hash generator |
| library       | libunwind   | [libunwind](http://git.savannah.gnu.org/cgit/libunwind.git) | stack unwinding lib |
| library       | MRNet       | http://www.paradyn.org/mrnet             | Multicast reduction network |
| library       | OCR         | https://01.org/open-community-runtime    | MPI alternative async communication library |
| library       | OpenCV      | http://opencv.org                        | computer vision and machine learning software library |
| library       | pyMPI	      | http://pympi.sourceforge.net             | Python MPI bindings |
| library       | scr         | https://computation.llnl.gov/project/scr | Scalable Checkpoint Restart |
| library       | TCLAP       | http://tclap.sourceforge.net [Also on GitHub(newer?)](https://github.com/eile/tclap) | Library to define and access CLI arguments |
| library       | UDUNITS     | [UDUNITS](http://www.unidata.ucar.edu/software/udunits) | Conversion between different units(udunits2?) |
| library       | VampirTrace | http://tinyurl.com/ozrs7e3 | detailed logging of program execution for parallel applications |
| | | | |	 	 	 	 
| packaging     | Spack	      | https://github.com/LLNL/spack            | HPC-centric Package Management |
| | | | |
| perf-tools    | Darshan     | [darshan](http://www.mcs.anl.gov/research/projects/darshan) | Characterize IO patterns | 
| perf-tools    | gperftools  | https://github.com/gperftools/gperftools | Google performance tools |
| perf-tools    | HPCToolkit  | http://hpctoolkit.org                    | HPC app profiling |
| perf-tools    | memP        | http://memp.sourceforge.net              | Parallel heap profiling |
| perf-tools    | papiex      | http://icl.cs.utk.edu/~mucci/papiex      | (unsupported) hw performance using papi |	 	 	 	 
| | | | |
| provisioning  | xCAT        | http://www.xcat.org                      | |
| | | | |
| visualization | Blender     | https://rcc.fsu.edu/software/blender     | 3D animation suite | 
| visualization | engauge     | http://digitizer.sourceforge.net         | Convert graph image to spreadsheet | 
| visualization	| ncl         | http://www.ncl.ucar.edu                  | NCAR Command Language |
| visualization | ParaView    | http://www.paraview.org                  | Parallel visualization application |
| visualization | PySide      | http://pypi.python.org/pypi/PySide/1.2.2 | Python QT bindings |
| visualization | VTK         | http://www.vtk.org/download              | Visualization Toolkit |
| | | | |	 	 	 
| utility       | AtomView3 (1&2?) | [AtomView](http://li.mit.edu/A/Graphics/A3/A3.html) | Atomistic configuration viewer |
| utility       | BlockBuster | [BlockBuster](http://sourceforge.net/projects/blockbuster) | High-resolution image/movie player | 
| utility       | GMT         | http://gmt.soest.hawaii.edu              | Generic Mapping Tools | 
| utility       | iRODS       | http://irods.org                         | open source data management software |
| utility       | LaunchMON   | [LaunchMON](https://github.com/scalability-llnl/LaunchMON) | co-locate tool daemons with HPC runtimes |
| utility       | magpie      | https://github.com/chu11/magpie          | run BigData(hadoop) jobs on HPC systems |
| utility       | mrsh        | https://github.com/chaos/mrsh            | Munge based remote shell |
| utility       | NCO         | http://nco.sourceforge.net/nco.html      | netCDF commandline operators | 
| utility       | patchelf    | https://github.com/NixOS/patchelf        | modify dynamic linker and RPATH of ELF executables |
| utility       | PMIx        | https://www.open-mpi.org/projects/pmix   | Exascale process management interface |
| utility       | SideCar     | ? ([about](https://computing.llnl.gov/vis/sidecarUM.html)) | Remote blockbuster control | 
| utility       | SQLCipher   | [SQLCipher](https://www.zetetic.net/sqlcipher/open-source) | SQL database encryption |	
| utility/lib	| szip        | [szip](https://www.hdfgroup.org/doc_resource/SZIP) | HDF file compression | 