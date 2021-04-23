---
layout: default
---

## Program
---
### April 26th, 2021

<span class="text-warning">All times are in Pacific Time</span>

<h4>Workshop Program</h4>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_time">08:00 am - 08:05 am</div>
    <div class="program_entry">
      <b>Welcome</b>
    </div>
  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_time">08:05 am - 09:05 am</div>
    <div class="program_entry">
      <b>Keynote</b>
    </div>
    <div class="program_entry_content">
      <div class="program_entry_content_title">
        <a href="#keynote_talk_content" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="invited_talk_1_content">
          Too Many Tests, Too Little Time: How to Find Bugs Faster
        </a>
      </div>
      <div class="program_entry_content_speakers">
        Haryadi Gunawi, University of Chicago
      </div>
      <div class="collapse program_entry_content_details" id="keynote_talk_content">
      <div class="program_entry_content_abstract">
        <p>
          As more data and computation move from local to cloud environments, datacenter distributed systems have become a dominant backbone for many modern applications.  However, the complexity of cloud-scale hardware and software ecosystems has outpaced existing testing, debugging, and verification tools.  I will describe a classical class of bugs that surface in large-scale datacenter distributed systems, distributed concurrency bugs, caused by non-deterministic timings of distributed events such as message arrivals as well as multiple crashes and reboots.  The challenge is the too many tests to perform.  I will describe our 7-year of experience in taming this problem, in particular how to systematically reduce the number of tests to perform when building software model checkers for distributed datacenter systems. 
        </p>
      </div>
      <div class="program_entry_content_bio">
        <div class="speaker_image">
          <img src="assets/image/speaker/haryadi-9.jpg" />
        </div>
        <div class="speaker_bio">
          <p>
            Haryadi S. Gunawi is an Associate Professor in the Department of Computer Science at the University of Chicago where he leads the UCARE research group (UChicago systems research on Availability, Reliability, and Efficiency). He received his Ph.D. in Computer Science from the University of Wisconsin, Madison in 2009. He was a postdoctoral fellow at the University of California, Berkeley from 2010 to 2012. His current research focuses on cloud computing reliability and new storage technology. He has won numerous awards including NSF CAREER award, NSF Computing Innovation Fellowship, Google Faculty Research Award, NetApp Faculty Fellowships, and Honorable Mention for the 2009 ACM Doctoral Dissertation Award.
          </p>
        </div>
      </div>
    </div>     
    </div>
  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_break_time">09:05 am - 09:30 am</div>
    <div class="program_entry">
      <b>Break</b>
    </div>
  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_time">09:30 am - 10:00 am</div>
    <div class="program_entry">
      <b>Paper Presentation Session I</b>
    </div>
    ------
    <div class="program_entry_content_title">
    <a href="#session1_1_content" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="session1_1_content">
        CARE: Infusing Causal Aware Thinking to Root Cause Analysis in Cloud System
      </a>
    </div>
    <div class="program_entry_content_speakers">
      <p>
        Yong Xu and Xu Zhang (Microsoft Research, Beijing, China); Chuan Luo and Si Qin (Microsoft Research); Rohit Pandey (Microsoft , Redmond); Chao Du and Qingwei Lin (Microsoft Research, Beijing, China); Yingnong Dang (Microsoft, Redmond); Andrew Zhou (Microsoft)
      </p>
    </div>
    <div class="collapse program_entry_content_details" id="session1_1_content">
      <div class="program_entry_content_abstract">
        <p>
          With millions of customers accessing online service all over the world, ensuring high service availability is very critical for cloud system. In recent years, empowered by advanced data mining and machine learning technology, there emerges extensive study on data-driven solution to detect anomalous system behavior and diagnose the root cause. However, without any surveilance of data generation process, the existing passive data-driven approach may lead to biased analysis result induced by observed and unobserved confounding factors in the dynamic and heterogeneous system, and thus affect service availability with misleading mitigation action.  In this paper, we propose to infuse causal thinking to the current data-driven solution for cloud system. We developed CARE, a causal aware root cause discovery engine, which utilizes Random Control Trial to proactively generate less ambiguous data for further analysis. A case study shows the application of CARE to Microsoft Office365.
        </p>
      </div>
    </div>
    <br/><br/>
    <div class="program_entry_content_title">
      <a href="#session1_2_content" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="session1_2_content">
        Frisbee: A Suite for Benchmarking Systems Recovery
      </a>
    </div>
    <div class="program_entry_content_speakers">
      <p>
        Fotis Nikolaidis (FORTH, Greece); Angelos Bilas (Univ. of Crete and FORTH, Greece); Manolis Marazakis (FORTH-ICS); Antonis Chazapis (FORTH, Greece)
      </p>
    </div>
    <div class="collapse program_entry_content_details" id="session1_2_content">
      <div class="program_entry_content_abstract">
        <p>
          With failures being unavoidable, a system's ability to recover from failures quickly is a critical factor in the overall availability of the system. Although many systems exhibit self-healing properties, their behavior in the presence of failures is poorly understood. This is primarily due to the shortcomings of existing benchmarks, which cannot generate failures. For a more accurate systems evaluation, we argue that it is essential to create new suites that treat failures as first-class citizens. We present Frisbee, a benchmark suite and evaluation methodology for comparing the recovery behavior of highly available systems. Frisbee is built for the Kubernetes environment, leveraging several valuable tools in its stack, including Chaos tools for fault injection, Prometheus for distributed monitoring, and Grafana for visualization. We discuss a set of design requirements and present an initial prototype that makes faultloads as easy to run and characterize as traditional performance workloads. Furthermore, we define a core set of failure patterns against which systems can be compared.
        </p>
      </div>
    </div>
  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_time">10:00 am - 10:30 am</div>
    <div class="program_entry">
      <b>Invited Talk I</b>
    </div>
    <div class="program_entry_content_title">
      <a href="#invited_talk_1_content" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="invited_talk_1_content">
        On the Art of Wielding a Double-Edged Sword (or Finessing Modern Networks)
      </a>
    </div>
    <div class="program_entry_content_speakers">
      Samer Al-Kiswany, University of Waterloo
    </div>
    <br>
    <div class="collapse program_entry_content_details" id="invited_talk_1_content">
      <div class="program_entry_content_abstract">
        <p>
          Unprecedented advances in networking technology have introduced network configurability and programmability. However, this increase in network "softwarization" is a double-edged sword. On one hand, network softwarization facilitates the building of line-rate application-specific packet-processing logic. On the other hand, increased network softwarization (perhaps unsurprisingly) increases the frequency and complexity of network faults. 
        </p>
        <p>
          In this talk, I will discuss a peculiar type of a network fault that my group identified: partial network partitioning. First, I will present a comprehensive study of system failures caused by this type of fault. Our study reveals that the studied failures are catastrophic (e.g., lead to data loss) and are easily manifested. Second, I will present an analysis of fault-tolerance techniques for eight popular systems and highlight their shortcomings. Finally, I will present Nifty, a transparent communication layer that masks partial network partitions. Nifty overcomes the shortcomings of current fault-tolerance approaches and effectively masks partial partitions while imposing negligible overhead.
        </p>
      </div>
      <div class="program_entry_content_bio">
        <div class="speaker_image">
          <img src="assets/image/speaker/samer.jpeg" />
        </div>
        <div class="speaker_bio">
          <p>
            Samer Al-Kiswany is an assistant professor at the David Cheriton School of Computer Science at the University of Waterloo, Canada. His research interests are in distributed systems, networking, and data management and processing engines. In particular, his work focuses on reconsidering systems design in light of recent changes in cloud applications and platforms. Samer received his PhD from the University of British Columbia in 2013. After earning his PhD, he joined the University of Wisconsin–Madison as a postdoctoral fellow. Dr. Al-Kiswany is the recipient of ten national and international awards, including the Killam Doctoral Fellowship and the NSERC Postdoctoral Fellowship.
          </p>
        </div>
      </div>
    </div>

  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_break_time">10:30 am - 10:40 am</div>
    <div class="program_entry">
      <b>Break</b>
    </div>
  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_time">10:40 am - 11:10 am</div>
    <div class="program_entry">
      <b>Paper Presentation Session II</b>
    </div>
    ------
    <div class="program_entry_content_title">
      <a href="#session2_1_content" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="session2_1_content">
        Examining Raft's behaviour during partial network failures
      </a>
    </div>
    <div class="program_entry_content_speakers">
      <p>
        Chris Jensen, Heidi Howard, and Richard Mortier (University of Cambridge)
      </p>
    </div>
    <div class="collapse program_entry_content_details" id="session2_1_content">
      <div class="program_entry_content_abstract">
        <p>
          State machine replication protocols such as Raft are widely used to build highly-available strongly-consistent services, maintaining liveness even if a minority of servers crash. As these systems are implemented and optimised for production, they accumulate many divergences from the original specification. These divergences are poorly documented, resulting in operators having an incomplete model of the system's characteristics, especially during failures. In this paper, we look at one such Raft model used to explain the November Cloudflare outage and show that etcd's behaviour during the same failure differs. We continue to show the specific optimisations in etcd causing this difference and present a more complete model of the outage based on etcd's behaviour in an emulated deployment using reckon. Finally, we highlight the upcoming PreVote optimisation in etcd, which might have prevented the outage from happening in the first place.
        </p>
      </div>
    </div>
    <br/><br/>
    <div class="program_entry_content_title">
      <a href="#session2_2_content" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="session2_2_content">
        Service mesh circuit breaker: From panic button to performance management tool
      </a>
    </div>
    <div class="program_entry_content_speakers">
      <p>
        Mohammad Reza Saleh Sedghpour, Cristian Klein, and Johan Tordsson (Umeå University)
      </p>
    </div>
    <div class="collapse program_entry_content_details" id="session2_2_content">
      <div class="program_entry_content_abstract">
        <p>
          Site Reliability Engineers are at the center of two tensions: On one hand, they need to respond to alerts within a short time, to restore a non-functional system. On the other hand, short response times is disruptive to everyday life and lead to alert fatigue. To alleviate this tension, many resource management mechanisms are proposed handle overload and mitigate the faults. One recent such mechanism is circuit breaking in service meshes. Circuit breaking rejects incoming requests to protect latency at the expense of availability (successfully answered requests), but in many scenarios achieve neither due to the difficulty of knowing when to trigger circuit breaking in highly dynamic microservice environments. 
        </p>
        <p>
          We propose an adaptive circuit breaking mechanism, implemented through an adaptive controller, that not only avoids overload and mitigate failure, but keeps the tail response time below a given threshold while maximizing service throughput. Our proposed controller is experimentally compared with a static circuit breaker across a wide set of overload scenarios in a testbed based on Istio and Kubernetes. The results show that our controller maintains tail response time below the given threshold 98% of the time (including cold starts) on average with an availability of 70% with 29% of requests circuit broken. This compares favorably to a static circuit breaker configuration, which features a 63% availability, 30% circuit broken requests, and more than 5% of requests timing out.
        </p>
        
      </div>
    </div>
  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_time">11:10 am - 11:40 am</div>
    <div class="program_entry">
      <b>Invited Talk II</b>
    </div>
    <div class="program_entry_content_title">
      <a href="#invited_talk_2_content" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="invited_talk_2_content">
        Sampling Distributed Traces: Evolution from 2005 to Today
      </a>
    </div>
    <div class="program_entry_content_speakers">
	      Kay Ousterhout, LightStep
    </div>
    <br>
    <div class="collapse program_entry_content_details" id="invited_talk_2_content">
      <div class="program_entry_content_abstract">
        <p> Distributed tracing has become a widespread tool for understanding the performance of large-scale systems: unlike metrics or logs, traces follow a request through every service to provide critical context for debugging problems. Retaining traces for every request through a system is typically prohibitively expensive, so all systems for distributed tracing sample a subset of traces to save. In this talk, I’ll talk about three iterations of sampling for distributed tracing, starting from the simple, random approach employed by Google’s production tracing system, Dapper, in 2005, and ending in a new approach that Lightstep is beginning to use in production. Over time, technology improvements have allowed sampling decisions to be delayed later and later in the data ingestion pipeline, which has enabled more sophisticated sampling algorithms that consider more dimensions in choosing which traces to save. I’ll end by talking about ongoing challenges and opportunities in selecting the most useful sample of tracing data.
        </p>
        <p>
        </p>
      </div>
      <div class="program_entry_content_bio">
        <div class="speaker_image">
          <img src="assets/image/speaker/kay_ousterhout.jpg" />
        </div>
        <div class="speaker_bio">
          <p>
            Kay Ousterhout is a software engineer at Lightstep, where she's building performance management tools that enable users to understand the performance of complex distributed systems. Before Lightstep, Kay received a PhD from UC Berkeley. Her thesis focused on building high-performance data analytics frameworks that allow users to reason about - and optimize for - performance. Kay is also a committer and PMC member for Apache Spark; her work on Spark has focused on improving scheduler performance.
          </p>
        </div>
      </div>
    </div>


  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_break_time">11:40 am - 11:50 am</div>
    <div class="program_entry">
      <b>Break</b>
    </div>
  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_time">11:50 am - 12:50 pm</div>
    <div class="program_entry">
      <b>Panel</b>
    </div>
    <div class="program_entry_content_title">
      <ul>
      <li>Moderator: John Wilkes, Google</li>
      <li>Panelists:
      <ul>
        <li>Evangelia Kalyvianaki, University of Cambridge</li>
        <li>Jonathan Mace, Max Planck Institute for Software Systems (MPI-SWS)</li>
        <li>Noa Zilberman, University of Oxford</li>
        <li>Yonatan Zunger, Twitter</li>
      </ul>
      </li>
      </ul>
    </div>
  </div>
</div>
<div class="row program_block">
  <div class="col">
    <div class="program_entry_time">12:50 pm - 1:00 pm</div>
    <div class="program_entry">
      <b>Wrap-up</b>
    </div>
  </div>
</div>
