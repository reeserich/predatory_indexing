# Code to prepare data and figures for "Predatory and legitimate indexing of scholarly journals".

Data is available on [Zenodo](https://doi.org/10.5281/zenodo.24546607). Drop all files in a data/ directory at the same level as notebooks/.

## Notebooks

**260513_cas_ewl_indexing.ipynb, 261028_doaj_indexing.ipynb, 261028_jufo_indexing.ipynb, 261028_kijl_indexing.ipynb, 261028_rw_hjc.ipynb, 261028_abdc_jql_indexing.ipynb, 261028_scopus_indexing_dataset.ipynb, 261028_wos_indexing_dataset.ipynb, 261028_combine_legitimate_indices.ipynb**: For processing and normalizing records from legitimate indices.

**260711_process_predatory_indices.ipynb**: For processing and normalizing records from predatory indices. Reproduces Figure 2.

**261028_analyze_journal_network.ipynb**: For combining predatory and legitimate datasets and disambiguating journals. Reproduces Table 2, Figure 5, Table 3 and Table 4. 

**261028_pick_journals_to_inspect.ipynb**: For randomly selecting URLs to inspect and processing my annotation.

**261028_url_builtwith.ipynb**: For querying domain properties and relationships with BuiltWith. Reproduces data for Figure 6, which was created in [Gephi](https://gephi.org/).
