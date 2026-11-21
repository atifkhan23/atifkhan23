<div align="center">

<h1>Atif Ullah Khan</h1>

<p><b>AI Engineer &nbsp;·&nbsp; Full-Stack Developer &nbsp;·&nbsp; Applied ML Researcher</b></p>

<a href="https://atif-portfolio-eta.vercel.app/"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=58A6FF&center=true&vCenter=true&width=640&lines=Agentic+AI+systems+and+RAG+pipelines;LLM+fine-tuning+and+evaluation;Computer+vision+and+3D+human+pose;Speech+and+text-to-speech" alt="Typing SVG" /></a>

<p>
  <a href="https://atif-portfolio-eta.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/atifullahkhan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://zenodo.org/search?q=%22Atif%20Ullah%20Khan%22"><img src="https://img.shields.io/badge/Zenodo-Research-1682D4?style=for-the-badge&logo=zenodo&logoColor=white"/></a>
  <a href="https://huggingface.co/itxmekan908067xcv"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/></a>
  <a href="https://www.kaggle.com/atifkhan89"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/></a>
  <a href="mailto:itxmeatif8@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<img src="https://komarev.com/ghpvc/?username=atifkhan23&style=flat-square&color=58A6FF&label=Profile+views"/>

</div>

<br/>

## About

I am an AI engineer based in Islamabad, Pakistan, with a bachelor's degree in **Artificial Intelligence** from **PAF-IAST**. I build AI systems end to end, from data and training to evaluation and deployment, and I care about testing models properly before trusting them.

My work spans **large language models**, **computer vision** and **speech**:

- Fine-tuning and evaluating LLMs (QLoRA, RAG, citation grounding, robustness testing)
- Agentic AI systems and retrieval-augmented applications
- Detection, tracking and 3D human pose reconstruction
- Text-to-speech adaptation and speech pipelines

I am currently seeking **funded graduate research opportunities** in AI.

<br/>

## Research

<p align="center"><i>Preprints and evaluation studies on making AI models more reliable.</i></p>

<table>
<tr>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/PREPRINT-LLM%20%C2%B7%20Legal%20NLP-1682D4?style=flat-square&labelColor=0D1117"/>

<h3>CPC-PKL</h3>

<p>Fine-tuning, retrieval and citation hallucination in legal question answering on Pakistan's Code of Civil Procedure 1908. A new dataset of 2,467 long-form QA pairs, comparing base and QLoRA fine-tuned Qwen2.5-7B with and without hybrid RAG.<br/><sub><b>Key result</b> — fine-tuning lifted ROUGE-L from 0.234 to 0.266 but learned to cite cases it could not ground; retrieval restored grounding.</sub></p>

<p><code>Qwen2.5-7B</code> <code>QLoRA</code> <code>Hybrid RAG</code> <code>Citation analysis</code></p>

<p><a href="https://zenodo.org/search?q=%22Atif%20Ullah%20Khan%22"><img src="https://img.shields.io/badge/Paper-1682D4?style=for-the-badge&logo=zenodo&logoColor=white"/></a> <a href="https://github.com/atifkhan23/pakistan-cpc-legal-llm"><img src="https://img.shields.io/badge/Code-24292F?style=for-the-badge&logo=github&logoColor=white"/></a></p>

</td>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/PREPRINT-Computer%20Vision%20%C2%B7%203D%20Pose-7C3AED?style=flat-square&labelColor=0D1117"/>

<h3>PoseGuard</h3>

<p>Occlusion-aware training for robust 2D-to-3D human pose lifting. Teaches pose-lifting models to stay accurate when keypoints are missing or hidden, as they often are in real-world video.</p>

<p><code>PyTorch</code> <code>2D→3D lifting</code> <code>Occlusion robustness</code> <code>Kaggle</code></p>

<p><a href="https://zenodo.org/search?q=%22Atif%20Ullah%20Khan%22"><img src="https://img.shields.io/badge/Paper-1682D4?style=for-the-badge&logo=zenodo&logoColor=white"/></a> <a href="https://github.com/atifkhan23/PoseGuard-Occlusion-Aware-Training-for-Robust-2D-to-3D-Human-Pose-Lift"><img src="https://img.shields.io/badge/Code-24292F?style=for-the-badge&logo=github&logoColor=white"/></a></p>

</td>
</tr>
<tr>
<td colspan="2" width="100%" valign="top">

<img src="https://img.shields.io/badge/STUDY-LLM%20Evaluation-0E9F6E?style=flat-square&labelColor=0D1117"/>

<h3>Efficiency vs. Trust on GSM8K</h3>

<p>How robust are open-weight LLMs at math reasoning? A controlled evaluation that rewrites GSM8K problems with systematic transformations and measures where accuracy breaks down, and whether smaller, faster models can still be trusted.</p>

<p><code>Open-weight LLMs</code> <code>GSM8K</code> <code>Robustness testing</code> <code>Python</code></p>

<p><a href="https://github.com/atifkhan23/efficiency-vs-trust-gsm8k"><img src="https://img.shields.io/badge/Code-24292F?style=for-the-badge&logo=github&logoColor=white"/></a></p>

</td>
</tr>
</table>

<br/>

## Selected Projects

<table>
<tr>
<td colspan="2" valign="top">

<img src="https://img.shields.io/badge/FLAGSHIP-Multimodal%20AI-D97706?style=flat-square&labelColor=0D1117"/>

<h3>Multimodal Surgical Video Analytics</h3>

<p>An end-to-end pipeline that detects and tracks surgical instruments frame by frame, then uses a fine-tuned vision-language model to describe what is happening in the procedure, turning raw surgical video into searchable, structured insight.</p>

