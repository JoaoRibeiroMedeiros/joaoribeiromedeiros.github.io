% a mashup of hipstercv, friggeri and twenty cv
% https://www.latextemplates.com/template/twenty-seconds-resumecv
% https://www.latextemplates.com/template/friggeri-resume-cv

\documentclass[lighthipster]{simplehipstercv}
% available options are: darkhipster, lighthipster, pastel, allblack, grey, verylight, withoutsidebar
% withoutsidebar
\usepackage[utf8]{inputenc}
\usepackage[default]{raleway}
\usepackage[margin=1cm, a4paper]{geometry}


%------------------------------------------------------------------ Variablen

\newlength{\rightcolwidth}
\newlength{\leftcolwidth}
\setlength{\leftcolwidth}{0.23\textwidth}
\setlength{\rightcolwidth}{0.75\textwidth}

%------------------------------------------------------------------
\title{New Simple CV}
\author{\LaTeX{} Ninja}
\date{June 2019}

\pagestyle{empty}
\begin{document}


\thispagestyle{empty}
%-------------------------------------------------------------

\section*{Start}

\simpleheader{headercolour}{Jo\~ao}{Ribeiro Medeiros}{Senior AI Engineer - Tech Lead - Data Scientist}{white}



%------------------------------------------------

% this has to be here so the paracols starts..
\subsection*{}
\vspace{4em}

\setlength{\columnsep}{1.5cm}
\columnratio{0.23}[0.75]
\begin{paracol}{2}
\hbadness5000
%\backgroundcolor{c[1]}[rgb]{1,1,0.8} % cream yellow for column-1 %\backgroundcolor{g}[rgb]{0.8,1,1} % \backgroundcolor{l}[rgb]{0,0,0.7} % dark blue for left margin

\paracolbackgroundoptions

% 0.9,0.9,0.9 -- 0.8,0.8,0.8


