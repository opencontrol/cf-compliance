
# Cloud Foundry Compliance
This repository contains compliance data for the following Cloud Foundry components:
Application Security Groups, Cloud Controller, Warden, BOSH, DEA, UAA, Loggregator

To import these data into a OpenControl project add the follow code to your opencontrol.yaml file. 
```yaml
dependencies:
  systems:
    - url: https://github.com/opencontrol/cf-compliance
      revision: master
```

For more information on the opencontrol.yaml visit the [Compliance Masonry CLI](https://github.com/opencontrol/compliance-masonry#creating-an-opencontrol-project). 

# BDD Tests
This repository also contains [setup and run instructions for a set of BDD test](https://github.com/opencontrol/cf-compliance/tree/master/BDD) that help verify Cloud Foundry control implementations. 
