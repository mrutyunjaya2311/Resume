\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]} 
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

\begin{center}
    \textbf{\Huge \scshape Mrutyunjaya Sethy} \\
    \href{mailto:mrutyunjaysethy165@gmail.com}{mrutyunjaysethy165@gmail.com} $|$ +91 7608020361\\
     \href{https://www.linkedin.com/in/mrutyunjay-sethy-38ab65275/}{\texttt{LinkedIn}} $|$
    \href{https://github.com/mrutyunjaya2311}{\texttt{GitHub}} \\
\end{center}

%-----------SUMMARY-----------
\section{Summary}
Interested and detail-oriented fresher with strong foundation in Java, Python, React.js, and web development. Passionate about building dynamic applications, integrating AI/ML models, and delivering user-friendly interfaces. Quick learner with solid problem solving skills and a collaborative mindset. 
%-----------EDUCATION-----------

\section{Education}
 \resumeSubHeadingListStart
    \resumeSubheading
      {ITER, SOA University}{Bhubaneswar, Odisha}
      {B.Tech in Computer Science and Engineering - 75\% (Ongoing)}{2022 -- Present}
  \resumeSubHeadingListEnd
  \resumeSubHeadingListStart
    \resumeSubheading
      {Tetraedron Junior College}{Tangi, Cuttack}
      {Higher Secondary - 83\%}{2020 -- 2022}
  \resumeSubHeadingListEnd
   \resumeSubHeadingListStart
    \resumeSubheading
      {Saraswati sishu vidya mandir}{Paradeep, Jagatsinghpur}
      {Secondary Education- 72\% }{2019 -- 2020}
  \resumeSubHeadingListEnd
 



%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart
  \resumeSubheading
    {Blood Report Analyzer and Disease Predictor}{2024}
    {Full Stack AI Project}{Self-driven}
    \resumeItemListStart
      \resumeItem{Developed a system to extract data from blood reports and predict potential diseases using NLP and ML models.}
      \resumeItem{Integrated the prediction model with a Node.js + Express backend and React.js frontend.}
    \resumeItemListEnd

  \resumeSubheading
    {Rock Paper Scissors Game}{2023}
    {Web Game}{Self-driven}
    \resumeItemListStart
      \resumeItem{Developed an interactive browser-based Rock Paper Scissors game using JavaScript, HTML, and CSS.}
      \resumeItem{Implemented logic to handle user inputs, computer-generated choices, and game outcome tracking in real time.}
    \resumeItemListEnd

  \resumeSubheading
    {Fashion Website}{2023}
    {Web Design Project}{Self-driven}
    \resumeItemListStart
      \resumeItem{Designed and developed a visually appealing frontend interface for a fashion-focused website using React.js and Bootstrap.}
      \resumeItem{Utilized reusable components and modular CSS for maintainable and scalable UI development.}

    \resumeItemListEnd

  \resumeSubheading
    {Comic Web UI}{2023}
    {Frontend Project}{Self-driven}
    \resumeItemListStart
      \resumeItem{Developed an engaging comic-themed web interface using HTML, CSS, and JavaScript, with emphasis on layout design and responsiveness.}
      \resumeItem{Focused on enhancing user experience through interactive elements and a clean, intuitive UI structure.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------ACHIEVEMENTS-----------
\section{Achievements}
\resumeItemListStart
  \resumeItem{Trained and deployed an AI-based disease prediction model using real medical report data.}
  \resumeItem{Regular participant in online coding contests and quizzes on platforms such as HackerRank, and LeetCode, actively improving problem-solving skills.}
  \resumeItem{Completed \textit{Master Data Structure in Java} course at LTLT, BBSR.}
\resumeItemListEnd



%-----------SKILLS-----------
\section{Technical Skills}
\begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: Java, Python, C, JavaScript, HTML, CSS} \\
     \textbf{Frameworks \,/\, Libraries}{: React.js, Express.js, Bootstrap, Node.js} \\
     \textbf{Tools and Concepts }{: MySQL,  VS Code, Jupyter Notebook,OOP,Data Structure ,Algorithm } \\
     \textbf{Domains}{: Web Development, AI/ML, NLP}
    }}

%-----------EXTRACURRICULAR ACTIVITIES-----------
\section{Extracurricular Activities}
\resumeItemListStart
  \resumeItem{Cricket – Regular player in college and local tournaments.}
  \resumeItem{Chess – Active player with strong strategic thinking and problem-solving interest.}
\resumeItemListEnd
\end{itemize}

\end{document}
