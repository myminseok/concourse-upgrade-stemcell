# concourse-upgrade-stemcell pipeline

This is a [Concourse](https://concourse.ci) pipelines for upgrading upgrading [Pivotal Cloud Foundry](https://pivotal.io/platform) stemcells.

**usage**
The pipeline tracks and updates a single stemcell major version for a single IaaS type. To track multiple stemcells / IaaS types, simply change `params.yml` and create a new pipeline for each combination.

For example, you might name a pipeline that uses the defaults in this repo 'upgrade-stemcell-3363-aws'.
