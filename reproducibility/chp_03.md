# Chapter 3 Reproducibility
- Introduction
	- What is Reproducibility?
	- What is our goal? months, years, forever?
	- Its a moving and evolving target.
	
- Sections

- Concepts
	- Being unable to reproduce scientific experiments has led to misleading information on the topic, caused second guessing and created doubt in our results.
	- What causes reproducibility issues?
		- lack of transparency
		- cherry picking
		- outdated software/hardware
		- research code
		
- Best Practices
	- How to make code more readable?
	- Reuse code
	- Containerization
	- Open Science Framework
	- Cloud based computing
	
- Tools and Methods
	- GitHub
	- OSF
	- FOSS principles
	- Docker
	- Singularity
	- HPCs
	- Atmosphere
	- JetStream
	
- Final Example(s)  -- May be part of running examples through the chapter.
	- Minimal working examples
		- Docker recipes
		- Docker to Singularity containers
		- Reusable/callable code chunks
		- requirements.txt
		
- Conclusion
	- ‘Good enough practices’
	
- References


From Raja Introduction Chapter:
Chapter 3 is a central chapter of the book and deals with reproducible computing. Reproducible results are the hallmark of any scientific endeavor – whether theoretical or empirical.  The three paradigms of research which preceded FTF, are built on this strong platform that every scientific result is experimented, and results reproduced again and again in order to ascertain the scientific conclusion. In theoretical research paradigm, this was done through proving and reproving theoretical and in empirical research through performing the experiment with different settings and by different researchers who validate the empirical conclusions. In the case of data-intensive research, reproducibility is also central in validating results. But there can be several problems that make it hard to reproduce the same conclusions. The problems can be due to differing hardware configurations, operating systems, compiler and interpreter variances and differing software libraries being used. Many a time, one cannot build the exact platform and software stack that was used by a researcher because of version differences and rapid changes in the hardware systems. 

Even with computational research (3rdparadigm) the reproducibility was a big problem mainly due to the changing hard wares and supercomputing systems. In such a case, painstaking portability was performed for taking software developed on one platform to reproduce similar results on other (possibly newer, larger, and faster) platforms.  Each supercomputer centers had a team of such software specialists who assist the domain scientists in porting their code from one platform to another. This chapter on reproducible computing tackles these problems through making use for virtual platforms and circumscribed software solutions. Virtual machines (VMs) in lieu of hardware platforms provide a stable and reproducible platform for conducting experiments and provide a similar experience for software programs that run on them independent of the underlying hardware. VMs made working with a diversity of hardware and operating systems easy for the researcher and provides a level of vendor independence.  Similarly, the software stack that is used to produce results was kept a constant through circumscribing and packaging the stack exactly each time that can be used on the VMs to provide exactly the same experience. These type of constancy through using pre-defined and pre-built software packages are the new evolution that are very useful in reproducibility. Based on these two concepts of virtual machines and software packages, several tools and services are being provided that help not only scientific reproducibility but also collaboration through reuse and repurpose. One such development is in the implementation of domain-specific portals for each discipline that provides a common platform for running experiments as well as sharing of the workflow with other researchers.  Development of workflow systems that can be used to chain multiple steps in a scientific experiment is also an important advance and are integrated into the scientific portals. 

Chapter 3 introduces concepts in reproducibility and how it can be achieved in highly data-intensive fourth paradigm. Practical tools for achieving reproducibility using virtual operating systems, containers, portals, and scientific workflow systems will be discussed as part of this chapter.
