---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

<script>
  function toggleBib(button) {
    const bib = button.nextElementSibling;
    bib.classList.toggle('visible');
  }
</script>


{% include base_path %}

<style>
  /* ---- Base button style ---- */
  a.definiteness,
  a.demonstrative,
  a.loci,
  a.plurality,
  a.quantifiers,
  a.anaphors,
  a.either,
  a.honorificity,
  a.verbs,
  a.korean {
    display: inline-block;
    padding: 0.15em 0.4em;         /* smaller padding = tighter box */
    margin: 0.1em;
    border: 1px solid currentColor;
    border-radius: 2px;            /* almost square corners */
    text-decoration: none;
    font-size: 0.9rem;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    line-height: 1.2;
    transition: all 0.15s ease;
  }

  /* ---- Individual colors ---- */
  .definiteness { color: #679e90; }
  .demonstrative { color: #8f9e67; }
  .loci { color: #b1a2c7; }
  .plurality { color: #9e677d; }
  .quantifiers { color: #88c7d6; }
  .anaphors { color: #d6c329; }
  .either { color: #d3ccaf; }
  .honorificity { color: #679e8a; }
  .verbs { color: #67919e; }
  .korean { color: #6ee5d1; }

  /* ---- Hover/focus effect ---- */
  a.definiteness:hover,
  a.definiteness:focus { background-color: #679e90; color: white; }

  a.demonstrative:hover,
  a.demonstrative:focus { background-color: #8f9e67; color: white; }

  a.loci:hover,
  a.loci:focus { background-color: #b1a2c7; color: white; }

  a.plurality:hover,
  a.plurality:focus { background-color: #9e677d; color: white; }

  a.quantifiers:hover,
  a.quantifiers:focus { background-color: #88c7d6; color: white; }

  a.anaphors:hover,
  a.anaphors:focus { background-color: #d6c329; color: white; }

  a.either:hover,
  a.either:focus { background-color: #d3ccaf; color: #333; }

  a.honorificity:hover,
  a.honorificity:focus { background-color: #679e8a; color: white; }

  a.verbs:hover,
  a.verbs:focus { background-color: #67919e; color: white; }

  a.korean:hover,
  a.korean:focus { background-color: #6ee5d1; color: #003333; }

  /* Optional: subtle lift */
  a.definiteness:hover,
  a.demonstrative:hover,
  a.loci:hover,
  a.plurality:hover,
  a.quantifiers:hover,
  a.anaphors:hover,
  a.either:hover,
  a.honorificity:hover,
  a.verbs:hover,
  a.korean:hover {
    transform: translateY(-1px);
  }



  /* Bib box styling */
  .bib-entry {
    opacity: 0;
    max-height: 0;
    overflow: hidden;
    white-space: pre;
    font-family: monospace;
    background-color: #f6f6f6;
    border: 1px solid #ddd;
    margin-top: 6px;
    border-radius: 4px;
    transition: all 0.25s ease;
  }

  .bib-entry.visible {
    opacity: 1;
    max-height: 500px;
    padding: 8px;
  }
</style>




**<span class="definiteness">Definiteness and anaphoric expressions</span>**

It is generally assumed that pronouns, definites, and demonstratives are separate semantic elements. However, cross-linguistic studies suggest that the morphosyntactically based distinction between these expressions do not always align with underlying meaning. In this line of work, I argue that the underlying semantics of these expressions are identical except for the restrictions that they carry, proposing a unified analysis that extends the general schema of a definite.

- Ahn, Dorothy & Ziling Zhu. 2025. <em class="definiteness">A bridge to definiteness: Identifying unique and relational definites through bridging</em>. Natural Language Semantics. <a href="https://link.springer.com/article/10.1007/s11050-025-09237-8" class="definiteness">pdf</a>
- Ahn, Dorothy. 2024. <em class="definiteness">A four-way distinction in English definite descriptions</em>. Proceedings of SuB28, University of Bochum, Germany 2023. <a href="https://ojs.ub.uni-konstanz.de/sub/index.php/sub/article/view/1104" class="definiteness">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&cstart=20&pagesize=80&citation_for_view=caKoCk4AAAAJ:qjMakFHDy7sC" class="definiteness">🎓google scholar</a> <a href="javascript:void(0);" class="definiteness" onclick="toggleBib(this)">
    bib
  </a>
  <pre div class="bib-entry"><code>@incollection{ahn2024definite,
    author={Ahn, Dorothy},
title={A four-way distinction in {E}nglish definite expressions},
year={2024},
    booktitle = {Proceedings of Sinn und Bedeutung 28},
publisher={Bochum: Ruhr-University Bochum},
volume={28},
editor={Baumann, Geraldine and Gutzmann, Daniel  and Koopman, Jonas  and Liefke, Kristina  and Renans, Agata  and Scheffler, Tatjana },
pages={1--17}
} 
</code></pre>
- Ahn, Dorothy. 2019. <em class="definiteness">THAT thesis: A competition-based mechanism for anaphoric expressions</em>. PhD thesis, Harvard University. <a href="https://ling.auf.net/lingbuzz/004742" class="definiteness">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:UebtZRa9Y70C" class="definiteness">🎓google scholar</a> <a href="javascript:void(0);" class="definiteness" onclick="toggleBib(this)">
    bib
  </a>
  <pre div class="bib-entry"><code>@phdthesis{ahn2019thatthesis,
    title={{\textit{THAT}} thesis: {A} competition mechanism for anaphoric expressions},
    author={Ahn, Dorothy},
    year={2019},
    school={Harvard University}
}
</code></pre>
- Ahn, Dorothy. 2017. <em class="definiteness">Semantics of definite descriptions: A micro-typology</em>. GLOW in Asia 2017, Singapore. February 20-22. <a href="https://glowlinguistics.org/asia11/wp-content/uploads/sites/3/2017/11/v1-ahn.pdf" class="definiteness">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:_FxGoFyzp5QC" class="definiteness">🎓google scholar</a> 
  <a href="javascript:void(0);" class="definiteness" onclick="toggleBib(this)">
    bib
  </a>
  <pre div class="bib-entry"><code>@inproceedings{ahn2017typology,
  title={Definite and demonstrative descriptions: a micro-typology},
  author={Ahn, Dorothy},
  booktitle={Proceedings of {Generative Linguistics in the Old World in Asia 11}},
  volume = 1,
  publisher = {MIT Working Papers in Linguistics},
  editor={Erlewine, Michael Yoshitaka},
  year = {2017},
  pages={33--48}
}
</code></pre>

**<span class="demonstrative">Demonstratives and pointing</span>**

Demonstratives received much attention in semantics and philosophy for their deictic and non-deictic uses. In gesture linguistics, demonstratives also show a unique behavior of bringing meaning of gesture to at-issue. I propose a new analysis of demonstratives based their ability to refer to non-familiar entities.

- Zhang, Ying & Dorothy Ahn. 2025. <em class="demonstrative">The most descriptive depiction</em>. Sinn und Bedeutung 30, Goethe University Frankfurt. <a href="https://doroahn.github.io/files/zhang-ahn-most-descriptive-depiction.pdf" class="demonstrative">[slides]</a>
- Ahn, Dorothy. 2025. <em class="demonstrative">Definite expressions with and without deixis</em>. Proceedings of WCCFL41, UC Santa Cruz. <a href="https://www.lingref.com/cpp/wccfl/41/paper3727.pdf" class="demonstrative">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&cstart=20&pagesize=80&citation_for_view=caKoCk4AAAAJ:zYLM7Y9cAGgC" class="demonstrative">🎓google scholar</a> <a href="javascript:void(0);" class="demonstrative" onclick="toggleBib(this)">
    bib
  </a>
  <pre div class="bib-entry"><code>@incollection{ahn2023deixis,
author={Ahn, Dorothy},
title={Definite expressions with and without deixis},
year={2025},
booktitle={Proceedings of the 41st West Coast Conference on Formal Linguistics},
editor={Webster, Nikolas  and Kiper, Yağmur  and Wang, Richard and Lyu, Sichen Larry},
publisher={Cascadilla Proceedings Project},
city={Somerville, MA, USA},
pages={1--17}
}
</code></pre>
- Ahn, Dorothy. 2022. <em class="demonstrative">Indirectly direct: An account of demonstratives and pointing</em>. In Linguistics and Philosophy. 45. 1345–1393. <a href="https://link.springer.com/article/10.1007/s10988-022-09350-5" class="demonstrative">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:Se3iqnhoufwC" class="demonstrative">🎓google scholar</a> <a href="javascript:void(0);" class="demonstrative" onclick="toggleBib(this)">
    bib
  </a>
  <pre div class="bib-entry"><code>@article{ahn2022indirect,
title={Indirectly direct: {A}n account of demonstratives and pronouns},
author={Ahn, Dorothy},
journal={Linguistics and Philosophy},
year={2022},
volume={45},
pages={1345--1393}
}
</code></pre>
- Ahn, Dorothy & Sudha Arunachalam. 2020. <em class="demonstrative">Anaphoric that: Difference between adults and children</em>. Proceedings of BUCLD 44. October 25-27. <a href="https://www.lingref.com/bucld/44/BUCLD44-03.pdf" class="demonstrative">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:Y0pCki6q_DkC" class="demonstrative">🎓google scholar</a> 
- Ahn, Dorothy & Jenneke van der Wal. 2019. <em class="demonstrative">What does that Lugwere demonstratives refer to? A semantic analysis of proximity and exteriority.</em> Studies in African Linguistics. 48(1):1-24. University of Florida: LibraryPress. <a href="https://journals.flvc.org/sal/article/view/114927" class="demonstrative">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:kNdYIx-mwKoC" class="demonstrative">🎓google scholar</a> 
- Ahn, Dorothy & Kathryn Davidson. 2017. <em class="demonstrative">Where pointing matters: English and Korean demonstratives</em>. NELS 2017, Iceland. October 27-20. <a href="/files/ahndavidson20217.pdf" class="demonstrative">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:u-x6o8ySG0sC" class="demonstrative">🎓google scholar</a>

**<span class="loci">ASL loci use</span>**

Sign languages such as American Sign Language (ASL) can use the indexical pointing handshape (IX; indexical) to refer to entities present in the context by pointing directly at them. Signers can also point to abstract locations in the signing space (locus, loci) to refer to entities who are not present in the content but familiar in the discourse. This use of loci in sign languages has been analyzed as overt instantiations of a referent tracking mechanism that is covert in spoken languages (see Lillo-Martin & Klima 1990). I propose an alternative account of loci as locational restrictions that function as modifiers added to anaphoric expressions.

- Ahn, Dorothy. 2020. <em class="loci">ASL IX to locus as a modifier</em>. Proceedings of NELS 50, MIT. <a href="https://www.dorothyahn.com/_files/ugd/697a33_645cbf2a52224f70b05f86d03b4330cb.pdf" class="loci">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:LkGwnXOMwfcC" class="loci">🎓google scholar</a>
- Ahn, Dorothy, Annemarie Kocab & Kathryn Davidson. 2019. <em class="loci">The role of contrast in anaphoric expressions in ASL</em>. Proceedings of GLOW in Asia 2019, Seoul, Korea. August 6-9, 2019. <a href="https://www.dorothyahn.com/_files/ugd/697a33_cac4bd55c4ca4b67a03003da9c66d89e.pdf" class="loci">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&cstart=20&pagesize=80&citation_for_view=caKoCk4AAAAJ:4TOpqqG69KYC" class="loci">🎓google scholar</a>
- Kocab, Annemarie, Dorothy Ahn, Gunnar Lund & Kathryn Davidson. 2019. <em class="loci">Reconsidering agreement in sign languages</em>. Poster at GLOW 42, Oslo, Norway. May 7-10. <a href="https://www.dorothyahn.com/_files/ugd/697a33_b47654000d8e4d66887df8a8b85c6a0a.pdf" class="loci">[poster]</a>
- Ahn, Dorothy. 2019. <em class="loci">Anaphoric expressions in ASL</em>. MS, Lingbuzz. <a href="https://ling.auf.net/lingbuzz/004594" class="loci">pdf</a>

**<span class="plurality">Plurality and number</span>**

Unlike languages like English that obligatorily marks number, many languages are 'optional number languages', meaning that they allow bare noun forms to be compatible with both singular and plural interpretations. I investigate one of the languages that have been identified as having an optional plural marker, Korean, and show that there is a more systematic restriction on when plural marker can be omitted in Korean. In Ahn, Saha, & Sauerland 2020, we present a novel observation that Korean and Bangla plural markers behave as positive polarity items, while in Ahn & Snedeker, we argue that definitely construed nouns must be number marked in Korean.

- Ahn, Dorothy, Ankana Saha, & Uli Sauerland. 2020. <em class="plurality">Positively Polar Plurals</em>. Poster at SALT 30, Cornell. August 17-20, 2020 <a href="https://osf.io/7dtbw/" class="plurality">[osf]</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:5nxA0vEk-isC" class="plurality">🎓google scholar</a> 
- Ahn, Dorothy & Jesse Snedeker. 2021. <em class="plurality">Early acquisition of plural morphology in a classifier language: Data from Korean 2-4 year olds</em>. Language Learning and Development. <a href="https://www.tandfonline.com/eprint/JDYWNDGUDDEFT3T82K6V/full?target=10.1080/15475441.2021.1922280" class="plurality">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:WF5omc3nYNoC" class="plurality">🎓google scholar</a> 

**​<span class="quantifiers">Relative measure constructions</span>**

Conservativity of determiners is one of the universal constraints assumed for natural language semantics. In this line of work, we look at proportional quantifiers such as sixty percent in Harvard hired sixty percent women that seem non-conservative on the surface, identify cross-linguistic generalizations on how the non-conservative construals are morphosyntactically marked, and propose an analysis that preserves conservativity at the LF level.

- Ahn, Dorothy & Heejeong Ko. 2022. <em class="quantifiers">On non-conservativity of Korean floating quantifiers​</em>. In Glossa. <a href="https://www.glossa-journal.org/article/id/5776/" class="quantifiers">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:W7OEmFMy1HYC" class="quantifiers">🎓google scholar</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:WF5omc3nYNoC" class="plurality">🎓google scholar</a> 
- Ahn, Dorothy. & Uli Sauerland. 2017. <em class="quantifiers">Measure constructions with relative measures: Towards a syntax of non-conservative construals</em>. The Linguistic Review. doi:10.1515/tlr-2017-0001 <a href="https://www.degruyterbrill.com/document/doi/10.1515/tlr-2017-0001/html" class="quantifiers">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:3fE2CSJIrl8C" class="quantifiers">🎓google scholar</a> 
- Ahn, Dorothy. & Uli Sauerland. 2015. <em class="quantifiers">The grammar of relative measurement</em>. Semantics and Linguistic Theory, 25, 125-142. doi:10.3765/salt.v25i0.3062 <a href="https://journals.linguisticsociety.org/proceedings/index.php/SALT/article/view/25.125" class="quantifiers">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:2osOgNQ5qMEC" class="quantifiers">🎓google scholar</a> 
- Ahn, Dorothy. & Uli Sauerland. 2015. <em class="quantifiers">Reverse Quantification with Proportional Quantifiers</em>. NELS 45: Proceedings of the Forty-Fifth Annual Meeting of the North East Linguistic Society, MIT. <a href="https://www.dorothyahn.com/_files/ugd/697a33_5fa95a929a284f1aa471761ebfb22685.pdf" class="quantifiers">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:UeHWp8X0CEIC" class="quantifiers">🎓google scholar</a> 

**<span class="anaphors">Exempt anaphors and logophoricity</span>**

While reflexive anaphors are assumed to be bound locally, there are cases of anaphors that appear outside their binding domain (exempt anaphors). In this line of work, I discuss a case of an exempt anaphor in Korean, caki-casin, and show that the licensing of caki-casin is associated with logophoricity (Charnavel 2012, 2019).

- Ahn, Dorothy. & Isabelle Charnavel. 2017. <em class="anaphors">Perspective on Korean Anaphors: Comparing Inanimate cachey vs. Animate caki-casin</em>. Proceedings of WCCFL34. <a href="http://www.lingref.com/cpp/wccfl/34/paper3292.pdf" class="anaphors">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:hqOjcs7Dif8C" class="anaphors">🎓google scholar</a>
- Ahn, Dorothy. 2016. <em class="anaphors">Empathy and deixis: A deictic analysis of giving verbs</em>. Harvard Working Papers in Linguistics.​ <a href="https://www.dorothyahn.com/_files/ugd/697a33_c32eec1edd074b67970750abea3923e3.pdf" class="anaphors">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&cstart=20&pagesize=80&citation_for_view=caKoCk4AAAAJ:MXK_kJrjxJIC" class="anaphors">🎓google scholar</a>
- Ahn, Dorothy. 2015. <em class="anaphors">Condition A, Exemption, and Logophoricity in Korean</em>. MS (Generals paper), Harvard. <a href="https://www.dorothyahn.com/_files/ugd/697a33_558f767ac2044b9aab5f2dbccfbf1027.pdf" class="anaphors">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&cstart=20&pagesize=80&citation_for_view=caKoCk4AAAAJ:0EnyYjriUFMC" class="anaphors">🎓google scholar</a>

**<span class="either">Additive either and too</span>** 

I propose that additive either in sentences such as Jin did not dance either is underlyingly a disjunction between the antecedent sentence (p in p either) and a propositional anaphor that refers to a contextually salient proposition in the discourse that is restricted by focus. This analysis derives the polarity sensitivity of either, while the conjunction analysis of too correctly predicts the NPI intervention effects of too. 

- Ahn, Dorothy. 2016. <em class="either">NPI intervention of too</em>. Proceedings of Sinn und Bedeutung 20. <a href="https://semanticsarchive.net/sub2015/SeparateArticles/Ahn-SuB20.pdf" class="either">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:YOwf2qJgpHMC" class="either">🎓google scholar</a>
- Ahn, Dorothy. 2015. <em class="either">The semantics of additive either</em>. Proceedings of Sinn und Bedeutung 19. <a href="https://semanticsarchive.net/Archive/TVlN2I2Z/sub19proc.pdf" class="either">pdf</a> <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:8k81kl-MbHgC" class="either">🎓google scholar</a>

**<span class="korean">Constructions in Korean</span>**

- Ye, Ariela & Dorothy Ahn. 2025. <em class="korean">Rethinking embeddability and context sensitivity in Honorification: Evidence from Korean _si_</em>. SALT 35. <a href="https://doroahn.github.io/files/ye_ahn_2025_salt35-korean-si.pdf" class="korean">[draft]</a>
- Ahn, Dorothy. 2018. <em class="korean">Korean classifier-less constructions</em>. Proceedings of Sinn und Bedeutung 22. <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=caKoCk4AAAAJ&citation_for_view=caKoCk4AAAAJ:_kc_bZDykSQC" class="korean">🎓google scholar</a>
