<img width="3000" height="1000" alt="readme-header" src="https://github.com/user-attachments/assets/692ddf32-0af6-41f3-92df-2d57671c71f7" />

I am a full-stack engineer and builder who transitions complex ideas into production ready software. My experience ranges from launching secure, high-traffic distributed applications to designing decoupled, AI driven SaaS architectures with active paying customers. I approach software with a fast execution, product first mindset, treating every technical constraint as a challenge to optimize for speed, maintainability, and scalability

---

### Featured Production Projects
#### <img width="24" height="24" alt="256x256_light" src="https://github.com/user-attachments/assets/0b672568-47b8-43b4-b092-cef4c011de9b" /> Gwens (AI Ad Generation Platform)
**Architecture & System Design**
* Onion Architecture (DDD-Lite): Implemented a strict layered architecture to decouple core domain logic from infrastructure and third-party dependencies. This structural order significantly reduced debugging cycle times by isolating bug origins and creating predictable code boundaries.
* Provider Agnostic Design: The decoupled infrastructure layer allowed seamless hot-swapping and scaling of external AI capabilities. The platform grew from a single video/image provider into a multi-capability suite supporting vision, speech recognition, and upscaling without requiring modifications to the core business logic.
* High-Concurrency Orchestration: Engineered a high-performance backend using parallel asynchronous commands to execute multi-stage AI asset generations concurrently, drastically reducing overall end-user wait times.

**Media Processing & Performance Optimization**
* Asynchronous State Management: Utilized Server-Sent Events (SSE) to push real-time task completion statuses from the backend to the client, replacing inefficient polling methods for long-running generation pipelines.
* FFmpeg Memory & Buffer Tuning: Orchestrated complex media compilation pipelines using FFmpeg and Python-based processing tools. Resolved severe container buffering bottlenecks by profiling resource consumption and optimizing code execution paths to drastically reduce memory overhead during heavy video rendering jobs.
* Next-Gen Development Workflow: Integrated AI-assisted engineering tools (Cursor / LLMs) to rapidly prototype algorithms, optimize media processing bottlenecks, and accelerate feature shipping velocity

**Deployment & Commercial Impact**
* Containerized SaaS Infrastructure: Successfully containerized the entire Python and Node.js multi-stage environment using Docker, deploying it as a stable, live production web application on Azure.
* Production Validation: Validated the platform’s technical architecture and commercial viability by taking the product live and acquiring active paying customers.

Want to check out what Gwens was able to produce in 30 mintues from just a single prompt?
<table>
  <tr>
    <td>
      <a href="https://youtu.be/Kyc6teD8lbQ" target="_blank"> 
        <img width="1928" height="1072" alt="Group 1000001859" src="https://github.com/user-attachments/assets/c869917b-4110-4484-b60e-a3219fa2036e" />
      </a>
    </td>
    <td>
      <a href="https://youtu.be/mfSH2hFCuUk" target="_blank">
        <img width="1928" height="1072" alt="Group 1000001862 (1)" src="https://github.com/user-attachments/assets/80d747c3-ab32-45bd-be0e-6fba47066e8c" />
      </a>
    </td>
    <td>
      <a href="https://youtu.be/BB2485nLA8o" target="_blank">
        <img width="1928" height="1072" alt="Group 1000001863 (1)" src="https://github.com/user-attachments/assets/3fc1294a-4f9d-4371-895f-9331247b11cd" />
      </a>
    </td>
  </tr>
</table>

---

#### <img width="24" height="24" alt="sumnews_logo_black" src="https://github.com/user-attachments/assets/e1ab58ce-7fac-4923-99d5-8fe68aa36b69" /> **[Sumnews](https://www.sumnews.net/) (Summarized Articles App)**

**Core Architecture & Cross-Platform Deployment**
* Hybrid Cross-Platform Mobile Deployment: Engineered a mobile application utilizing Capacitor to compile a unified, single-codebase web application into native wrappers, successfully shipping the product to both the Google Play Store and the iOS App Store.
* Distributed Cloud Hosting: Built and deployed a live MEVN stack application, hosting the backend services securely on Heroku and the frontend application on Vercel to maintain high availability.
* Self-Taught Execution Mindset: Successfully conceptualized, designed, and self-coded the entire end-to-end architecture as a foundational first project, leveraging advanced AI-assisted coding tools to accelerate development velocity and bridge complex implementation gaps.

