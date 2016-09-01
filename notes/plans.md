- Logistics
  - Will seek possible support from Intel, Amazon, MS, Google, others?
  - Formally plan to make this a student-run organization
  - Logistics: Monday 6-7 (?)
  - Format: Tutorial/discussion + lightning talks
  - Goal is to get this self-sustaining by the end of academic year
- Organizational models for learning about software
  - Courses, bootcamps, meetups, and communities of practice
  - <http://www.thehackerwithin.org/>
  - <https://science.mozilla.org/>
  - <http://software-carpentry.org/index.html>
  - <http://labcarpentry.org/>
- Cornell resources for scientific computing
  - [CAC](https://www.cac.cornell.edu/),
    [CIT](http://www.it.cornell.edu/),
    [RDMSG](http://data.research.cornell.edu/), and other groups
  - Local courses and workshops
  - Student-run tutorials
- Version control
  - [Git](https://git-scm.com/),
    [Mercurial](https://www.mercurial-scm.org/),
    [Subversion](https://subversion.apache.org/), and company
  - Hosted services: [GitHub](https://github.com/),
    [Bitbucket](https://bitbucket.org/),
    [Assembla](https://www.assembla.com/home), etc
  - Cornell-local options:
    [GitHub Enterprise](http://www.it.cornell.edu/support/coecis/github.cfm), [Sourceforge](https://forge.cornell.edu/)
  - What to control?  Issues with built artifacts and large data
  - Locks, pull requests, and collaboration with version control
- At the terminal
  - Local and remote terminals
  - Windows: [Cygwin](https://www.cygwin.com/),
    [MinGW](http://www.mingw.org/), and
    [Linux in Windows 10](https://msdn.microsoft.com/en-us/commandline/wsl/about)
  - SSH keys and password-free operation
  - [screen](https://www.gnu.org/software/screen/),
    [tmux](https://tmux.github.io/), and other terminal multiplexing options
  - Terminal sharing with [tmate](https://tmate.io/)
- Language environments and tooling
  - "Just enough" introductions:
    [Bash](http://tldp.org/LDP/abs/html/),
    [Python](https://docs.python.org/3/tutorial/),
    [MATLAB](http://www.cs.cornell.edu/courses/cs1132/2015sp/),
    [Julia](http://julialang.org/learning/),
    [R](https://www.r-project.org/)
  - Issues in high-performance scripting
  - Using [Jupyter notebooks](http://jupyter.org/)
  - Hosted notebooks ([Azure](https://notebooks.azure.com/), [Everware](https://github.com/everware), [Binder](http://mybinder.org/), [Wakari](https://wakari.io/), [SageMathCloud](https://cloud.sagemath.com/), etc).
- Workflow automation and documentation
  - [Make](https://www.gnu.org/software/make/manual/make.html),
    [Rake](https://ruby.github.io/rake/),
    [SnakeMake](https://bitbucket.org/snakemake/snakemake/wiki/Home),
    [PyDoIt](http://pydoit.org/), etc
  - Pipelines and notebooks
  - Reproducibility
  - Continuous integration environments ([Bamboo](https://www.atlassian.com/software/bamboo),
  [Jenkins](https://jenkins.io/), [TravisCI](https://travis-ci.org/), etc)
- Getting computing resources for scientific computing
  - Overview: Servers, clusters, clouds, supercomputers
  - Cornell-local resources
  - Supercomputing resources
  - Cloud resources
- Scientific computing in the cloud
  - Working with
    [EC2](https://aws.amazon.com/),
    [GCP](https://cloud.google.com/), and
    [Azure](https://azure.microsoft.com/en-us/) (try to get industry tutorials?)
  - [RedCloud](https://www.cac.cornell.edu/services/cloudservices.aspx) (get CAC tutorial?)
  - Accelerators, Infiniband, and other specialized support
- Environment virtualization
  - Virtual machines
  - [Docker](https://www.docker.com/) and containers
  - Language level: Python virtualenv and conda
- Reproducibility issues
  - Reproducibility best practices
  - Special issues with reproducibility and high-performance computing
- Build and configuration
  - "[The build problem](http://grosskurth.ca/bib/2003/dubois.pdf)": survey and history
  - [Autotools](https://www.gnu.org/software/automake/manual/html_node/Autotools-Introduction.html), [CMake](https://cmake.org/), [SCons](http://scons.org/), etc
- Packaging and distribution
  - [Semantic versioning](http://semver.org/)
  - Automating distribution
  - Packaging of compiled codes
  - Packaging in Python, Julia, R
  - Software licensing and copyright issues
- Documentation
  - [Javadoc](https://en.wikipedia.org/wiki/Javadoc),
    [Doxygen](http://www.doxygen.org/),
    [Sphinx](http://www.sphinx-doc.org/), and other tools
  - Plain-text formats: RESt, Markdown, LaTeX
  - [Pandoc](http://pandoc.org/)
  - [Literate programming](http://www.literateprogramming.com/)
- Data management
  - "Just enough" SQL
  - [HDF5](https://www.hdfgroup.org/HDF5/),
     [NetCDF](http://www.unidata.ucar.edu/software/netcdf/),
     and related formats
  - [XML](https://www.w3.org/XML/),
     [YAML](http://yaml.org/),
     [JSON](http://www.json.org/), metadata, and semi-structured data
  - Facilities for large-scale working data
  - Data set archival
- Plotting and visualization
  - [Matplotlib](http://matplotlib.org/),
     [Seaborn](https://stanford.edu/~mwaskom/software/seaborn/),
     [GNUPlot](http://www.gnuplot.info/),
     [D3](https://d3js.org/), etc
  - Visualization of network data
  - Simulation visualization with [VisIt](https://wci.llnl.gov/simulation/computer-codes/visit/) and [Paraview](http://www.paraview.org/)
  - [XTK](https://github.com/xtk/X)
- Testing and company
  - Linting code
  - Code reviews and tools
  - [Valgrind](http://valgrind.org/) and company
  - Types of tests: unit, integration, regression, etc
  - Test-driven development
  - Tooling for test automation
  - Continuous integration tools and services
  - Tickets and bug databases
  - Special issues in testing of numerical codes
- Monitoring and checkpointing
  - Assertions and exceptions
  - Logging systems
  - Automated checkpoints
  - Application-level checkpointing
- Tuning
  - "Just enough" computer architecture
  - Profiling for scripts and compiled codes
  - Profile-guided optimization
  - Sources for tuned libraries
  - Accelerator-aided libraries
  - Software modernization resources
- Mixed language programming
  - Models: script-driven, embedded scripting, configuration languages,
    cross-language library calls, code generation
  - Interface generators
  - Function calls vs inter-process communication
  - Build-time issues: portability, standard libraries, linkage
- Fast math frameworks and libraries
  - [PETSc](https://www.mcs.anl.gov/petsc/) and [Trilinos](https://trilinos.org/)
  - [ACTS collection](http://acts.nersc.gov/)