<p><code>LLaVA v1.5-7B</code> <code>QLoRA</code> <code>YOLOv8</code> <code>ByteTrack</code> <code>PyTorch</code></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/LEGAL%20AI-RAG-1682D4?style=flat-square&labelColor=0D1117"/>

<h3>AI Legal Case Management System</h3>

<p>Final-year project built with industry partner Insafdaar Law Firm: a RAG-based assistant that answers questions over legal case records using a knowledge graph.</p>

<p><code>Gemini API</code> <code>RAG</code> <code>Knowledge Graph</code></p>

<p><a href="https://129.154.41.160/"><img src="https://img.shields.io/badge/Live%20Demo-0E9F6E?style=for-the-badge&logo=googlechrome&logoColor=white"/></a></p>

</td>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/AGENTIC%20AI-Multi--Agent-7C3AED?style=flat-square&labelColor=0D1117"/>

<h3>Private AI Desktop Agent</h3>

<p>A private multi-agent system for sales and marketing: lead research, outreach, objection handling, call review, copywriting and funnel optimization.</p>

<p><code>LLM Agents</code> <code>Python</code> <code>Tool use</code></p>

<p></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/AGENTIC%20AI-Memory-7C3AED?style=flat-square&labelColor=0D1117"/>

<h3>Meeting Memory Agent</h3>

<p>An agent that turns meeting transcripts into structured, searchable memory so decisions and action items are never lost.</p>

<p><code>Python</code> <code>LLMs</code> <code>Retrieval</code></p>

<p><a href="https://github.com/atifkhan23/ami-meeting-memory-agent"><img src="https://img.shields.io/badge/Code-24292F?style=for-the-badge&logo=github&logoColor=white"/></a></p>

</td>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/COMPUTER%20VISION-Sports-D97706?style=flat-square&labelColor=0D1117"/>

<h3>Snooker Analytics</h3>

<p>Real-time ball detection and tracking with gameplay analytics built on top of the tracked trajectories.</p>

<p><code>YOLOX</code> <code>ByteTrack</code> <code>OpenCV</code></p>

<p></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/LOGISTICS-Routing-0E9F6E?style=flat-square&labelColor=0D1117"/>

<h3>Weather-Aware Truck Routing</h3>

<p>Route planning for trucks that takes live weather conditions into account.</p>

<p><code>TypeScript</code></p>

<p><a href="https://github.com/atifkhan23/Weather-Aware-Truck-Routing"><img src="https://img.shields.io/badge/Code-24292F?style=for-the-badge&logo=github&logoColor=white"/></a></p>

</td>
<td width="50%" valign="top">

<img src="https://img.shields.io/badge/LOGISTICS-ML%20Model-0E9F6E?style=flat-square&labelColor=0D1117"/>

<h3>Truck Freight Rate Model</h3>

<p>A machine-learning model for estimating truck freight rates.</p>

<p><code>Python</code> <code>scikit-learn</code></p>

<p><a href="https://github.com/atifkhan23/truck-freight-rate-model"><img src="https://img.shields.io/badge/Code-24292F?style=for-the-badge&logo=github&logoColor=white"/></a></p>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

<img src="https://img.shields.io/badge/SPEECH-Text--to--Speech-DB2777?style=flat-square&labelColor=0D1117"/>

<h3>Speech &amp; TTS</h3>

<p>Fine-tuning and adapting text-to-speech models for new voices and languages.</p>

<p><code>Chatterbox</code> <code>Meta MMS-TTS</code> <code>PyTorch</code></p>

</td>
</tr>
</table>

<p align="center">
  <a href="https://github.com/atifkhan23?tab=repositories"><img src="https://img.shields.io/badge/See%20all%2042%20repositories-0D1117?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<br/>

## Technical Skills

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,js,ts,html,css,bash,md&theme=dark" />
</p>

**Machine Learning & AI**

<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv,anaconda&theme=dark" />
</p>

<p>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/Transformers-FF9D00?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/LlamaIndex-6E44FF?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/YOLO-111F68?style=for-the-badge&logo=yolo&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gradio-F97316?style=for-the-badge&logo=gradio&logoColor=white"/>
</p>

**Web & Backend**

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,fastapi,flask,django,tailwind&theme=dark" />
</p>

**Databases**

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite,redis&theme=dark" />
</p>

**Cloud, DevOps & Tools**

<p>
  <img src="https://skillicons.dev/icons?i=gcp,azure,docker,linux,git,github,githubactions,vercel,vscode,postman&theme=dark" />
</p>

<br/>

## Experience

| Role | Organization | Period |
|---|---|---|
| Freelance AI / Computer Vision Engineer | Upwork & Fiverr | 2024 – Present |
| AI Systems Engineer | Insafdaar Law Firm | 2025 |
| Intern, Data Center Department | NTC Headquarters, Islamabad | Jun – Jul 2025 |
| Research Intern (3D pose estimation, Azure Kinect DK) | Sino-Pak Center for Artificial Intelligence | Sep – Oct 2023 |

<br/>

## GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=atifkhan23&show_icons=true&theme=github_dark&hide_border=true&count_private=true&bg_color=0D1117"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=atifkhan23&layout=compact&theme=github_dark&hide_border=true&langs_count=6&bg_color=0D1117"/>

<br/>

<img src="https://streak-stats.demolab.com?user=atifkhan23&theme=github-dark-blue&hide_border=true&background=0D1117" width="62%"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=atifkhan23&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FFFFFF&area=true&hide_border=true" width="100%"/>

</div>

<br/>

<div align="center">
  <sub>Open to research collaborations and graduate opportunities — reach out on <a href="https://www.linkedin.com/in/atifullahkhan">LinkedIn</a> or by <a href="mailto:itxmeatif8@gmail.com">email</a>.</sub>
</div>
