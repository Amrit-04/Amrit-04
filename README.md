 <p align="center">
  <a href="https://github.com/Amrit-04">
    <img src="https://capsule-render.vercel.app/api?type=rounded&color=0:0B0F19,55:1F2335,100:7AA2F7&height=220&section=header&text=Amritesh%20Yadav&fontSize=76&fontColor=C0CAF5&animation=fadeIn&fontAlignY=40&desc=AI%2FML%20Systems%20%C2%B7%20Backend%20Infrastructure%20%C2%B7%20Developer%20Tooling&descSize=19&descAlignY=64" width="100%" alt="Amritesh Yadav" />
  </a>
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=25&duration=2600&pause=1500&color=BB9AF7&background=0B0F19&center=true&vCenter=true&width=900&height=56&lines=%3E+building+observable+AI+systems.;%3E+engineering+reliable+data+pipelines.;%3E+exploring+graph+ML+and+computer+vision." width="100%" alt="Building observable AI systems" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/amriteshkumar-yadav-214594250/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-7AA2F7?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=161B2D" alt="LinkedIn" />
  </a>
  <a href="mailto:amriteshyadav2004@gmail.com">
    <img src="https://img.shields.io/badge/Email-Say%20Hello-BB9AF7?style=for-the-badge&logo=gmail&logoColor=white&labelColor=161B2D" alt="Email" />
  </a>
  <a href="https://github.com/Amrit-04">
    <img src="https://img.shields.io/badge/GitHub-Profile-C0CAF5?style=for-the-badge&logo=github&logoColor=white&labelColor=161B2D" alt="GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/IEEE_RMKMATE-2026_publication-7AA2F7?style=for-the-badge&labelColor=161B2D" alt="IEEE RMKMATE 2026 publication" />
  <img src="https://img.shields.io/badge/7%2C891.5_peak_consume_EPS-measured-BB9AF7?style=for-the-badge&labelColor=161B2D" alt="7,891.5 peak consume events per second" />
  <img src="https://img.shields.io/badge/900%2C469_valid_events-0_loss%2C_0_duplicates-7DCFFF?style=for-the-badge&labelColor=161B2D" alt="900,469 valid events reconciled with zero loss or duplicates" />
  <img src="https://img.shields.io/badge/0.439ms_p95-GNN_end--to--end_inference-C0CAF5?style=for-the-badge&labelColor=161B2D" alt="0.439 milliseconds end-to-end GNN inference p95" />
</p>

<p align="center">
  <sub>Measured project benchmarks, not production SLAs. Pipeline peak consume rate is distinct from database write throughput. The 900,469-event result is from a separate chaos test. GNN latency is from the documented ONNX CPU benchmark.</sub>
</p>

---

## 🧬 about

I build at the intersection of AI and systems engineering.

My work spans local-first LLM and RAG observability, fault-tolerant ML telemetry pipelines, graph-based query-cost modelling, and real-time computer vision.

I care about the engineering that makes intelligent applications dependable: durable data paths, explicit failure handling, measurable behaviour, and useful developer interfaces.

**Currently focused on**

- **AI/ML systems:** Building reliable infrastructure around LLMs, RAG applications, and intelligent agents.
- **Backend engineering:** Designing event-driven pipelines, distributed services, and fault-tolerant data systems.
- **Developer tooling:** Making complex systems easier to observe, debug, and operate.

**Areas I enjoy exploring**

- Graph machine learning and neural query optimization.
- Real-time computer vision and edge inference.
- Computational neuroscience and biologically inspired neural circuits.

