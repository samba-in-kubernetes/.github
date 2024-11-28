## Hi there 👋

The samba-in-kubernetes organisation is the home of a few software projects around the [Samba](https://samba.org) project.

The original purpose was to create samba containers and an operator for running Samba in  [kubernetes](https://kubernetes.io).

The two central projects for this purpose are [samba-container](https://github.com/samba-in-kubernetes/samba-container)
and [samba-operator](https://github.com/samba-in-kubernetes/samba-operator).

Additionally, [sambacc](https://github.com/samba-in-kubernetes/sambacc) hosts the samba configuration tool used as the container entry point
and [smbmetrics](https://github.com/samba-in-kubernetes/smbmetrics) is a software that exports metrics from Samba in prometheus format.

An additional purpose of this organisation is to provide Samba RPM builds (via [samba-build](https://github.com/samba-in-kubernetes/samba-build))


Finally, another purpose is to provide test infrastructure and test cases for testing clustered Samba on a distributed filesystem like
[Gluster](https://gluster.org) or [Ceph](https://ceph.io). The corresponding repositories for Samba Integration Testing (sit) are
[sit-environment](https://github.com/samba-in-kubernetes/sit-environment)
and[sit-test-cases](https://github.com/samba-in-kubernetes/sit-test-cases)

The nightly RPMs from samba-build are used in the nightly samba-container images hosted on [quay](https://quay.io).

Note that  the Samba container images are not specific to kubernetes at all.
They are for example used by the [Ceph](https://ceph.io) project.

