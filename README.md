# Azert.Pipeline
A simple synchronous pipeline utilising the pipes and filters pattern.

This contains a pipeline contract as well as implementation which you can sue in your projects.

Incldued is an IFilter contract. This should be implemented for each stage of your pipeline process. Each filter should then be registered with the pipeline, usually at application start.

There is also a nuget package available for this to easily consume in your applications https://www.nuget.org/packages/Azert.Pipeline.Synchronous/