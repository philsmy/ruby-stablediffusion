# RStableDiffusionAI::ExtrasBatchImagesRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**resize_mode** | **Integer** | Sets the resize mode: 0 to upscale by upscaling_resize amount, 1 to upscale up to upscaling_resize_h x upscaling_resize_w. | [optional] [default to RESIZE_MODE.0]
**show_extras_results** | **BOOLEAN** | Should the backend return the generated image? | [optional] [default to true]
**gfpgan_visibility** | [**BigDecimal**](BigDecimal.md) | Sets the visibility of GFPGAN, values should be between 0 and 1. | [optional] [default to 0]
**codeformer_visibility** | [**BigDecimal**](BigDecimal.md) | Sets the visibility of CodeFormer, values should be between 0 and 1. | [optional] [default to 0]
**codeformer_weight** | [**BigDecimal**](BigDecimal.md) | Sets the weight of CodeFormer, values should be between 0 and 1. | [optional] [default to 0]
**upscaling_resize** | [**BigDecimal**](BigDecimal.md) | By how much to upscale the image, only used when resize_mode&#x3D;0. | [optional] [default to 2]
**upscaling_resize_w** | **Integer** | Target width for the upscaler to hit. Only used when resize_mode&#x3D;1. | [optional] [default to 512]
**upscaling_resize_h** | **Integer** | Target height for the upscaler to hit. Only used when resize_mode&#x3D;1. | [optional] [default to 512]
**upscaling_crop** | **BOOLEAN** | Should the upscaler crop the image to fit in the chosen size? | [optional] [default to true]
**upscaler_1** | **String** | The name of the main upscaler to use, it has to be one of this list: None , Lanczos , Nearest , ESRGAN_4x , LDSR , R-ESRGAN 4x+ , R-ESRGAN 4x+ Anime6B , ScuNET GAN , ScuNET PSNR , SwinIR 4x | [optional] [default to &#x27;None&#x27;]
**upscaler_2** | **String** | The name of the secondary upscaler to use, it has to be one of this list: None , Lanczos , Nearest , ESRGAN_4x , LDSR , R-ESRGAN 4x+ , R-ESRGAN 4x+ Anime6B , ScuNET GAN , ScuNET PSNR , SwinIR 4x | [optional] [default to &#x27;None&#x27;]
**extras_upscaler_2_visibility** | [**BigDecimal**](BigDecimal.md) | Sets the visibility of secondary upscaler, values should be between 0 and 1. | [optional] [default to 0]
**upscale_first** | **BOOLEAN** | Should the upscaler run before restoring faces? | [optional] [default to false]
**image_list** | [**Array&lt;FileData&gt;**](FileData.md) | List of images to work on. Must be Base64 strings | 

