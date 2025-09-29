---
title: "Updated Virtual observatory (GVO) data"
summary: "This delivery updates the preliminary geomagnetic datasets and models delivered by DTU. The report delivered at that time described in detail the datasets and processing schemes, the details of the processing schemes are unchanged."
date: 2023-09-01
author: "Chris Finlay"
draft: false
---


From [this address](http://www.spacecenter.dk/files/magnetic-models/GVO/) one can access a zip file containing updated Swarm GVO data.

This contains updated 4 monthly and 12 monthly GVOs produced using DTU's GVO software, and also (for completeness) the latest 1 monthly official Swarm GVO product (which involves additional processing steps applied by BGS). These were derived from Swarm L1B Mag-L OPER data version 0602. Data up to end of April 2023 was used for the 4 monthly and 1 monthly GVOs and data up to end of 2022 for the 12 monthly GVOs. No update of the Oersted, CHAMP, Cryosat-2 or Grace GVOs is provided in this delivery, the latest versions of these legacy missions are still those of the previous release (see associated [zip folders for each mission](http://www.spacecenter.dk/files/magnetic-models/GVO/)) as there has been no change in the processing scheme.

Each GVO file includes values for observed field, core field (with estimates of magnetospheric and ionospheric fields removed) and SV (from annual difference of the core field data). The file format follows the Swarm Geomagnetic Virtual Observatories Product Definition, Rev.2B, SW-DS-DTU-GS-004_2-1_GVO_PDD. See [Hammer et al. (2021)](http://localhost:1313/4dearth/publications/#2021) for full details of the GVO processing algorithm. Further specific details regarding this update are found in the README file in the zipped folder.


Contact: Chris Finlay at cfinlay at space.dtu.dk 