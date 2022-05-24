### Research

In my research, I focus on understanding, describing, and facilitating software evolution and the impact of human factors, particularly developers cognition, by integrating psychological and economical concepts. Roughly, my research can be structured in five intersecting sub-topics, yielding empirical insights, novel techniques, conceptual models, and guidelines for conducting research.

<details>
<summary style="cursor:pointer;"><b style="cursor:pointer;">Re-engineering variant-rich systems</b></summary>

The primary focus of my <a href="assets/papers/diss.pdf" target="_blank" rel="me noopener noreferrer">dissertation</a><a href="assets/papers/diss.pdf" target="_blank" rel="me noopener noreferrer"></a> has been on the re-engineering of variant-rich systems. A variant-rich system describes a number of reused software variants that are similar, but have unique functionalities (i.e., features) to fulfill individual customer requirements. Organizations implement variant-rich systems through different techniques, which can be primarily distinguished into clone-based (e.g., copy-paste, clone & own) or platform-based (e.g., product-line engineering) strategies. Most developers start with clone-based development by creating and adapting a copy of an existing variant, since it is well supported and readily available, for instance, via forking on GitHub. However, an increasing number of cloned variants can easily cause problems in developing and maintaining the variant-rich system, for instance, because new features or bug fixes must be propagated between the independent and co-evolving variants. In such cases, organizations often decide to adopt a platform by re-engineering their cloned variants. A platform builds on a variability mechanism (i.e., a technique for implementing configuration options, such as the C preprocessor) and automated tool support (e.g., for modeling features, configuring, and deriving variants) to help developers reuse software artifacts more systematically.

<br>

<b>Contributions</b>
<ul>
  <li>Empirically elicited economical data on the (re-)engineering of variant-rich systems, highlighting that organizations should aim to iteratively move towards platform-based software reuse but must be aware about costly factors (e.g., feature location). The data can help organizations in their decision making and confirms/refutes established assumptions in research (e.g., change propagation can be more challenging in a platform than often assumed).</li>
  <li>Academic and industrial case studies on re-engineering variant-rich systems, providing insights into the processes, pitfalls, and benefits.<a href="assets/papers/Krueger2018FeatureC.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a></li>
  <li>Empirical insights into the feature-location and knowledge recovery problem and how to tackle it by eagerly tracing features in advance, recommending that feature traces in the source code should be lightweight and separated from variability mechanisms to facilitate program comprehension.<a href="assets/papers/Krueger2019FeatureFacets.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a><a href="assets/papers/Fenske2021IfdefsSE.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a></li>
  <li> Process model, conceptual model<a href="assets/papers/Ananieva2022ConceptualModelExtension.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>, and operations<a href="assets/papers/Ananieva2022UnifiedOperations.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a> for specifying and supporting the (re-)engineering and evolution of variant-rich systems by providing an understanding of contemporary practices.</li>
  <li>Techniques for supporting developers in (re-)engineering endeavors of variant-rich systems, for instance, for analyzing the variability of source code or feature modeling<a href="assets/papers/Kuiter2021varied.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>.</li>
  <li>Guidelines for assessing and planning the (re-)engineering of variant-rich systems, for instance, feature modeling principles.<a href="assets/papers/Lindohf2021LargeFEF.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a></li>
  <li>Other contributions on variant-rich systems include, for instance, datasets, definitions of benchmarks, concepts for enabling security analyses<a href="assets/papers/Kenner2021SecuritySfateySPL.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>, guiding research for modern technologies<a href="assets/papers/Assuncao2021VM4ModernTech.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>, and support for quality assurance<a href="assets/papers/Krueger2018MutationOperators.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>.</li>
</ul>

<b>Some interesting reads</b>
<ul>
  <li><a href="assets/papers/Ananieva2022ConceptualModelExtension.pdf" target="_blank" rel="me noopener noreferrer">Empirical Software Engineering 2022<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We have proposed a conceptual model for unifying variability in space and time to guide contemporary research and tool development.</li>
  <li><a href="assets/papers/Kuiter2021varied.pdf" target="_blank" rel="me noopener noreferrer">Empirical Software Engineering 2021<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: With funding from pure-systems GmbH, we have formalized and implemented operations in a tool that enables collaborative, distributed feature modeling; which works similar to Google Docs for text.</li>
  <li><a href="assets/papers/Lindohf2021LargeFEF.pdf" target="_blank" rel="me noopener noreferrer">Empirical Software Engineering 2021<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We have instantiated the Family Evaluation Framework for assessing software product-line engineering in a company, reporting how to use the framework for managing and monitoring.</li>
  <li><a href="assets/papers/Krueger2019FeatureFacets.pdf" target="_blank" rel="me noopener noreferrer">Journal of Systems and Software 2019<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We investigated how to recover feature facets for two open-source systems, showing what information sources in social-coding platforms (e.g., GitHub) can be helpful to understand important properties of the respective system.</li>
</ul>

