# PowellSoft.Attributes

## ValidateModelStateAsyncAttribute

Include Validate Model View State attribute for .net core.

The ValidateModelStateAsyncAttribute implements IAsyncActionFilter. It simply checks whether the ModelState is valid. If it isn't then it will set the context result to be a BadRequestObjectResult, passing in the ModelState.

Credit where it's due https://www.talkingdotnet.com/validate-model-state-automatically-asp-net-core-2-0/
