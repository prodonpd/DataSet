## The struct of DataSet
* name(slug): the name of image
* type: the type of this data
* publisher:
  * id: the id of this publisher
  * name: publisher's username
* created_at: the time that this image was created
* updated_at: the time that this image was updated
* short_description: short description of this image
* full_description: full description of this image
* source: source of this image(community or official)
* popularity: popularity of this image
* categories: categories of this image
* operating_systems:
  * label: operating system's label
  * name: operating system's name
* architectures:
  * label: architecture's label
  * name: architecture's name
* pull_count: pull count of image
* moreinfo:
  * user: user who own this image
  * name: name of this repo
  * namespace: namespace of this repo
  * pull_count: pull count of this image
  * last_updated: last update time of this image
  * full_description: full description of this image
* tag:
  * name: tag's name
  * full_size: size of this image's tag
  * images:
    * architecture: this tag's architecture
    * digest: this tag's digest
    * size: size of this image's tag
  * history:
    * layers:
      * digest: this layer's digest
      * size: this layer's size
      * instruction: the command execute in this layer

### egopulse\moon:v15994.json
* meta data of Docker iamge egopulse/moon:v15994, which contains a misconfiguration risk

### layer5\meshery-octarine:59e1a0d1ac22b2097a61286dfb8beed8114fe36d.json
* meta data of Docker image layer5/meshery-octarine:59e1a0d1ac22b2097a61286dfb8beed8114fe36d, which contains sensitive information

### monotosh\redis:3.0.7.json
* meta data of Docker image monotosh/redis:3.0.7, which contains unauthorized access risk

### node:12.10.json
* meta data of Docker image node:12.10, which contains software vulnerabilities

### killroytest\temp:latest.json
* meta data of Docker image killroytest/temp:latest, which contains coinminer malware