\footnotesize
{\setasidefontcolour
\flushright
\begin{center}
    \roundpic{3x4github.jpeg}
\end{center}

\bg{cvgreen}{white}{About me}\\[0.5em]

{\footnotesize
I'm João Ribeiro Medeiros, Tech lead, Senior AI Engineer and Data Scientist with a background in Statistical Physics and expertise in Data Engineering. I build AI systems that detect anomalies at scale, make legacy platforms smarter through LLMs, and turn organizational knowledge into a compounding asset.
\bigskip

\bg{cvgreen}{white}{personal} \\[0.5em]
Nationality: Brazilian

\bigskip

\bg{cvgreen}{white}{Areas of specialization} \\[0.5em]

AI Engineering ~•~ Data Science ~•~ Data Engineering ~•~ Physics

% \bigskip

% \bg{cvgreen}{white}{Languages}\\[0.5em]

% English ~•~ Portuguese ~•~ French ~•~ Spanish 

\bigskip

\bg{cvgreen}{white}{Interests}\\[0.5em]

Tech ~•~ Science ~•~ Literature ~•~ Music

\bigskip



\vspace{4em}

\infobubble{\faAt}{cvgreen}{white}{johananmdairus@gmail}
\infobubble{\faTwitter}{cvgreen}{white}{@RioJanu}
\infobubble{\faFacebook}{cvgreen}{white}{João Medeiros}
\infobubble{\faGithub}{cvgreen}{white}{JoaoRibeiroMedeiros}

\phantom{turn the page}

\phantom{turn the page}
}
%-----------------------------------------------------------
\switchcolumn

\small
\section*{Short Resumé}

\begin{tabular}{r| p{0.4\textwidth} c}
     \cvevent{2025--}{Senior AI Innovation Specialist}{Lead}{IgniteTech \color{cvred}}{Project lead for an end-to-end anomaly detection platform monitoring enterprise appliances in real time: supervised and unsupervised ML pipelines feeding agentic systems on distributed AWS architectures. Lead a cross-functional engineering team from sprint planning to production, reporting to VP-level stakeholders. Build AI coding assistants for legacy platforms (RAG, MCP) and lead knowledge-management initiatives that structure institutional expertise into AI-ready frameworks.
    }{ignite_technologies_logo.jpeg} \\
     \cvevent{2025}{AI Innovation Specialist}{Team}{IgniteTech \color{cvred}}{Designed and refined AI-systems to optimize software development: AI-driven solutions tailored for software engineering to accelerate development, reduce human errors, and enhance code quality, shortening time-to-market.
    }{ignite_technologies_logo.jpeg} \\
    \cvevent{2023--2024}{Head of AI}{Lead}{AI Collaborator \color{cvred}}{Lead AI and Data Science efforts at AI Collaborator, managing internal AI product development team as well as leading client facing AI development projects. Develop thought leadership initiatives and vision for company AIOps, strategy, team growth, and innovative AI offerings. 
}{aicollaborator_logo.jpeg} \\
    \cvevent{2021--2023}{Chief Data Officer}{Lead}{RIO analytics \color{cvred}}{Developed and deployed Predictive Maintenance cloud based Software, as well as ETL routines for monitoring large industrial operations, and AI/Machine Learning models for anomaly detection and asset health scoring.}{rio_analytics.png}\\
    \cvevent{2021}{Back-end Developer}{Team}{VIRTUAL Software \color{cvred}}{Developed automated integration tests for financial proof and transaction validation.}{virtualsoftware.jpeg} \\
    \cvevent{2018--2020}{Lead Data Scientist}{Lead}{CAMIN \color{cvred}}{Developed integrated hardware, software and data science solutions for Industrial Waste management in partnership with Ternium.}{CaminLogo.png}
\end{tabular}
\vspace{3em}
\vspace{3em}
\vspace{3em}
\vspace{3em}

\begin{minipage}[t]{0.35\textwidth}
\section*{Degrees}
\begin{tabular}{r p{0.6\textwidth} c}
    \cvdegree{2023}{PhD in Physics}{Non-Equilibrium Thermodynamics}{CBPF \color{headerblue}}{}{cbpf_mcti_logo-1.jpg} \\
    \cvdegree{2015}{MSc in Physics}{Non-Equilibrium Thermodynamics}{CBPF \color{headerblue}}{}{cbpf_mcti_logo-1.jpg} \\
    \cvdegree{2012}{B.Sc in Physics}{PhD}{PUC-Rio \color{headerblue}}{}{puc-rio.png}
\end{tabular}
\end{minipage}\hfill
\begin{minipage}[t]{0.3\textwidth}
\section*{Programming}
\begin{tabular}{r @{\hspace{0.5em}}l}
     \bg{skilllabelcolour}{iconcolour}{python} & \barrule{0.4}{0.5em}{cvpurple} \\
     \bg{skilllabelcolour}{iconcolour}{AWS CloudFormation}  &  \barrule{0.3}{0.5em}{cvpurple}\\
     \bg{skilllabelcolour}{iconcolour}{R} & \barrule{0.25}{0.5em}{cvpurple} \\
     \bg{skilllabelcolour}{iconcolour}{C} & \barrule{0.2}{0.5em}{cvpurple} \\
     \bg{skilllabelcolour}{iconcolour}{C \#} & \barrule{0.2}{0.5em}{cvpurple} \\
     \bg{skilllabelcolour}{iconcolour}{Arduino} & \barrule{0.2}{0.5em}{cvpurple} \\
     \bg{skilllabelcolour}{iconcolour}{\LaTeX} & \barrule{0.2}{0.5em}{cvpurple} \\
\end{tabular}
\end{minipage}

% \begin{tabular}{r| p{0.4\textwidth} c}
%     \cvevent{2023--2024}{Head of AI}{Lead}{AI Collaborator \color{cvred}}{Lead AI and Data Science efforts at AI Collaborator, managing internal AI product development team as well as leading client facing AI development projects. Develop Thought Leadership and vision for company AIOps, strategy, team growth, and innovative AI offerings. 
% }{aicollaborator_logo.jpeg} \\
%     \cvevent{2020--2023}{Chief Data Officer}{Lead}{RIO analytics \color{cvred}}{Developing and deploying ETL routines for software monitoring large industrial operations, as well as AI/Machine Learning models for anomaly identification.}{rio_analytics.png}
% \end{tabular}
 \vspace{3em}


\section*{Curriculum - Project Highlights}
\begin{tabular}{r| p{0.4\textwidth} c}
    \cvevent{2025--}{Enterprise Anomaly Detection Platform}{Project Lead}{IgniteTech \color{cvred}}{Architected real-time anomaly detection for enterprise appliances, with ML pipelines feeding agentic systems on distributed AWS; led the team through production deployment.}{ignite_technologies_logo.jpeg} \\
    \cvevent{2025}{AI Coding Assistants for Legacy Platforms}{Tech Lead}{IgniteTech \color{cvred}}{LLM assistants exposing legacy industrial platforms through natural language, integrating domain knowledge bases via RAG pipelines and Model Context Protocol (MCP) servers.}{ignite_technologies_logo.jpeg} \\
    \cvevent{2025--}{Organizational Knowledge Management}{Lead}{IgniteTech \color{cvred}}{Architected the continuous-evaluation and activity-metrics layer of a company-wide initiative turning team expertise into LLM-ready knowledge repositories.}{ignite_technologies_logo.jpeg} \\
    \cvevent{2024}{Open Loop}{Company Representative}{META \color{cvred}}{Collaborated with large team of technical and non-technical leaders in contributing to 2024 NIST framework update on Responsible AI and AI Alignment practices, particularly on Red Teaming and Synthetic Data.}{meta.jpg}  \\
    \cvevent{2023 - 2024}{Causal Machine Learning}{Tech Lead}{Apple \color{cvred}}{Led project to develop automated software to refine the use of causal inference methodologies within Marketing analytics context.}{apple.png}  \\
    \cvevent{2024}{Survey Insights Assistant}{Supervisor}{Apple \color{cvred}}{Supervised development of a software tool and accompanying data infrastructure to expedite behavioral research data processing and analysis.}{apple.png} \\
    \cvevent{2023--2024}{AI Collaborator Software Platform}{Tech Lead}{AI Collaborator \color{cvred}}{Led development of an LLM RAG based engine empowered by a knowledge graph (Neo4J) implementation for supporting AI collaborator's consultancy business.}{aicollaborator_logo.jpeg} \\
    \cvevent{2024}{Data Infrastructure Audit}{Tech Lead}{LG Ads \color{cvred}}{Built year-long roadmap for data infrastructure enhancements, indicating best practices for transition between bare metal and cloud-based approach. Solved data fragmentation issues and provided data access to downstream applications.}{LGAdsSolutions.jpg}  \\
    \cvevent{2021}{PREMON Phase 3}{Tech Lead}{REPSOL \color{cvred}}{Participated in developing an IoT fatigue damage tracking device for oil platforms, using TensorFlow Lite for local MLP Neural net model.}{Repsol_logo.png} \\
    \cvevent{2021--2022}{Fault Prediction Mechanism}{Tech Lead}{BELEM BIO Energia \color{cvred}}{Led the development  fault prediction based on feature importance evolution tracking over performance-driven assets in Boiler system. Led developments of MLOps infrastructure and workflow.}{BBMlogo.png} \\
    % \cvevent{2021--2022}{Data Infrastructure & Analytics}{Lead}{OCYAN \color{cvred}}{Developed AWS data infrastructure for real-time sensor data processing. Led Data Science team in developing pattern recognition and anomaly tracking for KAIROS platform.}{ocyan_logo.jpg} \\
    \cvevent{2021--2022}{Fatigue Damage Prediction}{Tech Lead}{BP \color{cvred}}{Led Data Science team in developing neural net Keras models for inferring fatigue damage in oil platforms based on sensor data.}{BPlogo.png} \\
    % \cvevent{2021--2022}{Machine State Tracking}{Developer}{ARCELORMITTAL / MOOVE \color{cvred}}{Developed system combining predictive modeling of temperature sensors and clustering models for industrial rolling mill machine phase space monitoring.}{} \
    \cvevent{2023}{Alarm Management Software}{Tech Lead}{VOLVO / MOOVE \color{cvred}}{Developed prototype providing health score for assets based on causal analysis of alarm time series and machine stoppage records.}{volvo_logo.png} \\
    \cvevent{2022--2023}{Locomotive Integrity Management}{Developer}{RUMO / MOOVE \color{cvred}}{Developed ML approaches for predicting sensor data evolution, identifying anomalies, and predicting failures in locomotives.}{rumo_logo.png} \\
    \cvevent{2021--2022}{Causal Relationship Research}{Technical Lead}{GM / AICollaborator \color{cvred}}{Led research project evaluating feasibility of approaches to causal relationship identification in data for improving high-impact business decisions.}{gmlogo.jpeg} \
\end{tabular}
\vspace{3em}



\begin{minipage}[t]{0.3\textwidth}
\section*{Certificates}
\begin{tabular}{>{\footnotesize\bfseries}r >{\footnotesize}p{0.55\textwidth}}
    2018 & HackingRio - Cleantech Cluster Champion \\
\end{tabular}
\bigskip

% \section*{Languages}
% \begin{tabular}{l | ll}
% \textbf{Portuguese} & C2 & {\phantom{x}\footnotesize mother tongue} \\
% \textbf{English} & C2 & \pictofraction{\faCircle}{cvgreen}{5}{black!30}{0}{\tiny} \\
% \textbf{French} & C2 & \pictofraction{\faCircle}{cvgreen}{4}{black!30}{1}{\tiny} \\
% \textbf{Spanish} & C2 & \pictofraction{\faCircle}{cvgreen}{3}{black!30}{2}{\tiny}
% \end{tabular}
% \bigskip


\section*{Languages}
\begin{tabular}{l | ll}
\textbf{Portuguese}  & {\phantom{x}\footnotesize mother tongue} \\
\textbf{English}  & \pictofraction{\faCircle}{cvgreen}{4}{cvgreen}{1}{\tiny} \\
\textbf{French} & \pictofraction{\faCircle}{cvgreen}{4}{black!30}{1}{\tiny} \\
\textbf{Spanish}  & \pictofraction{\faCircle}{cvgreen}{3}{black!30}{2}{\tiny}
\end{tabular}
\bigskip

\end{minipage}\hfill
\begin{minipage}[t]{0.3\textwidth}
\section*{Publications}
\begin{tabular}{>{\footnotesize\bfseries}r >{\footnotesize}p{0.7\textwidth}}
    2024 & \emph{Temperaturas Efetivas em Sistemas Atérmicos Simples}, PhD thesis, CBPF. \\
    2024 & \emph{Retrieval Augmented Genesis} and \emph{Holy Texts Semantics Analysis}, Medium. \\
    2021 & ``Effective temperatures for single particle system under dichotomous noise'', in: \emph{JSTAT} \\
    2016 & ``A large deviation analysis on the near-equivalence between external and internal reservoirs'', in: \emph{Physica A} \\
    2015 & ``Thermostatistics of a damped bimodal particle'', in: \emph{PRE} 
\end{tabular}
\bigskip

% \section*{Talks}
% \begin{tabular}{>{\footnotesize\bfseries}r >{\footnotesize}p{0.6\textwidth}}
%     Nov. 1726 & ``How I lost my ship (\& and how to get it back)'', at: \emph{Annual Pirate's Conference} in Tortuga, Nov. 1726.
% \end{tabular}
\end{minipage}




\vfill{} % Whitespace before final footer

%----------------------------------------------------------------------------------------
%	FINAL FOOTER
%----------------------------------------------------------------------------------------
\setlength{\parindent}{0pt}
\begin{minipage}[t]{\rightcolwidth}
\begin{center}\fontfamily{\sfdefault}\selectfont \color{black!70}
{\small Jo\~ao Ribeiro Medeiros \icon{\faEnvelopeO}{cvgreen}{} https://joaoribeiromedeiros.github.io/ \icon{\faMapMarker}{cvgreen}{} Rio de Janeiro
\newline\icon{\faAt}{cvgreen}{} \protect\url{johananmdairus@gmail.com}
\end{center}
\end{minipage}

\end{paracol}

\end{document}
