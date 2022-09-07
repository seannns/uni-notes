Complexity
	Computer systems are very complex, but complexity slows down processing.
	Size of systems contribute to complexity: billions of transistors operating billions of times per second.
	Rapid evolution contributes to complexity: how can software keep up with Moore's Law.

Ways to combat complexity
	Universality - eg. programming languages
	Hierarchical Abstraction - programming libraries

Universality
	Universal model of computation - powerful enough to compute all that can be computed.
		eg. Universal Turing Machine
	Anything that can be computed can be computed by a Universal Turing Machine.
	If a system is Turing equivalent, it can compute anything computable.

Programming Languages
	To simplify computers we must make them closer to humans.
		eg. make the language closer to human.
	Programming is the ultimate form of system configuration.

Emulators
	Universality allows us to emulate CPUs in software.
	eg. Game emulators let us run old console games on newer, different hardware.
	We can emulate old CPU/libraries/software by interpreting original machine code or compiling or JIT compiling.
	This is effective when it becomes too difficult to support old software on a new system.

Hierarchical Abstraction
	Software Libraries
	Essentially means hiding layers.
	Hiding complexity using layers of software libraries.
	Sophisticated higher levels of software on top of simpler layers.
		These layers help decouple software application, services, libraries, hardware

Execution
	Compilation:
		1. High Level (eg. Python)
		2. Assembly Code (human readable)
		3. Machine code (binary)
		4. CPU
	Interpretation
		1. High level (eg. Python)
		2. Intermediate form
		3. Interpreter (pretends to be a CPU)
		4. CPU
	JIT compilation
		Compiles program to machine code only when program about to be ran.
		1. High level (eg. Java)
		2. Intermediate form
		3. JIT compiler program/VM translate to bytecodes @ runtime
		4. Machine code (binary)
		5. CPU

JIT and VMs
	Modern HL programming languages, like Java
	Means that program can be optimised based on uses for the particular machine.

Software Libraries
	HL programming languages make it easier to make libraries of common components - pre written code.
	How we build layers of software, hierarchies of abstraction.
	Encapsulate complex code into libraries.

Software evolution
	As new hardware/features arise, software libraries can be updated. However, as updates occur old programs can be broken leading to compatibility issues.

Backwars/Forwards Compatibility
	Back: new program aware of old libraries
	New libraries should supply a new API and old API for legacy programs.

API