<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
    font-family: "Lato", sans-serif;
}

.sidenav {
    width: 200px;
    position: fixed;
    z-index: 1;
    top: 160px;
    left: 10px;
    background: #fff;
    overflow-x: hidden;
    padding: 8px 0;
}

.sidenav a {
    padding: 6px 8px 6px 16px;
    text-decoration: none;
    font-size: 20px;
    color: #029;
    display: block;
}

.sidenav a:hover {
    color: #064579;
}

.main {
    margin-left: 200px; /* Same width as the sidebar + left position in px */
    top: 100px;
}

@media screen and (max-height: 450px) {
    .sidenav {padding-top: 15px;}
    .sidenav a {font-size: 18px;}
}
</style>
</head>
<body>

<header class="main">
    <h1>KGCAU2019: International Workshop on Knowledge Graph Creation, Augmentation and Utilization</h1>
</header>

<div class="sidenav">
  <a href="#news">News</a>
  <a href="#introduction">Introduction</a>
  <a href="#important_dates">Important Dates</a>
  <a href="#topics_of_interest">Topics of Interest</a>
  <a href="#paper_submission">Paper Submission</a>
  <a href="#organization">Organization</a>
  <a href="#program_committee">Program Committee</a>
  <a href="#contact">Contact</a>
</div>

<div class="main" id="news">
    <h2>News</h2>
    <ul>
        <li>Oct 26, 2018: Workshop website is online</li>
    </ul>
</div>

<div class="main" id="introduction">
    <h2>Introduction</h2>
    <p>
        The term <i>Knowledge Graph</i> has been widely adopted to generally describe entities and their relationships. Nowadays, Knowledge Graphs are an active topic in many research areas, such as Databases, Computational Linguistics, Machine Learning and Semantic Web. The goal of our workshop is to explore the creation, augmentation and utilization of knowledge graphs, and to bring complementary research communities together to share their respective findings related to this topic.  
    </p>
    <p>
        A large amount of information is still only available in textual format, e.g., legal documents, financial reports, news articles, medical records, etc. Entity recognition, relation extraction, entity linking/disambiguation, coreference and other related techniques are the key to extracting valuable information from free text in order to build new or augment exisiting knowledge graphs (e.g., DBpedia, YAGO and Wikidata). Also, different knowledge graphs may describe the same entities differently in terms of schema/ontology or comprehensiveness. Record linkage, schema/ontology alignment and data integration in general are important techniques in breaking down the data silos. In terms of applications, knowledge graphs have been adopted in question answering, natural language generation, dialogue systems, and explainable AI in various domains, such as legal, tax, finance and healthcare.
    </p>
    <p>
        In practice, many industrial organizations have been building and adopting knowledge graphs: Google's Knowledge Vault, The LinkedIn Knowledge Graph, the Amazon Product Knowledge Graph, the Microsoft Academic Graph, and the Open PermID from Thomson Reuters. What are the technical challenges when building knowledge graphs? Were the knowledge graphs built from scratch or upon any existing open data? What are the challenges in designing the schema/ontology of a knowledge graph (e.g., lack of domain expertise)? How are knowledge graphs physically stored (e.g., graph databases, inverted indices, or relational databases) and queried? How did they evaluate the quality of knowledge graphs in order to provide high-quality customer-facing products, and how is customer feedback used to improve the quality and/or comprehensiveness of the knowledge graphs?
    </p>
    <p>
        Therefore, our workshop will solicit proposals related to knowledge graphs, the underlying key NLP and machine learning techniques, the diverse applications of knowledge graphs, and challenges and lessons learned during the process of building and adopting knowledge graphs, especially in diverse domains.
    </p>
</div>

<div class="main" id="important_dates">
    <h2>Important Dates</h2>
    <ul>
        <li>Submission Deadline: March 6, 2019</li>
        <li>Notification of Acceptance: March 27, 2019</li>
        <li>Camera-ready Deadline: April 5, 2019</li>
        <li>Workshop Date: June 6 or June 7, 2019</li>
    </ul>
</div>

