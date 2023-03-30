
Experience
======

### 2022-Present [Meta](https://meta.com)
#### First Party Game Studios PE : remote (team was disbanded due to reorganization)

  * Took over as lead developer and shipped a critical multiplayer server allocation and matchmaking service that was falling behind schedule (prior to my joining) by redesigning its approach to request handling, improving performance dramatically.

#### Traffic Platform PE : remote / Greater Seattle Area

  * Building tools to aid in root cause analysis for failures in Meta's in house content delivery network.
  * Improving a correlation engine critical to the maintenance of Meta's network infrastructure.
  * Eliminated N+1 queries in a critical system that were hindering production performance and causing data loss with a redesign - the data loss and performance issues were completely resolved.
 
### 2021-2022 [Twitter](https://twitter.com)
#### Core Infrastructure Services SRE : remote

Because Twitter is a very different organization today than it was when I joined, companies interested in hiring me who would like to know more about my work there could use [my manager](https://www.linkedin.com/in/patrick-newman-silicon-valley/) as a reference. Better yet you could try to hire him because he is amazing.

  * Team lead overseeing configuration management across Twitter data centers and cloud providers.
  * Wrote static analysis tools to detect problematic Puppet code and automatically fix it.
  * Wrote code generation tools to increase developer productivity.
  * Developed services to increase observability into the status of puppet releases.
  * Built cross-team relationships that unblocked important projects which had been stalled due to misunderstandings.
  * Held regular meetings with teammates to help them do their best work. (Mentoring)
  * Led yearly and quarterly team OKR/project planning and roadmapping.
  * Communicated the successes and ongoing progress of the team to the larger SRE and software engineering organizations.
  * Identified cross organizational opportunities and eliminated redundant work.

### 2020-2021 [Box](https://box.com)
#### Observability SRE : remote

  * Led development of an in house distributed log tailer and metric exporter.
  * Decreased memory usage by ~100x and CPU by ~10x in system daemons, with huge cumulative savings.
  * Mentored teammates and helped them identify opportunities for taking on impactful projects.
  * Helped build out an interview process for a newly minted SRE-SWE role pipeline.
  * Wrote mapping tools that revealed hidden dependencies between parts of our infrastructure.
  * Designed monitoring systems that helped us understand the performance of our logging platform.

### 2017-2020 [Google](https://google.com)

#### Payments SRE : Pittsburgh, Pennsylvania

  * Oncall for Google's entire payment processing infrastructure.
  * Wrote developer productivity tooling (with a focus on static analysis and debugging tools).
  * Reviewed design proposals, across teams and organizations, for new software.
  * Performed monitoring and SLO adjustments to decrease toil.

#### Google Global Cache Operations : Greater Denver Area, Colorado

  * Performed regular oncall shifts to support the world's largest CDN.
  * Built, trained and deployed (TensorFlow) models to help automate oncall work.
  * Wrote developer tooling for internal platforms and domain specific languages.
  * Troubleshot software and hardware problems with non-Google employees located in datacenters around the globe on a regular basis.

### 2014-2016 [Mozilla](https://mozilla.org) : Remote

#### JavaScript Engine
  * You can see many of my commits at => https://github.com/mozilla/gecko-dev/commits?author=usize
  * For WebAssembly work see => https://github.com/bytecodealliance/wasmtime/commits?author=usize
  * Implemented sorting for typed arrays ``(new Int32Array([4, 3, .., n])).sort();``
  * Implemented sorting for arrays with custom comparators ``[4, 3, .., n].sort((x, y) => x - y);``
  * Implemented object destructuring [with default values] ``{x=1} = {}; x === 1;``
  * Rewrote parsing logic for the ``Date`` object ``new Date("5-26-1988");``
  * Added `[Learn More]` links to JavaScript error messages in the Firefox web console.
  * Added smart multi-line editing to the Firefox web console.
  * Contributed to WasmTime, a code generator for WebAssembly.

#### Release Engineering / TaskCluster
  * Part of the team that built [TaskCluster](https://github.com/taskcluster), a task queuing system that powered Mozilla's build pipeline.
  * Designed and built a [continuous integration system on top of TaskCluster](https://github.com/taskcluster/taskcluster-github/commits?author=usize), tailored to the needs of Mozilla's GitHub hosted repositories.
  * Created a [secret management service](https://github.com/taskcluster/taskcluster-secrets/commits?author=usize), along with a novel (http proxy based) method for injecting secrets into running CI jobs.
  * Contributed to [RelengAPI](https://wiki.mozilla.org/ReleaseEngineering/Applications/RelengAPI), a platform for building infrastructure services with RESTful APIs and nice self-serve interfaces.
  * Primary maintainer of "Runner," a specialized init system which forms the foundation of Mozilla's current build infrastructure. Runner [saved over 72,000 minutes](https://archive.fo/fKuHW) of compute time per day by reducing the setup/teardown time between builds.
  * Primary maintainer of "Clobberer," a service which allows developers to easily flush object caches across large numbers of hosts.
  * Containerized Linux Firefox Builds.

Education
======

### 2012 Western Kentucky University : Bowling Green, KY

    B.S. Physics
    GPA: 3.47/4.00

#### Honors/Awards
  * George V. Page Physics Award for Outstanding Scholarship in Physics (top GPA in graduating class)


### Other Information
  * Programming Languages: Python, Go, JavaScript, C, C++, Bash, AWK, Rust, Java, Ruby, Scala

----
