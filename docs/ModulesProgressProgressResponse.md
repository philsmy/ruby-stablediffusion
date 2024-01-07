# RStableDiffusionAI::ModulesProgressProgressResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**active** | **BOOLEAN** |  | 
**queued** | **BOOLEAN** |  | 
**completed** | **BOOLEAN** |  | 
**progress** | [**BigDecimal**](BigDecimal.md) | The progress with a range of 0 to 1 | [optional] 
**eta** | [**BigDecimal**](BigDecimal.md) |  | [optional] 
**live_preview** | **String** | Current live preview; a data: uri | [optional] 
**id_live_preview** | **Integer** | Send this together with next request to prevent receiving same image | [optional] 
**textinfo** | **String** | Info text used by WebUI. | [optional] 

