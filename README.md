# Awesome Drug Discovery [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A meticulously curated resource list focused on computational methods for drug discovery.

> Drug discovery is the process by which new candidate medications are identified, designed, and developed using experimental, computational, and informational techniques to address complex challenges in biology, chemistry, and medicine. — [Wikipedia](https://en.wikipedia.org/wiki/Drug_discovery)

---

## Contents
- [Databases and Chemical Libraries](#databases-and-chemical-libraries)  
  - [General Compound Libraries](#general-compound-libraries)  
  - [Natural Product Libraries](#natural-product-libraries)  
  - [Bioactivity Databases](#bioactivity-databases)  
- [Target and Protein Data](#target-and-protein-data)  
  - [Protein Structures](#protein-structures)  
  - [Binding Site and Pocket Detection](#binding-site-and-pocket-detection)  
  - [Protein Engineering and Modeling](#protein-engineering-and-modeling)
- [Network Pharmacology](#network-pharmacology)  
- [Ligand Design and Optimization](#ligand-design-and-optimization)  
  - [Pharmacophore Modeling](#pharmacophore-modeling)  
  - [QSAR and Descriptor Tools](#qsar-and-descriptor-tools)  
  - [Descriptor and Featurization Tools](#descriptor-and-featurization-tools)
  - [Molecular Property Prediction](#molecular-property-prediction)  
  - [Fragment-Based Drug Design](#fragment-based-drug-design)  
- [Virtual Screening and Docking](#virtual-screening-and-docking)  
- [Interaction Analysis and Visualization](#interaction-analysis-and-visualization)  
- [Molecular Dynamics and Simulation](#molecular-dynamics-and-simulation)  
  - [Engines](#engines)  
  - [Topology and Force Field Tools](#topology-and-force-field-tools)  
  - [Analysis Tools](#analysis-tools)  
- [Synthesis and Retrosynthesis Planning](#synthesis-and-retrosynthesis-planning)  
- [Specialized Modalities](#specialized-modalities)  
  - [PROTACs and Ternary Complexes](#protacs-and-ternary-complexes)  
  - [Peptide Design](#peptide-design)  
- [Machine Learning and AI](#machine-learning-and-ai)  
  - [Core Libraries](#core-libraries)  
  - [Chemistry-focused ML Frameworks](#chemistry-focused-ml-frameworks)  
  - [Pretrained Models](#pretrained-models)  
  - [AutoML and Optimization](#automl-and-optimization)  
  - [Molecule Standardization](#molecule-standardization)  
- [Utility and Workflow Tools](#utility-and-workflow-tools)  
- [Learning Resources](#learning-resources)  
  - [Free Courses](#free-courses)  
  - [Blogs](#blogs)  
  - [Instructional Notebooks](#instructional-notebooks)
- [Labs and Research Groups](#labs-and-research-groups)
---

## Databases and Chemical Libraries

### General Compound Libraries
- [DrugBank](https://go.drugbank.com/) - Comprehensive data on approved and investigational drugs.
- [ZINC](https://zinc.docking.org/) - Free compounds for screening.  
- [ChemSpider](http://www.chemspider.com/) - Chemical structures and data.  
- [DrugSpaceX](https://drugspacex.simm.ac.cn/) - Chemical and biological spaces.  
- [Mcule](https://mcule.com/) - Virtual screening platform with purchasable compounds.  
- [Otava Chemicals](https://www.otavachemicals.com/) - Screening compounds and building blocks.  
- [Vitas-M Laboratory](https://vitasmlab.biz/) - Chemical libraries for HTS and lead discovery.
- [Eximed](https://eximedlab.com/Screening-Compounds.html) - 60k+ compounds for virtual screening.
- [OTAVA NP-like Library](https://otavachemicals.com/sdf) - Screening compounds for prompt delivery.
- [Ambinter](https://www.ambinter.com/) - 40M+ compounds for HTS, building blocks, and a wide selection of fragments and natural products.  

### Natural Product Libraries
- [ZINC15 Natural Products](https://zinc15.docking.org/substances/subsets/natural-products/) - 200k+ natural compounds.  
- [COCONUT](https://coconut.naturalproducts.net/) - 400k+ natural products.  
- [LOTUS](https://lotus.naturalproducts.net/) - Annotated molecular data with sourcing organisms.  
- [NPASS](http://bidd.group/NPASS/index.php) - 94k activity-species links.  
- [ANPDB](https://phabidb.vm.uni-freiburg.de/anpdb/) - 27k+ African medicinal plant compounds.  
- [SANCDB](https://sancdb.rubi.ru.ac.za/) - Natural compounds from the plant and marine life in and around South Africa.  
- [CMNPD](https://www.cmnpd.org/) - 31k+ marine natural products.  
- [SistematX](https://sistematx.ufpb.br/) - 8k+ secondary metabolites.  
- [CoumarinDB](https://yboulaamane.github.io/CoumarinDB/) - A manually curated database on coumarins from plants.  
- [ArtemisiaDB](https://yboulaamane.github.io/ArtemisiaDB/) - Artemisia genus compounds.  
- [BIAdb](https://webs.iiitd.edu.in/raghava/biadb/type.php?tp=natural) - A database for benzylisoquinoline alkaloids.  
- [IMPPAT](https://cb.imsc.res.in/imppat/home) - Phytochemicals from Indian medicinal plants.  
- [NP-MRD](https://np-mrd.org/natural_products) - 280k+ NMR-based NP studies.  
- [IBS Natural Compounds](https://www.ibscreen.com/natural-compounds) - 60k+ compounds.  
- [PhytoHub](https://phytohub.eu/) - Dietary phytochemicals and metabolites.  
- [Dr. Duke's Phytochemical DB](https://phytochem.nal.usda.gov/) - Plant compounds and uses.  
- [CyanoMetDB](https://zenodo.org/records/13854577) - Over 3,000 cyanobacterial metabolites.  
- [Seaweed Metabolite DB](https://www.swmd.co.in/) - Marine algae compounds.  
- [FooDB](https://foodb.ca/) - A comprehensive resource on food constituents.  

### Bioactivity Databases
- [ChEMBL](https://www.ebi.ac.uk/chembl/) - Bioactivity and ADMET data.  
- [SureChEMBL](https://www.surechembl.org/) - Patent chemistry search.  
- [BindingDB](https://www.bindingdb.org/) - Binding affinities for biomolecules.  
- [PubChem](https://pubchem.ncbi.nlm.nih.gov/) - Structures, properties, and bioassays.  
- [PDBbind](http://www.pdbbind.org.cn/index.php) - Protein-ligand affinity data.  
- [BRENDA](https://www.brenda-enzymes.org/) - Enzyme properties and functions.  
- [ExCAPE-DB](https://solr.ideaconsult.net/search/excape/) - A large-scale chemogenomics database.  
- [Therapeutics Data Commons](https://tdcommons.ai/) - AI/ML-ready datasets and learning tasks for therapeutics.
- [Therapeutic Target Database (TTD)](https://idrblab.net/ttd/) - Drug targets with linked diseases and compounds.
- [Aircheck Datasets](https://aircheck.ai/datasets) - Curated DEL datasets for AI‑driven drug discovery, enabling benchmarking and model development.

---

## Target and Protein Data

### Protein Structures
- [RCSB PDB](https://www.rcsb.org/) - Repository for macromolecular structures.
- [PDBe](https://www.ebi.ac.uk/pdbe/) - European counterpart to RCSB PDB.
- [OPM](https://opm.phar.umich.edu/) - Orientation of proteins in membranes.
- [UniProt](https://www.uniprot.org/) - Protein sequences, structures, and functions.
- [InterPro](https://www.ebi.ac.uk/interpro/) - Protein classification and domain prediction.
- [AlphaFold DB](https://alphafold.ebi.ac.uk/) - Predicted structures from AlphaFold.
- [Proteopedia](https://proteopedia.org/wiki/index.php/Main_Page) - Interactive protein visualizations.

### Binding Site and Pocket Detection
- [PrankWeb](https://prankweb.cz/) - Pocket prediction and analysis.
- [CASTp](http://sts.bioe.uic.edu/castp/index.html?2r7g) - Pocket geometry and volume analysis.
- [CavityPlus](http://www.pkumdl.cn:8000/cavityplus/index.php#/) - Pocket detection and druggability.
- [CaverWeb](https://loschmidt.chemi.muni.cz/caverweb/) - Tunnel and channel detection.
- [PASSer](https://passer.smu.edu/) - Allosteric site prediction.

### Protein Engineering and Modeling
- [DynaMut](https://biosig.lab.uq.edu.au/dynamut/) - Predicts mutation-induced stability changes.
- [SWISS-MODEL](https://swissmodel.expasy.org/) - A fully automated protein structure homology-modeling server.
- [MODELLER](https://salilab.org/modeller/) - A software for homology or comparative modeling of protein structures.
- [PDBFixer](https://github.com/openmm/pdbfixer) - Repairs PDB files by adding missing atoms, residues, and hydrogens for MD simulations.
---

## Network Pharmacology
- [GeneCards](https://www.genecards.org/) - Human gene database with genomic, proteomic, and clinical data.
- [SwissTargetPrediction](http://www.swisstargetprediction.ch/) - Predicts targets of small molecules via similarity-based screening.
- [STITCH](https://stitch.embl.de/) - Integrates chemical–protein interactions across organisms.
- [STRING](https://string-db.org/) - A database of known and predicted protein–protein interactions.
- [Cytoscape](https://cytoscape.org/) - Visualizes and analyzes molecular interaction networks.
- [Open Targets](https://platform.opentargets.org/) - Integrative platform for therapeutic target identification.
- [OmicsNet](https://www.omicsnet.ca/) - Builds multi-omics networks for systems biology.
- [DisGeNET](https://disgenet.com/) - Curated gene–disease associations for network analysis.
- [PharmMapper](https://www.lilab-ecust.cn/pharmmapper/) - Identifies potential targets via reverse pharmacophore mapping.
- [ChEA3](https://maayanlab.cloud/chea3/) - Transcription factor enrichment tool integrating ChIP-seq, co-expression, and perturbation datasets.
- [miRDB](https://mirdb.org/) - Predicts functional microRNA targets using machine learning and high-throughput data.
- [Venny 2.1](https://bioinfogp.cnb.csic.es/tools/venny/) - A web tool for comparing lists using Venn diagrams.

## Ligand Design and Optimization

### Pharmacophore Modeling
- [ZINCPharmer](http://zincpharmer.csb.pitt.edu/) - Pharmacophore screening.
- [Pharmit](https://pharmit.csb.pitt.edu/) - Interactive pharmacophore modeling.
- [AnchorQuery](http://anchorquery.csb.pitt.edu/) - Pharmacophore-based search engine specialized in protein–protein interaction sites.

### QSAR and Descriptor Tools
- [QSAR Toolbox](https://qsartoolbox.org/) - Hazard assessment and QSAR.
- [OCHEM](https://ochem.eu/home/show.do) - QSAR model building and prediction.
- [ChemMaster](https://crescent-silico.com/chemmaster/) - QSAR and cheminformatics suite.
- [3D-QSAR](https://www.3d-qsar.com/) - Web resources for 3D QSAR modeling.
- [QSAR-Co](https://sites.google.com/view/qsar-co/) - Robust multitarget QSAR modeling.
- [DataWarrior](https://openmolecules.org/datawarrior/) - Free software for chemical analysis, QSAR, and visualization.
- [KNIME](https://www.knime.com/) - Workflow platform for cheminformatics and ML integration.
- [pyADA](https://github.com/jeffrichardchemistry/pyADA) - Assesses the applicability domain of molecular fingerprints via similarity-based thresholds for QSAR validation.
  
### Descriptor and Featurization Tools
- [RDKit](https://www.rdkit.org/) - Open-source cheminformatics toolkit with descriptor, fingerprint, and molecular manipulation support.  
- [PaDEL-Descriptor](http://www.yapcwsoft.com/dd/padeldescriptor/) - Java tool for calculating molecular descriptors and fingerprints.  
- [Mordred](https://github.com/mordred-descriptor/mordred) - Python library with 1800+ molecular descriptors.  
- [CDK](https://cdk.github.io/) - Java cheminformatics library with descriptor calculators.  
- [alvaDesc](https://www.alvascience.com/alvadesc/) - Commercial software for molecular descriptors and fingerprints.  
- [MolFeat](https://molfeat.datamol.io/) - Python package for molecular featurization and embeddings.
- [Dragon](https://www.talete.mi.it/products/dragon_description.htm) - Commercial molecular descriptor calculator (widely cited).  

### Molecular Property Prediction
- [SwissADME](http://www.swissadme.ch/) - Drug-likeness and PK.
- [pkCSM](https://biosig.lab.uq.edu.au/pkcsm/) - ADMET property prediction.
- [DeepPK](https://biosig.lab.uq.edu.au/deeppk/) - DL-based pharmacokinetics.
- [admetSAR 2.0](https://lmmd.ecust.edu.cn/admetsar2/) - Comprehensive ADMET.
- [ADMETlab 2.0](https://admetmesh.scbdd.com/) - PK, toxicity and drug-likeness.
- [ProTox-II](https://tox-new.charite.de/protox_II/) - Toxicity predictions.
- [PreADMET](https://preadmet.webservice.bmdrc.org/) - PK property predictions.
- [FAF-Drugs](https://bioserv.rpbs.univ-paris-diderot.fr/services.html) - ADMET filtering.
- [Admetboost](https://ai-druglab.smu.edu/admet) - ML-based ADMET prediction.
- [MetaPredict](http://metapredict.icoa.fr/) - Predict molecular properties from structure.
- [ADMET-AI](https://admet.ai.greenstonebio.com/) - A web-based tool for predicting ADMET properties based on Chemprop-RDKit models trained on datasets from the TDC.

### Fragment-Based Drug Design

- [SwissSidechain](https://www.swisssidechain.ch/) - Fragment and linker library for small molecule design.
- [BoBER](http://bober.insilab.org/) - Bioisosteric replacements for lead optimization.
- [FragBuilder](https://github.com/andersx/fragbuilder) - Python API for building peptide-like and small molecule fragments.  
- [SeeSAR](https://www.biosolveit.de/SeeSAR/) - Fragment growing and linking software (free academic version).
- [Enamine Fragment Libraries](https://enamine.net/compound-libraries/fragment-libraries) - Large curated collection of diverse fragments for FBDD.
  
---

## Virtual Screening and Docking
- [OpenBabel](https://openbabel.org/index.html) - Format conversion and ligand prep.
- [Meeko](https://github.com/forlilab/Meeko) - Prepares ligands/receptors for AutoDock by assigning partial charges and atom types.
- [MolScrub](https://github.com/forlilab/molscrub) - Enumerates tautomers, pH states, and conformers for docking and structure-based modeling.
- [MGLTools](https://ccsb.scripps.edu/mgltools/) - Structure preparation.
- [AutoDockTools](https://autodocksuite.scripps.edu/adt/) - AutoDock GUI.
- [AutoDock Vina](https://vina.scripps.edu/) - Popular docking software.
- [AutoDock-GPU](https://github.com/ccsb-scripps/AutoDock-GPU) - GPU-accelerated version of AutoDock for faster ligand-receptor docking.
- [DiffDock](https://github.com/gcorso/DiffDock) - Deep learning-based docking tool that predicts ligand poses directly from protein structures using diffusion models.  
- [EasyDockVina2](https://github.com/S3cr3t-SDN/EasyDockVina2) - Vina automation.  
- [Webina](https://durrantlab.pitt.edu/webina/) - Web-based Vina.
- [Smina](https://github.com/mwojcikowski/smina) - Vina fork with extra features.
- [Gnina](https://github.com/gnina/gnina) - CNN-scoring docking.
- [EasyDock](https://github.com/ci-lab-cz/easydock) - Vina/Smina pipeline.
- [HADDOCK](https://wenmr.science.uu.nl/haddock2.4/) - Flexible docking suite.
- [PandaDock](https://github.com/pritampanda15/PandaDock) - Python docking tool.
- [ZDOCK](https://zdock.wenglab.org/) - Protein-protein docking.
- [ClusPro](https://cluspro.org/) - Protein-protein docking server.
- [pyDockWEB](https://life.bsc.es/pid/pydockweb/) - Electrostatics-based docking.
- [SwissDock](https://www.swissdock.ch/) - Web docking for beginners.
- [MzDOCK](https://github.com/Muzatheking12/MzDOCK) - GUI docking pipeline.
- [Uni-Mol Docking V2](https://www.bohrium.com/apps/unimoldockingv2/job?type=app) - AI-assisted docking.
- [Vina on Colab](https://autodock-vina.readthedocs.io/en/latest/colab_examples.html) - Run Vina in Google Colab.
- [MetalDock](https://metaldock.readthedocs.io/en/latest/) -  A Python-based tool designed for the docking of metal-organic compounds to proteins, DNA, or other biomolecules. 

---

## Interaction Analysis and Visualization
- [PLIP](https://plip-tool.biotec.tu-dresden.de/plip-web/plip/index) - Protein-ligand interaction profiling.
- [LigPlot+](https://www.ebi.ac.uk/thornton-srv/software/LigPlus/) - 2D interaction diagrams.
- [Discovery Studio Visualizer](https://discover.3ds.com/discovery-studio-visualizer-download) - Advanced visualization.
- [PyMOL](https://www.pymol.org/) - Python-based molecular visualization software.
- [UCSF ChimeraX](https://www.rbvi.ucsf.edu/chimerax/) - A molecular visualization program with emphasis on structural biology.
- [Avogadro](https://avogadro.cc/) - Cross-platform molecular editor and visualizer featuring an extensible plugin system.

---

## Molecular Dynamics and Simulation

### Engines
- [GROMACS](https://www.gromacs.org/) - Fast, scalable MD engine optimized for biomolecular simulations and energy minimization.
- [OpenMM](https://openmm.org/) - Flexible MD toolkit with GPU acceleration and Python bindings.
- [LAMMPS](https://www.lammps.org/) - Classical MD simulator for materials science and soft matter.
- [NAMD](https://www.ks.uiuc.edu/Research/namd/) - Highly parallel MD engine tailored for large biomolecular systems.
- [AMBER](https://ambermd.org/) - Suite for biomolecular simulations and free energy calculations.
- [Desmond](https://www.deshawresearch.com/resources.html) - GPU-accelerated MD engine for high-performance simulations.

### Topology and Force Field Tools
- [CGenFF](https://cgenff.umaryland.edu/) - CHARMM force field parametrization of drug-like molecules.
- [SwissParam](https://www.swissparam.ch/) - Rapid generation of CHARMM-compatible parameters for small organic molecules.
- [ATB](https://atb.uq.edu.au/) - Automated topology builder and repository for classical force field parameters.
- [CHARMM-GUI](https://www.charmm-gui.org/) - Web-based interface for building complex biomolecular systems and generating MD input files.
- [LigParGen](https://zarbi.chem.yale.edu/ligpargen/) - Automated OPLS-AA parameter generator for organic ligands.

### Analysis Tools
- [MD DaVis](https://md-davis.readthedocs.io/en/latest/index.html) - Interactive visualization and analysis of MD trajectories.
- [iMod](https://imods.iqfr.csic.es/) - Normal Mode Analysis toolkit using internal coordinates.
- [MolAiCal](https://molaical.github.io/) - Web-based platform for binding free energy calculations using MM/PBSA and MM/GBSA methods.
- [gmx_MMPBSA](https://valdes-tresanco-ms.github.io/gmx_MMPBSA/dev/) - Port of AMBER MMPBSA.py for GROMACS.
- [VMD](https://www.ks.uiuc.edu/Research/vmd/) - Large biomolecular systems visualization and analysis using 3D graphics and scripting.
- [Grace](https://plasma-gate.weizmann.ac.il/Grace/) - 2D plotting tool for Unix-like systems with advanced graphing, fitting, and analysis features.
- [CPPTRAJ](https://amberhub.chpc.utah.edu/cpptraj/) - Fast, parallelizable trajectory analysis from AMBER.
- [MDAnalysis](https://www.mdanalysis.org/) - Open-source Python library for analyzing MD simulations.
---

## Synthesis and Retrosynthesis Planning
- [Spaya](https://spaya.ai/app/search) - AI-driven retrosynthesis engine with route ranking and synthetic feasibility scoring.
- [AiZynthFinder](https://github.com/MolecularAI/aizynthfinder) - Monte Carlo tree search-based retrosynthesis using trained neural networks.
- [ASKCOS](https://askcos.mit.edu/) - Synthesis route prediction with ML, developed by MIT.
- [IBM RoboRXN](https://rxn.res.ibm.com/rxn/robo-rxn/welcome) - Automated reaction prediction using transformer models.
- [MANIFOLD](https://app.postera.ai/manifold/) - Search engine for synthetically accessible molecules and building blocks.
---

## Specialized Modalities

### PROTACs and Ternary Complexes
- [PROTAC-db](http://cadd.zju.edu.cn/protacdb/) - Curated database of PROTAC molecules, targets, and linkers for degrader design.
- [PROsettaC](https://prosettac.weizmann.ac.il/) - Structure-based modeling of ternary complexes for targeted protein degradation.

### Peptide Design
- [PepDraw](https://pepdraw.com/) - Peptide visualization with annotated physicochemical properties.
- [PepSite](http://pepsite2.russelllab.org/) - Predict peptide binding sites on protein surfaces using structural data.
- [Peptimap](https://peptimap.bu.edu/) - Peptide mapping and binding hotspots identification.
---

## Machine Learning and AI

### Core Libraries
- [scikit-learn](https://scikit-learn.org/) - General-purpose ML library for classification, regression, clustering, and model evaluation.
- [PyTorch](https://pytorch.org/) - Deep learning framework with extensive support for neural network modeling.
- [TensorFlow](https://www.tensorflow.org/) - End-to-end ML platform for scalable model development and deployment.
- [Keras](https://keras.io/) - High-level neural network API running on top of TensorFlow, designed for fast experimentation.
- [NumPy](https://numpy.org/) - Core library for numerical computing with support for arrays, matrices, and linear algebra.
- [Pandas](https://pandas.pydata.org/) - Data manipulation and analysis toolkit built on top of NumPy.
- [Matplotlib](https://matplotlib.org/) - Comprehensive library for creating static, animated, and interactive visualizations in Python.
- [Seaborn](https://seaborn.pydata.org/) - Statistical data visualization library built on top of Matplotlib.

### Chemistry-focused ML Frameworks
- [DeepChem](https://github.com/deepchem/deepchem) - Open-source deep learning framework for chemistry and biology.
- [scikit-mol](https://github.com/datamol-io/scikit-mol) - Open-source toolkit bridging RDKit and scikit-learn for molecular ML workflows.  
- [Chemprop](https://github.com/chemprop/chemprop) - Directed message passing neural networks for molecular property prediction.
- [ChemML](https://github.com/hachmannlab/chemml) - Machine learning and informatics suite for analyzing, mining, and modeling chemical and materials data.
- [Oloren ChemEngine](https://github.com/Oloren-AI/olorenchemengine) - Unified API for molecular property prediction with uncertainty quantification, interpretability, and model tuning.
- [TorchDrug](https://torchdrug.ai/) - A machine learning library for drug discovery with support for GNNs and molecular datasets.
- [DGL-LifeSci](https://github.com/awslabs/dgl-lifesci) - Graph deep learning toolkit for life sciences using the Deep Graph Library.

### Pretrained Models
- [MolBERT](https://github.com/BenevolentAI/MolBERT) - Transformer-based molecular representation learning.
- [ChemBERTa](https://huggingface.co/seyonec/ChemBERTa-zinc-base-v1) - Pretrained BERT-like models for molecules from SMILES.
- [Uni-Mol](https://github.com/dptech-corp/Uni-Mol) - 3D molecular representation learning framework.
- [Boltz-2](https://github.com/jwohlwend/boltz) - A foundation model that jointly predicts structure and binding affinity, rivaling physics-based FEP methods in accuracy.  

### AutoML and Optimization
- [Auto-sklearn](https://automl.github.io/auto-sklearn/master/) - Automated machine learning for scikit-learn.
- [TPOT](https://epistasislab.github.io/tpot/) - Genetic programming-based AutoML for optimizing ML pipelines.
- [Optuna](https://optuna.org/) - Hyperparameter optimization framework for machine learning.

### Molecule Standardization
- [MolVS](https://github.com/mcs07/MolVS) - Molecule validation and standardization library based on RDKit.

---

## Utility and Workflow Tools
- [ProteinsPlus](https://proteins.plus/) - A web-based platform designed to assist life scientists in analyzing and working with protein structures.
- [OPSIN](https://opsin.ch.cam.ac.uk) - Convert IUPAC names to chemical structures.
- [OSRA](https://cactus.nci.nih.gov/cgi-bin/osra/index.cgi) - Extract chemical structures from images.
- [ChemPlot](https://chemplot.streamlit.app/) - Chemical space visualization.
- [ChemDB](http://cdb.ics.uci.edu/) - Chemoinformatics portal with compound data and tools.
- [Screening Explorer](http://stats.drugdesign.fr/) - Analyze screening datasets and hit distributions.
- [LigRMSD](https://ligrmsd.appsbio.utalca.cl/) - Calculate RMSD between ligand poses.
- [NERDD](https://nerdd.univie.ac.at/) - Curated drug discovery resources.
- [LigBuilder3](http://www.pkumdl.cn:8080/ligbuilder3/) - De novo ligand design.
- [ChemMine Tools](https://chemminetools.ucr.edu/) - Web-based cheminformatics toolkit for compound analysis.
- [MayaChemTools](http://www.mayachemtools.org/index.html) - Perl/Python scripts for cheminformatics.
- [Click2Drug](https://www.click2drug.org/) - CADD software and databases directory.
- [Galaxy Europe](https://usegalaxy-eu.github.io/index-cheminformatics.html) - Galaxy instance for cheminformatics.
- [CADD Vault](https://drugbud-suite.github.io/CADD_Vault/) - CADD resources repository.
- [BioMoDes](https://abeebyekeen.com/biomodes-biomolecular-structure-prediction/) - Biomolecular structure prediction and modeling tools.
- [PlayMolecule](https://open.playmolecule.org/landing) - Interactive molecular modeling and simulation platform.
- [Ertl Molecular](https://ertlmolecular.com/) - Cheminformatics tools for medicinal chemists, including scaffold analysis, ring replacement, and property calculators.
- [Datagrok](https://datagrok.ai/) - Environment for working with chemical data, covering full-range of tasks from data access to de novo design.
---

## Learning Resources

### Free Courses
- [TMP Chem Lectures](https://youtube.com/playlist?list=PLm8ZSArAXicIWTHEWgHG5mDr8YbrdcN1K) - Recorded lectures from a leading cheminformatics summer school.
- [Strasbourg Summer School in Chemoinformatics](https://youtube.com/playlist?list=PLhgURFExPmJsDuHevu5n8y0R41WsXfbnC) - Summer school lectures.
- [BIGCHEM](https://bigchem.eu/node/63) - Online course on big data applications in chemistry.
- [Drug Discovery Course](https://www.stereoelectronics.org/webDD/DD_home.html) - Foundations of drug discovery and development.
- [drugdesign.org](https://www.drugdesign.org/) - Free courses on drug design and cheminformatics.
- [Cheminformatics OLCC](https://chem.libretexts.org/Courses/Intercollegiate_Courses/Cheminformatics) - Intercollegiate course on cheminformatics theory and coding.
- [Python For Cheminformatics Docking](https://pdb101.rcsb.org/train/training-events/python4) - Python tutorials for molecular docking via RCSB.
- [DDA CDD Workshop](https://wcair.dundee.ac.uk/training/training-resources/computational-drug-design/) - Workshop on generative and computational drug design.
- [MDTutorials](http://www.mdtutorials.com/gmx/) - Step-by-step tutorials for MD simulations using GROMACS.

### Blogs
- [Practical Fragments](http://practicalfragments.blogspot.com/) - Insights into fragment-based drug discovery.
- [Practical Cheminformatics](http://practicalcheminformatics.blogspot.com/) - Tools and tips for cheminformatics workflows.
- [Neovarsity](https://neovarsity.org/blogs?categories=CHEMINFORMATICS) - Deep-tech blog on cheminformatics and drug discovery applications.
- [Cheminformania](https://www.cheminformania.com/) - Cheminformatics meets deep learning and molecular modeling.
- [Daily Dose of Data Science](https://www.blog.dailydoseofds.com/) - Digestible data science tutorials and concepts.
- [Machine Learning Mastery](https://machinelearningmastery.com/) - Practical ML guides for developers and scientists.
- [Chem-Workflows](https://chem-workflows.com/index.html) - Jupyter-based chemistry workflows and tutorials.
- [Structural Bioinformatics](https://proteinstructures.com/) - Guide to structure-based drug design and protein modeling.
- [McConnellsMedChem](https://mcconnellsmedchem.com/) - Medicinal chemistry insights and commentary.
- [DrugDiscovery.NET](http://www.drugdiscovery.net/) - AI-powered approaches to drug discovery.
- [MacinChem](https://macinchem.org/) - Computational chemistry tools for macOS users.
- [Jeremy Monat](https://bertiewooster.github.io/) - Cheminformatics research and academic resources.
- [RDKit blog](https://greglandrum.github.io/rdkit-blog/) - A rich collection of tutorials, technical tips, and experimental insights from Greg Landrum.
- [DeepMedChem](https://www.deepmedchem.com/) - AI-powered insights, tool reviews, and workflows for modern drug discovery.

### Instructional Notebooks
- [TeachOpenCADD](https://projects.volkamerlab.org/teachopencadd/all_talktorials.html) - Modular Jupyter tutorials for CADD workflows and concepts.
- [intro_pharma_ai](https://github.com/kochgroup/intro_pharma_ai) - Notebook-based introduction to AI applications in pharma.
- [Practical Cheminformatics Tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials) - Hands-on Jupyter tutorials for RDKit, SAR, clustering, generative models, and ML pipelines.
- [AI/DL for Life Sciences](https://onlinelibrary.wiley.com/doi/10.1002/ardp.202200628) - Interactive notebooks showcasing AI/DL use cases in life sciences.

## Labs and Research Groups

- [Carlsson Lab](https://www.carlssonlab.org/) - GPCR modeling, receptor-ligand interactions, MD, docking, and AI for drug discovery. (Uppsala University, Sweden)
- [InSiliChem](https://insilichem.com/) - Computational chemobiology and metalloenzyme design. (Universitat Autònoma de Barcelona, Spain)
- [LCBC](https://sites.google.com/view/lcbc) - Molecular dynamics, free energy calculations, retrosynthesis using machine learning. (Seoul National University, Korea) 
- [Angelo Raymond Rossi](https://angeloraymondrossi.github.io/) - High-performance computing for computational chemistry and cheminformatics. (University of Connecticut, USA)
- [Laboratory of Chemoinformatics](https://complex-matter.unistra.fr/en/research-teams/laboratory-of-chemoinformatics/team/) - QSAR/QSPR, chemical similarity, and virtual screening. (Université de Strasbourg / CNRS, France)
- [Erastova Lab](https://www.erastova.xyz/) - Molecular modeling of soft matter and biomolecular simulations. (University of Edinburgh, UK)
- [The Ballester Group](https://ballestergroup.github.io/) - Developing ML/AI methods for structure-based scoring and virtual screening. (Imperial College London, UK)
- [Meiler Lab](https://meilerlab.org/) - Rosetta software, protein design, and ML-based protein engineering. (Vanderbilt / Leipzig University, USA / Germany)
- [COMP3D](https://comp3d.univie.ac.at/) - Develops and applies AI methods to design safe, effective pharmaceuticals and agrochemicals. (University of Vienna, Austria) 
- [Bonvin Lab](https://www.bonvinlab.org/) - Computational structural biology, HADDOCK, and integrative modeling. (Utrecht University, Netherlands)
- [Volkamer Lab](https://volkamerlab.org/) - Binding site analysis and AI-powered virtual screening. (Saarland University, Germany)
- [AI Laboratory for Molecular Engineering](https://ailab.bio/) - PROTACs, molecular glues, and ML for chemistry and life sciences. (Chalmers University, Sweden)  
- [Loschmidt Labs - PEG](https://loschmidt.chemi.muni.cz/peg/) - Protein and enzyme engineering, AI-assisted enzyme design. (Masaryk University, Czechia)
- [QSAR4U](https://qsar4u.com/index.php) - Cheminformatics tools, QSAR modeling, CReM, and EasyDock. (Palacky University, Czechia)
- [LBMD](https://www.chem.kuleuven.be/lbmd/index.html) - Computational strategies to understand and engineer biomolecular systems. (KU Leuven, Belgium)

---
