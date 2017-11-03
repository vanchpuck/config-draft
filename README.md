# Possible config merging strategy
* Configs are hierarchically structured.
* .properties files are merged on build (more specific config could override less specific),
* .xml files aren't merged together but its properties are merged on oozie runtime and the override order corresponds to order in which corresponding files are imported in workflow.xml