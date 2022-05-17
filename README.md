# D7.5: Data collected for the FSA and environmental impact study

<p float="center">
  <img src="./prepare_ships_logo.png" width="200" />
  <img src="./EUSPA Horizon logo.png" width="400" /> 
</p>

This repository contains deliverable D7.5 of the research project [PrePare Ships](https://prepare-ships.eu/).

Author(s): Fredrik Olsson (RISE)

Reviewer(s): Luis Sanchez-Heres (RISE), Joakim Lundman (RISE)

The headlines below follow the expected template for the Open Research Data Pilot's [Data Management Plan](https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-data-mgt_en.pdf).


## 1. Data Summary
The data present in this repository was generated and collected for the purpose of deliverable `D7.1 Report on FSA and environmental impact` which is the main report describing the **validation** of the PrePare Ships system as a whole.

This repository contains two distinct data sets:
* **Simulation output from full mission bridge simulations**

  Format: [CSV](https://sv.wikipedia.org/wiki/Comma-separated_values)
  
  Origin: [Chalmers Full Mission Bridge Simulator](https://www.chalmers.se/en/researchinfrastructure/cms/Pages/Full-Mission-Bridge-Simulator.aspx)

* **Simulation output from desktop simulations** 
  
  Format: [JSON](https://sv.wikipedia.org/wiki/JSON)
  
  Origin: [FakECDIS](https://github.com/MO-RISE/fakecdis)

The total size of both datasets is on the order of 10s of MBs. For further details about the datasets, please refer to `D7.1 Report on FSA and environmental impact`.

The data is mainly expected to be useful for cross-examination of the results presented in `D7.1 Report on FSA and environmental impact`


## 2. FAIR Data

### 2.1 Making data findable, including provisions for metadata
The datasets are small, contain relevant metadata and follows naming conventions according to common practice in the field of Naval Architecture. 

The datasets are timeseries and, as such, the time parameter is the unique identifier for each row (csv) or object (JSON) in each dataset respectively.

The datasets are versioned through the inclusion of [`tags`](https://git-scm.com/docs/git-tag) in the repository adhering to the concept of [semantic versioning](https://semver.org/).


### 2.2 Making data openly accessible
All data part of this repository is openly available. It is made available as a git repository hosted on the well known development collaboration platform Github. The data may be accessed either directly through a browser or through any git client of choice.

### 2.3 Making data interoperable
The datasets are stored in clear text using well-known and standardized formats (csv and JSON) making them interoperable with most existing programming languages of today.

### 2.4 Increase data re-use (through clarifying licences)
All data part of this repository is made available under the [Apache 2.0 license](./LICENSE)

## 3. Allocation of resources
The estimated cost of making these datasets FAIR is negligible. The cost of  long term preservation is directly dependant on the hosting cost on Github, which at the moment of writing is zero. However, the potential value of preserving these datasets during any prolonged time is questionable.

## 4. Data security
The datasets do not contain any sensitive data and all of the datasets are openly available in this repository. In general, this repository is directly affected by the policies, warranties and liabilities outlined in [Github's Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service).

## 5. Ethical aspects
The datasets do not contain any directly personal data or data that can be traced back to any specific individual.

## 6. Other
N/A