<b>Projects and funding</b>
<ul>
  <li>Pure-Systems GmbH: Go SPLC 2019 Challenge project</li>
  <li>German Academic Exchange Service: IFI fellowship, research visits fellowship, conference traveling fellowship</li>
  <li>European Union: Erasmus traineeship grant</li>
</ul>

</details>

<br>

<details>
<summary style="cursor:pointer;"><b style="cursor:pointer;">Quality in software evolution</b></summary>

Most software systems exist for a longer time, and thus are evolving. There are numerous reasons why software evolves, for instance, because new features are added (with the system potentially becoming variant-rich), refactorings employed, or bugs fixed. However, not every evolution may improve the system. Instead, a change may lead to new bugs in the system or a general degeneration of the source code; causing, for instance, architectural or code smells<a href="assets/papers/Gnoyke2022ArchSmellsEvolutionSE.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a><a href="assets/papers/Gnoyke2021ArchSmellsEvolution.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>, technical debt, or incomprehensible code. It is important to understand how software degenerates and how this is impacted or impacts developers. Precisely, a system may become less and less comprehensible, requiring major re-engineering to improve its quality and make it usable for an organization.

<br>
  
<b>Contributions</b>
<ul>
  <li></li>
</ul>

<b>Some interesting reads</b>
<ul>
  <li><a href="assets/papers/Gnoyke2021ArchSmellsEvolution.pdf" target="_blank" rel="me noopener noreferrer">ICSME 2021<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We advanced existing tools to conduct a novel mining study on the evolution of architectural smells in open-source software and their impact on technical debt (e.g., cyclic dependencies have particular impact).</li>
  <li><a href="assets/papers/Nielebock2019Comments.pdf" target="_blank" rel="me noopener noreferrer">Empirical Software Engineering 2019<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We conducted a large experiment in which developers had to comprehend smaller code examples with different types of comments, with our results and comparison to the related work indicating that comments are less helpful for smaller code excerpts and that developers often mistrust them.</li>
</ul>

<b>Projects and funding</b>
  
</details>

<br>

<details>
<summary style="cursor:pointer;"><b style="cursor:pointer;">Cognition in software evolution</b></summary>



<br>
  
<b>Contributions</b>
<ul>
  <li></li>
</ul>

<b>Some interesting reads</b>
<ul>
  <li></li>
</ul>

<b>Projects and funding</b>

</details>

<br>

<details>
<summary style="cursor:pointer;"><b style="cursor:pointer;">Fork-based software development</b></summary>



<br>
  
<b>Contributions</b>
<ul>
  <li></li>
</ul>

<b>Some interesting reads</b>
<ul>
  <li></li>
</ul>

<b>Projects and funding</b>
  
</details>

<br>

<details>
<summary style="cursor:pointer;"><b style="cursor:pointer;">Guidelines for conducting research</b></summary>

<a href="assets/papers/Shakeel2020PrimaryStudySelection.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>
  
  <a href="assets/papers/Alchokr2022GoldenAge.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>
  
  <a href="assets/papers/Alchokr2021JuniorResearchers.pdf" target="_blank" rel="me noopener noreferrer"><img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>
  

<br>
  
<b>Contributions</b>
<ul>
  <li></li>
</ul>

<b>Some interesting reads</b>
<ul>
  <li><a href="assets/papers/Alchokr2022ReviewingDynamics.pdf" target="_blank" rel="me noopener noreferrer">EASE 2022<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We conducted a survey among software engineering researchers to explore the challenges they observe for junior researchers to actively participate in the community.</li>
  <li><a href="assets/papers/Shakeel2022LiteratureAnalyses.pdf" target="_blank" rel="me noopener noreferrer">EASE 2022<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We propose a techniques that incorporates various metrics to facilitate the discovery, selection, and quality assessment of publications during literature analyses.</li>
  <li><a href="assets/papers/Shakeel2022Altmetrics.pdf" target="_blank" rel="me noopener noreferrer">JCDL 2022<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We report on a large study of the computer science community in which we compare citations and altmetrics for a number of high reputation venues.</li>
  <li><a href="assets/papers/Alchokr2021ArticleRecommendation.pdf" target="_blank" rel="me noopener noreferrer">JCDL 2021<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We performed a comparative survey of existing article recommendation platforms, which help research disseminate and discuss their publications after they have been accepted.</li>
  <li><a href="assets/papers/Heumuller2020Artifacts.pdf" target="_blank" rel="me noopener noreferrer">Empirical Software Engineering 2020<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We have studied how research artifacts are (and should be) shared, indicating that researchers should be motivated to publish their artifacts in persistent repositories.</li>
  <li><a href="assets/papers/Krueger2020ReplicatingSLRs.pdf" target="_blank" rel="me noopener noreferrer">Empirical Software Engineering 2020<img src="logos/pdf.png" height="12px" style="margin-inline-start: 0.5em" alt="pdf"/></a>: We report on a large-scale experiment that shows the limitations and problems of search engines in computer science, indicating clear threats to the conduct and replication of literature reviews.</li>
</ul>

<b>Projects and funding</b>

</details>
