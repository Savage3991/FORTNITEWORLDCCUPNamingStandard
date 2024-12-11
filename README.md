# Central Naming Convention (CNC)

## Overview

**Central Naming Convention (CNC)** has kept the tradition of the abandoned [Unified Naming Convention (UNC)](https://github.com/UnifiedNamingConvention/). CNC will pave a way into having a seamless and universally compatible scripting API, both code maintainable and user-friendly. On the terrain of UNC, CNC intends to cover all the new aspects of scripting challenges while keeping the experience a "vanilla" one for developers.

## Why CNC?

As of now, scripting has posed trouble in support for multiple executors. Each executor has its own names of generic functions, leading to buggy scripts and more time used coding executor support. For instance, the condition of checking whether it is being executed by various executors now becomes : 

```lua
local is_executor_closure = is_syn_closure or is_fluxus_closure or is_sentinel_closure or is_krnl_closure or is_proto_closure or is_calamari_closure or is_electron_closure or is_elysian_closure
```

This redundancy imposes an additional annoyance of writing cross-compatibility scripts on developers. It defeats that by establishing a central , brandless standard which all executors can use.

## Contributing
The standard is written in markdown on this GitHub. Edits or additions are done through pull requests. Edits and additions are manually approved by the CNC Team and its advisors then is discussed by everyone. Go [here](CONTRIBUTING.md) for a guide on contributing.

## Supporting the CNC
As a product owner, your support of the CNC by following the API will result in a far smoother experience for scripters, as they are able to work on scripts that they can confidently say will work on **most** products. Once you have implemented the CNC's API, you can display so by adding the badge to your website, thread or application.

You can find the badge avaliable on our repo soon :)

This will notify people of your alliance in providing scripters with an easier method of engineering scripts that your consumers can enjoy.

NOTICE: If you, as a product owner, do not have all of these functions but yet support the ones you do - you then support UNC! You are more than able to display the badge on your website.

## Compatability:
You can run the CNC environment checking script to see how well your executor environment supports the CNC standard. Find the script [here.](CNCTest.lua)
