<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# CTX-Gateway
This module contains a Cortex subtask which allows users to interact with the Cortex Flow API both locally and remotely

## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other)
1) [Support and Warranty](#support-and-warranty)
1) [Installation](#installation)
1) [How to use](#how-to-use)
1) [How you can contribute](#how-you-can-contribute)
1) [Versioning](#versioning)
1) [Licensing](#licensing)

## Dependencies
### Cortex Version
The CTX-Gateway subtasks require the following:
*	Cortex v6.5, v7.0 or v7.1 installed on the Cortex Application Server

The following subtasks are associated with endpoints within the Cortex Flow API that will be supported in future versions of Cortex:
*	FN-Flow-Names
*	SF-Start-Flow
*	SFA-Start-Flow-Async
*	StoF-Stop-Flow

The following subtasks are associated with endpoints within the Cortex Flow API that MAY OR MAY NOT be supported in future versions of Cortex. They have been developed and tested on versions v6.5, v7.0 and v7.1 of Cortex, but are subject to change at ANY time from v7.2 onwards.
*	GGBT-Get-Gateway-Bearer-Token
*	EF-Export-Flows
*	IF-Import-Flows
*	PFTS-Publish-Flows-To-Server


### OCIs
The CTX-Gateway module requires a Cortex PowerShell Agent, which should be installed by default

### Files
The CTX-Gateway module requires the following files:
* [CTX-Gateway Studio Package](https://github.com/CortexIntelligentAutomation/CTX-Gateway/releases/download/V1.0/CTX-Gateway.studiopkg)


### Other
The CTX-Gateway module has no additional requirements

## Support and Warranty 
This module is supplied as a template that you can amend and extend to fit your requirements, as such it is not supported as part of the Cortex Product suite under the Cortex product support agreement.

## Installation
Details of how the module should be imported into Cortex can be found in the [Deployment Plan](https://github.com/CortexIntelligentAutomation/CTX-Gateway/blob/master/CTX-Gateway%20-%20Deployment%20Plan.pdf).

## How to use
A detailed User Guide has been provided with instructions on how to use the module, available [here](https://github.com/CortexIntelligentAutomation/CTX-Gateway/blob/master/CTX-Gateway%20-%20User%20Guide.pdf). Configuring the subtask's inputs and outputs are detailed in notes on the subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
The CTX-Gateway module has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.0 | 15/10/2020 | Cortex Gateway | Creation of: FN-Flow-Names, SF-Start-Flow, SFA-Start-Flow-Async, StoF-Stop-Flow, GGBT-Get-Gateway-Bearer-Token, EF-Export-Flows, IF-Import-Flows, PFTS-Publish-Flows-To-Server


## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2018 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
