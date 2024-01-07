# RStableDiffusionAI::EmbeddingItem

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**step** | **Integer** | The number of steps that were used to train this embedding, if available | [optional] 
**sd_checkpoint** | **String** | The hash of the checkpoint this embedding was trained on, if available | [optional] 
**sd_checkpoint_name** | **String** | The name of the checkpoint this embedding was trained on, if available. Note that this is the name that was used by the trainer; for a stable identifier, use &#x60;sd_checkpoint&#x60; instead | [optional] 
**shape** | **Integer** | The length of each individual vector in the embedding | 
**vectors** | **Integer** | The number of vectors in the embedding | 

