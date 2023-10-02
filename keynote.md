---
layout: page
slide_id: 1
---

<div class="card">
	<div class="card-header text-white bg-inverse"><i class="fa fa-users mr-3" aria-hidden="true"></i>Keynote I</div>
	<div style="margin: 10px">
		<h5>Too Much Parallelism, and the Need for Compiler Support in Asynchronous Many-Task Systems</h5>
		<p>Sean Treichler, NVIDIA</p>
        From the start, Legion was designed to be part of a larger software stack, with a distributed execution runtime
(i.e. Realm) below it, but also libraries, frameworks, and DSLs above it. Early successes with Legion came from
application code written directly to the Legion API, but more recently the vision of being an enabler for higher
levels of abstraction is coming to fruition. I will review several of these efforts, talk about their successes in 
scaling (whether to larger systems, larger workloads, or larger programmer audiences), and that will lead me into
discussion of some key challenges that are becoming more critical as this scaling continues.
<br><br>
Legion, and really all AMT systems, are at risk of becoming victims of their success. If anything, they are too good
at extracting parallelism from application code, and this manifests as increasing demands on the runtime portions
of these systems at larger scales. Much of the analysis and decision making being performed in real time (and
therefore with real overhead) is not actually contributing to improved performance because there was already
enough work to keep processors busy and data movement latencies hidden. I'll touch on past and current efforts
to attack this at the application level and in runtime implementation, but the best place in the stack to perform
optimizations like this (i.e. compilers) is severely underrepresented, and we should fix that.
	</div>
</div>

<div class="card">
	<div class="card-header text-white bg-inverse"><i class="fa fa-users mr-3" aria-hidden="true"></i>Keynote II</div>
		<div style="margin: 10px">
		<h5>Deep Codesign in the Post-Exascale Computing Era</h5>
		<p>Jeffrey Vetter, Oak Ridge National Laboratory, https://vetter.github.io/</p>
		<p markdown="1">
			DOE has just deployed its first Exascale system at ORNL, so now is an appropriate time to revisit our Exascale predictions from over a decade ago 
			and think about post-Exascale. We are now seeing a Cambrian explosion of new technologies during this ‘golden age of architectures,’ making codesign of architectures 
			with software and applications more critical than ever. In this talk, I will revisit the Exascale trajectory, survey post-Exascale technologies, and discuss their implications 
			for both system design and software. As an example, I will describe Abisko, a new microelectronics codesign project, that focuses on designing a chiplet for analog spiking neural 
			networks using novel neuromorphic materials like electrochemical random access memory.
		</p>
    </div>
</div>

<div class="card">
	<div class="card-header text-white bg-inverse"><i class="fa fa-users mr-3" aria-hidden="true"></i>Keynote III</div>

	<div style="margin: 10px">
		<h5>TBA</h5>
		<p>Richard Harrison, Stony Brook University</p>

</div>
</div>
