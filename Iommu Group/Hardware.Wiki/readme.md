# Intel Xeon has ACS Support, whereas most Desktops Don't:
https://www.reddit.com/r/VFIO/comments/gwsw6y/iommu_groups_explained_or_how_to_run_dual_gpus/

## quote:
>There are two main takeaways to all this:
>
>A luxury "enthusiast" configuration with two high-end GPUs is not happening on a regular Intel consumer CPU (anything with only 16 lanes). This insufficient PCIe bandwidth is (partly) why the SLI bridge had to be invented. In 2020 PCIe lanes are actually starting to matter for GPUs, so do yourself a favor and stop trying to connect 32 lanes when you only have 16. You need a workstation CPU (and socket) for that (i.e. X-series or Xeon), they are the only ones with more lanes. These should also support ACS directly. Or consider AMD, they have more lanes and PCIe 4.0 (big win once cards support it).
