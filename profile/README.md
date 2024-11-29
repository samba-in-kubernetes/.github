## Hi there 👋

The samba-in-kubernetes organization is the home of a few software projects related to the [Samba](https://samba.org) project.

The original purpose was to create Samba Containers and a [Kubernetes](https://kubernetes.io) operator for running Samba within Kubernetes clusters.

Two major projects for this purpose are [samba-container](https://github.com/samba-in-kubernetes/samba-container)
and [samba-operator](https://github.com/samba-in-kubernetes/samba-operator). These projects are intended for direct use by a wide audience.

Additionally, this organization hosts many related projects that help support, build, and test the container and operator projects.

[sambacc](https://github.com/samba-in-kubernetes/sambacc) hosts a samba configuration tool and server container entry point.
[smbmetrics](https://github.com/samba-in-kubernetes/smbmetrics) provides a server that exports metrics from Samba in Prometheus format.
[samba-build](https://github.com/samba-in-kubernetes/samba-build) is used to continuously build Samba RPMs from Samba development branches.

Test infrastructure and test cases for testing clustered Samba on distributed filesystems like
[Gluster](https://gluster.org) and [Ceph](https://ceph.io) can be found in the Samba Integration Testing (SIT) repositories:
[sit-environment](https://github.com/samba-in-kubernetes/sit-environment)
and [sit-test-cases](https://github.com/samba-in-kubernetes/sit-test-cases)

Container images produced by our projects are hosted in our [quay.io](https://quay.io) image repositories: [samba container images](https://quay.io/samba.org)

Note that the images produced by samba-containers and smbmetrics are not specific to Kubernetes at all.
For example, these images are also used by the [Ceph](https://ceph.io) project. Only the samba-operator image requires Kubernetes.

