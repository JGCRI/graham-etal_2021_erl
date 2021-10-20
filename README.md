_your zenodo badge here_

# graham-etal_2021_erl

**Future evolution of virtual water trading in the United States electricity sector**

Neal Graham<sup>1\*</sup>, Gokul Iyer<sup>1</sup>, Marshall Wise<sup>1</sup>, Mohamad Hejazi<sup>2</sup>, Thomas B. Wild<sup>1,3,4</sup>

<sup>1 </sup> Joint Global Change Research Institute, College Park, MD, USA
<sup>2 </sup> King Abdullah Petroleum Studies and Research Center (KAPSARC), Riyadh 11672, Saudi Arabia
<sup>3 </sup> Earth System Science Interdisciplinary Center (ESSIC), University of Maryland, College Park, MD 20740, USA
<sup>4 </sup> Department of Civil and Environmental Engineering, University of Maryland, College Park, MD 20740, USA

\* corresponding author:  neal.graham@pnnl.gov

## Abstract
Future transformations in the electricity sector could entail major shifts in power sector technology mixes and electricity trade, with consequences for the trading of virtual water. Previous virtual water trade studies largely focus on historical timeframes. We explore, for the first time, future – through 2050 – virtual water trade driven by electricity trade under a range of future electricity sector transformation scenarios using the United States as an example. Under a business-as-usual scenario, virtual water trading in 2050 decreases by 3% relative to 2015 levels. By contrast, virtual water trading increases respectively by 3%, 26%, and 32%, in scenarios characterized by higher socioeconomic growth, higher potential for transmission expansion, and low-carbon transitions. These increases are driven by electricity generation expansion in the western U.S., resulting in higher virtual water trade to the east. In addition, we find that as electricity generation shifts west, an increased amount of nonrenewable groundwater will be consumed to generate electricity that is supplied to the east. Independent of scenario, the US electricity grid largely relies on virtual water exports from only a few states. Our study highlights the need for integrated and national strategies to manage the water and electric systems.

## Journal reference
TBD

## Code reference
References for each minted software release for all code involved.  

These are generated by Zenodo automatically when conducting a release when Zenodo has been linked to your GitHub repository. The Zenodo references are built by setting the author order in order of contribution to the code using the author's GitHub user name.  This citation can, and likely should, be edited without altering the DOI.

If you have modified a codebase that is outside of a formal release, and the modifications are not planned on being merged back into a version, fork the parent repository and add a `.<shortname>` to the version number of the parent and construct your own name.  For example, `v1.2.5.hydro`.

Human, I.M. (2021, April 14). Project/repo:v0.1.0 (Version v0.1.0). Zenodo. http://doi.org/some-doi-number/zenodo.7777777

## Data reference

### Input data
Reference for each minted data source for your input data.  For example:

Human, I.M. (2021). My input dataset name [Data set]. DataHub. https://doi.org/some-doi-number

### Output data
Reference for each minted data source for your output data.  For example:

Human, I.M. (2021). My output dataset name [Data set]. DataHub. https://doi.org/some-doi-number

## Contributing modeling software
| Model | Version | Repository Link | DOI |
|-------|---------|-----------------|-----|
| model 1 | version | link to code repository | link to DOI dataset |
| model 2 | version | link to code repository | link to DOI dataset |
| component 1 | version | link to code repository | link to DOI dataset |

## Reproduce my experiment
Fill in detailed info here or link to other documentation that is a thorough walkthrough of how to use what is in this repository to reproduce your experiment.


1. Install the software components required to conduct the experiement from [Contributing modeling software](#contributing-modeling-software)
2. Download and install the supporting input data required to conduct the experiement from [Input data](#input-data)
3. Run the following scripts in the `workflow` directory to re-create this experiment:

| Script Name | Description | How to Run |
| --- | --- | --- |
| `step_one.py` | Script to run the first part of my experiment | `python3 step_one.py -f /path/to/inputdata/file_one.csv` |
| `step_two.py` | Script to run the last part of my experiment | `python3 step_two.py -o /path/to/my/outputdir` |

4. Download and unzip the output data from my experiment [Output data](#output-data)
5. Run the following scripts in the `workflow` directory to compare my outputs to those from the publication

| Script Name | Description | How to Run |
| --- | --- | --- |
| `compare.py` | Script to compare my outputs to the original | `python3 compare.py --orig /path/to/original/data.csv --new /path/to/new/data.csv` |

## Reproduce my figures
Use the scripts found in the `figures` directory to reproduce the figures used in this publication.

| Script Name | Description | How to Run |
| --- | --- | --- |
| `generate_figures.py` | Script to generate my figures | `python3 generate_figures.py -i /path/to/inputs -o /path/to/outuptdir` |
