## Hi there 👋

The samba-in-kubernetes organisation is the home of a few software projects around the [Samba](https:/samba.org) project. 

The original purpose was to create samba containers and an operator for running Samba in  [kubernetes](https:/kubernetes.io).

The two central projects for this purpose are [samba-container](https:/github.com/samba-in-kubernetes/samba-container)
and [samba-operator](https:/github.com/samba-in-kubernetes/samba-operator).

Additionally, [sambacc](https:/github.com/samba-in-kubernetes/sambacc) hosts the samba configuration tool used as the container entry point
and [smbmetrics](https:github.com/samba-in-kubernetes/smbmetrics) is a software that exports metrics from Samba in prometheus format.

An additional purpose of this organisation is to provide Samba RPM builds (via [samba-build](https:/github.com/samba-in-kubernetes/samba-build))


Finally, another purpose is to provide test infrastructure and test cases for testing clustered Samba on a distributed filesystem like
[Gluster](httpsgluster.org) or [Ceph](https:/ceph.io). The correspomdomg repositories for Samba Integration Tesing (sit) are
[sit-environment](https:/github.com/samba-in-kubernetes/sit-environment)
and[sit-test-cases](https:/github.com/samba-in-kubernetes/sit-test-cases)

The nightly RPMs from samba-build are used in the nightly samba-container images hosted on [quay](https:/quay.io).

Note that  the Samba container images are not specific to kubernetes at all. 
They are for example used by the [Ceph](https:/ceph.io) project. 






<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
