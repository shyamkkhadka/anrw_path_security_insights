# Artifacts of the paper submitted in Applied Networking Research Workshop (ANRW'24)
Infers possible paths from one AS to another, then gives Route Origin Validation (ROV) status of the overall path. 
Paper: **Assessing the security of Internet paths: A case study
of Dutch critical infrastructures**
## Program file information
1. ing_ms_path_finder.ipynb: Finds paths from an ASN to other
2. check-valley-free-rov-ing-ms.ipynb: Checks valley-free conditons of new paths and calcuate ROV scores based on [RoVista](https://rovista.netsecurelab.org/)
3. anrw-plot-results.ipynb: Plots results

If you this code, please cite the paper as below:
```
@inproceedings{10.1145/3673422.3674899,
    author = {Khadka, Shyam Krishna and Bayhan, Suzan and Holz, Ralph and Hesselman, Cristian},
    title = {Assessing the security of Internet paths: A case study of Dutch critical infrastructures},
    year = {2024},
    isbn = {9798400707230},
    publisher = {Association for Computing Machinery},
    address = {New York, NY, USA},
    url = {https://doi.org/10.1145/3673422.3674899},
    doi = {10.1145/3673422.3674899},
    abstract = {Many critical infrastructures (CIs) rely on cloud services (e.g., email) for their daily operations. However, these CIs typically have limited insight into the security status of the paths that their traffic might follow across the Internet to reach their cloud provider's infrastructures. For example, a CI might not know that their traffic passes through Autonomous Systems (ASes) that do not implement Route Origin Validation (ROV). As a result, the CI is vulnerable to prefix hijacks, which can render the cloud operator unavailable to the CI or breach the confidentiality and integrity of the CI's data. To provide such insights, we develop a generic method that finds plausible paths from one AS to another and identifies to what extent the ASes on the path support ROV. We use our method for a case study to find secure paths from four CIs in the Netherlands to Microsoft mail, which many CIs use. We use Border Gateway Protocol (BGP) routing data from four route collectors in the Netherlands in combination with the ROV scores of the ASes. Our analysis shows the existence of multiple fully ROV-protected paths from the four CIs to Microsoft among a larger set of partially ROV-protected paths. Our case study also shows that implementing ROV fully by the immediate upstream providers of CIs would result in an increase in the number of fully ROV-protected paths by 72.5\% on average.},
    booktitle = {Proceedings of the 2024 Applied Networking Research Workshop},
    pages = {67–73},
    numpages = {7},
    keywords = {Internet path finding, Path security},
    location = {Vancouver, AA, Canada},
    series = {ANRW '24}
}
```