<div class="main" id="topics_of_interest">
    <h2>Topics of Interest</h2>
    Topics include, but are not limited to, the following:
    <br>
    <ul>
        <li><b>Knowledge Graphs</b></li>
        <ul>
            <li>Knowledge graph creation and quality evaluation</li>
            <li>Augmenting existing knowledge graphs</li>
            <li>Integrating large-scale and heterogeneous knowledge graphs</li>
            <li>Schema alignment and ontology mapping</li>
        </ul>
        <br>
        <li><b>Natural Language Processing and machine learning</b></li>
        <ul>
            <li>Named entity and relation recognition</li>
            <li>Knowledge graph embeddings</li>
            <li>Learning ontologies and schemas from textual data</li>
            <li>Using knowledge graphs for better machine learning model explainability</li>
        </ul>
        <br>
        <li><b>Applications</b></li>
        <ul>
            <li>Question answering</li>
            <li>Natural language generation</li>
            <li>Dialogue systems</li>
            <li>Novel tools for visualizing and navigating knowledge graphs</li>
        </ul>
        <br>
        <li><b>Knowledge Graph in Practice (in various domains, e.g., medicine, law, environment, healthcare)</b></li>
        <ul>
            <li>Real-world use cases of knowledge graphs</li>
            <li>Integrating knowledge graphs into customer-facing products</li>
            <li>Challenges and lessons learned in building and adopting knowledge graphs in real-world applications</li>
        </ul>
    </ul>
</div>

<div class="main" id="paper_submission">
    <h2>Paper Submission</h2>
    <ul>
        <li>We welcome both full and short paper submissions.</li>
        <li>Full and short papers should not exceed 8 pages and 4 pages respectively.</li>
        <li>Submissions must be in PDF and formatted according to the NAACL-HLT 2019 paper style.</li>
    </ul>
</div>

<div class="main" id="organization">
    <h2>Organization</h2>
    <ul>
        <li>Dezhao Song, Thomson Reuters, USA</li>
        <li>Yunyao Li, IBM Research - Almaden, USA</li>
        <li>Karin Verspoor, University of Melbourne, Australia</li>
        <li>Frank Schilder, Thomson Reuters, USA</li>
    </ul>
</div>

<div class="main" id="program_committee">
    <h2>Program Committee</h2>
    <ul>
        <li>Gerhard Weikum, Max-Planck Institute for Informatics, Germany (<b>confirmed</b>)</li>
        <li>Diana Maynard, University of Sheffield, UK (<b>confirmed</b>)</li>
        <li>Chin-Yew Lin, Microsoft Research Asia, China (<b>confirmed</b>)</li>
        <li>Hannaneh Hajishirzi, University of Washington, USA (<b>confirmed</b>)</li>
        <li>Craig Knoblock, University of Southern California, USA (<b>confirmed</b>)</li>
        <li>Claire Gardent, French National Center for Scientific Research, France (<b>confirmed</b>)</li>
        <li>Xiang Ren, University of Southern California, USA (<b>confirmed</b>)</li>
        <li>Vanessa Lopez, IBM Research, Ireland (<b>confirmed</b>)</li>
        <li>Philippe Cudré-Mauroux, University of Fribourg, Switzerland (<b>confirmed</b>)</li>
        <li>Afsaneh Fazly, Samsung Research America, Canada (<b>confirmed</b>)</li>
        <li>Varish Mulwad, GE Global Research, USA (<b>confirmed</b>)</li>
        <li>Tonya Custis, Thomson Reuters, USA (<b>confirmed</b>)</li>
        <li>Jeff Heflin, Lehigh University, USA (<b>confirmed</b>)</li>
        <li>Marieke van Erp, KNAW Humanities Cluster, The Netherlands (<b>confirmed</b>)</li>
        <li>Quanzhi Li, Alibaba, USA (<b>confirmed</b>)</li>
        <li>Ben Hachey, Red Marker and Ergo AI, Australia (<b>confirmed</b>)</li>
        <li>Sudha Rao, University of Maryland, College Park, USA (<b>confirmed</b>)</li>
        <li>Anna Lisa Gentile, IBM Research - Almaden, USA (<b>confirmed</b>)</li>
        <li>Steffen Staab, Universität Koblenz-Landau, Germany (<b>confirmed</b>)</li>
    </ul>
</div>

<div class="main" id="contact">
    <h2>Contact</h2>
    Please contact Dezhao Song (songdezhao@gmail.com) for questions and comments about the workshop.
</div>

</body>
</html> 
