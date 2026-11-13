# Syed Zain-ul-Wahaj

AI engineer in Islamabad. At GenMediTech, a healthcare SaaS company, I build LLM agents and the
web apps and AWS infrastructure around them. I'm also in the final year of a BS in Artificial
Intelligence at COMSATS University Islamabad.

## Work

The code for these is private; the products are live.

- **Reseptive**: an AI receptionist that answers a multi-provider clinic's phone line. It books
  appointments through the clinic's EMR, takes messages and consult requests, and routes each one
  to the on-call provider. I built the voice agent and the console the office works from.
  ElevenLabs, Twilio, Next.js, Prisma, PostgreSQL.
- **[SmartNotes AI](https://smartnotesai.com)**: medical scribing with real-time transcription and
  SOAP notes that a physician signs off before they reach the record. LangGraph, OpenAI Agents SDK.
- **[MedCodifier](https://medcodifier.com)**: ICD and CPT code extraction with conflict checks and
  reimbursement estimates. LangChain, LangGraph, Pinecone.
- EHR integrations with eClinicalWorks, CareCloud and Cerner, and the AWS infrastructure for all
  of it in CDK.

## Projects

| Project | What it is | Stack |
| --- | --- | --- |
| [tokforge](https://github.com/zainulwahaj/tokforge) | BPE tokenizer written from scratch in Rust, with a Python package on PyPI. Token ids identical to tiktoken for GPT-2, GPT-4 and GPT-4o, checked on 110M differential inputs. [Live demo](https://tokforge.clairoai.tech). | Rust, PyO3, GitHub Actions |
| [SecureVault](https://github.com/zainulwahaj/SecureVault) | File vault where all encryption happens in the browser, so the server cannot read what it stores. | Next.js, FastAPI, libsodium, PostgreSQL |
| [RecipeHub](https://github.com/zainulwahaj/recipehub-be) | Recipe platform with AI generation from ingredients, JWT auth and role-based access. [Frontend](https://github.com/zainulwahaj/recipehub-fe). | FastAPI on AWS Lambda, React 19 |
| [termview](https://github.com/zainulwahaj/termview) | Images, GIFs and video in the terminal, with audio. [Browser version](https://termview-web.vercel.app). | Python, React |
| [TaskMGR-clone](https://github.com/zainulwahaj/TaskMGR-clone) | Task manager for Windows and macOS from one C# codebase. | .NET 8, Avalonia UI |
| [selfhealing-mlops](https://github.com/zainulwahaj/selfhealing-mlops-FA23-BAI-058) | Blue-green Kubernetes deployment where a Prometheus alert triggers a Jenkins rollback. | Kubernetes, Jenkins, Prometheus, Grafana |

## Contact

- Email: zainulwhaj4@gmail.com
- LinkedIn: [zain-ul-whaj-a6678719a](https://www.linkedin.com/in/zain-ul-whaj-a6678719a)
- Portfolio: [portfolio-orpin-eight-48.vercel.app](https://portfolio-orpin-eight-48.vercel.app)
