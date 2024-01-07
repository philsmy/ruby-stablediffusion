# RStableDiffusionAI::ModulesApiModelsProgressResponse

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**progress** | [**BigDecimal**](BigDecimal.md) | The progress with a range of 0 to 1 | 
**eta_relative** | [**BigDecimal**](BigDecimal.md) |  | 
**state** | **Object** | The current state snapshot | 
**current_image** | **String** | The current image in base64 format. opts.show_progress_every_n_steps is required for this to work. | [optional] 
**textinfo** | **String** | Info text used by WebUI. | [optional] 

