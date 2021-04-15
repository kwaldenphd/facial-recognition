# Facial Recognition and Biometric Identification Lab

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
This tutorial is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

# Table of Contents

- [Overview](#overview)
- [Prompt 1: Further Background Research](#prompt-1-further-background-research)
- [Prompt 2: Tech Deep Dive](#tech-deep-dive)
  * [Types of Facial Recognition Technology](#types-of-facial-recognition-technology)
  * [Facial Recognition Products](#facial-recognition-products)
  * [Benchmark Datasets](#benchmark-datasets)
- [Prompt 3: Exploring the Gender Shades Lit Review](#prompt-3-exploring-the-gender-shades-lit-review)
  * [Work They Build On](#work-they-build-on)
  * [Work They Critique](#work-they-critique)
  * [Other Topics](#other-topics)
    * [Emotion Detection](#emotion-detection)
    * [Autism Spectrum Work](#autism-spectrum-work)
- [Prompt 4: NIST System Audits](#prompt-4-nist-system-audits)
- [Prompt 5: Congressional Hearings and Federal Reports](#prompt-5-congressional-hearings-and-federal-reports)
  * [Senate Subcommittee on Privacy, Technology, and the Law (July 2012)](#senate-subcommittee-on-privacy-technology-and-the-law-july-2012)
  * [Federal Bureau of Investigation Privacy Impact Assessment (May 2015)](#federal-bureau-of-investigation-privacy-impact-assessment-may-2015)
  * [Updated FBI Privacy Impact Assessment (July 2018)](#updated-fbi-privacy-impact-assessment-july-2018)
  * [United States Government Accountability Office Report (May 2016)](#united-states-government-accountability-office-report-may-2016)
  * [US. GAO-19-579T Report (June 2019)](#us-gao-19-579t-report-june-2019)
  * [ Committee on Homeland Security "About Face" Hearing (July 2019)](#committee-on-homeland-security-about-face-hearing-july-2019)
- [Prompt 6: Lawsuits](#prompt-6-lawsuits)
  * [Lynch v. Florida](#lynch-v-florida)
  * [Webster v. Hennepin County](#webster-v-hennepin-county)
  * [Williams v. Detroit Police Department](#williams-v-detroit-police-department)
  * [All the Clearview AI Lawsuits](#all-the-clearview-ai-lawsuits)
    * [Vermont Attorney General (March 2020)](#vermont-attorney-general-march-2020)
    * [ACLU v. Clearview AI (May 2020)](#aclu-v-clearview-ai-may-2020)
    * [Mutnick v. Clearview AI Class Action (August 2020)](#mutnick-v-clearview-ai-class-action-august-2020)
    * [Mijente and NorCal Resist Immigrants Rights Groups (March 2021)](#mijente-and-norcal-resist-immigrants-rights-groups-march-2021)
- [Prompt 7: Hands-On Work With Face Detection](#prompt-7-hands-on-work-with-face-detection)
- [Lab Notebook Components](#lab-notebook-components) 


# Overview

The lab procedure document includes 7 different prompt options. Folks can go in-depth with one prompt or explore a couple of prompts. 

As a starting place, the Electronic Frontier Foundation has [a useful primer](ttps://www.eff.org/pages/face-recognition) for how facial recognition technologies work.

# Prompt 1: Further Background Research

In 2016, Georgetown University Law School's Center on Privacy and Technology researchers Claire Garvie, Alvaro Bedoya, and Jonathan Frankle published ground-breaking research on law enforcement use of facial recognition technologies. 

["The Perpetual Lineup: Unregulated Police Face Recognition in America"](https://www.perpetuallineup.org/) emphasizes the number of open questions around law enforcement use of facial recognition technology.

<blockquote>"We know very little about these systems. We don’t know how they impact privacy and civil liberties. We don’t know how they address accuracy problems. And we don’t know how any of these systems—local, state, or federal—affect racial and ethnic minorities.

"This report closes these gaps. The result of a year-long investigation and over 100 records requests to police departments around the country, it is the most comprehensive survey to date of law enforcement face recognition and the risks that it poses to privacy, civil liberties, and civil rights. Combining FBI data with new information we obtained about state and local systems, we find that law enforcement face recognition affects over 117 million American adults. It is also unregulated. A few agencies have instituted meaningful protections to prevent the misuse of the technology. In many more cases, it is out of control."</blockquote>

Spend some time looking through the report. Start with the Executive Summary, but dig into the report's analysis and recommendations sections.

Questions to consider:
- What do the Gender Shades authors say about this research? 
- What stands out from reading the executive summary?
- What questions, topics, or issues were the authors looking at? 
- What research methods or approaches did the authors use?
  * Particularly, how did the authors go about gathering information for their analysis?
- What conclusions do the authors draw from their analysis?
- Other questions/comments/etc

# Prompt 2: Tech Deep Dive

The Gender Shades article mentions a few types or big categories for facial recognition (face detection, classification, emotion detection, etc). Both of our readings for this week mention a number of specific systems.

Select one of these categories or specific tech programs.

Questions to consider:
- How (and why) was this technology developed?
- Who all was involved, or where did it originate?
- What can you tell about how the technology works?
  * In the case of technology products, what can you tell about how the facial recognition system was built or trained?
  * In the case of benchmark datasets, what can you tell about how the images where gathered (and the level of transparency/informed consent involved)?
- Where is this technology used?
- Other observations/comments/questions

## Types of Facial Recognition Technology

- Computer vision ([Wikipedia](https://en.wikipedia.org/wiki/Computer_vision))
- Face detection ([Wikipedia](https://en.wikipedia.org/wiki/Face_detection), [Electronic Frontier Foundation](https://www.eff.org/pages/face-recognition))
- Face recognition/identification ([Electronic Frontier Foundation](https://www.eff.org/pages/face-recognition))
- Emotion recognition ([Wikipedia page for Affectiva](https://en.wikipedia.org/wiki/Affectiva))

Or another term/concept mentioned in the Gender Shades article.

## Facial Recognition Products

- Amazon's Rekognition ([Amazon](https://aws.amazon.com/rekognition/), [Wikipedia](https://en.wikipedia.org/wiki/Amazon_Rekognition))
- Microsoft Azure Face ([Microsoft](https://azure.microsoft.com/en-us/services/cognitive-services/face/), ["What is the Azure Face service?", Microsoft Docs](https://docs.microsoft.com/en-us/azure/cognitive-services/face/overview))
- IBM Watson ([IBM](https://www.ibm.com/dk-en/cloud/watson-visual-recognition))
- Clearview AI ([Clearview AI](https://clearview.ai/))
- Face++ ([Face++](https://www.faceplusplus.com/), [Wikipedia](https://en.wikipedia.org/wiki/Megvii))
- Affectiva ([Affectiva](https://www.affectiva.com/), [Wikipedia](https://en.wikipedia.org/wiki/Affectiva))

Or another product/company mentioned in the Gender Shades article.

## Benchmark Datasets

- [MegaFace](http://megaface.cs.washington.edu/)
- [Labeled Faces in the Wild (LFW)](http://vis-www.cs.umass.edu/lfw/)
- [IJB (A,B,C)](https://www.nist.gov/programs-projects/face-challenges)
- [Adience](https://talhassner.github.io/home/projects/Adience/Adience-data.html)

# Prompt 3: Exploring the Gender Shades Lit Review

The Gender Shades authors reference a wide range of prior work that relates to their study.

Select one of the articles to read/explore.

Questions to consider:
- What do the Gender Shades authors say about this work? 
- What stands out from reading the abstract?
- What questions, topics, or issues were the authors looking out? 
- What research methods or approaches did the authors use?
- What conclusions do the authors draw from their analysis?
- Other questions/comments/etc

## Work They Build On

- Citron, Danielle Keats and Pasquale, Frank A., The Scored Society: Due Process for Automated Predictions (2014). Washington Law Review, Vol. 89, 2014, p. 1-, U of Maryland Legal Studies Research Paper No. 2014-8, Available at SSRN: https://ssrn.com/abstract=2376209
- Bolukbasi, T., Chang, K. W., Zou, J. Y., Saligrama, V., & Kalai, A. T. (2016). Man is to computer programmer as woman is to homemaker? debiasing word embeddings. In Advances in neural information processing systems (pp. 4349-4357). URL: https://arxiv.org/abs/1607.06520
- Caliskan, Aylin, Joanna Bryson, and Arvind Narayanan. “Semantics Derived Automatically from Language Corpora Contain Human-Like Biases.” Science 356, no. 6334 (2017): 183–86. https://doi.org/10.1126/science.aal4230. [Link to access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_proquest1887393228)
- Kilbertus, Niki & Rojas-Carulla, Mateo & Parascandolo, Giambattista & Hardt, Moritz & Janzing, Dominik & Schölkopf, Bernhard. (2017). Avoiding Discrimination through Causal Reasoning. URL: https://arxiv.org/abs/1706.02744
- Hardt, Moritz & Price, Eric & Srebro, Nathan. (2016). Equality of Opportunity in Supervised Learning. In Advances in Neural Information Processing Systems, 3315-3323. URL: https://arxiv.org/abs/1610.02413. 
- Esteva, Andre, and Brett Kuprel, Roberto A. Novoa, Justin Ko, Susan M. Swetter, Helen M. Blau, and Sebastian Thrun. “Dermatologist-Level Classification of Skin Cancer with Deep Neural Networks.” Nature 542, no. 7639 (2017): 115–18. https://doi.org/10.1038/nature21056. [Link to online access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_nature_a10.1038/nature21056)
- Popejoy, Alice B, and Stephanie M Fullerton. “Genomics is failing on diversity.” Nature vol. 538,7624 (2016): 161-164. [doi:10.1038/538161a](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5089703/)
- Melloni, Chiara S., Jeffrey Y. Berger, Tracy J. Wang, Funda B. Gunes, Amanda Kristin Stebbins, Karen Pieper, Rowena Dolor, Pamela Douglas, Daniel Mark, and L Newby. “Representation of Women in Randomized Clinical Trials of Cardiovascular Disease Prevention.” Circulation: Cardiovascular Quality and Outcomes 3, no. 2 (2010): 135–42. [https://doi.org/10.1161/CIRCOUTCOMES.110.868307](https://www.ahajournals.org/doi/10.1161/CIRCOUTCOMES.110.868307)
- Klare, Brendan F., Mark J. Burge, Joshua C. Klontz, Richard W. Vorder Bruegge, and Anil K. Jain. “Face Recognition Performance: Role of Demographic Information.” IEEE Transactions on Information Forensics and Security 7, no. 6 (2012): 1789–1801. https://doi.org/10.1109/TIFS.2012.2214212. [Link to online access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_crossref10.1109/TIFS.2012.2214212)

## Work They Critique

- Wu, Xiaolin & Zhang, Xi. (2016). Automated Inference on Criminality using Face Images. Preprint URL: https://arxiv.org/abs/1611.04135v1
- Wang Y, Kosinski M. Deep neural networks are more accurate than humans at detecting sexual orientation from facial images. J Pers Soc Psychol. 2018 Feb;114(2):246-257. doi: 10.1037/pspa0000098. PMID: 29389215. Link to access: https://pubmed.ncbi.nlm.nih.gov/29389215/
  * Articles that critique this work:
    * Blaise Agüera y Arcas, Margaret Mitchell and Alexander Todorov, ["Physiognomy's New Clothes"](https://medium.com/@blaisea/physiognomys-new-clothes-f2d4b59fdd6a) *Medium blog* (6 May 2017)
    * Blaise Agüera y Arcas, Alexander Todorov and Margaret Mitchell, ["Do algorithms reveal sexual orientation or just expose our stereotypes?"](https://medium.com/@blaisea/do-algorithms-reveal-sexual-orientation-or-just-expose-our-stereotypes-d998fafdf477) *Medium blog post* (11 January 2018)

- Farinella, G, and J Dugelay. “Demographic Classification: Do Gender and Ethnicity Affect Each Other?” In 2012 International Conference on Informatics, Electronics & Vision (ICIEV), 383–90. IEEE, 2012. https://doi.org/10.1109/ICIEV.2012.6317383. [Link to online access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_ieee_s6317383)

## Other Topics

### Emotion Detection

- Dehghan, Afshin, Enrique G. Ortiz, Guang Shu, and Syed Zain Masood. “DAGER: Deep Age, Gender and Emotion Recognition Using Convolutional Neural Network,” 2017. Preprint URL: https://arxiv.org/abs/1702.04280
- Srinivasan, R., J. D. Golomb, and A. M. Martinez. “A Neural Basis of Facial Action Recognition in Humans.” Journal of Neuroscience 36, no. 16 (2016): 4434–42. [https://doi.org/10.1523/JNEUROSCI.1704-15.2016](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4837681/)
- Benitez-Quiroz, C. Fabian, Ramprakash Srinivasan, and Aleix M Martinez. “EmotioNet: An Accurate, Real-Time Algorithm for the Automatic Annotation of a Million Facial Expressions in the Wild.” In 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016:5562–70. IEEE, 2016. https://doi.org/10.1109/CVPR.2016.600. [Link to online access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_ieee_s7780969)

### Autism Spectrum Work

- Leo, M, Del Coco, Carcagni, Distante, Bernava, Pioggia, and Palestra. “Automatic Emotion Recognition in Robot-Children Interaction for ASD Treatment.” In 2015 IEEE International Conference on Computer Vision Workshop (ICCVW), 2015:537–45. IEEE, 2015. https://doi.org/10.1109/ICCVW.2015.76. [Link to online access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_ieee_s7406425)
- Palestra, Giuseppe, Giovanna Varni, Mohamed Chetouani, and Floriana Esposito. “A Multimodal and Multilevel System for Robotics Treatment of Autism in Children.” In Proceedings of the International Workshop on Social Learning and Multimodal Interaction for Designing Artificial Agents, 1–6. ACM, 2016. https://doi.org/10.1145/3005338.3005341. [Link to online access throug Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_acm3005341)      

# Prompt 4: NIST System Audits

The National Institute of Standards and Technology (NIST) has ongoing work with Face Recognition Vendor Test (FRVT) research.
- Learn more about NIST's ["Face Projects"](https://www.nist.gov/programs-projects/face-projects) research and initiatives.
- Learn more about NIST's ["FRVT"](https://www.nist.gov/programs-projects/face-recognition-vendor-test-frvt-ongoing) ongoing work, including additional technical documentation.

NIST has produced a number of technical whitepapers from the FRVT program.

- NISTIR 8271 ["FRVT Part 2: Identification"](https://doi.org/10.6028/NIST.IR.8271) (September 2019) builds on and expands NIST Interagency Report (NISTIR) 8238, which documents NIST's evalaution of facial recognition algorithms.

- You can also read the original NISTIR 8238 publication ["Ongoing FRVT Part 2: Identification"](https://doi.org/10.6028/NIST.IR.8238) (November 2018).

But, most recently, NIST released NISTIR 8280 ["FRVT Part 3: Demographic Effects"](https://doi.org/10.6028/NIST.IR.8280) (December 2019), which "describes and quantifies demographic differentials for contemporary face recognition algorithms. NIST has conducted tests to quantify demographic differences for nearly 200 face recognition algorithms from nearly 100 developers, using four collections of photographs with more than 18 million images of more than 8 million people. Using both one-to-one verification and one-to-many identification algorithms submitted to NIST, the report found empirical evidence for the existence of a wide range of accuracy across demographic differences in the majority of the current face recognition algorithms that were evaluated" (["New FRVT Demographic Effects Report"](https://www.nist.gov/programs-projects/face-recognition-vendor-test-frvt-ongoing)).

Read through (explore/browse) NISTIR 8290.
- [NIST press release that accompanied publication of NISTIR 8280](https://www.nist.gov/news-events/news/2019/12/nist-study-evaluates-effects-race-age-sex-face-recognition-software)

Questions to consider:
- What questions, topics, or issues were the authors looking out? What did they set out to do?
- What types of prior work do they reference? How do they engage with that work (critique, build on, etc)?
- What are some of the authors’ main arguments or findings?
- What research methods or approaches did the authors use? What steps did they take to answer their original research questions?
- What conclusions do the authors draw from their analysis (of prior research, benchmark datasets, or commercial systems)?
- Other questions/comments/etc

# Prompt 5: Congressional Hearings and Federal Reports

There have been a number of federal reports and hearings on facial recognition technologies, in relation to questions of privacy and civil liberties.

Select one or two of these reports or hearings and explore the linked material.

Questions to consider:
- What are you able to learn about the background or context for this hearing or report?
- What are some of the specific concerns articulated in the report or hearing testimony?
  * How did the report come to exist, or who commissioned it?
  * Who all was involved in authoring the report? Or who was called to testify as part of the committee hearing?
- Where and how do you see race and surveillance at work?
- What were some of the recommendations or conclusions for the report/hearing?
- Did anything happen or change because of this hearing/report?
- Other thoughts/questions/comments

##  Senate Subcommittee on Privacy, Technology and the Law (July 2012)

In July 2012, The Senate Judiciary Committee Subcomittee on Privacy, Technology and the Law heled a hearing "What Facial Recognition Technology Means for Privacy and Civil Liberties." The hearing included testimony from Federal Bureau of Investigation, Federal Trade Commission, Facebook, MorphoTrust USA, Carnegie Mellon University, National Sheriffs' Association, and Duke University representatives.

[Link to hearing homepage (includes testimony transcripts and hearing video)](https://www.judiciary.senate.gov/meetings/what-facial-recognition-technology-means-for-privacy-and-civil-liberties)

## Federal Bureau of Investigation Privacy Impact Assessment (May 2015)

In May 2015, the FBI issued an internal study, "Privacy Impact Assessment for the Facial Analysis, Comparison, and Evaluation (FACE) Services Unit," which considered privacy implications for FACE Services Unit applications.

The report was made public via Freedom of Information/Privacy Act request.

[Link to report](https://www.fbi.gov/services/information-management/foipa/privacy-impact-assessments/facial-analysis-comparison-and-evaluation-face-services-unit)

## Updated FBI Privacy Impact Assessment (July 2018)

The FBI released an update to the May 2015 report in July 2018.

The report was made public via Freedom of Information/Privacy Act request.

[Link to report](https://www.fbi.gov/file-repository/pia-face-phase-2-system.pdf/view)

## United States Government Accountability Office Report (May 2016)

In May 2016, the United States Government Accountability Office published GAO-16-267, a report titled "Face Recognition Technology: FBI Should Better Ensure Privacy and Accuracy." The report was addressed to then Sen. Al Franken, who was at the time the Ranking Member of the Subcommittee on Privacy, Technology and the Law, part of the Senate Judiciary Committee.

[Link to full report](https://www.gao.gov/products/gao-16-267)

## U.S. GAO-19-579T Report (June 2019)

The GAO released a follow-up report to GAO-16-267 in June 2019. That report, titled "Face Recognition Technology: DOJ and FBI Have Taken Some Actions in Response to GAO Recommendations to Ensure Privacy and Accuracy, But Additional Work Remains." The report was addressed to members of the House Committee on Oversight and Reform.

[Link to full report](https://www.gao.gov/products/gao-19-579t)

## Committee on Homeland Security "About Face" Hearing (July 2019)

In 2019, the House Committee on Homeland Security convened a hearing titled "About Face: Examining the Department of Homeland Security’s Use of Facial Recognition and Other Biometric Technologies." The hearing included testimony from U.S. Customs and Border Protection, U.S. Department of Homeland Security, U.S. Secret Service, Transportation Security Administration, and National Institute of Standards and Technology (U.S. Department of Commerce) representatives.

[Link to hearing homepage (includes testimony transcripts and hearing video)](https://homeland.house.gov/activities/hearings/about-face-examining-the-department-of-homeland-securitys-use-of-facial-recognition-and-other-biometric-technologies)

Following the publication of NISTIR 8280 (see Prompt #3), Rep. Bennie G. Thompson (D-MS), Chairman of the Committee on Homeland Security, [wrote a public letter](https://homeland.house.gov/news/correspondence/chairman-thompson-writes-dhs-on-shocking-facial-recognition-report) to then Acting Homeland Security Secretary Chad Wolf regarding the discrepencies between the NIST report and the testimony provided by DHS.  

# Prompt 6: Lawsuits

CNET's Alfred Ng has a great overview of some of the legal challenges being posted to facial recognition technologies.
- Alfred Ng, ["Facial recognition's fate could be decided in 2021"](https://www.cnet.com/news/facial-recognitions-fate-could-be-decided-in-2021) *CNET* (11 December 2020)

Select one or two of these lawsuits and explore the provided resources.

Questions to consider:
- What are you able to learn about the background or context for the case?
- What are some of the specific concerns articulated in the legal documents (where available)?
  * Is there precedent being cited?
  * Are there Constitutional amendments or other legal foundations for the lawsuit?
- Where and how do we see race and surveillance at work?
- What are you able to tell about the status of the case?
- Other thoughts/questions/comments

Additional resources for a few specific cases.

## Lynch v. Florida

- [Justitia legal resources](https://law.justia.com/cases/florida/first-district-court-of-appeal/2018/16-3290.html)

- Aaron Mak, ["Facing Facts: A case in Florida demonstrates the problems with using facial recognition to identify suspects in low-stakes crimes"](https://slate.com/technology/2019/01/facial-recognition-arrest-transparency-willie-allen-lynch.html) *Slate* (25 January 2019)

- Somil Trivedi and Nathan Freed Wessler, ["Florida Is Using Facial Recognition to Convict People Without Giving Them a Chance to Challenge the Tech"](https://www.aclu.org/blog/privacy-technology/surveillance-technologies/florida-using-facial-recognition-convict-people) *ACLU* (12 March 2019)

## Webster v. Hennepin County

- David Chanen, ["Facial recognition technology comes out of the shadows"](https://www.startribune.com/facial-recognition-technology-comes-out-of-the-shadows/382954891/) *Minnesota Star Tribune* (14 June 2016)

- Aaron Mackey, ["EFF To Minneosta Supreme Court: Sheriff Must Release Emails Documenting Biometric Technology Use"](https://www.eff.org/deeplinks/2017/07/eff-minnesota-supreme-court-sheriff-must-release-emails-documenting-biometric) *Electronic Frontier Foundation* (17 July 2017)

- Libor Jany, ["Police use of facial recognition technology soars in Minnesota"](https://www.eff.org/deeplinks/2017/07/eff-minnesota-supreme-court-sheriff-must-release-emails-documenting-biometric) *Minnesota Star Tribune* (4 December 2020)

- ACLU Minnesota, ["Webster v. Hennepin County"](https://www.aclu-mn.org/en/cases/webster-v-hennepin-county) *ACLU Minnesota*

## Williams v. Detroit Police Department

- ACLU Michigan, ["Farmington Hills Father Sues Detroit Police Department for Wrongful Arrest Based on Faulty Facial Recognition Technology"](https://www.aclumich.org/en/press-releases/farmington-hills-father-sues-detroit-police-department-wrongful-arrest-based-faulty) *ACLU Michigan* (13 April 2021)

- Tate Ryan-Mosley, ["The new lawsuit that shows facial recognition is officially a civil rights issue"](https://www.technologyreview.com/2021/04/14/1022676/robert-williams-facial-recognition-lawsuit-aclu-detroit-police) *MIT Technology Review* (14 April 2021)

- Drew Harwell, ["Wrongfully arrested man sues Detroit police over false facial recognition match"](https://www.washingtonpost.com/technology/2021/04/13/facial-recognition-false-arrest-lawsuit) *Washington Post* (13 April 2021)

## All the Clearview AI Lawsuits

Clearview AI is facing a number of lawsuits related to its facial recognition technology and partnerships with law enforcement.

For more background on Clearview AI:
- Ryan Mac, Caroline Haskins, Brianna Sacks, and Logan McDonald, ["Surveillance Nation: How A Facial Recognition Tool Found Its Way Into Hundreds Of US Police Departments, Schools, And Taxpayer-Funded Organizations"](https://www.buzzfeednews.com/article/ryanmac/clearview-ai-local-police-facial-recognition) *BuzzFeed News* (6 April 2021).
- New York Times reporter Kashmir Hill has been reporting on Clearview AI and facial recognition tech for over a year. [Link to an archive of her work in the Times](https://www.nytimes.com/by/kashmir-hill).

A few specific lawsuits.

### Vermont Attorney General (March 2020)

- Office of the Vermont Attorney General, ["Attorney General Donovan Sues Clearview AI for Violations of Consumer Protection Act and Data Broker Law"](https://ago.vermont.gov/blog/2020/03/10/attorney-general-donovan-sues-clearview-ai-for-violations-of-consumer-protection-act-and-data-broker-law) *Office of the Vermont Attorney General* (10 March 2020)

- Office of the Vermont Attorney General, ["Attorney General Wins Significant Victory in Clearview AI Lawsuit"](https://ago.vermont.gov/blog/2020/09/11/attorney-general-wins-significant-victory-in-clearview-ai-lawsuit/) *Office of the Vermont Attorney General* (11 September 2020)

### ACLU v. Clearview AI (May 2020)

- Ryan Mac and Caroline Haskins, ["The ACLU Is Suing Clearview AI to Stop 'Privacy-Destroying Face Surveillance'"](https://www.buzzfeednews.com/article/ryanmac/aclu-suing-clearview-ai-privacy-destroying-surveillance) *BuzzFeed News* (28 May 2020)

- ACLU, ["ACLU v. Clearview AI- Complaint"](https://www.aclu.org/legal-document/aclu-v-clearview-ai-complaint) *ACLU* (25 September 2020)

### Mutnick v. Clearview AI Class Action (August 2020)

- Legal filings in Mutnick v. Clearview AI (August 2020)
  * [Justitia](https://law.justia.com/cases/federal/district-courts/illinois/ilndce/1:2020cv00512/372790/86/)
  * [Additional filings on Scribd](https://www.scribd.com/document/444154093/gov-uscourts-ilnd-372790-1-0)

### Mijente and NorCal Resist Immigrants Rights Groups (March 2021)

Background:
- Irina Ivanova, ["Immigrant Rights Groups Sue Facial-Recognition Company Clearview AI"](https://www.cbsnews.com/news/clearview-ai-facial-recognition-sued-mijente-norcal-resist/) *CBS News* (9 March 2021)
- Rachel Metz, ["Clearview AI sued in California by immigrant rights groups, activists"](https://www.cnn.com/2021/03/09/tech/clearview-ai-mijente-lawsuit/index.html) *CNN Business* (9 March 2021)
- Johana Bhuiyan, ["Clearview AI uses your online photos to instantly ID you. That's a problem, lawsuit says"](https://www.latimes.com/business/technology/story/2021-03-09/clearview-ai-lawsuit-privacy-violations) *Los Angeles Times* (9 March 2021)

- [Legal filing](https://justfutureslaw.org/wp-content/uploads/2021/03/2021-03-09-Complaint-vs-Clearview.pdf)

# Prompt 7: Hands-On Work With Face Detection

Work through one of the linked Python face detection tutorials.
- Kristijan Ivancic, ["Traditional Face Detection With Python"](https://realpython.com/traditional-face-detection-python/) *Real Python*
- Shantnu Tiwari, ["Face Recognition With Python"](https://realpython.com/face-recognition-with-python/)
- Adrian Rosebrock, ["Face recognition with OpenCV, Python, and deep learning"](https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/) *PyImageSearch* (18 June 2018)
- Marcelo Rovai, ["Real-Time Face Recognition: An End-To-End Project"](https://towardsdatascience.com/real-time-face-recognition-an-end-to-end-project-b738bb0f7348) *Towards Data Science* (12 March 2018)
- Parul Pandey, ["Face Detection With Python using OpenCV"](https://www.datacamp.com/community/tutorials/face-detection-python-opencv) *DataCamp* (20 December 2018)

Reflection questions:
- What challenges did you face, and how did you solve them?
- What did you learn about facial recognition/face detection through the tutorial you looked at?
- How are you thinking about facial recognition/face detection differently after working through a tutorial?
- Other comments/questions/observations

You're welcome (but not required) to include code + screenshots as part of that narrative.

# Lab Notebook Components

Each prompt has some reflection questions to consider as a starting place. 

We'll combine the lab notebook and reflection for next week, so your reflection can combine or synthesize the work that happened in the lab as well as readings/class meetings.
