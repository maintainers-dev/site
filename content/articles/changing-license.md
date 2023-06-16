---
title: "Can I Change the License of my Project?"
date: 2023-06-16T21:32:13+01:00
draft: false
tags: ["starter", "growing"]
---

If you have permission from all of the copyright holders of the codebase the, generally speaking, yes! Otherwise, like most things, it depends.

If everything in the project was written and belongs to you, and you're not distributing other works as part of your project, then you're free to change the license however you desire. Keep in mind though, changing a license won't retroactively apply to older versions that have been distributed as open source, but you can change the license for newer versions.

If your software under the license contains, or is being distributed with, other software then the licenses of that software can affect which license you use. This is the same as when first choosing a license. As an example, using GPL licensed library code in your project can mean your project has to be provided under a compatible license.

If others have contributed code to your project, then by default they are still the copyright holder of that code. Changing the license would mean changing the freedoms upon the code that those users provided their contributions under. For many "permissive" open source licenses, this isn't a concern since they don't assure the code freedoms, or have the requirements, that need to be considered when changing licenses. For many licenses, specifically those referred to as "copyleft", you'd need to get permission from the existing contributors if changing to an incompatible license. In such an event, the three most common options are:

- Contact the previous contributes to request permission.
- Remove and/or replace the previous contributions.
- Before accepting any contributions, require contributors to agree that future relicensing of their contributions is allowed.

That last one is commonly achieved by what's known as a "Contributor License Agreement" (CLA). Many projects using copyleft licenses, especially those managed by large companies, will have a requirement to sign a CLA as part of their contributor  process, to allow future relicensing among other things.

## Common Questions

- [How do I Choose a License?](/articles/choosing-a-license/)

## Further Reading

- [Wikipedia - Contributor License Agreement](https://en.wikipedia.org/wiki/Contributor_License_Agreement)