**AI Optimization & Data Engineering**
* Bulk Token Optimization: Designed an efficient data-ingestion pipeline that bundles multiple raw text articles into unified batch requests for AI processing.
* This bulk-summarization technique drastically minimized external API token consumption and significantly reduced overall ingestion execution times.
* Algorithmic Content Curation: Programmed advanced content filtering and categorization mechanisms, empowering users to easily isolate targeted topics and customize their information feeds on the fly.
* Dynamic UX Component (Daily Recaps): Engineered an engaging "Instagram-style" ephemeral story component for the daily recap feature, providing a highly visual, fast-paced interface that aggregates and renders the day's most critical news developments cleanly

<table>
  <tr>
    <td>
      <img width="200" alt="Screen 01" src="https://github.com/user-attachments/assets/02dcab35-8499-4aa8-a82c-9baf809758b2" />
    </td>
    <td>
      <img width="200" alt="Screen 02" src="https://github.com/user-attachments/assets/73135252-f655-4148-b33f-314f2bce6552" />
    </td>
    <td>
      <img width="200" alt="Screen 03" src="https://github.com/user-attachments/assets/1d64d155-65cc-407f-8722-4f852b09220c" />
    </td>
    <td>
      <img width="200" alt="Screen 04" src="https://github.com/user-attachments/assets/3d372457-9371-4d08-a171-b0de2f8d00e0" />
    </td>
    <td>
      <img width="200" alt="Screen 05" src="https://github.com/user-attachments/assets/9a7e15a0-5a35-4946-9b20-18b5ecad349c" />
    </td>
    <td>
      <img width="200" alt="Screen 06" src="https://github.com/user-attachments/assets/3de3fc98-ad31-431a-bef1-767c94069d21" />
    </td>
    <td>
      <img width="200" alt="Screen 07" src="https://github.com/user-attachments/assets/843d0c27-da60-4961-8417-dc8f5f8c501c" />
    </td>
  </tr>
</table>

---

#### <img height="24" alt="idf" src="https://github.com/user-attachments/assets/bd35f8ad-4bae-4fb9-b718-c29dec716248" /> IDF 

**Speech-to-Text & AI Summarization System (IDF Meitav Call Center)**

*Architecture & Pipeline EngineeringBatch Audio Ingestion:*
* Orchestrated an automated backend data pipeline that periodically fetched large volumes of recorded call audio from Azure Blob Storage for high-throughput batch processing.
* High-Volume Processing: Scaled the processing flow to successfully ingest, transcribe, and analyze thousands of calls per day, ensuring robust system stability under continuous heavy data loads.

*Structured AI Analytics & CRM Integration*
* Deterministic JSON Schema Extraction: Advanced prompt engineering techniques forced the LLM to output precise, structured JSON payloads. This allowed the backend to reliably extract metadata fields including caller temperament, core subject matter, resolution verification, and satisfaction metrics.
* CRM Automation: Seamlessly integrated the parsed AI insights back into the primary call center CRM as an dedicated data tab, completely automating data entry and drastically reducing manual documentation overhead for operators.

**[Keren Hasiyua](https://mushlam-frontend.wiz.digital.idf.il/m/PYZ55QW4F9) (National Reservist Compensation Platform)**

*High-Velocity Engineering & Delivery*
* Rapid Prototyping & Execution: Shattered traditional development timelines by building, testing, and shipping a production-ready digital claims platform in under two weeks to meet critical national needs.
* National-Scale Impact: Successfully deployed the platform to tens of thousands of citizens, business owners, and reservists, ensuring rapid delivery of crucial financial compensations.

*Complex Business Logic & UX Streamlining*
* Advanced Conditional Architecture: Engineered an intricate HTML/JS frontend architecture capable of executing dense, complex validation logic to accurately compute distinct legal compensation scenarios on the fly.
* Legacy Process Modernization: Replaced a tedious, painfully slow phone-intake bottleneck with an intuitive digital portal, drastically reducing processing backlogs and optimizing workflows for both applicants and administrative staff.
* Executive Recognition: The project's unprecedented deployment speed and sweeping civilian impact earned a formal presentation to senior national leadership, including the IDF Chief of Staff and the Minister of Defense.

---

### Tech Stack & Toolbox

* **Languages & Backend:** Node.js, Python, REST APIs, PostgreSQL, MongoDB, Vue (MEVN Stack)
* **AI & Automation:** LLM APIs, prompt engineering, AI workflow orchestration, media processing pipelines
* **DevOps & Cloud:** Azure, Docker, containerization, open-source tool integration

---

### Connect With Me
**LinkedIn:** [/in/eden-levin](https://www.linkedin.com/in/eden-levin-b298812b5/)
