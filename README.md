# SS Wrapper Service

### Overview

The purpose of this service is to simply proxy incoming Shared Service calls, capture the output from the SS calls, and then 
asynchronously publish the results to the ss-comparison-service for comparison with results from another call.

This is intended to be used only in the non-prod environments and mirrors what the prod aims environment (mirth) does.
