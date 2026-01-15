# Akash Bhat (quentesia)

_`Developer & Linux Enthusiast`_

I enjoy building systems and automating tasks to make my life easier.

### Why?

_~~Because I can~~_ Because it's more fun to spend 3 hours automating a 10-minute task than to do it manually.

### 🧰 Languages and Tools

<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" />
<img align="left" alt="C++" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" />
<img align="left" alt="C" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" />
<img align="left" alt="Java" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"/>
<img align="left" alt="Rust" width="30px" style="padding-right:10px;" src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Original_Ferris.svg" />
<img align="left" alt="JavaScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />
<img align="left" alt="Bash" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
<img align="left" alt="React" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
<img align="left" alt="PyTorch" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" />
<img align="left" alt="TensorFlow" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" />
<img align="left" alt="Docker" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" />
<img align="left" alt="Kubernetes" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" />
<img align="left" alt="AWS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" />
<img align="left" alt="PostgreSQL" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" />
<img align="left" alt="MongoDB" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" />
<img align="left" alt="Redis" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
<br />
<img align="left" alt="Pop!_OS" width="30px" style="padding-right:10px;" src="https://cdn.simpleicons.org/popos" />
<br />
<br />

#

### Currently Working On

<!-- START CURRENT PROJECTS -->

> ### [Distributed ML Training Platform](https://github.com/quentesia/Distributed-ML-Training-Platform)
>
> Scalable asynchronous ML training system processing 10K batches/day
>
> **Tech:** Python, FastAPI, RabbitMQ, Celery, Redis, PyTorch, Docker
>
> _Had 4 days to finish an ML project. Training was impossible on my laptop. Spent 2 days building distributed infrastructure instead. Made the deadline with a day to spare. Building the system was more fun than the project anyway._
>
> ✧ 50% latency reduction via Redis caching  
> ✧ 5K concurrent tasks with fault tolerance  
> ✧ Containerized AWS deployment

> ### Agentic Dependency Manager _(Currently Private)_
>
> AI-powered dependency upgrade system that autonomously analyzes, reasons about, and applies package updates
>
> **Tech:** Python, LangChain, OpenAI API, uv
>
> _Tired of manual dependency hell and breaking changes. Building an agent that autonomously checks all possible upgrade combinations, provides concrete reasoning for each change, predicts potential issues, and safely applies updates. Currently Python-only but planning multi-language support._
>
> ✧ Autonomous upgrade analysis with reasoning  
> ✧ Supports requirements.txt, poetry, uv and conda environments  
> ✧ Breaking change prediction and mitigation  
> ✧ Safe rollback on failure

<!-- END CURRENT PROJECTS -->

#

### A Few Past Projects

<!-- START PAST PROJECTS -->

> ### 📅 [AI Meeting Scheduler](https://github.com/quentesia/ai_scheduler)
>
> Natural language meeting scheduling that actually understands what you mean
>
> **Tech:** Python, Dialogflow, Google Calendar API, Flask, Twilio
>
> _Scheduling meetings across time zones is painful. Built an AI agent that understands natural language requests like "schedule a meeting with the team next Tuesday at 2pm" and handles the entire flow. It parses intent with Dialogflow, resolves conflicts, manages time zones, syncs with Google Calendar, and sends SMS confirmations via Twilio. Validated with 2,000+ simulated requests achieving 95% accuracy. Now I just text my scheduler instead of opening a calendar app._
>
> ✧ Natural language understanding via Dialogflow  
> ✧ Intelligent conflict resolution and time zone handling  
> ✧ Automated calendar sync and SMS notifications

> ### [GUOQ Compiler Benchmarking](https://github.com/quentesia/guoq)
>
> ![Gate Error Rates](https://github.com/quentesia/guoq/blob/main/plots/guoq_compiler_wins_by_hw.png?raw=true)
> Testing which quantum compiler actually performs best for different workloads
>
> **Tech:** Python, Qiskit, IBM Quantum, IonQ, Rigetti, GUOQ, TKET, PyZX
>
> _Quantum computing class introduced me to GUOQ, our university's circuit compiler. Got curious: how does it stack up against industry tools? Forked it and ran exhaustive benchmarks against TKET and PyZX across IBM, IonQ, and Rigetti hardware with 5 circuit categories._
>
> **\*Result**: GUOQ dominated gate error rates, but each compiler had sweet spots—physics simulations favored GUOQ's unitary synthesis approach, while PyZX excelled at arithmetic circuits with graph-based rewrites. Used this data to identify exactly where GUOQ's optimization strategy could be pushed further.\*
>
> ✧ 3-compiler comparison across 4 quantum platforms  
> ✧ Created specific circuits for testing different workloads  
> ✧ Circuit-specific optimization trade-off analysis  
> ✧ Mapped improvement opportunities for GUOQ's rewrite rules

> ### [🏴‍☠ One Piece Laugh Analyzer](https://github.com/quentesia/one_piece_laugh_analyzer)
>
> Training AI to recognize anime characters by their ridiculous laughs
>
> **Tech:** Python, librosa, NumPy, scipy, scikit-learn
>
> _One Piece characters have the most distinctive laughs I've ever heard. "Zehahahaha!", "Shorororo!", "Fufufufu". Got curious if they were actually different enough to classify algorithmically. Built a tool to extract laugh audio, split it into segments, generate spectrograms, and analyze frequency patterns._
>
> _Spoiler: they're absolutely distinguishable. Each laugh has its own frequency signature and rhythm. This started as a meme project but turned into a bit of legitimate audio analysis._
>
> ✧ Automated laugh extraction and segmentation  
> ✧ Spectrogram generation for pattern analysis  
> ✧ Character-specific frequency signature identification

<!-- END PAST PROJECTS -->

#

_If you made it here, check out my [art page](https://artstation.com/quentesia) as well!_
