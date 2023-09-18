# quickhaul
Fast containers - optimise container cold start

![Containerd Architecture](https://github.com/akhilac1/quickhaul/assets/3939554/c88531d5-aaf3-4384-a232-b40169d95b73 "Containerd Architecture")

#Goals
- Experiment with stargz container format and derive metrics
- Deploy e2e setup and measure the improvement in size/launch time 
  
#References
- [What is a containerd snapshotter? - DEV Community](https://dev.to/napicella/what-is-a-containerd-snapshotters-3eo2)
- [Startup Containers in Lightning Speed with Lazy Image Distribution on Containerd | by Kohei Tokunaga](https://medium.com/nttlabs/startup-containers-in-lightning-speed-with-lazy-image-distribution-on-containerd-243d94522361)
- [firecracker-containerd/docs/architecture.md at main · firecracker-microvm/firecracker-containerd · GitHub](https://github.com/containerd/containerd/issues/3731)
- [Support remote snapshotter to speed up image pulling · Issue #3731 · containerd/containerd · GitHub] (https://github.com/containerd/containerd/issues/3731)
- [remote filesystem snapshotter · Issue #2943 · containerd/containerd · GitHub] (https://github.com/containerd/containerd/issues/2943)
- [Slacker](https://www.usenix.org/system/files/conference/fast16/fast16-papers-harter.pdf)
- [GitHub - containerd/stargz-snapshotter: Fast container image distribution plugin with lazy pulling] (https://github.com/containerd/stargz-snapshotter)
- [stargz-snapshotter/docs/ctr-remote.md at main · containerd/stargz-snapshotter · GitHub] (https://github.com/containerd/stargz-snapshotter/blob/main/docs/ctr-remote.md)
- [stargz-snapshotter/docs/estargz.md at main · containerd/stargz-snapshotter · GitHub] (https://github.com/containerd/stargz-snapshotter/blob/main/docs/estargz.md)
