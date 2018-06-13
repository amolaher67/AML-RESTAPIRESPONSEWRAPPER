# AML-RESTAPIRESPONSEWRAPPER
To use the filter and wrapper, you just need to register them within your WebApiConfig.cs file:

Hide   Copy Code
config.Filters.Add(new ApiExceptionFilter());
config.MessageHandlers.Add(new WrappingHandler());
