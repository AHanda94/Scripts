##vLUME Scripts

An important feature of vLUME the ability to perform local analysis on a subregion of point-cloud data (RoI). C#
scripts can be programmed to perform any custom analysis once uploaded to the folder
\vLume_Data\StreamingAssets\Scripts within the vLUME installation directory (.cs file extension). You can find
further information on how program and use the scripts in the software manual.
We include four useful functions as .cs scripts for the vLUME interpreter that can be used for local cloud data-point
analysis and that are often used in SMLM. You can apply them by selecting a RoI and toggling to the scripting menu
(see manual). Note: depending on the complexity of the script you might see a busy indicator (out of the virtual
environment) when called which is normal. Also be aware that some operations require more than the available memory
particularly in large datasets (i.e. density plots with millions of points that need to compute every single distance from
one point to another).
We include four scripts however it is our hope that we will nucleate communities to develop and share their own,
included are:

#
![](https://www.biorxiv.org/content/biorxiv/early/2020/01/21/2020.01.20.912733/F1.large.jpg?width=800&height=600&carousel=1)

**Fig. 1** **a)**  *v*LUME rapidly and simply takes large, multidimensional point-cloud datasets from 2D visualization into an immersive 3D VR environment through a systematic workflow: 1) multi-dimensional, SMLM image stacks are processed with any standard fitting algorithms providing multiparameter outputs as .csv or .txt files. 2) The resultant datasets can then be dragged and dropped directly into the *v*LUME software and instantly visualised in virtual reality. 3) By anchoring at user-defined waypoints around these data, a smoothly interpolated fly-through video can be created and exported providing the user with a tool to effectively communicate their discoveries. **b)**  *v*LUME facilitates the 3D, VR visualization of millions of localizations, demonstrated by the super-resolved membrane of a T cell with *v*LUME. The accessible interface enables the user to customize their *v*LUME. The T cell is ~10 μm in diameter and has a isotropic resolution of ~24 nm. (FSA) **c)** Comparative inspection of artifacts introduced into data by localization fitting tools can be quickly performed. This can be seen by comparing localizations of Nuclear Pore Complexes fitted with both QuickPALM and ThunderSTORM algorithms. Scale the NPC of the ~100 nm in diameter, and the nuclear membrane ~20μm in diameter, data is taken over ~200 nm range axial range in z **d)** Selection and isolation of nanoscale, complex biological features can be easily achieved by the user. As examples, a stalk of _a Caulobacter crecentus_ bacterium and a filament of a tubulin network were isolated and a Rol saved for further analysis. The microtubules tangle shows a region of ~ 20 μm × 30 μm (and about 500 nm in depth). The diameter section of a single microtubule is ~40 nm. **e)** Regions of interest can then be analyzed to instantly quantify desired properties using bespoke C# scripts (Ripley’s K, Local Density Plots, Nearest Neighbors and any others).

## Video Samples

As a demonstration of the capabilities of *v*LUME we show four videos corresponding to the four key benefits using cutting edge SMLM samples. These and other supplementary videos can be found in the BioRXiv preprint repository.

|                |Link                          |Description                         |
|----------------|---------------------------------|-----------------------------|
|Walk-through     |[Video 1](https://www.biorxiv.org/content/biorxiv/early/2020/01/21/2020.01.20.912733/DC2/embed/media-2.zip?download=true)           |Overview of the main GUI and functionality in vLUME             |
|Segmentation         |[Video 2](https://www.biorxiv.org/content/biorxiv/early/2020/01/21/2020.01.20.912733/DC3/embed/media-3.zip?download=true)             |Demonstration of a user isolating a single microtubule from a complex tangle            |
|Local bespoke analysis          |[Video 3](https://www.biorxiv.org/content/biorxiv/early/2020/01/21/2020.01.20.912733/DC6/embed/media-6.zip?download=true) |Nearest Neighbour script application to a NPC dataset|
|Exporting features          |[Video 4](https://www.biorxiv.org/content/biorxiv/early/2020/01/21/2020.01.20.912733/DC7/embed/media-7.zip?download=true) |Setting waypoints in the 3D space using vLUME and saving these points as a video|
