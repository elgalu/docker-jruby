# Changelog

Note sha256 digests are generated after pushing the image to the registry therefore the last version of this docker-selenium will always have digest TBD (to be determined) but will be updated manually at [releases][]

Note image ids also change after scm-source.json has being updated which triggers a cyclic problem so value TBD will be set here and updated in the [releases][] page by navigating into any release tag.

###### To get container versions
    docker exec jruby versions

## 9.1.2b
 + Date: 2016-06-09
 + TravisCI first run
 + Image tag details:
  + Timezone: Europe/Berlin
  + FROM ubuntu:xenial-20160525
  + JRuby: 9.1.2.0
  + Tested on kernel dev host: 4.4.0-23-generic x86_64
  + Tested on kernel CI  host: 3.19.0-30-generic x86_64
  + Built at dev host with: Docker version 1.11.2, build b9f10c9
  + Built at CI  host with: Docker version 1.11.2, build b9f10c9
  + Image size: 916.5 MB
  + Digest: sha256:731f2c9a7552f1bfcb74a2b73a1f2845a362c8162f7b1d796f54158abfe85751
  + Image ID: sha256:f2afce3599896b8c308797a85fdddda60eab3a1d18c103bf5102082b50fb8838

[releases]: https://github.com/elgalu/docker-jruby/releases/
