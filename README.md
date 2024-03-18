# a3s
Backing code for Articleman As A Service

This software should not be considered "open-source." It is "source-available" under the Sustainable Use License.

None of this code is required to compile and use Articleman, even for commercial purposes. You are free to commercialize any and all of `libArticles/articleman` in any way you see fit as long as it still complies with the AGPL. This repository, `libArticles/a3s`, cannot be commercialized by anyone other than us, `libArticles`, unless we have given explicit, written consent and therefore bypassed the SUL ourselves by providing a custom license to you.

---

A3S contains code that can be optionally compiled into Articleman or run separately to provide features like:
* multi-tenancy (MultiTen)
* billing
* auto-config of third-party services
* scaling and orchestration
* collection of metrics that would otherwise be irrelevant.

As long as you follow the SUL, you can run A3S on your own servers, but we *do not* support it. If you'd like something that's easy to set up, just run Articleman. You don't need A3S to get all of Articleman's user-facing features. 