## 🚀 selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛰️ <a href="https://github.com/Amrit-04/llm-reliability-control-plane">LLM Reliability Control Plane</a></h3>
      <sub><b>LLM / RAG observability</b></sub>
      <p>A self-hosted, local-first observability platform for LLM applications and AI agents. Features a C++20 OTLP gateway, durable write-ahead logging, Parquet-based trace storage, FastAPI analytics, and a Next.js trace explorer.</p>
      <p><code>C++20</code> <code>OpenTelemetry</code> <code>FastAPI</code> <code>DuckDB</code> <code>Next.js</code> <code>Redis</code></p>
      <a href="https://github.com/Amrit-04/llm-reliability-control-plane">
        <img src="https://img.shields.io/badge/Explore_Project-7AA2F7?style=for-the-badge&labelColor=161B2D" alt="Explore project" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/Amrit-04/Fault-Tolerant-ML-Telemetry-Feature-Streaming-Pipeline">Fault-Tolerant ML Pipeline</a></h3>
      <sub><b>Distributed systems / streaming</b></sub>
      <p>A polyglot telemetry streaming platform using concurrent Go ingestion, Kafka, Python feature processing, PostgreSQL persistence, and Redis-based serving. Includes dead-letter queue auditing, event re-drive, and Prometheus/Grafana monitoring.</p>
      <p><code>Go</code> <code>Python</code> <code>Kafka</code> <code>PostgreSQL</code> <code>Redis</code> <code>Docker</code></p>
      <a href="https://github.com/Amrit-04/Fault-Tolerant-ML-Telemetry-Feature-Streaming-Pipeline">
        <img src="https://img.shields.io/badge/Explore_Project-BB9AF7?style=for-the-badge&labelColor=161B2D" alt="Explore project" />
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 <a href="https://github.com/Amrit-04/neural-query-optimizer">Neural Query Cost Model</a></h3>
      <sub><b>Graph ML / database systems</b></sub>
      <p>A learned query-cost estimator and physical plan ranker for PostgreSQL. Converts EXPLAIN execution plans into graph representations and applies GNN-based ranking to compare alternative query plans.</p>
      <p><code>Python</code> <code>PyTorch</code> <code>PyG</code> <code>PostgreSQL</code> <code>ONNX Runtime</code></p>
      <p><b>Benchmark:</b> 0.439 ms end-to-end p95 CPU inference latency.</p>
      <a href="https://github.com/Amrit-04/neural-query-optimizer">
        <img src="https://img.shields.io/badge/Explore_Project-7DCFFF?style=for-the-badge&labelColor=161B2D" alt="Explore project" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>🦺 <a href="https://github.com/Amrit-04/workplace-safety-vision">Workplace Safety Vision</a></h3>
      <sub><b>Real-time computer vision / IEEE publication</b></sub>
      <p>A real-time vision framework for PPE compliance and restricted-zone intrusion detection. Features dual-model inference, worker tracking, interactive geofencing, incident auditing, and a live monitoring dashboard.</p>
      <p><code>Python</code> <code>YOLO11</code> <code>OpenCV</code> <code>Flask</code></p>
      <p><a href="https://ieeexplore.ieee.org/document/11518869">IEEE RMKMATE 2026 publication ↗</a></p>
      <a href="https://github.com/Amrit-04/workplace-safety-vision">
        <img src="https://img.shields.io/badge/Explore_Project-7AA2F7?style=for-the-badge&labelColor=161B2D" alt="Explore project" />
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🪰 <a href="https://github.com/Amrit-04/Fly_pet">Fly-Magotchi</a></h3>
      <sub><b>Computational neuroscience / interactive simulation</b></sub>
      <p>A biologically inspired desktop pet whose behaviour emerges from a compact neural-circuit simulation. Uses Leaky Integrate-and-Fire dynamics, sensory integration, and procedural pixel-art rendering.</p>
      <p><code>Python</code> <code>NumPy</code> <code>PyQt6</code> <code>Neural simulation</code></p>
      <a href="https://github.com/Amrit-04/Fly_pet">
        <img src="https://img.shields.io/badge/Explore_Project-BB9AF7?style=for-the-badge&labelColor=161B2D" alt="Explore project" />
      </a>
    </td>
    <td width="50%" valign="top">
      <h3>📂 <a href="https://github.com/Amrit-04?tab=repositories">More Work</a></h3>
      <sub><b>Experiments and engineering</b></sub>
      <p>More experiments, prototypes, and technical explorations across software engineering, AI, infrastructure, and developer tooling.</p>
      <a href="https://github.com/Amrit-04?tab=repositories">
        <img src="https://img.shields.io/badge/View_All_Repositories-7DCFFF?style=for-the-badge&labelColor=161B2D" alt="View repositories" />
      </a>
    </td>
  </tr>
</table>

## 📊 engineering highlights

| Project | Measurement | Result |
|---|---|---:|
| Fault-Tolerant ML Pipeline | Peak Kafka consumer rate | **7,891.5 events/s** |
| Fault-Tolerant ML Pipeline | Average consumer rate over 310 seconds | **7,116.6 events/s** |
| Fault-Tolerant ML Pipeline | Chaos-test valid event reconciliation | **900,469 / 900,469** |
| Fault-Tolerant ML Pipeline | Duplicate rows after chaos test | **0** |
| Fault-Tolerant ML Pipeline | Malformed events isolated in DLQ | **44,493 / 44,493** |
| Neural Query Cost Model | ONNX end-to-end inference p95 | **0.439 ms** |

<sub>These results come from documented local benchmark runs. The pipeline's 10,000 events/s target was not sustained, and peak consume rate is not database write throughput. See the project repositories for methodology and raw results.</sub>

## 🧰 technology stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,rust,go,scala,ts,pytorch,opencv,fastapi,postgres,redis,docker,linux&perline=7&theme=dark" alt="Python, C++, Rust, Go, Scala, TypeScript, PyTorch, OpenCV, FastAPI, PostgreSQL, Redis, Docker, and Linux" />
</p>

<p align="center">
  <sub>Also working with: Kafka · OpenTelemetry · DuckDB · Parquet · ONNX Runtime · PyTorch Geometric · CMake · PyQt6 · Prometheus · Grafana</sub>
</p>

## 📈 GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=Amrit-04&show_icons=true&hide_border=true&include_all_commits=true&bg_color=0B0F19&title_color=7AA2F7&text_color=C0CAF5&icon_color=BB9AF7" alt="GitHub statistics" />
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Amrit-04&layout=compact&hide_border=true&langs_count=8&bg_color=0B0F19&title_color=7AA2F7&text_color=C0CAF5" alt="Most used languages" />
</p>

---

<p align="center">
  <b>Have an interesting systems or applied-ML problem?</b>
  <br />
  Let's build something useful.
</p>

<p align="center">
  <a href="mailto:amriteshyadav2004@gmail.com">
    <img src="https://img.shields.io/badge/Let's_Talk-BB9AF7?style=for-the-badge&logo=gmail&logoColor=0B0F19&labelColor=161B2D" alt="Let's talk" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rounded&color=0:7AA2F7,100:0B0F19&height=90&section=footer&text=Build%20thoughtfully.%20Measure%20honestly.&fontSize=25&fontColor=C0CAF5&fontAlignY=52" width="100%" alt="Build thoughtfully. Measure honestly." />
</p>
