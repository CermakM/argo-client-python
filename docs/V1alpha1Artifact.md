# V1alpha1Artifact

Artifact indicates an artifact to place at a specified path
## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**archive** | [**V1alpha1ArchiveStrategy**](V1alpha1ArchiveStrategy.md) |  | [optional] 
**archive_logs** | **bool** | ArchiveLogs indicates if the container logs should be archived | [optional] 
**artifactory** | [**V1alpha1ArtifactoryArtifact**](V1alpha1ArtifactoryArtifact.md) |  | [optional] 
**_from** | **str** | From allows an artifact to reference an artifact from a previous step | [optional] 
**git** | [**V1alpha1GitArtifact**](V1alpha1GitArtifact.md) |  | [optional] 
**global_name** | **str** | GlobalName exports an output artifact to the global scope, making it available as &#39;{{workflow.outputs.artifacts.XXXX}} and in workflow.status.outputs.artifacts | [optional] 
**hdfs** | [**V1alpha1HDFSArtifact**](V1alpha1HDFSArtifact.md) |  | [optional] 
**http** | [**V1alpha1HTTPArtifact**](V1alpha1HTTPArtifact.md) |  | [optional] 
**mode** | **int** | mode bits to use on this file, must be a value between 0 and 0777 set when loading input artifacts. | [optional] 
**name** | **str** | name of the artifact. must be unique within a template&#39;s inputs/outputs. | 
**optional** | **bool** | Make Artifacts optional, if Artifacts doesn&#39;t generate or exist | [optional] 
**path** | **str** | Path is the container path to the artifact | [optional] 
**raw** | [**V1alpha1RawArtifact**](V1alpha1RawArtifact.md) |  | [optional] 
**s3** | [**V1alpha1S3Artifact**](V1alpha1S3Artifact.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


