<p style="text-align:center;" align="center"><a href="https://layer5.io/meshery"><img align="center" style="margin-bottom:20px;" src="https://raw.githubusercontent.com/layer5io/layer5/master/assets/images/meshery/meshery-logo-tag-light-text-side.png"  width="70%" /></a><br /><br /></p>

[![Docker Pulls](https://img.shields.io/docker/pulls/layer5/meshery.svg)](https://hub.docker.com/r/layer5/meshery)
[![Go Report Card](https://goreportcard.com/badge/github.com/layer5io/meshery)](https://goreportcard.com/report/github.com/layer5io/meshery)
[![Build Status](https://github.com/layer5io/meshery/workflows/Meshery/badge.svg)](https://github.com/layer5io/meshery/actions)
[![GitHub](https://img.shields.io/github/license/layer5io/meshery.svg)](LICENSE)
[![GitHub issues by-label](https://img.shields.io/github/issues/layer5io/meshery/help%20wanted.svg)](https://github.com/issues?utf8=✓&q=is%3Aopen+is%3Aissue+archived%3Afalse+org%3Alayer5io+label%3A%22help+wanted%22+")
[![Website](https://img.shields.io/website/https/layer5.io/meshery.svg)](https://layer5.io/meshery/)
[![Twitter Follow](https://img.shields.io/twitter/follow/layer5.svg?label=Follow&style=social)](https://twitter.com/intent/follow?screen_name=mesheryio)
[![Slack](http://slack.layer5.io/badge.svg)](http://slack.layer5.io)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/3564/badge)](https://bestpractices.coreinfrastructure.org/projects/3564)

<h5><p align="center"><i>If you’re using Meshery or if you like the project, please <a href="https://github.com/layer5io/meshery/stargazers">★</a> this repository to show your support! 🤩</i></p></h5>

[Meshery](https://meshery.io) is the multi-service mesh management plane offering lifecycle, configuration and performance management of service meshes and their workloads.

## <a name="running"></a>Run Meshery

See the [getting started](https://meshery.io/#getting-started) section to quickly deploy Meshery on any of these supported platforms:

| Platform | Supported? |
| --- | :---: |
| <img src="docs/assets/img/platforms/docker.svg" width="20" height="20" /> [Docker](https://meshery.layer5.io/docs/installation/platforms/docker) | ✔️ |
| - <img src="docs/assets/img/platforms/docker.svg" width="20" height="20" />  [Docker - Docker App](https://meshery.layer5.io/docs/installation/platforms/docker) | ✔️ |
| <img src="docs/assets/img/platforms/kubernetes.svg" width="20" height="20" /> [Kubernetes](https://meshery.layer5.io/docs/installation/platforms/kubernetes) | ✔️ |
| - <img src="docs/assets/img/platforms/aks.svg" width="20" height="20" /> [Kubernetes - AKS](https://meshery.layer5.io/docs/installation/platforms/aks) | ✔️ |
| - <img src="docs/assets/img/platforms/docker.svg" width="20" height="20" /> [Kubernetes - Docker Desktop](https://meshery.layer5.io/docs/installation#mac-or-linux) | ✔️ |
| - <img src="docs/assets/img/platforms/eks.png" width="20" height="20" />  [Kubernetes - EKS](https://meshery.layer5.io/docs/installation/platforms/eks) | ✔️ |
| - <img src="docs/assets/img/platforms/gke.png" width="20" height="20" /> [Kubernetes - GKE](https://meshery.layer5.io/docs/installation/platforms/gke) | ✔️ |
| - <img src="docs/assets/img/platforms/helm.svg" width="20" height="20" />  [Kubernetes - Helm](https://meshery.layer5.io/docs/installation/platforms/kubernetes#using-helm) | ✔️ |
| - <img src="docs/assets/img/platforms/kind.png" width="20" height="20" />  [Kubernetes - kind](https://meshery.layer5.io/docs/installation/platforms/kind) | ✔️ |
| - <img src="docs/assets/img/platforms/minikube.png" width="20" height="20" />  [Kubernetes - Minikube](https://meshery.layer5.io/docs/installation/platforms/minikube) | ✔️ |
| - <img src="docs/assets/img/platforms/openshift.svg" width="20" height="20" /> Kubernetes - OpenShift | In Progress |
|<img src="docs/assets/img/platforms/linux.svg" width="20" height="20" /> [Linux](https://meshery.layer5.io/docs/installation#mac-or-linux) | ✔️ |
|<img src="docs/assets/img/platforms/apple.svg" width="20" height="20" /> [Mac](https://meshery.layer5.io/docs/installation#mac-or-linux) | ✔️ |
| - <img src="docs/assets/img/platforms/homebrew.png" width="20" height="20" /> [Mac - Homebrew](https://meshery.layer5.io/docs/installation#mac-or-linux) | ✔️ |
|<img src="docs/assets/img/platforms/wsl2.png" width="20" height="20" /> [Windows](https://meshery.layer5.io/docs/installation#windows) | ✔️ |
| - [Scoop](https://meshery.layer5.io/docs/installation#windows) | ✔️ |
| - <img src="docs/assets/img/platforms/wsl2.png" width="20" height="20" />  [WSL2](https://meshery.layer5.io/docs/installation/platforms/wsl2) | ✔️ |
| <img src="docs/assets/img/platforms/raspberry-pi.png" width="20" height="20" /> Raspberry Pi | In Progress |

[Meshery documentation](https://meshery.layer5.io/docs/installation) offers thorough installation guides for your platform of choice.

## <a name="service-meshes"></a>Supported Service Meshes

<div class="container flex">
  <div class="text editable">
    <p>Service mesh adapters provision, configure, and manage their respective service meshes.
      <table class="adapters">
        <thead style="display:none;">
          <th>Status</th>
          <th>Adapter</th>
        </thead>
        <tbody>
        <tr>
          <td rowspan="7" class="stable-adapters">stable</td>
        </tr>
        <tr>
          <td><a href="https://github.com/layer5io/meshery-istio">
            <img src='https://raw.githubusercontent.com/layer5io/meshery.io/master/images/istio.png' alt='Istio Service Mesh adapter' align="middle" hspace="10px" vspace="5px" height="30px" > Meshery adapter for Istio</a>
          </td>
        </tr>
        <tr>
          <td><a href="https://github.com/layer5io/meshery-linkerd">
            <img src='https://raw.githubusercontent.com/layer5io/meshery.io/master/images/linkerd.png' alt='Linkerd' align="middle" hspace="5px" vspace="5px" height="30px" width="30px"> Meshery adapter for Linkerd</a>
          </td>
        </tr>
        <tr>
          <td><a href="https://github.com/layer5io/meshery-consul">
            <img src='https://raw.githubusercontent.com/layer5io/meshery.io/master/images/consul.png' alt='Consul Connect' align="middle" hspace="5px" vspace="5px" height="30px" width="30px"> Meshery adapter for Consul</a>
          </td>
        </tr>
        <tr>
          <td><a href="https://github.com/layer5io/meshery-octarine">
            <img src='https://raw.githubusercontent.com/layer5io/meshery.io/master/images/octarine.png' alt='Octarine Service Mesh' align="middle" hspace="5px" vspace="5px" height="30px" width="30px">Meshery adapter for Octarine</a>
          </td>
        </tr>
        <tr>
          <td><a href="https://github.com/layer5io/meshery-nsm">
            <img src='https://raw.githubusercontent.com/layer5io/meshery.io/master/images/nsm.png' alt='Network Mesh' align="middle" hspace="5px" vspace="5px" height="30px" width="30px">Meshery adapter for Network Service Mesh</a>
          </td>
        </tr>
        <tr><td class="stable-adapters"></td></tr>
        <tr>
          <td rowspan="4" class="beta-adapters">beta</td>
          <td><a href="https://github.com/layer5io/meshery-cpx">
            <img src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQksHj15DkID308qQw3cmkQrRULPxyzbVquSZVev-9dj1L6sPs-rQ&s' alt='Citrix CPX Service Mesh' align="middle" hspace="5px" vspace="5px" height="30px" width="30px">Meshery adapter for Citrix CPX</a>
          </td>
        </tr>
         <tr>
           <td><a href="https://github.com/layer5io/meshery-kuma">
             <img src='docs/_adapters/kuma/Kuma.svg' alt='Kuma Service Mesh' align="middle" hspace="5px" vspace="5px" height="30px" width="30px">Meshery adapter for Kuma</a>
           </td>
        </tr>
          <tr>
          <td><a href="https://github.com/layer5io/meshery-osm">
            <img src='docs/_adapters/osm/Osm.svg' alt='Open Service Mesh' align="middle" hspace="5px" vspace="5px" height="30px" width="30px">Meshery adapter for Open Service Mesh</a>
          </td>
        </tr>
        <tr><td class="beta-adapters"></td></tr>
        <tr>
          <td rowspan="5" class="alpha-adapters">alpha</td>
        </tr>
        <tr>
          <td><a href="https://github.com/layer5io/meshery-maesh">
            <img src='https://github.com/containous/maesh/raw/master/docs/content/assets/img/maesh.png' alt='Maesh Service Mesh' align="middle" hspace="5px" vspace="5px" height="30px" width="30px">Meshery adapter for Maesh</a>
          </td>
        </tr>
         <tr>
          <td><a href="https://github.com/layer5io/meshery-tanzu-sm">
            <img src='https://raw.githubusercontent.com/layer5io/meshery/master/docs/assets/img/service-meshes/tanzu.png' alt='Tanzu Service Mesh' align="middle" hspace="5px" vspace="5px" height="30px" width="30px">Meshery adapter for Tanzu SM</a>
          </td>
        </tr>
        <tr>
          <td><a href="https://github.com/layer5io/meshery-app-mesh">
            <img src='https://raw.githubusercontent.com/layer5io/meshery.io/master/images/aws-app-mesh.png' alt='AWS App Mesh Service Mesh' align="middle" hspace="5px" vspace="5px" height="30px" width="30px">Meshery adapter for App Mesh</a>
          </td>
        </tr>
        <tr>
        <tr></tr>
        </tbody>
    </table>
  </p>
</div>


## <a name="functionality">Functionality</a>

<p style="clear:both;">
<a href="https://raw.githubusercontent.com/layer5io/meshery/master/docs/assets/img/readme/meshery_multi_mesh.png"><img alt="Layer5 Service Mesh Management" src="docs/assets/img/readme/meshery_multi_mesh.png"  style="margin-left:10px; margin-bottom:10px;" width="45%" align="right"/></a>
<h3>Service Mesh Lifecycle Management</h3>
Meshery manages the provisioning, configuration and operation your service mesh. While supporting different types of service meshes, Meshery also offers a simple way to explore each service mesh and compare them using bundled sample applications.

Interoperate multiple service meshes with service mesh adapters provision, configure, and manage their respective service meshes. Meshery is an implementation of Service Mesh Interface (SMI).
<br /><br /><br /><br />
</p>

<p style="clear:both;">
<a href="https://raw.githubusercontent.com/layer5io/meshery/master/docs/assets/img/readme/meshery_lifecycle_management.png"><img alt="Layer5 Service Mesh Configuration Management" src="docs/assets/img/readme/meshery_lifecycle_management.png"  style="margin-right:10px;margin-bottom:10px;" width="45%" align="left"/></a>
<h3>Service Mesh Configuration Management</h3>

Assess your service mesh configuration against deployment and operational best practices with Meshery's configuration validator.

Onboard your workload onto the service mesh with confidence. Check your service mesh configuration for anti-patterns and avoid common pitfalls.
<br /><br /><br /><br />
</p>


<h3>Adhering to Service Mesh Standards</h3>
In an effort to produce service mesh agnostic tooling, Meshery uses the [service mesh performance](https://smp-spec.io/) as a common format to capture and measure your mesh's performance against a universal service mesh performance index. As a partner of VMware's Multi-Vendor Service Mesh Interoperation (Hamlet) and Service Mesh Interface (SMI), Meshery participates in advancing service mesh adoption through standardization of APIs.

<p style="clear:both;">
<a href="https://raw.githubusercontent.com/layer5io/meshery/master/docs/assets/img/readme/meshery_benchmark_screen.png"><img alt="Layer5 Service Mesh Performance Management" src="docs/assets/img/readme/meshery_benchmark_screen.png" style="margin-left:10px;margin-bottom:10px;" width="45%" align="right" /></a>
<!-- <a href="https://raw.githubusercontent.com/layer5io/meshery/master/docs/assets/img/readme/Meshery-Grafana-Charts.png"><img alt="Meshery Grafana Boards" src="docs/assets/img/readme/Meshery-Grafana-Charts.png" style="padding-top:10px;margin-left:10px;" width="45%" align="right" /></a> -->
<h4>Standardized Service Performance Management</h4>

Meshery is the service-mesh-neutral utility for uniformly managing the performance of services and the meshes that run them. As an implementation of the Service Mesh Performance ([SMP](https://layer5.io/performance)), Meshery enables you to measure the value provided by a service mesh in context of the overhead incurred.
<br /><br />
</p>

<h4>Conforming to Service Mesh Interface (SMI)</h4>

<p style="clear:both;">

Meshery provides tooling to validate any service mesh that claims to implement and <a href="https://raw.githubusercontent.com/layer5io/meshery/master/docs/assets/img/readme/smi-conformance-with-meshery.png"><img alt="SMI Validation, Verification, and Conformance with Meshery" src="docs/assets/img/readme/smi-conformance-with-meshery.png" style="margin-right:10px;margin-bottom:10px;" width="45%" align="left" /></a>conform to SMI specifications. Working in accordance with the [SMI Conformance project](https://layer5.io/projects/service-mesh-interface), it essentially provides:

✔︎ Defines compliant behavior.<br />
✔︎ Produces compatibility matrix. <br />
✔︎ Ensures provenance of results. <br />
✔︎ Runs a set of conformance tests. <br />
✔︎ Built into participating service mesh’s release pipeline. <br />
✔︎ Provides [Learn Layer5](https://github.com/layer5io/learn-layer5) sample application used for validating test assertions. <br />

<br /><br />
</p>

<div>&nbsp;</div>

## Meshery Architecture
You may deploy Meshery internal to your cluster or external to your cluster.
<p align="center"><a href="https://raw.githubusercontent.com/layer5io/meshery/master/docs/assets/img/architecture/meshery-architecture.svg"><img src="docs/assets/img/architecture/meshery-architecture.svg" width="90%" align="center" /></a></p>
Learn more about <a href="https://meshery.layer5.io/docs/architecture">Meshery's architecture</a>.

<div>&nbsp;</div>

## Join the service mesh community!

<a name="contributing"></a><a name="community"></a>
Our projects are community-built and welcome collaboration. 👍 Be sure to see the <a href="https://docs.google.com/document/d/17OPtDE_rdnPQxmk2Kauhm3GwXF1R5dZ3Cj8qZLKdo5E/edit">Layer5 Community Welcome Guide</a> for a tour of resources available to you and see the <a href="https://docs.google.com/document/d/1brtiJhdzal_O6NBZU_JQXiBff2InNtmgL_G1JgAiZtk/edit?usp=sharing">Layer5 Repository Overview</a> for a cursory description of repository by technology and programming language. Jump into community <a href="http://slack.layer5.io">Slack</a> to engage!

<p style="clear:both;">
<a href ="https://layer5.io/community"><img alt="MeshMates" src="docs/assets/images/Layer5-MeshMentors.png" style="margin-right:10px; margin-bottom:7px;" width="28%" align="left" /></a>
<h3>Find your MeshMate</h3>

<p>MeshMates are experienced Layer5 community members, who will help you learn your way around, discover live projects and expand your community network.
Become a <b>Meshtee</b> today!</p>

Find out more on the <a href="https://layer5.io/community#meshmate">Layer5 community</a>. <br />
<br /><br /><br /><br />
</p>

<a href="https://meshery.io/community"><img alt="Layer5 Service Mesh Community" src="docs/assets/img/readme/slack-128.png" style="margin-left:10px;padding-top:5px;" width="110px" align="right" /></a>

<a href="http://slack.layer5.io"><img alt="Layer5 Service Mesh Community" src="docs/assets/img/readme/community.png" style="margin-right:8px;padding-top:5px;" width="140px" align="left" /></a>

<p>
✔️ <em><strong>Join</strong></em> any or all of the weekly meetings on <a href="https://calendar.google.com/calendar/b/1?cid=bGF5ZXI1LmlvX2VoMmFhOWRwZjFnNDBlbHZvYzc2MmpucGhzQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20">community calendar</a>.<br />
✔️ <em><strong>Watch</strong></em> community <a href="https://www.youtube.com/playlist?list=PL3A-A6hPO2IMPPqVjuzgqNU5xwnFFn3n0">meeting recordings</a>.<br />
✔️ <em><strong>Access</strong></em> the <a href="https://drive.google.com/drive/u/4/folders/0ABH8aabN4WAKUk9PVA">community drive</a>.<br />
</p>
<p align="center">
<i>Not sure where to start?</i> Grab an open issue with the <a href="https://github.com/issues?utf8=✓&q=is%3Aopen+is%3Aissue+archived%3Afalse+org%3Alayer5io+label%3A%22help+wanted%22+">help-wanted label</a>.
</p>

<div>&nbsp;</div>

## Contributing (yes!)
We're a warm and welcoming community of open source contributors. Please join. All types of contribution are welcome. Be sure to read the <a href="https://docs.google.com/document/d/17OPtDE_rdnPQxmk2Kauhm3GwXF1R5dZ3Cj8qZLKdo5E/edit">Meshery Contributors Welcome Guide</a> for a tour of resources available to you and how to get started.

- [General Contributing](CONTRIBUTING.md/#contributing)
- [Write an adapter](CONTRIBUTING.md/#adapter)
- [Build the project](CONTRIBUTING.md/#building)

<a href="https://youtu.be/MXQV-i-Hkf8"><img alt="Deploying Linkerd with Meshery" src="docs/assets/img/readme/deploying-linkerd-with-meshery.png"  style="margin-left:10px; margin-bottom:10px;" width="45%" align="right"/></a>

<div>&nbsp;</div>

## See Meshery in Action
- [DockerCon 2020](https://docker.events.cube365.net/docker/dockercon/content/Videos/63TCCNpzDC7Xxnm8b) | ([video](https://www.youtube.com/watch?v=5BrbbKZOctw&list=PL3A-A6hPO2IN_HSU0pSfijBboiHggs5mC&index=4&t=0s), [deck](https://calcotestudios.com/talks/decks/slides-dockercon-2020-service-meshing-with-docker-desktop-and-webassembly.html))
- [Deploying Linkerd with Meshery](https://youtu.be/MXQV-i-Hkf8)
- [KubeCon EU 2019](https://kccnceu19.sched.com/event/MPf7/service-meshes-at-what-cost-lee-calcote-layer5-girish-ranganathan-solarwinds?iframe=no&w=100%&sidebar=yes&bg=no) | ([video](https://www.youtube.com/watch?v=LxP-yHrKL4M&list=PLYjO73_1efChX9NuRaU7WocTbgrfvCoPE), [deck](https://calcotestudios.com/talks/decks/slides-kubecon-eu-2019-service-meshes-at-what-cost.html))
- Istio Founders Meetup @ KubeCon EU 2019 | [deck](https://calcotestudios.com/talks/decks/slides-istio-meetup-kubecon-eu-2019-istio-at-scale-large-and-small.html)
- [Cloud Native Rejekts EU 2019](https://cfp.cloud-native.rejekts.io/cloud-native-rejekts-eu-2019/speaker/GZQTEM/) | [deck](https://calcotestudios.com/talks/decks/slides-cloud-native-rejekts-2019-evaluating-service-meshes.html)
- [DockerCon 2019 Open Source Summit](https://dockercon19.smarteventscloud.com/connect/sessionDetail.ww?SESSION_ID=309149&tclass=popup#.XJxH-TOcbjI.twitter) | [deck](https://calcotestudios.com/talks/decks/slides-dockercon-2019-establishing-an-open-source-office.html), [video](https://www.docker.com/dockercon/2019-videos?watch=open-source-summit-service-mesh)
- [Container World 2019](https://tmt.knect365.com/container-world/speakers/lee-calcote) | [deck](https://calcotestudios.com/talks/decks/slides-container-world-2019-service-meshes-but-at-what-cost.html)
- [Service Mesh Day](https://servicemeshday.com/schedule/) | [deck](https://docs.google.com/presentation/d/1HwG03okX3DHgGKbma4PL-MO7Xr9zDrjQgd05PRi9i8E/edit?usp=sharing), [video](https://youtu.be/CFj1O_uyhhs)
- [Innotech San Antonio](https://innotechsanantonio2019.sched.com/event/Lmlb/the-enterprise-path-to-service-mesh-architectures?iframe=no&w=100%&sidebar=yes&bg=no) | [deck](https://calcotestudios.com/talks/decks/slides-innotech-san-antonio-2019-the-enterprise-path-to-service-mesh.html)
- [CNCF Networking WG](https://github.com/cncf/wg-networking) | [deck](https://www.slideshare.net/leecalcote/benchmarking-service-meshes-cncf-networking-wg-141938576), [video](https://www.youtube.com/watch?v=2_JwCc-kLMA&list=PLYjO73_1efChX9NuRaU7WocTbgrfvCoPE)

### Stargazers
<p align="center">
  <i>If you’re using Meshery or if you like the project, please <a href="../../stargazers">★</a> star this repository to show your support! 🤩</i>
<a href="../../stargazers"><img align="right" src="https://starchart.cc/layer5io/meshery.svg" /></a></p>

### License

This repository and site are available as open source under the terms of the [Apache 2.0 License](https://opensource.org/licenses/Apache-2.0).

### About Layer5

**Community First**
<p>The <a href="https://layer5.io">Layer5</a> community represents the largest collection of service mesh projects and their maintainers in the world.</p>

**Open Source First**
<p>Our projects establish industry standards and enable service developers, owners, and operators with repeatable patterns and best practices for managing all aspects of distributed services. Our shared commitment to the open source spirit push the Layer5 community and its projects forward.</p>
